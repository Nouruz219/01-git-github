# Download GIT

Disni akan dijelaskan bagaimana cara mendownload dan proses penginstallan Git versi Windows

## Langkah-Langkah Mendownload GIT

* Sebelum menggunakan GIT, anda harus terlebih dahulu mendownload GIT [di sini](https://git-scm.com/downloads)
* Sesuaikan sistem operasi yang akan anda gunakan sebelum memulai proses mendownload
* Ada tiga jenis Sistem Operasi yang dapat menggunakan GIT yaitu Windows, Linux, dan macOS
* Untuk GIT versi windows sendiri memiliki versi yang 32 bit dan 64 bit, sesuaikan dengan versi OS Windows yang anda miliki

## Langkah-Langkah Penginstalan GIT

![01-screenshoot](/images/Screenshot_181.png)

* Pada awal proses penginstallan Git, akan ditampilkan Documnet License dari Git
* Klik **Next** untuk melanjutkan

![02-screenshoot](/images/Screenshot_182.png)

* Pilih lokasi penginstallan aplikasi Git di komputer anda
* Jika ingin mengubah lokasi penginstallan dapat mengklik browse
* Klik **Next** untuk melanjutkan

![03-screenshoot](/images/Screenshot_183.png)

* Kemudian pilih komponen tambahan untuk install Git
* Fungsi komponen ini adalah untuk memperlancar penggunaan Git dan mendukung file dengan kapasitas besar
* Klik **Next** untuk melanjutkan

![04-screenshoot](/images/Screenshot_184.png)

* Anda dapat mengganti nama aplikasi Git sesuai kemauan anda
* Namun disarankan untuk tetap menggunakan Git untuk kemudahan saat akan mencari aplikasinya di laptop anda
* Klik **Next** untuk melanjutkan

![05-screenshoot](/images/Screenshot_185.png)

* Anda dapat menentukan file editor yang akan anda gunakan
* Klik **Next** untuk melanjutkan

![06-screenshoot](/images/Screenshot_186.png)

* Kemudian anda harus mengatur path environment
* Path Environment berfungsi untuk mengeksekusi perintah perintah pada GIT
* Klik **Next** untuk melanjutkan

![07-screenshoot](/images/Screenshot_192.png)

* Pilih Use OpenSSH, aplikasi default SSH dari Git
* Klik **Next** untuk melanjutkan

![08-screenshoot](/images/Screenshot_189.png)

* Pilih Checkout Windows-style, commit Unix-style line endings
* Klik **Next** untuk melanjutkan

![09-screenshoot](/images/Screenshot_190.png)

* Anda bisa menggunakan Command Prompt atau MinTTY sebagai emulator terminal
* Klik **Next** untuk melanjutkan

![10-screenshoot](/images/Screenshot_191.png)

* Untuk opsi ekstra, anda dapat memilih Enable File System Caching dan Enable Git Credential Manager
* Klik **Next** untuk melanjutkan

![11-screenshoot](/images/Screenshot_193.png)

* Terakhir anda dapat memulai proses Installasi Git

![12-screenshoot](/images/Screenshot_193.png)

## Konfigurasi Git

Untuk konfigurasi dapat langsung membuka Git Bash dan gunakan perintah:

'''
$ git config --global user.name "user name di GitHub"
$ git config --global user.email alamat@email.github
'''

Untuk melihat konfigurasi, dapat menggunakan perintah:

'''
$ git config --list
'''