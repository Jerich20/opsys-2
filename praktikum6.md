#Praktikum 6 aruanne
Praktikum 6 oli üsna keeruline ja tuli palju otsida käsklusi internetist ja kuidas neid modifitseerida. Kokku läks mul u 3 tundi.
Ülesanne 1
<img width="979" alt="Kuvatõmmis 2023-10-16 111032" src="https://github.com/Jerich20/opsys2023/assets/144961112/03deb54c-7f93-485f-a1c9-0abd7a08b956">
Ülesanne 2
Käsklus SIGHUP signaali saatmisest, mill järel gedit % sulgus
<img width="960" alt="Kuvatõmmis 2023-10-27 203040" src="https://github.com/Jerich20/opsys2023/assets/144961112/01e41c71-5fa0-4401-bf44-caaf640a41a5">
Nüüd käivitasin gediti NOHUP käsuga ja proovisin selle sulgeda saates SIGHUP signaali, kuid gedit jäi edasi jooksma
<img width="960" alt="Kuvatõmmis 2023-10-27 203145" src="https://github.com/Jerich20/opsys2023/assets/144961112/a9c508a6-2f59-42dd-90ea-f51c34aab1f8">
Nüüd tapsin NOHUP gediti käsuga kill -9
<img width="960" alt="Kuvatõmmis 2023-10-27 203218" src="https://github.com/Jerich20/opsys2023/assets/144961112/c292c89d-bf8d-4685-8281-90725f51c3cb">
Ülesanne 3
Käsujada: ps -axu | grep '[d]aemon' | awk '{print $11, $12, $13}'
<img width="960" alt="Kuvatõmmis 2023-10-27 203747" src="https://github.com/Jerich20/opsys2023/assets/144961112/0c1a9cfe-78fe-4ad3-a344-b6fbe833cab1">
Käsujada: ip a | grep -oP 'inet \K[\d.]+' | head -n 1 | tee ipaddress.txt
<img width="960" alt="Kuvatõmmis 2023-10-27 204042" src="https://github.com/Jerich20/opsys2023/assets/144961112/3e563f15-2bae-4d05-9cf2-2b2f81d3a826">
