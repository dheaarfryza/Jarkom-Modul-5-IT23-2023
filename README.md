# Jarkom-Modul-5-IT23-2023

**Praktikum Jaringan Komputer Modul 5**

## Author
| Nama | NRP |
|---------------------------|------------|
|Rendy Anfi Yudha| 5027211006 |
|Dhea Arfryza Ananda P. | 5027211013 |

# Laporan Resmi
## Daftar Isi
- [Topologi](#topologi)
- [Subnetting VLSM](#subnetting)
- [Konfigurasi](#konfigurasi)

## Topologi

![Group 801 (2)](https://github.com/dheaarfryza/Jarkom-Modul-5-IT23-2023-/assets/89828723/0c370577-5c8a-4fb3-86dd-bc09df5217a5)


## Rute

| Subnet | Rute                          | Jumlah IP | Netmask | 
|--------|-------------------------------|-----------|---------|
| A1     | Revolte-Switch2               | 2         | /30     |
| A2     | Fern-Richter                  | 2         | /30     |
| A3     | Himmel-Switch1-SchwerMountain | 66        | /25     |
| A4     | Himmel-LaubHills              | 256       | /23     |
| A5     | Frieren-Himmel                | 2         | /30     |
| A6     | Frieren-Stark                 | 2         | /30     |
| A7     | Aura-Frieren                  | 2         | /30     |
| A8     | Aura-Heiter                   | 2         | /30     |
| A9     | Heiter-TurkRegion             | 1023      | /21     |
| A10    | Sein-Switch3-GrabForest       | 514       | /22     |
| Total  |                               | 4255      |         |


## Pembagian IP VLSM

| Subnet | Network ID   | Subnet Mask      | Broadcast        | Netmask | Jumlah IP |
|--------|--------------|------------------|------------------|---------|-----------|
| A1     | 10.75.14.128 | 255.255.255.252  | 10.75.14.131     | /30     | 2         |
| A2     | 10.75.14.132 | 255.255.255.252  | 10.75.14.135     | /30     | 2         |
| A3     | 10.75.14.0   | 255.255.255.128  | 10.75.14.127     | /25     | 66        |
| A4     | 10.75.12.0   | 255.255.254.0    | 10.75.13.255     | /23     | 256       |
| A5     | 10.75.14.136 | 255.255.255.252  | 10.75.14.139     | /30     | 2         |
| A6     | 10.75.14.140 | 255.255.255.252  | 10.75.14.143     | /30     | 2         |
| A7     | 10.75.14.144 | 255.255.255.252  | 10.75.14.147     | /30     | 2         |
| A8     | 10.75.14.148 | 255.255.255.252  | 10.75.14.151     | /30     | 2         |
| A9     | 10.75.0.0    | 255.255.248.0    | 10.75.7.255      | /21     | 1023      |
| A10    | 10.75.8.0    | 255.255.252.0    | 10.75.11.255     | /22     | 514       |


## Konfigurasi GNS
