# Laporan Resmi Praktikum Jarkom Modul 4 Kelompok B09

Anggota Kelompok B09:
| Nama | NRP |
| ---------------------- | ---------- |
| Melanie Sayyidina Sabrina Refman | 5025211029 |
| I Gusti Agung Ngurah Adhi Sanjaya | 5025211056 |

----

## CIDR

## Topologi

Berikut adalah topologi yang digunakan dalam metode CIDR dengan CPT

![topologi CIDR](https://github.com/melanierefman/Jarkom-Modul-4-B09-2023/assets/87106838/47fdb81c-4a0e-4120-89fe-292f5189d76d)

## Tree CIDR

![TREE CIDR (CPT)](https://github.com/melanierefman/Jarkom-Modul-4-B09-2023/assets/87106838/3feaa2f5-8f79-4171-9bb0-1fd52aa159a6)

## Penggabungan IP

![Penggabungan IP](https://github.com/melanierefman/Jarkom-Modul-4-B09-2023/assets/87106838/f2962821-ad18-448b-9713-f57d860992b7)

## Pembagian IP

![pembagian IP](https://github.com/melanierefman/Jarkom-Modul-4-B09-2023/assets/87106838/51a995eb-9082-4a64-9cba-5e812ff173b6)

## Subneting

- Kanao

![1  Kanao](https://github.com/melanierefman/Jarkom-Modul-4-B09-2023/assets/87106838/77b80a49-a269-495c-9722-e041b75ffb9d)

- Zenitsu

![2  Zenitsu](https://github.com/melanierefman/Jarkom-Modul-4-B09-2023/assets/87106838/ff0f165f-d781-4e57-9094-a7b08445244b)
  
- Tanjiro

![3  Tanjiro](https://github.com/melanierefman/Jarkom-Modul-4-B09-2023/assets/87106838/32e4943f-6bfd-4ea5-b063-57e585795bec)
  
- Nezuko

![4  Nezuko](https://github.com/melanierefman/Jarkom-Modul-4-B09-2023/assets/87106838/7868514c-23b9-4967-9b29-e2c54b46b88d)

- Inosuke

![5  Inosuke](https://github.com/melanierefman/Jarkom-Modul-4-B09-2023/assets/87106838/021b2eaa-5e8a-443e-bebf-4090277de104)
  
- Genya

![6  Genya](https://github.com/melanierefman/Jarkom-Modul-4-B09-2023/assets/87106838/bc6ba2ab-e770-462c-8c37-4aac291c5c62)
  
- Sanemi

![7  Sanemi](https://github.com/melanierefman/Jarkom-Modul-4-B09-2023/assets/87106838/d731cee6-642c-48e8-ace4-8e21bb4d3217)
  
- Obanai

![8  Obanai](https://github.com/melanierefman/Jarkom-Modul-4-B09-2023/assets/87106838/e21e85eb-d998-4e6c-a1e3-e8c6d86a1dbc)
  
- Mitsuri

![9  Mitsuri](https://github.com/melanierefman/Jarkom-Modul-4-B09-2023/assets/87106838/ad3c73e2-c57a-47f4-b8fd-2a8b19a84573)
  
- Giyuu

![10  Giyuu](https://github.com/melanierefman/Jarkom-Modul-4-B09-2023/assets/87106838/752be3c7-feaa-4193-a021-0f2a55f3d821)
  
- Rengoku

![11  Rengoku](https://github.com/melanierefman/Jarkom-Modul-4-B09-2023/assets/87106838/95a8c7a2-35b7-472c-bd08-aa7218beccf2)
  
- Ichiro

![12  Ichiro](https://github.com/melanierefman/Jarkom-Modul-4-B09-2023/assets/87106838/4466ff73-0f75-489c-b8f0-08251cedc882)
  
- Shinobu

![13  Shinobu](https://github.com/melanierefman/Jarkom-Modul-4-B09-2023/assets/87106838/7f3732b6-ba27-4b11-b3c4-bfb378b8c434)

## Routing

- Muzan
```
10.15.32.128/30 via 10.15.64.2
10.15.32.0/25 via 10.15.64.2
10.15.0.0/21 via 10.15.64.2
10.15.8.0/25 via 10.15.64.2
10.13.64.0/28 via 10.13.128.2
10.13.0.0/21 via 10.13.128.2
10.13.9.0/25 via 10.13.128.2
10.13.8.0/24 via 10.13.128.2
10.13.10.0/30 via 10.13.128.2
10.13.16.0/30 via 10.13.128.2
10.13.32.0/22 via 10.13.128.2
10.13.64.16/30 via 10.13.128.2
10.14.0.8/30 via 10.14.0.18
10.14.0.0/29 via 10.14.0.18
```

- Daki
```
10.13.0.0/21 via 10.13.16.2
10.13.8.0/24 via 10.13.16.2
10.13.9.0/25 via 10.13.16.2
10.13.10.0/30 via 10.13.16.2
10.13.64.0/28 via 10.13.64.18
0.0.0.0/0 via 10.13.128.1
```

- Yoriichi
```
10.15.32.0/25 via 10.15.32.130
10.15.0.0/21 via 10.15.16.2
10.15.8.0/25 via 10.15.16.2
0.0.0.0/0 via 10.15.64.1
```

- Tamayo
```
0.0.0.0/0 via 10.13.16.1
10.13.8.0/24 via 10.13.10.2
10.13.9.0/25 via 10.13.10.2
```

- Akaza
```
0.0.0.0/0 via 10.14.0.17
10.14.0.0/29 via 10.14.0.10
```

- Gyutarou
```
0.0.0.0/0 via 10.13.64.17
```

- Yushiro
```
0.0.0.0/0 via 10.13.10.1
```

- Douma
```
0.0.0.0/0 via 10.14.0.9
```

- Gyokko
```
0.0.0.0/0 via 10.15.16.1
```

- Hantengu
```
0.0.0.0/0 via 10.15.32.129
```

## Testing

Berikut testing dengan melakukan ping

![testing](https://github.com/melanierefman/Jarkom-Modul-4-B09-2023/assets/87106838/58a46ea1-8d7a-47dd-9346-ae15c06a23b8)

## Kendala

- Nguli
