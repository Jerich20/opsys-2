# Praktikum 5 aruanne

Kokku läks praktikumi läbimiseks u2 tundi ja vastustele mõtlemisele veel umbes tund. Siin on vastused küsimustele:
5.1 minufail.txt lugemiseks on vaja kaustale vähemalt chmod 700 ja failile chmod 600. Kustutamiseks on kaustale vaja vähemalt samuti chmod 700 ja failile chmod 600.
5.2 Kuna tegu on skriptiga ei piisa a=x õigusteks lisaks tuleb anda chmod +x skript.sh
5.3
5.4 minimaalne fail sisu uusfail.txt kuvamiseks on r. siin on kuvatõmmised vajalikest käskudest:

<img width="959" alt="Kuvatõmmis 2023-10-17 195547" src="https://github.com/Jerich20/opsys2023/assets/144961112/d368327e-6d4a-4c27-9347-fbbfedb9ff9e">
<img width="451" alt="Kuvatõmmis 2023-10-17 195604" src="https://github.com/Jerich20/opsys2023/assets/144961112/781ad944-507d-4ae4-80af-649874cc7f27">
<img width="342" alt="Kuvatõmmis 2023-10-17 195626" src="https://github.com/Jerich20/opsys2023/assets/144961112/628bf16b-ae15-4974-ba43-a00e3da362fc">





5.5 


<img width="288" alt="Kuvatõmmis 2023-10-17 202539" src="https://github.com/Jerich20/opsys2023/assets/144961112/10b49f58-6c78-4c1e-bb9c-0d72b9213ccd">

setuid õigusi on vaja, et kasutaja saaks avada faile õigustega, mis neil muidu puudavad.

5.6 Jah. Sest kui need õigused anda kogemata valele kasutajale või valele kaustale/failidele siis see kasutaja saab neid faile muuta nagu ta oleks nende omanik.

5.7 opetaja, root ja peeter

5.8 
# file: hinded.txt
# owner: opetaja
# group: opetaja
user::rw-
group::---
group:direktor:rw-
mask::rw-
other::---
5.9 Mitte keegi ei saa chattr +i parameetritega faili modifitseerida ega kustutada. Et seda faili kustutada tuleb kasutada käsku chattr -i testFail-2.
