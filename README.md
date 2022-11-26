# Jarkom-Modul-4-B05-2022

## Anggota 
Nama            | NRP
-------------   | -------------
Helsa Nesta Dhaifullah  | 5025201005
Achmad Nashruddin Riskynanda    | 5025201021
Haniif Ahmad Jauhari  | 5025201224

## Problem VLSM dengan CPT
### Pembagian Subnet
![image](https://user-images.githubusercontent.com/70515589/203836567-31e771a2-980c-4682-b3a4-3afafd9007b5.png)

### Penentuan Jumlah Alamat IP
Menentukan jumlah alamat IP yang dibutuhkan oleh tiap subnet dan melabel netmask berdasarkan jumlah IP yang dibutuhkan. <br>
![image](https://user-images.githubusercontent.com/70515589/203837484-b7f58c31-413d-444e-bfd5-63ac56867307.png)

### Pembentukan Pohon IP
Subnet besar yang dibentuk memiliki NID 192.175.0.0 dengan netmask /20 sehingga pembagian IP berdasarkan NID dan netmask dihitung sesuai dengan pohon berikut. <br>
![image](https://user-images.githubusercontent.com/70515589/203839382-19c1a64d-7d61-4288-8f4a-2b2f897e36b1.png)
Untuk lebih jelasnya dapat dilihat di dalam link berikut https://miro.com/app/board/uXjVPB21bHY=/?share_link_id=260511014183 

### Subnet + IP
Selanjutnya menyesuaikan pembagian IP sesuai dengan subnet yang telah dibagi berdasarkan pohon diatas pada topologi. Setelah itu akan didapatkan pembagian IP untuk tiap nodenya. <br>
![image](https://user-images.githubusercontent.com/70515589/203838694-86031795-294c-4ecd-8db0-0ba065c20793.png)

### Pengaturan Konfigurasi IP
1. Pengaturan konfigurasi Router dengan cara masuk ke router --> config --> masukkan ke fastethernet maupun ethernet yang sudah dipasang dengan modul pada router.
2. Pengaturan konfigurasi PC dengan cara masuk ke dekstop --> IP configuration
#### The Resonance
```
- The Order <br>
  192.175.0.9 subnet 255.255.255.252
- The Instrument <br>
  192.175.0.13 subnet 255.255.255.252
- The Magical <br>
  192.175.0.25 subnet 255.255.255.252
- Server The Beast <br>
  192.175.0.33 subnet 255.255.255.252
```

#### The Order
```
- The Resonance <br>
  192.175.0.10 subnet 255.255.255.252
- Ashaf <br>
  192.175.0.65 subnet 255.255.255.192
- The Minister <br>
  192.175.0.5 subnet 255.255.255.252
```

#### The Minister
```
- The Dauntless <br>
  192.175.0.1 subnet 255.255.255.252
- Guideau <br>
  192.175.8.1 subnet 255.255.252.0
- The Order <br>
  192.175.0.6 subnet 255.255.255.252
```

#### The Dauntless
```
- The Minister <br>
  192.175.0.2 subnet 255.255.255.252
- Phanora dan Johan <br>
  192.175.2.1 subnet 255.255.255.0
```

#### The Instrument
```
- The Resonance <br>
  192.175.0.14 subnet 255.255.255.252
- Matt Cugad <br>
  192.175.0.129 subnet 255.255.255.128
- The Firefist <br>
  192.175.0.17 subnet 255.255.255.252
- The Profound <br>
  192.175.0.21 subnet 255.255.255.252
```

#### The Firefist 
```
- The Instrument <br>
  192.175.0.18 subnet 255.255.255.252
- The Queen <br>
  192.175.3.1 subnet 255.255.255.0
- Oakleave <br>
  192.175.4.1 subnet 255.255.254.0
```

#### The Queen
```
- The Firefist <br>
  192.175.3.2 subnet 255.255.255.0
- Server The Witch <br>
  192.175.0.29 subnet 255.255.255.252
```

#### The Profound
```
- The Instrument <br>
  192.175.0.22 subnet 255.255.255.252
- Spendrow <br>
  192.175.1.1 subnet 255.255.255.128
- Helga <br>
  192.175.1.129 subnet 255.255.255.128
```

#### The Magical 
```
- The Resonance <br>
  192.175.0.26 subnet 255.255.255.252
- Haines dan Corvect
  192.175.6.1 subnet 255.255.254.0
```

#### PC Phanora
```
- IPv4 Address	: 192.175.2.2
- Subnet Mask	:  255.255.255.0
- Default Gateway : 192.175.2.1
- DNS Server 	: 255.255.255.0
```

#### PC Johan
```
- IPv4 Address	: 192.175.2.3
- Subnet Mask	:  255.255.255.0
- Default Gateway : 192.175.2.1
- DNS Server 	: 255.255.255.0
```

#### PC Guideau
```
- IPv4 Address	: 192.175.8.2
- Subnet Mask	:  255.255.252.0
- Default Gateway : 192.175.8.1
- DNS Server 	: 255.255.252.0
```

#### PC Ashaf
```
- IPv4 Address	: 192.175.0.66
- Subnet Mask	:  255.255.255.192
- Default Gateway : 192.175.0.65
- DNS Server 	: 255.255.255.192
```

#### PC Matt Cugad
```
- IPv4 Address	: 192.175.0.130
- Subnet Mask	:  255.255.255.128
- Default Gateway : 192.175.0.129
- DNS Server 	: 255.255.255.128
```

#### PC Keith
```
- IPv4 Address	: 192.175.3.3
- Subnet Mask	:  255.255.255.0
- Default Gateway : 192.175.3.1
- DNS Server 	: 255.255.255.0
```

#### PC Oakleave
```
- IPv4 Address	: 192.175.4.2
- Subnet Mask	:  255.255.254.0
- Default Gateway : 192.175.4.1
- DNS Server 	: 255.255.254.0
```

#### PC Spendrow
```
- IPv4 Address	: 192.175.1.2
- Subnet Mask	:  255.255.255.128
- Default Gateway : 192.175.1.1
- DNS Server 	: 255.255.255.128
```

#### PC Helga
```
- IPv4 Address	: 192.175.1.130
- Subnet Mask	:  255.255.255.128
- Default Gateway : 192.175.1.129
- DNS Server 	: 255.255.255.128
```

#### PC Haines
```
- IPv4 Address	: 192.175.6.2
- Subnet Mask	:  255.255.254.0
- Default Gateway : 192.175.6.1
- DNS Server 	:  255.255.254.0
```

#### PC Corvekt
```
- IPv4 Address	: 192.175.6.3
- Subnet Mask	:  255.255.254.0
- Default Gateway : 192.175.6.1
- DNS Server 	: 255.255.254.0
```

#### Server The Beast
```
- IPv4 Address	: 192.175.0.34
- Subnet Mask	:  255.255.255.252
- Default Gateway : 192.175.0.33
- DNS Server 	: 255.255.255.252
```

#### Server The Witch
```
- IPv4 Address	: 192.175.0.30
- Subnet Mask	:  255.255.255.252
- Default Gateway : 192.175.0.29
- DNS Server 	: 255.255.255.252
```

### Pengaturan Routing
Mengatur konfigurasi static pada setiap router, caranya klik router --> config --> isi format pada submenu static --> klik add

#### The Resonance
``` 
- 192.175.0.64/26 via 192.175.0.10
- 192.175.0.4/30 via 192.175.0.10
- 192.175.0.0/30 via 192.175.0.10
- 192.175.8.0/22 via 192.175.0.10
- 192.175.2.0/24 via 192.175.0.10
- 192.175.0.128/25 via 192.175.0.14
- 192.175.0.16/30 via 192.175.0.14
- 192.175.3.0/24 via 192.175.0.14
- 192.175.4.0/23 via 192.175.0.14
- 192.175.0.28/30 via 192.175.0.14
- 192.175.0.20/30 via 192.175.0.14
- 192.175.1.0/25 via 192.175.0.14
- 192.175.1.128/25 via 192.175.0.14
- 192.175.6.0/23 via 192.175.0.26
```

#### The Order
```
- 0.0.0.0/0 via 192.175.0.9
- 192.175.2.0/24 via 192.175.0.6
- 192.175.0.0/30 via 192.175.0.6
- 192.175.8.0/22 via 192.175.0.6
```

#### The Minister
```
- 0.0.0.0/0 via 192.175.0.5
- 192.175.2.0/24 via 192.175.0.2
```

#### The Dauntless
```
- 0.0.0.0/0 via 192.175.0.1
```

#### The Instrument
```
- 0.0.0.0/0 via 192.175.0.13
- 192.175.3.0/24 via 192.175.0.18
- 192.175.4.0/23 via 192.175.0.18
- 192.175.0.28/30 via 192.175.0.18
- 192.175.1.0/25 via 192.175.0.22
- 192.175.1.128/25 via 192.175.0.22
```

#### The Firefist
```
- 0.0.0.0/0 via 192.175.0.17
- 192.175.0.28/30 via 192.175.3.2
```

#### The Queen
```
- 0.0.0.0/0 via 192.175.3.1
```

#### The Profound
```
- 0.0.0.0/0 via 192.175.0.21
```

#### The Magical
```
- 0.0.0.0/0 via 192.175.0.25
```

### Testing
Untuk testing sendiri dapat dilakukan dengan cara berikut : <br>
  1. Klik Menu Add Simple PDU
  2. Pilih Source
  3. Pilih Destination
  4.  Cek apakah ping tersebut success atau tidak
  
Untuk hasil yang kelompok kami dapat seperti berikut. <br>
![image](https://user-images.githubusercontent.com/70515589/203866153-420a1a7e-8c44-4fba-9e76-6b275cb2a513.png) 
![image](https://user-images.githubusercontent.com/70515589/203866191-161e85e2-60d1-41cf-b52a-e926d654cc01.png)


## Problem CIDR dengan GNS3
### Screenshot Testing

* Guideau
![Guideau](https://user-images.githubusercontent.com/91010605/203541831-df65eaab-2c93-4b78-9e35-955077a308ba.png)
* Ashaf
![Ashaf](https://user-images.githubusercontent.com/91010605/203542613-bcf18cee-9810-4d91-843d-46a8896ade87.png)

* Haines
![Haines](https://user-images.githubusercontent.com/91010605/203542680-0d1bd483-6bfe-4ebe-acd7-5e668463e771.png)

* Corvekt
![Corvekt](https://user-images.githubusercontent.com/91010605/203542705-44d43233-8749-44db-8d40-aa2aa1dc1c01.png)

* MattCugat
![MattCugat](https://user-images.githubusercontent.com/91010605/203542746-e5f3e17f-102a-4a18-a360-b1c1b64a4481.png)

* Spendrow
![Spendrow](https://user-images.githubusercontent.com/91010605/203543224-5961a9a6-f95c-4332-946c-c64695b29e0f.png)

* Phanora
![Phanora](https://user-images.githubusercontent.com/91010605/203543253-27068c71-6230-4247-a747-18f1a103ab0e.png)

* Johan
![Johan](https://user-images.githubusercontent.com/91010605/203543281-65ddfcf0-aca5-4328-a7c3-91022519a74f.png)

* Keith
![Keith](https://user-images.githubusercontent.com/91010605/203543298-e6a97fa7-905c-490e-895f-d2af08d42f93.png)

* Helga
![Helga](https://user-images.githubusercontent.com/91010605/203543325-e38909e3-2417-4c4d-99bc-9a483b62cf12.png)

* Oakleave
![Oakleave](https://user-images.githubusercontent.com/91010605/203543338-58be44b2-7a5a-4b42-b5b8-0e5604a9a2f0.png)


## Kendala 
- Saat Pengerjaan VLSM, konfigurasi IP nya ternyata harus sesuai dengan kabelnya mengarah ke node mana, jadi kemarin sempat gagal karena belum mengetahui hal itu.
