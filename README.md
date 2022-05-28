## Nama dan NIM Anggota Kelompok
| Nama | NIM | Github |
| :---: | :---: | :---: |
| Muhammad Muslim Nur Wahyudi		| 120140008 | [muslimnwhy](https://github.com/muslimnwhy)     |
| Rendy Prayoga			| 120140036 | [rendyprayoga](https://github.com/rendyprayoga)       |
| Fatkhan Aziez Suffi			| 120140181 | [fatkhanas17](https://github.com/fatkhanas17)               |
| Moch Pratama Hidayat			| 120140069 | [MochPratamaHidayat](https://github.com/TamTam4U)     |
| Elgania Aulia Gemintang		| 120140113 | [elganiaaulia](https://github.com/elganiaaulia)               |
| Fauzan Tofikanagari Kumandang	| 120140216 | [Fauzankumandang](https://github.com/Fauzankumandang)                 |


## Jumlegris
#### Deskripsi Projek
Jumlegris adalah sebuah game 2D yang dibuat dengan bahasa Python. Game ini terinspirasi dari Google Chrome ketika tidak ada koneksi internet akan menampilkan game dinosaurus. Jumlegris ini menggunakan karakter yang sesuai dengan namanya yaitu Kalkun. Game ini sangatlah simpel dimana player hanya perlu melompati rintangan yang ada di dalam game.
Game dimulai ketika player menekan tombol play, setelah itu player memainkan seekor kalkun yang dimana kalkun ini avatar dari si player,player harus membuat kalkun tersebut tidak mengenai rintangan yang ada dengan cara akan ada trigger button keyboard spasi(contoh buat lompat ketika ada rintangan di darat ) dan arrow down(contoh buat ada rintangan diatas kepala kalkun ),ketika player gagal menghindari rintangan maka kalkun akan pingsan, dan ketika player berhasil melewati rintangan maka player akan mendapatkan score

## Cara Menjalankan Kontainer
Clone repositori ini atau [unduh disini]([git@github.com:muslimnwhy/Docker-Sistem-Operasi.git](https://github.com/muslimnwhy/Docker-Sistem-Operasi/archive/refs/heads/main.zip)) lalu pindahkan pygame scripts ke folder `~/Downloads`.

Selanjutnya buka terminal pada direktori folder tersebut lalu jalankan perintah build seperti berikut:

    make build

lalu pastikan ada repositori pada docker, dengan cara jalankan command images untuk melihat daftar images pada local storage seperti berikut:

    docker images

Jika proses build telah selesai, jalankan perintah run seperti berikut:

untuk Windows

    make run-windows

untuk Linux

    make run-linux

untuk Mac

    make run-mac

Langkah terakhir yaitu menjalankan pygame melalui container yang telah kita buat dengan perintah seperti berikut:

    python3 -m main.py

## Video Demo Kontainer

[![LIHAT VIDEO DISINI]()

KLIK GAMBAR UNTUK MELIHAT VIDEO :

