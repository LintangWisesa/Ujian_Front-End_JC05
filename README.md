# Soal Ujian Purwadhika Front-End Web Development

![Lintang_Purwadhika](https://static.wixstatic.com/media/2e6af2_f69a4271c3534ae1869a7ed63e278b2b~mv2.png/v1/fill/w_246,h_39,al_c,usm_0.66_1.00_0.01/2e6af2_f69a4271c3534ae1869a7ed63e278b2b~mv2.png)

**Materi Front-End Web Dev dapat diakses di [klik sini!](https://github.com/LintangWisesa/Purwadhika-JC05-02_FrontEnd)**
#

Panduan selengkapnya klik video berikut atau [klik di sini!](https://www.youtube.com/watch?v=mMdf0Q5VeCc)

[![Video_Lintang](https://img.youtube.com/vi/mMdf0Q5VeCc/0.jpg)](https://www.youtube.com/watch?v=mMdf0Q5VeCc)

#
### **Soal 1 - Kartu Lebaran**

Hanya dengan HTML & CSS, buatlah sebuah kartu Lebaran sederhana seperti gambar di bawah ini. Fitur yang diminta hanya gambar belah ketupat (_**bukan gambar/image!**_) dan teks dengan Google Fonts.

![Lintang_Lebaran](https://2.bp.blogspot.com/-wEKPsXIBSx4/Ww9iaGiv4TI/AAAAAAAAEK8/TEpx9tKDUOwaXcJzDe9UDQ6xGwFi3gfbwCLcBGAs/s1600/soal1b.png)

>_**Catatan:**_ *Commit/upload project ini ke akun Github Anda dengan nama repo: **Kartu-Lebaran-NamaAnda**. Salin file HTML aplikasi ini ke dalam format .txt, sertakan pula link url ke repo Github project ini. Lanjutkan ke soal nomor 2, Kemudian kirimkan via email ke lintang@purwadhika.com dengan subject email: __Ujian-Front-1&2-namaAnda__.*

#
### **Soal 2 - Dropdown Bersambung**

Buatlah sebuah project React yang memiliki 2 buah dropdown menu (_**Jenjang Pendidikan**_ dan _**Tingkatan Pendidikan**_), di mana konten opsi menu dropdown kedua (**_Tingkatan Pendidikan_**) bergantung pada pilihan user di menu dropdown pertama (_**Jenjang Pendidikan**_). Opsi yang user pilih akan ditampilkan sebagai title pada button dropdown. Adapun susunan opsi menu sebagai berikut:

- __Pendidikan Pra Sekolah__
  - *PAUD (Pendidikan Anak Usia Dini)*
  - *TK (Taman Kanak-kanak)*
  - *RA (Raudhatul Athfal)*

- __Pendidikan Dasar__
  - *SD (Sekolah Dasar)*
  - *MI (Madrasah Ibtidaiyah)*
  - *SMP (Sekolah Menengah Pertama)*
  - *MTs (Madrasah Tsanawiyah)*

- __Pendidikan Menengah__
  - *SMA (Sekolah Menengah Atas)*
  - *MA (Madrasah Aliyah)*
  - *SMK (Sekolah Menengah Kejuruan)*

- __Pendidikan Tinggi__
  - *D3 Diploma*
  - *S1/D4 Sarjana*
  - *S2 Magister*
  - *S3 Doktoral*

![Lintang_Dropdown](https://1.bp.blogspot.com/-NCLE7bZNi-c/Ww9icUaTBXI/AAAAAAAAELA/Cnto57R195UeJcTHPHHEXViUuhukqCplgCLcBGAs/s1600/soal2a.png)

>_**Catatan:**_ *Commit/upload project ini ke akun Github Anda dengan nama repo: **Dropdown-NamaAnda**. Salin file App.js aplikasi ini ke dalam format .txt, sertakan pula link url ke repo Github project ini. Kemudian kirimkan beserta jawaban nomor 1 via email ke lintang@purwadhika.com dengan subject email: __Ujian-Front-1&2-namaAnda__.*

#
### **Soal 3 - Aplikasi Info Bitcoin**

Buatlah sebuah aplikasi React yang memanfaatkan info seputar Bitcoin dari Blockchain Exchange Rates API ([https://blockchain.info/api/exchange_rates_api](https://blockchain.info/api/exchange_rates_api)), dengan persyaratan sebagai berikut:

- **Gunakan navigasi React-Router-DOM**
  - Aplikasi terdiri atas **_3 halaman utama_**: halaman info harga Bitcoin, halaman konversi Rupiah ke Bitcoin dan halaman konversi Bitcoin ke Rupiah. Gunakan Route untuk membuat path bagi setiap halaman.

- **Gunakan Blockchain API**
  - Halaman pertama (info harga Bitcoin) menyajikan harga jual & harga beli Bitcoin terhadap 5 mata uang asing: **_Dollar Australia (AUD), Euro Eropa (EUR), Poundsterling Inggris (GBP), Yen Jepang (JPY)_** dan **_Dollar Amerika (USD)_**. Gunakan Exchange Rates API yang disediakan [Blockchain.info](https://blockchain.info/api/exchange_rates_api). Untuk mendapatkan semua data harga Bitcoin terhadap beberapa mata uang asing, gunakan:
    ```bash
    GET
    https://blockchain.info/ticker
    ```

  - Halaman kedua (konversi Rupiah ke Bitcoin) menyajikan fitur bagi user untuk mengkonversi Rupiah menjadi Bitcoin, dengan catatan 1 USD setara dengan Rp 14.000,-. Gunakan Bitcoin Conversion API yang disediakan [Blockchain.info](https://blockchain.info/api/exchange_rates_api). Sebagai contoh, untuk mengkonversi 500 USD menjadi harga Bitcoin, gunakan: 
    ```bash
    GET   
    https://blockchain.info/tobtc?currency=USD&value=500
    ```
  
  - Halaman ketiga (konversi Bitcoin ke Rupiah) menyajikan fitur bagi user untuk mengkonversi Bitcoin menjadi Rupiah, dengan catatan 1 USD setara dengan Rp 14.000,-. Gunakan Bitcoin Conversion API yang disediakan [Blockchain.info](https://blockchain.info/api/exchange_rates_api), yang sudah Anda pakai sebelumnya. 
  
    > _**Catatan:**_
    Mata uang Indonesia (IDR/Rupiah) tidak termasuk dalam data yang disediakan oleh API [Blockchain.info](https://blockchain.info/api/exchange_rates_api). Jadi, silakan modifikasi data yang Anda dapat dari API tersebut dengan algoritma yang sesuai.

![Lintang_Bitcoin](https://4.bp.blogspot.com/-B6q5J-hz70Q/Ww9ic69eVnI/AAAAAAAAELE/W8cStewOUt8tk1NLkdRFArqfKVzgt9C_QCLcBGAs/s1600/soal3a.png)

>_**Catatan:**_ *Commit/upload project ini ke akun Github Anda dengan nama repo: **Bitcoin-NamaAnda**. Salin file App.js aplikasi ini ke dalam format .txt, sertakan pula link url ke repo Github project ini. Kemudian kirimkan via email ke lintang@purwadhika.com dengan subject email: __Ujian-Front-Bitcoin-namaAnda__.*

#

*__#HappyCoding__*

#### Lintang Wisesa :love_letter: _lintangwisesa@ymail.com_

[Facebook](https://www.facebook.com/lintangbagus) | 
[Twitter](https://twitter.com/Lintang_Wisesa) |
[Google+](https://plus.google.com/u/0/+LintangWisesa1) |
[Youtube](https://www.youtube.com/user/lintangbagus) | 
:octocat: [GitHub](https://github.com/LintangWisesa) |
[Hackster](https://www.hackster.io/lintangwisesa)
