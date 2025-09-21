# tutorial mengintegrasikan aplikasi Vscode dengan Github

## setp 1 : buka aplikasi vscode di laptop
## step 2 : klik ikon terminal yang berada di barisan kanan atas
## step 3 : buat folder ssh
untuk membuat folder ssh, tambahkan text
```
ssh-keygen -t ed25519 -C "your email"
```
## step 4 : masukkan nama file
## step 5 : masukkan password 
jika file yang ingin kita integrasikan bersifat rahasia, jika tidak, maka kosongkan saja dengan menekan tombol **enter**
## step 6 : verifikasi password 
isi verifikasi password jika file yang ingin di integrasikan memiliki password
## step 7 : buat file
untuk membuat file, tambahkan text
```
mkdir .ssh
```
## step 8 : buka dokumen di terminal
untuk membuka dokumen di terminal, tambahkan text
```
cd
```
## step 9 : lihat list dokumen yang ada
untuk melihat list dokumen yang ada, tambahkan text
```
ls
```
## step 10 : pindahkan file ke folder ssh
untuk memindahkan file ke dalam folder ssh, tambahkan text
```
cat .ssh/"nama file"
```
## step 11 : copy link yang telah muncul
## step 12 : buka github
untuk membuka website github, bisa menggunakan link
```
https://github.com/.
```
## step 13 : klik ikon profile di pojok kanan atas
## step 14 : klik ikon settings
## step 15 : klik ikon ssh and gpg keys yang ada di barisan kanan
## step 16 : klik ikon new ssh key yang berwarna hijau
## step 17 : tambahkan judul pada bagian tittle
## step 18 : isi authentication key 
jika file yang ingin kita integrasikan bersifat rahasia
## step 19 : masukkan link yang telah di copy kedalam bagian key
## step 20 : klik ikon add ssh key yang berwarna hijau
# maka file telah di integrasikan
