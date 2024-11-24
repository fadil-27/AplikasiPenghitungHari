# AplikasiPenghitungHari
 Tugas 4 - Muhammad Fadilah (2210010500)

## Deskripsi Program

Aplikasi ini menghitung jumlah hari dalam suatu bulan tertentu pada tahun yang dipilih, dan juga memberikan informasi tentang hari pertama dan terakhir pada bulan tersebut. Program ini menggunakan `JComboBox` untuk memilih bulan, `JSpinner` untuk memasukkan tahun, dan `JCalendar` untuk memilih tanggal secara visual. Program ini akan menghitung dan menampilkan hasilnya setelah tombol "Hitung" ditekan. Selain itu, aplikasi ini juga dapat menghitung selisih hari antara dua tanggal yang dipilih oleh pengguna.

## Fitur Utama

1. **Perhitungan Jumlah Hari dalam Bulan**
   - Pengguna memilih bulan dari `JComboBox` dan memasukkan tahun menggunakan `JSpinner`.
   - Program akan menghitung jumlah hari dalam bulan dan tahun yang dipilih.
   - Hasil jumlah hari ditampilkan setelah tombol "Hitung" ditekan.

2. **Informasi Hari Pertama dan Terakhir**
   - Aplikasi akan menampilkan informasi hari pertama dan hari terakhir pada bulan yang dipilih.

3. **Perhitungan Selisih Hari**
   - Aplikasi dapat menghitung selisih hari antara dua tanggal yang dipilih dari dua `JCalendar`.

4. **Tahun Kabisat**
   - Program akan mendeteksi apakah tahun yang dimasukkan adalah tahun kabisat dan memperhitungkan jumlah hari dalam bulan Februari.

## Komponen GUI

Aplikasi ini menggunakan beberapa komponen GUI dari Java Swing:
- `JFrame` - Untuk menampilkan window utama aplikasi.
- `JPanel` - Sebagai container untuk elemen GUI lainnya.
- `JLabel` - Untuk menampilkan teks, seperti hasil perhitungan jumlah hari.
- `JComboBox` - Untuk memilih bulan.
- `JSpinner` - Untuk memasukkan tahun.
- `JButton` - Untuk memicu perhitungan jumlah hari.
- `JCalendar` - Untuk memilih dua tanggal dan menghitung selisih antara keduanya.

## Cara Menggunakan Aplikasi

1. **Memilih Bulan dan Tahun**
   - Pilih bulan dari dropdown `JComboBox`.
   - Masukkan tahun menggunakan `JSpinner` atau pilih tahun menggunakan `JCalendar`.

2. **Menghitung Jumlah Hari**
   - Tekan tombol "Hitung" untuk menampilkan jumlah hari dalam bulan dan tahun yang dipilih.
   - Program juga akan menampilkan hari pertama dan hari terakhir dalam bulan tersebut.

3. **Menghitung Selisih Hari**
   - Pilih dua tanggal menggunakan dua `JCalendar` yang tersedia.
   - Tekan tombol "Hitung" untuk melihat selisih hari antara kedua tanggal tersebut.

## Logika Program

- **Perhitungan Jumlah Hari dalam Bulan**  
  Program menggunakan API `LocalDate` untuk memanipulasi dan menghitung jumlah hari dalam bulan yang dipilih. API `lengthOfMonth()` digunakan untuk mendapatkan jumlah hari dalam bulan tertentu.

- **Tahun Kabisat**  
  Program memeriksa apakah tahun yang dimasukkan adalah tahun kabisat dengan menggunakan metode `isLeapYear()` dari kelas `LocalDate`.

- **Selisih Hari antara Dua Tanggal**  
  Program menghitung selisih hari antara dua tanggal yang dipilih dengan menggunakan `ChronoUnit.DAYS.between()`.

## Screenshot
![AplikasiPenghitungHari](https://github.com/user-attachments/assets/839b0e9b-b423-4aec-a6cc-efd12bd5b7d4)


