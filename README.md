PAU
===
Petugas Administrasi Unit (PAU), bertugas untuk memberikan laporan harian. Dengan aplikasi ini, memungkinkan bagi petugas untuk memberikan laporan tersebut melalui browser, baik melalui komputer maupun perangkat genggam.

---

### Teknologi yang digunakan
* [CodeIgniter 3.1.2](https://github.com/bcit-ci/CodeIgniter/archive/3.1.2.zip "klik untuk download")
* [CodeIgniter Modular Extentions HMVC by wiredesignz](https://bitbucket.org/wiredesignz/codeigniter-modular-extensions-hmvc/get/f77a3fc9a6fd.zip "klik untuk download")[Klik disini untuk melihat cara konfigurasi HMVC](#konfigurasi_hmvc)

###<a id="konfigurasi_hmvc"></a>konfigurasi HMVC
1. Unzip Modular Extentions HMVC
2. pindahkan folder `core/` dan `third_party/` ke folder `application/`
3. Buat folder `application/modules/welcome/controllers/`
4. Pindahkan `welcome.php` dari `application/controllers/` ke folder seperti pada langkah 3
5. Buat folder `application/modules/welcome/views/`
6. Pindahkan `welcome_message.php` dari `application/views/` ke folder seperti pada langkah 3

**Note:** Tidak berlaku untuk CodeIgniter 2.x