# Tugas 4 - Aplikasi Perhitungan Hari ([screenshot](#screenshot))

Aplikasi ini adalah sebuah program berbasis GUI yang memungkinkan pengguna untuk melakukan perhitungan terkait informasi tanggal dan hari pada bulan tertentu, serta menghitung selisih hari antara dua tanggal.

## Fitur Aplikasi

- **Jumlah Hari dalam Bulan**  
  Menampilkan jumlah hari pada bulan dan tahun yang dipilih.

- **Tahun Kabisat**  
  Menentukan apakah tahun yang dipilih adalah tahun kabisat atau bukan.

- **Hari Pertama dan Terakhir Bulan**  
  Menampilkan hari pertama dan hari terakhir pada bulan yang dipilih.

- **Perhitungan Selisih Hari**  
  Menghitung selisih hari antara tanggal yang dipilih pada kalender pertama dengan tanggal yang dipilih pada kalender kedua.

## Cara Menjalankan Aplikasi

### 1. **Instalasi Dependensi**

Aplikasi ini menggunakan library `JCalendar` untuk memilih tanggal. Anda dapat menambahkannya ke project melalui Maven atau mengimpor JAR `JCalendar` secara manual.

### 2. **Kompatibilitas**

Aplikasi ini dirancang untuk berjalan di Java 8 ke atas, pastikan Anda sudah menginstal Java SE Development Kit (JDK) yang sesuai.

### 3. **Langkah Menjalankan**

- Buka project ini di IDE seperti **NetBeans**.
- Klik tombol **Run** untuk menjalankan aplikasi.

### 4. **Interaksi dengan Aplikasi**

- Pilih bulan dan tahun pada **ComboBox** dan **Spinner**.
- Klik tombol **Hitung** untuk melihat hasilnya di **Dialog**.

## Desain GUI

Aplikasi ini memiliki tampilan antarmuka sederhana dengan komponen berikut:

- **JCalendar1**: Digunakan untuk memilih tanggal pertama.
- **JCalendar2**: Digunakan untuk memilih tanggal kedua untuk menghitung selisih hari.
- **ComboBox**: Untuk memilih bulan.
- **Spinner**: Untuk memilih tahun.
- **Button**: Untuk menghitung hasilnya.

## Penjelasan Fitur

1. **Jumlah Hari dalam Bulan**  
   Menghitung dan menampilkan jumlah hari dalam bulan yang dipilih.
   
2. **Tahun Kabisat**  
   Menentukan apakah tahun yang dipilih adalah tahun kabisat.

3. **Hari Pertama dan Terakhir Bulan**  
   Menampilkan hari pertama dan hari terakhir dari bulan yang dipilih.

4. **Selisih Hari**  
   Menghitung dan menampilkan selisih hari antara dua tanggal yang dipilih di dua kalender.

## Detail tugas

1. Deskripsi Program:

   - Pengguna memilih bulan dari JComboBox dan memasukkan tahun menggunakan JSpinner
   - Gunakan JCalendar untuk memilih bulan dan tahun
   - Hasil jumlah hari ditampilkan setelah tombol ditekan

2. Komponen GUI: JFrame, JPanel, JLabel, JComboBox, JSpinner, JButton, JCalendar

3. Logika Program: Penggunaan API tanggal (LocalDate), Perhitungan hari dalam bulan, Perhitungan tahun kabisat

4. Events:

   - ActionListener untuk tombol Hitung
   - ChangeListener pada JSpinner untuk input tahun

5. Variasi:

   - Tampilkan informasi tambahan seperti hari pertama dan terakhir dalam bulan tersebut
   - Integrasikan fitur untuk menghitung selisih hari antara dua tanggal

## Screenshot

Nama : Ahmad Yasser

NPM  : 2210010525

Kelas: 5A REGULER BJB TI

1. Tampilan awal
![image](https://github.com/user-attachments/assets/bec0c5a7-868e-422f-823b-890e076bd9d2)

2. Hitung 8 februari 2024 (kabisat) dan selisihnya dengan 8 november 2024
![image](https://github.com/user-attachments/assets/94259655-e5e9-4cc8-9aeb-4ce42645925f)

3. Hitung 8 februari 2025 (bukan kabisat) dan selisih dengan 8 november 2024
![image](https://github.com/user-attachments/assets/6f507c3f-ef72-422c-badd-9c4cd4f257cd)
