# Jarkom-Modul-1-IT28-2024


|Nama  | NRP |
|--|--|
| Muhammad Hildan Adiwena | 5027231077 |
| Syela Zeruya Tandi Lalong | 5027231076 |


## Content

## Pegawai Negeri Sebelah
Kamu seorang data analisis diminta untuk memastikan ulang data-data dari beberapa pegawai

nc 10.15.42.60 53000

![PNS](https://github.com/user-attachments/assets/241ee5b5-50fa-49e6-8ffa-72a73f739d14)

Siapa yang memiliki password nNnM%coQuF?
Format: String
> Jawaban : Vero Tampubolon


![PNS 2](https://github.com/user-attachments/assets/3c18d432-4c49-48b6-ba49-7a088404b677)
Apa jabatan dari Taufan Kuswandari?
Format: String
> Jawaban : Analis Kebijakan


![PNS 3](https://github.com/user-attachments/assets/f2d152ce-4ad7-4b26-97eb-32b8629246f2)
Siapa yang paling awal di list?
Format: String
> Jawaban : Cici Mustofa


![PNS 4](https://github.com/user-attachments/assets/1d4ff442-d834-4a20-8f15-54927ae359fd)
Apa password paling akhir dari list?
Format: String
> jawaban : RyxaJPv^yF

>Jawaban : Benar! Ini flag-mu: JarkomIT{Tum8eN_p45SnYa_Ku4t_B1aS4Nya_N3A9jnIprJGJrdx4R1O9alr9sL3mXJ1G1KVH8mFFcpptu1ezhPulM4h}


## FTP LOGIN
Seseorang menemukan sebuah celah dalam sebuah server. Ia mencoba untuk melakukan brute force login dan ia berhasil masuk. Lakukan pemeriksaan untuk melihat apa yang dilakukan oleh orang tersebut!
nc 10.15.42.60 49000 


Apa username yang berhasil digunakan untuk FTP login?
Format: username
> sn34ky


Apa password yang berhasil digunakan untuk FTP login?
Format: string
> sup3rsn1ff3r
![FTP LOGIN](https://github.com/user-attachments/assets/650d2afa-41ac-403c-a1f0-514fd201f7f5)

> Benar! Ini flag-mu: JarkomIT{n0t_s0_s3cur3_ftp_ViBfewQD7HaaYfe2DPHec0XStL06tJKa0iNpX9KXCfevKuOkkDXXG1N}

## EZ
Aku sedang mencoba bikin chat service tapi kayanya pesannya bisa di sniffing deh? coba temukan pesannya.
nc 10.15.42.60 54000


Temukan jawaban dari log tersebut
Format: string ex. kata kata
> jawabannya jawaban


![EZ](https://github.com/user-attachments/assets/66f3f4ee-a4e5-4d8d-b194-139979f3e3d3)
Port berapa yang digunakan service tersebut
Format: xxxx: ex. 443
> 1234

> Benar! Ini flag-mu: JarkomIT{BiAr_aman_Pake_sSh_hpu14J3zRLaRxbznIQywbdINW3ztho0kZAdBvDBJOWrcGfHFfs2FEZ}


## Advance Sanity Check
Setelah memasukkan `nc 10.15.42.60 44000` ke terminal, terdapat beberapa pertanyaan:
1. Apa username pengirim?
   Format: Username
   > jawaban: JaneD03

2. Apa nama file yang dikirim?
   Format filename.extension
   > jawaban: Clue3.txt

3. Ikuti petunjuk untuk mendapatkan pesan rahasia
   > jawaban: penword

>Flag: JarkomIT{8uK4n_S4n1ty_b1a5A_yEdRj09BR4vCks0pC1iAeXOljSu5uBIpD3ZaiFZTDMl6BscdbzwpXIKK}


## Illegal Breakthrough
Setelah memasukkan `nc 10.15.42.60 46000` ke terminal, terdapat beberapa pertanyaan:
1. Apa IP address dari korban?
   Format: xxx.xxx.xxx.xxx
    > 172.21.88.207     

2. Apa port yang digunakan sebagai webserver?
   Format: xxxx: ex. 443
    > 1917

3. Dimana endpoint yang terdapat login?
   Format: /endpoint/path.php
    > /ww1.php

4. Tools apa yang digunakan oleh attacker?
   Format: toolsname-version ex. hydra-v9.0-dev
    > ffuf-v2.1.0-dev 

5. Apa kredensial yang berhasil digunakan oleh attacker untuk login?
   Format: username:password
    > Redbaron:fly1ng4c3

> Flag: JarkomIT{d34th_fr0m_th3_sky_Fcjy4bimYXweRsjNT8w9zgfICH1GKhpB8PUtDEYnXmsCjp2XHbczWW1}


## Surprise 
Setelah memasukkan `nc 10.15.42.60 48500` ke terminal, terdapat beberapa pertanyaan:
1. Apa service yang digunakan pada FTP server?
   Format: service ver ex. proFTPd 1.1.0
    > vsFTPd 3.0.3

2. Apa nama file yang dikirim oleh attacker?
   Format: filename.extension
    > g0tcha.cpp

3. Apa pesan rahasia yang ditinggalkan oleh attacker?
   Format: string ex. h4lo wor1d
    > g0tchu n0w l1ttl3 m0us3

> Flag: JarkomIT{l1ttl3_m0us3_1n_th3_h0us3_Yk9Y8LcLDGxNJItaKOTNVAVQCG08z4VgD1El4jjeKbJKqK9K8U9oTCHU}


## Packets Barrage
Setelah memasukkan `nc 10.15.42.60 47000` ke terminal, terdapat beberapa pertanyaan:
1. Apa IP address dari attacker?
   Format: xxx.xxx.xxx.xxx
    > 172.21.80.1

2. Berapa total attempt dari bruteforce attacker?
   Format: number
    > 1917

3. Apa nama file yang didownload oleh attacker setelah berhasil login?
   Format: filename.extension
    > Albatros.txt

4. Apa isi dari file yang disisipkan oleh attacker?
   Format: string ex. sine sole nihil sum
    > Der Rote Kampfflieger

> Flag: JarkomIT{th3_fly1ng_c1rcus_0f_w4r_zakJr4URtWZbniQyepZj0xrqK5StUTLamJCi5tATTd6pTveEXkXqBACE}


## Gajah Terbang
Setelah memasukkan `nc 10.15.42.60 61000` ke terminal, terdapat beberapa pertanyaan:
1. Apa DBMS yang digunakan pada server tersebut?
Format: string ex. MonggoDB
> PostgreSQL

2. Di port berapa DBMS server tersebut berjalan?
   Format: xxxx ex. 443
    > 6969

3. OS apa yang digunakan untuk server tersebut?
   Format: string ex. linux
    > Debian

4. Apa credentials username DBMS valid yang digunakan?
   Format: string
    > s1gm4

5. Apa nama database yang digunakan?
   Format: string
    > sigmaskibidigyatrizzzz

6. Ada berapa banyak users dalam database tersebut?
   Format: number
    > 4

7. Apa email yang digunakan oleh admin?
   Format: email@gmail.com
    > jojohermawan@gmail.com

8. Apa password yang digunakan oleh admin?
   Format: string
    > admin1234

> Flag: JarkomIT{Gy4tT_M5g_4U_GKIF5Uj2pTWNA42KXarPBk3ra5k1VbXAX8ZcWCHiZWSV4SFlGJNQ5BiD1}



