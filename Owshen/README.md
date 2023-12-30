## Bagaimana cara membuat dompet?

### Instalasi dependensi
Pastikan sistem Anda terupdate:
```bash
sudo apt update && sudo apt list --upgradable && sudo apt upgrade -y
```
#### Instal dependensi yang diperlukan:
```
sudo apt install libfuse2
```
### Unduh installer dompet
#### Unduh installer dompet Owshen:
```
wget https://github.com/OwshenNetwork/owshen/releases/download/v0.1.0/Owshen_v0.1.0_x86_64.AppImage
```
#### Buat file yang diunduh menjadi bisa dieksekusi:
```
chmod +x Owshen_v0.1.0_x86_64.AppImage
```
### Membuat dompet baru
'Untuk membuat dompet baru, jangan lupa untuk menyimpan frase sandi:'
```
./Owshen_v0.1.0_x86_64.AppImage init
```
### Pemulihan dompet
'Untuk memulihkan dompet menggunakan frase pemulihan yang sudah ada:'
```
./Owshen_v0.1.0_x86_64.AppImage init --mnemnonic "frase_sandi_anda"
```
### Melihat informasi dompet
'Untuk memeriksa informasi dompet:'
```
./Owshen_v0.1.0_x86_64.AppImage info
```
