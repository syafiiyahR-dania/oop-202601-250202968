# Catatan Minggu-03: Inheritance

## Yang saya kerjakan
Minggu ini saya membuat tiga class, yaitu `Ruang.java`, `Laptop.java`, dan `AlatLab.java`, yang mewarisi dari kelas `Aset.java`. Saya menambahkan atribut, konstruktor, getter, dan metode `getJenis()` ke masing-masing class. Saya juga menambahkan aturan validasi agar kapasitas ruangan harus lebih dari 0, spesifikasi.

## Keputusan desain
Saya menggunakan inheritance agar kelas anak bisa mewarisi data dan validasi dari `Asset`, sementara atribut spesifik disimpan di masing-masing kelas. Komposisi lebih cocok untuk hubungan bagian dari objek, seperti laptop dan charger.

## Kendala
Tantanganku adalah mencocokkan tipe data dari metode getJenis() dan hitungDenda() dengan kelas induk Aset. Aku menyelesaikannya dengan memperbaiki tipe pengembalian dari metode-metode itu sehingga semua 19 tes lolos tanpa masalah.

## Penggunaan AI
- Alat yang dipakai: ChatGPT
- Bagian yang dibantu AI: AI membantu memeriksa kode dan memperbaiki kesalahan di kelas Ruang, Laptop, dan AlatLab.
- Prompt utama: 
    1. Apakah kode Ruang.java saya sudah benar?
    2. Apakah hasil pengujian kode saya sudah benar?
- Yang saya ubah atau tolak dari saran AI, dan alasannya: Saya menyesuaikan kode dengan ketentuan tugas dan tidak mengubah bagian denda karena belum masuk materi minggu ini.
- Satu hal yang saya pahami lebih baik sekarang:Aku lebih paham tentang inheritance, yaitu cara membuat subclass yang bisa menggunakan field dan method dari kelas induk supaya kodenya lebih terstruktur dan kamu nggak perlu nulis ulang bagian yang sama.


## uji test
![uji test](/catatan/3%20(1).png)
![uji test](/catatan/3%20(2).png)