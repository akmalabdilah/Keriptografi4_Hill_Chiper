# Kriptografi Pertemuan 5


## Profil
| #               | Biodata                      |
| --------------- | ---------------------------- |
| **Nama**        | M. AKMAL AL ABDILAH          |
| **NIM**         | 312110034                    |
| **Kelas**       | TI.21.A.1                    |
| **Mata Kuliah** | Kriptografi                  |

## Note Sebelum Membaca Tonton Video Singkat Ini  Dulu

## Encryption Hill Cipher Video Simulasi Singgat



Lihat video YouTube [di sini](video.html).
<p align="center">
 <img src="[screen-capture.webm](https://github.com/akmalabdilah/Keriptografi4_Hill_Chiper/assets/92352562/5cb957d2-eb57-455c-9ac5-7dea35019678)"/>
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/91085882/137566814-9c8c078c-1c3e-475c-b23d-7f4922f74beb.gif"/>
</p>
<p align="center">
<a href="https://github.com/akmalabdilah"><img title="Author" src="https://img.shields.io/discord/102860784329052160?color=BLUE&label=M.%20AKMAL%20AL%20ABDILAH1&logo=GITHUB&logoColor=BLACK&style=plastic"></a>
<p align="center">



<hr>

## Kriptografi membuat sistem aplikasi  enkripsi  Hill chipper 

<hr>



## Encryption Hill Cipher
<p>Hill Cipher adalah sebuah algoritma enkripsi dalam kriptografi yang menggunakan matriks sebagai kunci enkripsi. Algoritma ini dikembangkan oleh Lester S. Hill pada tahun 1929. Hill Cipher digunakan untuk mengenkripsi dan mendekripsi teks dengan menggunakan kunci matriks. Enkripsi Hill Cipher adalah proses mengubah teks plainteks menjadi teks terenkripsi, sedangkan dekripsi adalah proses mengubah teks terenkripsi kembali menjadi teks asli (plainteks).</p>

### Cara Kerja

<p>Cara kerja program ini secara detail adalah sebagai berikut:</p>

1. **Input Pengguna**:
   - Pengguna mengakses halaman `index.php` yang menampilkan formulir untuk memasukkan teks plainteks, matriks kunci (2x2), dan memilih mode enkripsi atau dekripsi (dengan mode diatur dalam radio button). 

2. **Pengolahan Input**:
   - Setelah pengguna mengisi formulir dan mengirimkannya, data yang dimasukkan diambil dengan metode POST di halaman `hill_cipher.php`.

3. **Inisialisasi Koneksi Database**:
   - Halaman `hill_cipher.php` menginisialisasi koneksi ke database MySQL. Informasi koneksi seperti nama host, nama pengguna, kata sandi, dan nama database didefinisikan di halaman ini.

4. **Pemrosesan Data**:
   - Halaman `hill_cipher.php` mengambil data yang dimasukkan oleh pengguna, termasuk teks plainteks, matriks kunci, dan mode (enksripsi atau dekripsi). Data ini kemudian disimpan ke dalam variabel-variabel yang sesuai.

5. **Enkripsi atau Dekripsi**:
   - Program menggunakan fungsi `hill_cipher` dari `functions.php` untuk melakukan enkripsi atau dekripsi, tergantung pada mode yang dipilih oleh pengguna. Fungsi ini bekerja sebagai berikut:
     - Mengubah teks plainteks menjadi huruf kapital dan menghapus spasi (jika ada).
     - Memastikan panjang teks genap dengan menambahkan huruf "X" jika perlu.
     - Memproses teks plainteks per karakter atau per pasangan karakter, tergantung pada mode.
     - Menggunakan matriks kunci untuk melakukan operasi enkripsi atau dekripsi sesuai dengan aturan Hill Cipher.

6. **Penyimpanan Hasil**:
   - Hasil enkripsi atau dekripsi disimpan dalam variabel `result`.

7. **Simpan ke Database**:
   - Hasil enkripsi atau dekripsi bersama dengan teks, kunci, dan mode disimpan ke dalam database MySQL menggunakan perintah SQL. Hasil ini akan digunakan untuk ditampilkan di halaman `data.php` dan dapat diakses kembali di masa mendatang.

8. **Tampilan Hasil**:
   - Halaman `hill_cipher.php` menampilkan hasil enkripsi atau dekripsi, teks, kunci, dan mode kepada pengguna dalam bentuk yang mudah dibaca.

9. **Navigasi Kembali**:
   - Pengguna dapat kembali ke halaman `index.php` untuk melakukan operasi Hill Cipher lainnya atau melihat hasil yang telah disimpan.

10. **Penghapusan Data**:
    - Pengguna dapat mengakses halaman `data.php` untuk melihat hasil enkripsi Hill Cipher yang telah disimpan dalam database. Mereka juga dapat memilih untuk menghapus hasil tertentu dengan mengklik tautan yang sesuai di halaman `data.php`. Penghapusan ini diimplementasikan di halaman `delete.php`.


<P>
Oke sekian penjelasan singkat saya mengenai tugas kriptografi kali ini jika kalian masih penasara kalian bisa mencoba file lengkap  Hill chiper code yang ada di atas kurang lebih saya mohon maaf.
</P>

<p>
 sekian and selesai.
</p>

<div>
<h2 align="center">Thanks For Reading!!!</h2>
<div align="center">
<img src="https://user-images.githubusercontent.com/91085882/222731693-24383140-7623-4e7a-a528-6621380b7be8.gif">
