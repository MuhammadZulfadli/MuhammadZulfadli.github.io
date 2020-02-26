# Overview Materi Tgl 25 Februari
## GIT

### Menggunakan Git

- Membuat repository project di Github
- Pindah ke direktori project
- lakukan perintah

Untuk menginisialiasi repository pada komputer lokal

```sh
$ git init
```
Untuk menambahkan file baru ke repository

```sh
$ git add nama_file
```

Cek status repository dengan perintah berikut : 
```sh
$ git status
```

Lakukan commit, yang bertujuan untuk menyimpan perubahan yang baru saja di lakukan

```sh
$ git commit -m "pesan perubahan"
```

mengirimkan file ke dalam repository
```sh
$ git push -u origin master
```


##### Solve conflict

Melakukan clone pada project

```sh
$ git clone https://github.com/adhewahyu-dev/adhewahyu-dev.github.io.git => alamat project tim
```
membuat branch baru

```sh
$ git branch nama_branch
```

pindah ke branch yang baru saja dibuat
```sh
$ git checkout nama_branch
```

Lakukan perubahan pada file project tersebut, lalu add, cek status dan commit
```sh
$ git add nama_file
```

```sh
$ git status
```

```sh
$ git commit -m "pesan perubahan"
```

lakukan push pada file yang diubah di sisi branch baru
```sh
$ git push origin nama_branch
```

### contribute project tim
```sh
$ git clone https://github.com/adhewahyu-dev/adhewahyu-dev.github.io.git => alamat project tim
```

membuat branch baru

```sh
$ git branch nama_branch
```

pindah ke branch yang baru saja dibuat
```sh
$ git checkout nama_branch
```

Lakukan perubahan pada file projectnya lalu add, commit dan push
```sh
$ git add nama_file
```

```sh
$ git commit -m "pesan perubahan"
```

```sh
$ git push origin nama_branch
```
