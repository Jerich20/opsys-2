# Praktikum 12 aruanne
Ülesanne 3
#!/bin/sh
echo "Sisesta nimi: "
read nimi
echo "Sisesta eriala: "
read eriala
echo "Sisesta martiklinumber: "
read number
echo "Õpilane $nimi, erialal $eriala, martiklinumbriga $number"

Ülesanne 4
#!/bin/bash
for i in $(ls)
do
if [ "${i: -4}" == "$1" ]
then
echo "$i"
mv -- "$i" "${i%$1}$2"
echo "${i%$1}$2"
fi
done

Ülesanne 5
#!/bin/bash
IFS=$'\n'
#Eraldaja ümber muutmine tühikust reavahetuseks
echo $(ps -A | tr -s ' ' | grep -w $1 |cut -d ' ' -f2) $1

Ülesanne 6
#!/bin/bash
astendamine () {
a=1
b=$2
while [ $b -ge 1 ]
do
a=$(($a * $1))
b=$(($b - 1))
done
echo $a
}
a=$1
b=$2
vastus=$(astendamine $a $b)
echo "$1 astmes $2 on: $vastus"
