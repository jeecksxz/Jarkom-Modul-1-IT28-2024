# Jarkom-Modul-1-IT28-2024


|Nama  | NRP |
|--|--|
| Muhammad Hildan Adiwena | 5027231077 |
| Syela Zeruya Tandi Lalong | 5027231076 |


# Content

## Pegawai Negeri Sebelah
Kamu seorang data analisis diminta untuk memastikan ulang data-data dari beberapa pegawai

`nc 10.15.42.60 53000`

![PNS](https://github.com/user-attachments/assets/241ee5b5-50fa-49e6-8ffa-72a73f739d14)

1. Siapa yang memiliki password nNnM%coQuF?
   Format: String
   > Jawaban : Vero Tampubolon

   ![PNS 2](https://github.com/user-attachments/assets/3c18d432-4c49-48b6-ba49-7a088404b677)
   
2. Apa jabatan dari Taufan Kuswandari?
   Format: String
   > Jawaban : Analis Kebijakan

   ![PNS 3](https://github.com/user-attachments/assets/f2d152ce-4ad7-4b26-97eb-32b8629246f2)

3. Siapa yang paling awal di list?
   Format: String
   > Jawaban : Cici Mustofa

   ![PNS 4](https://github.com/user-attachments/assets/1d4ff442-d834-4a20-8f15-54927ae359fd)

4. Apa password paling akhir dari list?
   Format: String
   > jawaban : RyxaJPv^yF
```
>Jawaban : Benar! Ini flag-mu: JarkomIT{Tum8eN_p45SnYa_Ku4t_B1aS4Nya_N3A9jnIprJGJrdx4R1O9alr9sL3mXJ1G1KVH8mFFcpptu1ezhPulM4h}
```


## FTP LOGIN
Seseorang menemukan sebuah celah dalam sebuah server. Ia mencoba untuk melakukan brute force login dan ia berhasil masuk. Lakukan pemeriksaan untuk melihat apa yang dilakukan oleh orang tersebut!

`nc 10.15.42.60 49000`

1. Apa username yang berhasil digunakan untuk FTP login?
   Format: username
   > sn34ky

2. Apa password yang berhasil digunakan untuk FTP login?
   Format: string
   > sup3rsn1ff3r
   
   ![FTP LOGIN](https://github.com/user-attachments/assets/650d2afa-41ac-403c-a1f0-514fd201f7f5)
```
> Benar! Ini flag-mu: JarkomIT{n0t_s0_s3cur3_ftp_ViBfewQD7HaaYfe2DPHec0XStL06tJKa0iNpX9KXCfevKuOkkDXXG1N}
```


## EZ
Aku sedang mencoba bikin chat service tapi kayanya pesannya bisa di sniffing deh? coba temukan pesannya.

`nc 10.15.42.60 54000`

1. Temukan jawaban dari log tersebut
   Format: string ex. kata kata
   > jawabannya jawaban

   ![EZ](https://github.com/user-attachments/assets/66f3f4ee-a4e5-4d8d-b194-139979f3e3d3)
2. Port berapa yang digunakan service tersebut
   Format: xxxx: ex. 443
   > 1234
```
> Benar! Ini flag-mu: JarkomIT{BiAr_aman_Pake_sSh_hpu14J3zRLaRxbznIQywbdINW3ztho0kZAdBvDBJOWrcGfHFfs2FEZ}
```


## Advance Sanity Check
Setelah memasukkan `nc 10.15.42.60 44000` ke terminal, terdapat beberapa pertanyaan:
1. Apa username pengirim?
   Format: Username
   > jawaban: JaneD03
   
   ![FTP2](https://github.com/user-attachments/assets/b9d04266-cd38-48b5-b71b-1fcee09b6b79)

2. Apa nama file yang dikirim?
   Format filename.extension
   > jawaban: Clue3.txt
   
   ![a](https://github.com/user-attachments/assets/a72ea087-eeac-4840-802f-c27dc19da54a)

3. Ikuti petunjuk untuk mendapatkan pesan rahasia
   > jawaban: penword
   
   ![Cuplikan layar 2024-09-19 011919](https://github.com/user-attachments/assets/9c599742-772c-4746-8d0b-102b8e62aa4c)
   Kemudian di decode dari Base64 sehingga hasilnya adalah `penword`
```
>Flag: JarkomIT{8uK4n_S4n1ty_b1a5A_yEdRj09BR4vCks0pC1iAeXOljSu5uBIpD3ZaiFZTDMl6BscdbzwpXIKK}
```


## Illegal Breakthrough
Setelah memasukkan `nc 10.15.42.60 46000` ke terminal, terdapat beberapa pertanyaan:
1. Apa IP address dari korban?
   Format: xxx.xxx.xxx.xxx
    > 172.21.88.207
    
    ![f](https://github.com/user-attachments/assets/8058ec62-58c9-4fc4-91a3-0a30e64d0267)

2. Apa port yang digunakan sebagai webserver?
   Format: xxxx: ex. 443
    > 1917
    
    ![f](https://github.com/user-attachments/assets/2dd00850-a6c9-46e2-9ba0-96ea58044395)

3. Dimana endpoint yang terdapat login?
   Format: /endpoint/path.php
    > /ww1.php
    
    ![f](https://github.com/user-attachments/assets/44288188-ec7e-486d-9e20-0b06ff22ba80)

4. Tools apa yang digunakan oleh attacker?
   Format: toolsname-version ex. hydra-v9.0-dev
    > ffuf-v2.1.0-dev
    
    ![f](https://github.com/user-attachments/assets/3f2443f9-0453-4e21-9f04-3bf373064a15)

5. Apa kredensial yang berhasil digunakan oleh attacker untuk login?
   Format: username:password
    > Redbaron:fly1ng4c3
    
    ![w](https://github.com/user-attachments/assets/15fcd61e-d45a-4f32-a340-2d063f095bb6)

```
> Flag: JarkomIT{d34th_fr0m_th3_sky_Fcjy4bimYXweRsjNT8w9zgfICH1GKhpB8PUtDEYnXmsCjp2XHbczWW1}
```

## Surprise 
Setelah memasukkan `nc 10.15.42.60 48500` ke terminal, terdapat beberapa pertanyaan:
1. Apa service yang digunakan pada FTP server?
   Format: service ver ex. proFTPd 1.1.0
    > vsFTPd 3.0.3
    
    ![as](https://github.com/user-attachments/assets/366b8c35-8a2a-44f2-b710-372fb7ee7b24)

2. Apa nama file yang dikirim oleh attacker?
   Format: filename.extension
    > g0tcha.cpp
    
    ![d](https://github.com/user-attachments/assets/edd90273-5beb-458b-a61d-184c71f614fa)

3. Apa pesan rahasia yang ditinggalkan oleh attacker?
   Format: string ex. h4lo wor1d
    > g0tchu n0w l1ttl3 m0us3
    
    ![b](https://github.com/user-attachments/assets/90fa296a-3843-4c4b-ac30-7afbfe5c6191)
   
```
> Flag: JarkomIT{l1ttl3_m0us3_1n_th3_h0us3_Yk9Y8LcLDGxNJItaKOTNVAVQCG08z4VgD1El4jjeKbJKqK9K8U9oTCHU}
```

## Packets Barrage
Setelah memasukkan `nc 10.15.42.60 47000` ke terminal, terdapat beberapa pertanyaan:
1. Apa IP address dari attacker?
   Format: xxx.xxx.xxx.xxx
    > 172.21.80.1
    
    ![q](https://github.com/user-attachments/assets/741fd409-b55a-4afc-bb1f-684e6e635285)

2. Berapa total attempt dari bruteforce attacker?
   Format: number
    > 1917

3. Apa nama file yang didownload oleh attacker setelah berhasil login?
   Format: filename.extension
    > Albatros.txt
    
    ![v](https://github.com/user-attachments/assets/fd91679b-5180-40f4-a4d0-c229865f98b1)

4. Apa isi dari file yang disisipkan oleh attacker?
   Format: string ex. sine sole nihil sum
    > Der Rote Kampfflieger
    
    ![v](https://github.com/user-attachments/assets/4b25837b-3066-42b8-bef9-21f85be7a3e0)
   
```
> Flag: JarkomIT{th3_fly1ng_c1rcus_0f_w4r_zakJr4URtWZbniQyepZj0xrqK5StUTLamJCi5tATTd6pTveEXkXqBACE}
```

## Gajah Terbang (Server Recon)
Setelah memasukkan `nc 10.15.42.60 61000` ke terminal, terdapat beberapa pertanyaan:
1. Apa DBMS yang digunakan pada server tersebut?
   Format: string ex. MonggoDB
    > PostgreSQL
    
    ![qw](https://github.com/user-attachments/assets/1d3edf38-6daf-4c6b-bcc4-1b3f6f347876)

2. Di port berapa DBMS server tersebut berjalan?
   Format: xxxx ex. 443
    > 6969

3. OS apa yang digunakan untuk server tersebut?
   Format: string ex. linux
    > Debian

4. Apa credentials username DBMS valid yang digunakan?
   Format: string
    > s1gm4
    
    ![qw](https://github.com/user-attachments/assets/a0679c33-35ba-47ab-be6c-3ba9f92840e3)

5. Apa nama database yang digunakan?
   Format: string
    > sigmaskibidigyatrizzzz
    
    ![qw](https://github.com/user-attachments/assets/1bd6762c-29f0-4d6d-9b3a-5af38310f2db)

6. Ada berapa banyak users dalam database tersebut?
   Format: number
    > 4
    
    ![n](https://github.com/user-attachments/assets/f7619817-f1a3-4169-841b-3a8ae31592ba)

7. Apa email yang digunakan oleh admin?
   Format: email@gmail.com
    > jojohermawan@gmail.com
    
    ![n](https://github.com/user-attachments/assets/e1673acb-ba06-48e0-8c9a-f1f43f19a0db)

8. Apa password yang digunakan oleh admin?
   Format: string
    > admin1234
    
    ![m](https://github.com/user-attachments/assets/bb91b479-6242-43b1-b158-bffaf95593de)
    Kemudian di decrypt dari Md5 sehingga hasilnya adalah `admin1234`

```
> Flag: JarkomIT{Gy4tT_M5g_4U_GKIF5Uj2pTWNA42KXarPBk3ra5k1VbXAX8ZcWCHiZWSV4SFlGJNQ5BiD1}
```


# Revisi
## Corporate Breach
Setelah memasukkan `nc 10.15.42.60 51000` ke terminal, terdapat beberapa pertanyaan:
1. Siapa nama attacker?
   Format: string
    > Nakhimov

   ![CB1](https://github.com/user-attachments/assets/a272d13b-d7d2-448a-ad5b-4220d6d7a0c6)

2. Apa email yang digunakan untuk login?
   Format: email@gmail.com
    > jarkomsupport@gmail.com
    
   ![CB2](https://github.com/user-attachments/assets/5ff0c616-3fea-433b-9a06-c075c3e5ef6d)
 
3. Apa password yang digunakan untuk login?
   Format: string
    > j4rk0mg4c0rbg
    
   ![CB3](https://github.com/user-attachments/assets/4d4dec6e-82b4-41c2-a026-f3741fc79caa)

```
> Flag: JarkomIT{supp0rt_k0k_l3m4h_bg_fH9URn8RFHBqmBD2Bm8xuvBHRG6BETVBmm6jGxOnr6Pffc6SHQIDG6}
```


## Rizzset
Setelah memasukkan `nc 10.15.42.60 59500` ke terminal, terdapat beberapa pertanyaan:
1. Apa nama domain dari dns query pada log?
   Format: www.domain.com
    > www.its.ac.id
    
   ![rizz1](https://github.com/user-attachments/assets/e4394962-01f7-4517-813f-23220633c482)

2. Berapa IP dari domain tersebut?
   Format: xxx.xxx.xxx.xxx
    > 103.94.189.5
    
   ![rizz2](https://github.com/user-attachments/assets/0bb0162a-3edf-4e5c-acd5-4effdd1d6249)

3. Tuliskan JARM Fingerprint yang dihasilkan dari domain tersebut
   Format: string
   ex. abcdef0123456789abcdef0123456789abcdef0123456789abcdef01234567
    > 2ad2ad16d2ad2ad22c2ad2ad2ad2ad74aaecca9f9c4a3303863dfee62b241e
    
   ![rizz3](https://github.com/user-attachments/assets/bb67e492-a44f-4548-b77f-7456f227e3b2)

```
> Flag: JarkomIT{Dn5_C0rR34t10n_xriKpucsqRXp12XJ1JotbPpanr1zZLLcWEi72PyhYsg8jMTDVNn1Jh1T5} 
```


## Malicious Code
Setelah memasukkan `nc 10.15.42.60 52000` ke terminal, terdapat beberapa pertanyaan:
1. Berapa total attempt attacker melakukan dir listing?
   Format: number
    > 52

2. Apa endpoint yang berhasil attacker dapatkan untuk login page?
   Format: /endpoint/path.php
    > /index.php
    
   ![MC2](https://github.com/user-attachments/assets/6ddbbc5c-0d2f-422e-a480-e1c406f90301)

3. Pada attempt ke berapa attacker menemukan email dan password yang benar?
   Format: number
    > 153

4. Apa jawaban dari pertanyaan sang attacker?
   Format: string
    > merah
    
   ![MC4 1](https://github.com/user-attachments/assets/ae54ab46-b573-462a-a0de-141116d1ac3d)
   ![MC4 2](https://github.com/user-attachments/assets/01121768-4efc-4ac4-a635-82cfb4c074e8)

```
> Flag: JarkomIT{s3cr3t_m3ss4ge_fr0m_4uth0r_4AOwEpWJ1orJLG4LTMFqrbBYDC0mpBv9TES06O1VAF9QTiqpS6ftL0R} 
```


## Gajah Terbang (Attacker Recon)
Setelah memasukkan `nc 10.15.42.60 62000` ke terminal, terdapat beberapa pertanyaan:
1. Akun apa yang dimiliki oleh penyerang dalam database tersebut, berikan emailnya!
   Format: user@gmail.com
    > kuntoajiisrillll@gmail.com
    
   ![GTAR1](https://github.com/user-attachments/assets/9b8ea388-9a30-48fe-af24-4f61b3d352f5)

2. Apa password yang digunakan oleh penyerang?
   Format: string
    > kissme
    
   ![GTAR2 1](https://github.com/user-attachments/assets/3a70e840-d0f2-4b22-84b9-118f8fe9f2f9)
   ![GTAR2 2](https://github.com/user-attachments/assets/a6d0eb8d-6b88-490a-af4d-154df2d47956)

3. Pada tanggal berapa akun penyerang diban?
   Format:  YYYY-MM-DD
   ex. 1945-08-17
    > 2024-06-09
    
   ![GTAR3](https://github.com/user-attachments/assets/c46ea1a6-3fe3-41aa-802e-32378382cc11)

4. Table apa saja yang dimodifikasi oleh penyerang?
   Format: string dan string
    > users dan banned_users
    
   ![GTAR4 1](https://github.com/user-attachments/assets/61383ece-22c8-480f-aa0d-1b32c8478f95)

5. Barang apa saja yang telah dibeli oleh penyerang?
   Format: string dan string
    > rokok dan es krim
    
   ![GTAR5](https://github.com/user-attachments/assets/1d9046a3-32df-403c-bdf7-1d2a5a956edb)

6. Berapa total transaksi dari barang yang dibeli oleh penyerang?
   Format: number
    > 24500
    
   ![GTAR6](https://github.com/user-attachments/assets/65acaab2-179e-4f27-8ad3-49255572be49)

```
Flag: JarkomIT{G4jaH_K0k_t3RbaNG_6M1foskk5Gh9poxHHNJavpWYuYntx8SoLYVniUcVLZaqdgciE7XqGKt5} 
```
