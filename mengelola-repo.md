# Mengelola Repository

Disini akan dijelaskan bagaimanan cara mengelola repository Github melalui komputer lokal

## Personal Access Token

Saat menggunakan Git, kita akan dimintai untuk otentikasi. Nah, untuk proses otentikasi kita harus memiliki personal access token. Untuk proses memperoleh Personal Access Token, dapat di cek [di sini](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)

## Clone Repository

Lakukan Clone repository menggunakan perintah:

        $ git clone https://github.com/Nouruz219/01-git-github.git
        Cloning into '01-git-github'...
        warning: You appear to have cloned an empty repository.

Akan muncul peringatan bahwa repo yang anda clone kosong, abaikan saja karena repo akan kita kelola melalui komputer lokal

## Mengubah Branch Master Menjadi Main

Untuk mengubah branch utama menjadi main menggunakan perintah:

        $ cd 01-git-github
        $ git branch -m main

## Mengirim Hasil Manipulasi ke Repo Github (Push)

Untuk melakukan push, gunakan perintah:

        $ git status
        On branch main

        No commits yet

        Untracked files:
          (use "git add <file>..." to include in what will be committed)
                download-dan-penginstallan-git.md
                images/

        nothing added to commit but untracked files present (use "git add" to track)

        $ git add -A
        $ git commit -m "Add: download-dan-penginstallan-git.md"
        [main (root-commit) d89e7a2] Add: download-dan-penginstallan-git.md
         2 files changed, 14 insertions(+)
         create mode 100644 download-dan-penginstallan-git.md
         create mode 100644 images/Screenshot_181.png

        $ git push origin main
        Enumerating objects: 5, done.
        Counting objects: 100% (5/5), done.
        Delta compression using up to 12 threads
        Compressing objects: 100% (4/4), done.
        Writing objects: 100% (5/5), 18.70 KiB | 9.35 MiB/s, done.
        Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
        To https://github.com/Nouruz219/01-git-github.git
         * [new branch]      main -> main

## Singkronasi

Untuk melakukukan singkronisasi repo ke komputer lokal menggunakan perintah:

        $ git pull

## Membatalkan Commit Terakhir

Untuk membatalkan commit terakhir saat terjadi kesalahan, maka menggunkan perintah:

        $ git revert HEAD