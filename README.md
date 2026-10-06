# Tugas 1 – Basic Network Configuration

## Identitas

Nama: Tegar Aditya Suratama  
NPM: 2415061100  
Program Studi: Teknik Informatika  
Universitas: Universitas Lampung

## Judul Praktikum

Basic Network Configuration

## Materi

Konfigurasi Dasar Switch, Router, dan End Device

## Software

Cisco Packet Tracer

## Topologi

Topologi praktikum terdiri dari:
- 2 PC
- 1 Switch 2960-24TT
- 1 Router 2911

Koneksi perangkat:
- PC-A Fa0 → S1 Fa0/1
- S1 Fa0/2 → R1 G0/0
- R1 G0/1 → PC-B Fa0

## Konfigurasi IP Address

| Perangkat | Interface | IP Address | Subnet Mask | Default Gateway |
|---|---|---|---|---|
| PC-A | NIC | 192.168.1.10 | 255.255.255.0 | 192.168.1.1 |
| S1 | VLAN 1 | 192.168.1.2 | 255.255.255.0 | 192.168.1.1 |
| R1 | G0/0 | 192.168.1.1 | 255.255.255.0 | - |
| R1 | G0/1 | 192.168.0.1 | 255.255.255.0 | - |
| PC-B | NIC | 192.168.0.10 | 255.255.255.0 | 192.168.0.1 |

## Langkah Praktikum

1. Membangun topologi jaringan
2. Konfigurasi IP address pada end device
3. Konfigurasi switch
4. Verifikasi konfigurasi switch
5. Konfigurasi router
6. Verifikasi konfigurasi router
7. Uji konektivitas jaringan
8. Menjawab soal evaluasi
9. Membuat kesimpulan

## Video Praktikum

[Video Praktikum – Basic Network Configuration](https://youtu.be/oUW1VgDGkps)

## Timestamp Video

- 00:00 Pembukaan
- 00:15 Topologi Jaringan
- 01:14 Step 1 – Membangun Topologi Jaringan
- 02:56 Step 2 – Konfigurasi IP Address End Device
- 05:53 Step 3 – Konfigurasi Switch
- 09:34 Step 4 – Verifikasi Konfigurasi Switch
- 11:20 Step 5 – Konfigurasi Router
- 14:36 Step 6 – Verifikasi Konfigurasi Router
- 15:56 Step 7 – Uji Konektivitas Jaringan
- 17:47 Soal Evaluasi
- 21:25 Kesimpulan
- 23:15 Penutup

## File Praktikum

File Cisco Packet Tracer hasil praktikum ditempatkan di folder ini dengan nama:

`Basic_Network_Configuration.pkt`

