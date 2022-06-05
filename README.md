# Tugas-6-Sistem-Basis-Data-20.D1

| Nama      | Fakhrudin Nizar |
| ----------- | ----------- |
| NIM     | 312010195  |
| Kelas   | TI.20.D.1    |

### LANGKAH - LANGKAH TUGAS 6 SISTEM BASIS DATA TI.20.D1

### 1. Masuk Ke Database Nama_nim

![soal nomor1](https://user-images.githubusercontent.com/74331125/172011921-1c0c8fce-0266-4de7-a2eb-be9010967eef.png)

### 2. Lakukan proses Backup Dengan Sql Dari Database Tugas Sebelumnya !

![soal nomor 2 recovery](https://user-images.githubusercontent.com/74331125/172042063-e679f4ca-760c-4acb-8180-102e76c723d1.png)

### 3. Jika Proses Berhasil Maka Akan Muncul File Backup Pada Direktori C:\xampp\mysql\data\nama database

![2022-06-04 (6)](https://user-images.githubusercontent.com/74331125/172012120-4da64af9-9eeb-4f90-8373-e8a3460e244e.png)

### 4.  Recovery
Data Yang Telah Di-Backup Dapat Dikembalikan Kapan Saja Bila Diperlukan. Sintaks SQL Yang Digunakan Adalah LOAD DATA INFILE. Perintah Yang Dijalankan Adalah :
- LOAD DATA INFILE ‘Nama_backup_file’ INTO TABLE nama_table ;

![soal nomor 2 backup](https://user-images.githubusercontent.com/74331125/172012852-4ad72a5f-da12-4856-876f-00f2a6eab83c.png)

### 5. Lakukan Proses Backup dan Recovery Dengan Sqldump Dari Database Tugas Sebelumnya !

![versi dump1](https://user-images.githubusercontent.com/74331125/172012909-ce675d94-361e-40a5-b18a-0b8dd91e64fd.png)

### 6.  Tulisakan Script Cron Job Untuk Melakukan Backup Otomatis Setiap Hari Minggu Jam 12 Malam !

- Crontab –e

5923***myqldump -u adminklinik -p klinik_312010195>BackupTugas6.sql
