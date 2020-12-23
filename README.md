# Versija V0.5
Penktos versijos testavimas (su list'u) ir jos palyginimas su ketvirta versija (su vektoriumi). <br/>
**Testavimo sistemos parametrai :** <br/>
CPU: i5-7200U 2.70 GHz <br/>
RAM: 8.00 GB <br/>
HDD: 237.00 GB <br/>
## Versijų V0.4 ir V0.5 palyginimas :
| Studentų skaičius | Nuskaitymo laikas (su vektoriumi) | Nuskaitymo laikas (su list'u) | Rūšiavimo laikas (su vektoriumi) | Rūšiavimo laikas (su list'u) | Bendras laikas (su vektoriumi)        | Bendras laikas (su list'u)
|-------------------|-----------------------------------|-------------------------------|----------------------------------|------------------------------|----------------------------------|------------------------------|
|100                 | 0.0063279 s | 0.0058842 s | 0.0025045 s | 0.0015731 s | 2.58058 s | 4.65763 s |
|1000                | 0.0573661 s | 0.0425347 s | 0.0232645 s | 0.0124618 s | 2.78001 s | 3.42072 s |
|10000               | 0.459018 s | 0.517759 s | 0.240593 s | 0.12372 s | 4.77639 s | 3.70593 s |
|100000              | 4.91634 s | 3.63084 s | 2.26144 s | 1.06545 s | 12.4399 s | 11.5192 s |
|1000000             | 65.5192 s | 36.8776 s | 29.2887 s | 11.5433 s | 98.1781 s | 87.8045 s |
<br/>
Abiejose versijose buvo naudojami tie patys failai su studentų duomenimis, kurie buvo sugeneruoti anksčiau.
Versija V0.5 (su list'u) veikia greičiau negu versija V0.4 (su vektoriumi), ypač skirtumas išryškėja, kai studentų yra labai daug, pvz. 1000000. Iš laikų duomenų, pavaizduotų lentelėje, galima daryti išvadą, kad būtų geriau programą realizuoti su list'u, negu su vektoriumi, norint sutaupyti laiką.
