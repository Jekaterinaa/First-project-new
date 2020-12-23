# Versija V1.0 (realizacija su list'u)
**Testavimo sistemos parametrai :** <br/>
CPU: i5-7200U 2.70 GHz <br/>
RAM: 8.00 GB <br/>
HDD: 237.00 GB <br/>
## Pirmos ir antros studentų dalijimo strategijų palyginimas :
| Studentų skaičius | Rūšiavimo laikas (1 strategija)  | Rūšiavimo laikas (2 strategija)  |
|-------------------|----------------------------------|----------------------------------|
|100                | 0.0015731 s | 0.0012076 s |
|1000               | 0.0124618 s | 0.018049 s |
|10000              | 0.12372 s | 0.13194 s |
|100000             | 1.06545 s | 1.53694 s |
|1000000            | 11.5433 s | 13.3499 s|
 
**Išvados :** <br/>
Kai programa realizuojama su list'u geriau veikia antra strategija, kur vargšiukai užrašomi į naują list'ą ir ištriname iš seno list'o, o kietieji lieka sename. Taip pat versijos V1.0 su list'u veikimo laikas yra mažesnis negu tos pačios versijos su vektoriumi.
