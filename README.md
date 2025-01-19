# Google Maps Scrapper

Ini merupakan projek Scrapping Data dari data Gmaps menggunakan Playwright.
Cuman beberapa kode kita sudah bisa untuk melakukan Scrapping Data.

## Install Library yang dibutuhkan
-  Buat sebuah environment baru/opsional untuk ini, tapi jika ada dependensi conflict bisa terselesaikan
-  `pip install -r requirements.txt`
-  `playwright install chromium`

## Bagaimana cara melakukannya?
**Pencarian Tunggal**
Untuk melakukan pencarian ini, cukup dengan run code berikut :
- `python3 main.py -s=<Apa dan dimana yang ingin dicari -t=Berapa banyak`

**Pencarian Beberapa Kata tapi dalam satu kali run**
Untuk melakukannya cukup dengan menambahkan query yang ingin dicari di google maps, dan tiap query yang berbeda berada pada garis yang berbeda.
Contohnya :

- `Semua toko yang ada di Bandung`
- `Rumah sakit di Jakarta`
- `Toko baju di Surabaya`

