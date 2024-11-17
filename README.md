# Jarkom-Modul-4-IT32-2024
##### Praktikum Jaringan Komputer Modul 4 Tahun 2024

### Author
| Nama | NRP |
|---------|---------|
| Muhammad Kenas Galeno Putra | 5027231069   |
| Veri Rahman | 5027231088   |

# Laporan Resmi

# Daftar Isi
- [Topologi GNS](#topologi-gns)
- [Perhitungan CIDR](#perhitungan-cidr)
- [CIDR Tree](#cidr-tree)
- [Config dan Routing](#config-cidr)
- [Topologi CPT](#topologi-cpt)
- [Perhitungan VLSM](#perhitungan-vlsm)
- [VLSM Tree](#vlsm-tree)
- [Config dan Routing](#config-vlsm)

### Prefix IP
Kelompok kami memiliki prefix IP *10.79*

### Topologi GNS
<a name="topologi-gns"></a>
<img src="img/topologi-gns.png">

### Perhitungan CIDR
<a name="perhitungan-cidr"></a>
### Pengabungan
Cara :
1. Kelompokkan dari node terjauh dari awan. Hitung router terjauh
2. Gabungkan lagi dari yang sudah dikelompokkan sebelumnya

Pengabungan A
<img src="img/A.png">
Pengabungan B
<img src="img/B.png">
Pengabungan C
<img src="img/C.png">
Pengabungan D
<img src="img/D.png">
Pengabungan E
<img src="img/E.png">
Pengabungan F
<img src="img/F.png">
Pengabungan G
<img src="img/G.png">
Pengabungan H
<img src="img/H.png">
Pengabungan I
<img src="img/I.png">
Pengabungan J
<img src="img/J.png">
Pengabungan K
<img src="img/K.png">

### CIDR Tree
<a name="cidr-tree"></a>
<img src="img/.png">

### Config dan Routing
<a name="config-cidr"></a>
<img src="img/.png">

### Perhitungan VLSM
<a name="perhitungan-vlsm"></a>
<img src="img/.png">
Subnet	Network ID	Netmask	Broadcast	Range IP
A12	10.79.0.0	255.255.248.0	10.79.7.255	10.79.0.1 - 10.79.7.254
A18	10.79.8.0	255.255.252.0	10.79.11.255	10.79.8.1 - 10.79.11.254
A3	10.79.12.0	255.255.254.0	10.79.13.255	10.79.12.1 - 10.79.13.254
A15	10.79.14.0	255.255.254.0	10.79.15.255	10.79.14.1 - 10.79.15.254
A22	10.79.16.0	255.255.254.0	10.79.17.255	10.79.16.1 - 10.79.17.254
A14	10.79.18.0	255.255.255.128	10.79.18.127	10.79.18.1 - 10.79.18.126
A6	10.79.18.128	255.255.255.192	10.79.18.191	10.79.18.129 - 10.79.18.190
A20	10.79.18.192	255.255.255.192	10.79.18.255	10.79.18.193 - 10.79.18.254
A8	10.79.19.0	255.255.255.224	10.79.19.31	10.79.19.1 - 10.79.19.30
A11	10.79.19.32	255.255.255.240	10.79.19.47	10.79.19.33 - 10.79.19.46
A4	10.79.19.48	255.255.255.248	10.79.19.55	10.79.19.49 - 10.79.19.54
A5	10.79.19.56	255.255.255.248	10.79.19.63	10.79.19.57 - 10.79.19.62
A10	10.79.19.64	255.255.255.248	10.79.19.71	10.79.19.65 - 10.79.19.70
A1	10.79.19.72	255.255.255.252	10.79.19.75	10.79.19.73 - 10.79.19.74
A2	10.79.19.76	255.255.255.252	10.79.19.79	10.79.19.77 - 10.79.19.78
A7	10.79.19.80	255.255.255.252	10.79.19.83	10.79.19.81 - 10.79.19.82
A9	10.79.19.84	255.255.255.252	10.79.19.87	10.79.19.85 - 10.79.19.86
A13	10.79.19.88	255.255.255.252	10.79.19.91	10.79.19.89 - 10.79.19.90
A16	10.79.19.92	255.255.255.252	10.79.19.95	10.79.19.93 - 10.79.19.94
A17	10.79.19.96	255.255.255.252	10.79.19.99	10.79.19.97 - 10.79.19.98
A19	10.79.19.100	255.255.255.252	10.79.19.103	10.79.19.101 - 10.79.19.102
A21	10.79.19.104	255.255.255.252	10.79.19.107	10.79.19.105 - 10.79.19.106

### Topologi CPT
![Screenshot 2024-11-17 2024558](https://github.com/user-attachments/assets/3f104672-857e-4293-8729-6273ae2630ee)

### VLSM Tree
<a name="vlsm-tree"></a>
<img src="img/.png">
![image](https://github.com/user-attachments/assets/a2fda60b-9c9c-48dc-b064-56cd802a0742)

### Config dan Routing
<a name="config-vlsm"></a>
<img src="img/.png">
Nama Subnet	Rute	Jumlah IP	Netmask
A1	Hololive > HoloEN	2	/30
A2	Hololive > HoloEN > Holo-Myth	2	/30
A3	Hololive > HoloEN > Holo-Myth > SW2 > Gura_Ame_Ina, Kiara  Calli	503	/23
A4	Hololive > HoloEN > Holo-Myth > HoloPromise > Router4, Holo-Council	3	/29
A5	Hololive > HoloEN > Holo-Myth > HoloPromise > Router4 > Tys	3	/29
A6	Hololive > HoloEN > Holo-Myth > HoloPromise >  Holo-Council > SW4 > Kronii_Mumei, Bae_Fauna	62	/26
A7	Hololive > HoloEN > HoloAdvent	2	/30
A8	Hololive > HoloEN > HoloAdvent > SW0 > FuwaMoco, Shiori_Nerissa, Biboo	28	/27
A9	Hololive > Holo-JP	2	/30
A10	Hololive > Holo-JP > SW1 > DEV_IS, GEN:0	3	/29
A11	Hololive > Holo-JP > SW1 > DEV_IS > Re:GLO$$ > Ririka_Raden, Ao, Hajime_Kanade	14	/28
A12	Hololive > Holo-JP > SW1 > DEV_IS, GEN:0 > SW3 > MiComet, Sora_Robo_AZki, GEN:1	2045	/21
A13	Hololive > Holo-JP > SW1 > DEV_IS, GEN:0 > SW3 > GEN:1 > GAMERS	2	/30
A14	Hololive > Holo-JP > SW1 > DEV_IS, GEN:0 > SW3 > GEN:1 > GAMERS > SW13 > Korone, Okayu, Mio	120	/25
A15	Hololive > Holo-JP > SW1 > DEV_IS, GEN:0 > SW3 > GEN:1 > Member > PBK_Matsuri, Aki_Hachama	470	/23
A16	Hololive > Holo-ID	2	/30
A17	Hololive > Holo-ID > SW6 >  AREA15	2	/30
A18	Hololive > Holo-ID > SW6 > AREA15 > Moona, Bisu, lofi	661	/22
A19	Hololive > Holo-ID > holoro	2	/30
A20	Hololive > Holo-ID > holoro > SW7, Ollie, Anya, Reine	34	/26
A21	Hololive > Holo-ID > holoh3ro	2	/30
A22	Hololive > Holo-ID > holoh3ro > SW8 > Zeta, Kaela, Kobo	299	/23
Total		4263	/19

