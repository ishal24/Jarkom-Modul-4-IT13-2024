# Lapres Praktikum Jaringan Komputer Modul-3 IT13
**Anggota Kelompok**

| Nama                   | NRP          |
| ---------------------- | ------------ |
| Muhammad Faishal Rizqy | `5027221026` |
| Rafif Dhimaz Ardhana   | `5027221066` |


## 1. Topologi CPT, CIDR
![topologicidr](./img/Topology-CIDR.png)

## 2. Topologi GNS, VLSM
![topologivlsm](./img/Topology-VLSM.jpg)

## 3. Rute
![rute](./img/Rute.jpg)

## 4. VLSM
### 4.a. Tree
![treevlsm](./img/tree/Tree-VLSM.jpg)
### 4.b. Pembagian IP
![ipvlsm](./img/Pembagian-IP-VLSM.jpg)
### 4.c. Network Config

`Jawa`
```bash
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet dhcp

#A3
auto eth1
iface eth1 inet static
address 10.70.21.185
netmask 255.255.255.252

#A15
auto eth2
iface eth2 inet static
address 10.70.21.201
netmask 255.255.255.252

#A16
auto eth3
iface eth3 inet static
address 10.70.21.205
netmask 255.255.255.252
```


### 4.d. Routing
### 4.e. Testing

## 5. CIDR
### 5.a. Penggabungan Subnet

- Subnet Awal
![Subnet_A](./img/subnet/Subnet%20A.png)

- Penggabungan Subnet pertama (Subnet B)
![Subnet_B](./img/subnet/Subnet%20B.png)
![Subnet_B](./img/penggabungan/B.png)

- Penggabungan Subnet kedua (Subnet C)
![Subnet_C](./img/subnet/Subnet%20C.png)
![Subnet_C](./img/penggabungan/C.png)

- Penggabungan Subnet ketiga (Subnet D)
![Subnet_D](./img/subnet/Subnet%20D.png)
![Subnet_D](./img/penggabungan/D.png)

- Penggabungan Subnet keempat (Subnet E)
![Subnet_E](./img/subnet/Subnet%20E.png)
![Subnet_E](./img/penggabungan/E.png)

- Penggabungan Subnet kelima (Subnet F)
![Subnet_F](./img/subnet/Subnet%20F.png)
![Subnet_F](./img/penggabungan/F.png)

- Penggabungan Subnet keenam (Subnet G)
![Subnet_G](./img/subnet/Subnet%20G.png)
![Subnet_G](./img/penggabungan/G.png)

- Penggabungan Subnet ketujuh (Subnet H)
![Subnet_H](./img/subnet/Subnet%20H.png)
![Subnet_H](./img/penggabungan/H.png)

- Penggabungan Subnet kedelapan (Subnet I)
![Subnet_I](./img/subnet/Subnet%20I.png)
![Subnet_I](./img/penggabungan/I.png)

- Penggabungan Subnet kesembilan (Subnet J)
![Subnet_J](./img/subnet/Subnet%20J.png)
![Subnet_J](./img/penggabungan/J.png)

- Penggabungan Subnet terakhir (Subnet K)
![Subnet_K](./img/subnet/Subnet%20K.png)
![Subnet_K](./img/penggabungan/K.png)

### 5.b. Tree
![Tree_CIDR](./img/tree/Tree-CIDR.jpg)

### 5.c. Pembagian IP
![Pembagian_IP](./img/Pembagian-IP-CIDR.png)

### 5.d. Testing

https://github.com/ishal24/Jarkom-Modul-4-IT13-2024/blob/main/vid/Test_CIDR.mp4