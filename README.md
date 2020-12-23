# Versija V1.0 (realizacija su vektoriumi)
**Testavimo sistemos parametrai :** <br/>
CPU: i5-7200U 2.70 GHz <br/>
RAM: 8.00 GB <br/>
HDD: 237.00 GB <br/>
## Pirmos ir antros studentų dalijimo strategijų palyginimas :
| Studentų skaičius | Rūšiavimo laikas (1 strategija)  | Rūšiavimo laikas (2 strategija) |
|-------------------|----------------------------------|---------------------------------|
|100                |0.0025045 s   | 0.0020567 s |            
|1000               |0.0232645 s  | 0.0417151 s |
|10000              |0.240593 s  | 0.158468 s |
|100000             |2.26144 s  | 1.66653 s |
|1000000            |29.2887 s | 17.0475 s |    

**Išvados :** <br/>
Realizacijoje su vektoriumi (kaip ir realizacijoje su list'u) geriau veikia antra strategija. V0.4 ir V1.0 versijose (kurias lyginame) naudojami tie patys failai su studentų duomenimis. Duomenys iš jo nuskaitomi ir įrašomi į duomenų struktūros "duomuo" vektorių. Studentai rūšiuojami, naudojant antrą strategiją - studentai, kurių galutinis pažymys žemesnis negu 5 balai įrašomas į naują vektorių - "vargšiukai", o iš seno ištrinamas. O tie, kurių galutiniai pažymiai yra aukštesni negu 5 balai lieka sename vektoriuje. Pabaigoje sukuriami du nauji failai - protingų ir kvailų studentų, kur išvedami vardai, pavardės ir galutiniai pažymiai. 
