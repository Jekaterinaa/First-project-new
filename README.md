# Versija V1.1 (realizacija su vektoriumi)
**Testavimo sistemos parametrai :** <br/>
CPU: i5-7200U 2.70 GHz <br/>
RAM: 8.00 GB <br/>
HDD: 237.00 GB <br/>
## Versijos V1.1 (su klase) veikimo sparta :
| Studentų skaičius | Duomenų nuskaitymas | Dalijimas (2 strategija) | 
|-------------------|---------------------|--------------------------|
|100000             | 6.65415 s           | 1.86616 s                |
|1000000            | 60.084 s            | 18.0013 s                |

## Versijos V1.0 (su struktūra) veikimo sparta :
| Studentų skaičius | Duomenų nuskaitymas | Dalijimas (2 strategija) | 
|-------------------|---------------------|--------------------------|
|100000             | 5.05911 s           | 1.67164 s                |
|1000000            | 43.1325 s           | 18.0267 s                |

**Išvados :** <br/>
Abiejų programų (ir su struktūra, ir su klase) veikimo laikas yra apytiksliai vienodas, bet duomenų nuskaitymas iš failo į klasės vektorių trunka šiek tiek ilgiau, negu į struktūrą. Duomenų dalijimas, naudojant sparčiausią (antrą) strategiją yra praktiškai vienodas ir naudojant struktūrą, ir naudojant klasę
