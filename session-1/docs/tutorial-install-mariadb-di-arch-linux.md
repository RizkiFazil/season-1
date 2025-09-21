# tutorial install mariabd

## step 1 : install mariadb
untuk menginstall mariadb tambahkan text
```
sudo pacman -S mariadb
```
kemudian tekan enter untuk mulai menginstall
## step 2 : masukkan password dan kembali menekan enter

## step 3 : tambahkan Y
ketika muncul pilihan untuk memproses instalasi, masukkan text 
```
Y
```
## step 4 : install mariadb dengan menggunakan link mysql
```
mariadb-install-db --user=mysql --base dir=/usr --datadir=/var/lib/mysql
```
## step 5 : tekan enter dan masukkan password
## step 6 : aktifkan aplikasi mariadb
untuk mengaktifkan aplikasi mariadb tambahkan text 
```
sudo systemctl start mariadb
```
tekan enter dan masukkan password
## step 7 :jalankan aplikasi mariadb
untuk menjalankan aplikasi mariadb tambahkan text 
```
mariadb
```
