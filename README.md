# COVID-19-magyar-adatok
koronavirus.gov.hu COVID 19 magyar adatok

Adatok forrása: https://atlo.team/koronamonitor/  
Adatok elsődleges forrása: koronavirus.gov.hu  

A koronavirus.gov.hu 2023 Január elsejétől megszűnt.  
A járvánnyal kapcsolatos hivatalos tájékoztatás azután az MTI-n keresztül lesz elérhető a sajtó számára.  

<hr>

A repositoryban elérhető egy sqlite adatbázis (covid_19_hun.sqlite),   
ami a koronamonitoros korona_hun - koronahun.xlsx adattáblára támaszkodik.
  
korona_hun - koronahun.xlsx mezőnevek VS covid_19_hun.sqlite mezőnevek

'Dátum' -> 'date'  
'Új esetek száma' -> 'new_cases'  
'Az új elhunytak száma naponta' -> 'new_deaths'  
'Új mintavételek száma' -> 'new_samples'  
'Új gyógyultak naponta' -> 'new_recoveries'  
'Új beoltottak száma Magyarországon' -> 'new_vaccinated'  


cid|name|type|notnull|dflt_value|pk
--- | --- | ---|--- | --- | ---|
0|id|INTEGER|0||1
1|date|TEXT|0||0
2|new_cases|INTEGER|0||0
3|new_deaths|INTEGER|0||0
4|new_samples|INTEGER|0||0
5|new_recoveries|INTEGER|0||0
6|new_vaccinated|INTEGER|0||0
