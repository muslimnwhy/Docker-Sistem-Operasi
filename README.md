## Nama dan NIM Anggota Kelompok
| Nama | NIM | Github |
| :---: | :---: | :---: |
| Muhammad Muslim Nur Wahyudi		| 120140008 | [muslimnwhy](https://github.com/muslimnwhy)     |
| Rendy Prayoga			| 120140036 | [rendyprayoga](https://github.com/rendyprayoga)       |
| Fatkhan Aziez Suffi			| 120140181 | [fatkhanas17](https://github.com/fatkhanas17)               |
| Moch Pratama Hidayat			| 120140069 | [MochPratamaHidayat](https://github.com/MochPratamaHidayat)     |
| Elgania Aulia Gemintang		| 120140113 | [elganiaaulia](https://github.com/elganiaaulia)               |
| Fauzan Tofikanagari Kumandang	| 120140216 | [Fauzankumandang](https://github.com/Fauzankumandang)                 |


## Jumlegris
#### Deskripsi Projek
Bounce Back merupakan game yang mampu menampilkan objek pemantul yang warnanya dapat dipilih oleh user dan menampilkan objek bola, bata, bonus, score dan menghentikan game ketika menu permainan ditampilkan. Ketika bola menyentuh bagian bawah layar, maka game akan berakhir. Selain itu program akan menampilkan sebuah menu dimana pemain dapat memainkan game dimulai dari awal atau pemain ingin mengakhiri permainan.

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
