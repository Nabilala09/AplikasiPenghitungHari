# Tugas 4: Aplikasi Perhitungan Hari

**Nabila Parastiwi - 2210010420 - Kelas 5A Reg Pagi Banjarmasin**  
Mata Kuliah: Pemrograman Berbasis Objek

## Deskripsi

Aplikasi ini digunakan untuk menghitung jumlah hari dalam bulan tertentu pada tahun tertentu. Selain itu, aplikasi dapat menampilkan informasi tambahan seperti hari pertama dan terakhir pada bulan tersebut.

## Fitur

- **Penghitungan Hari**: Menghitung jumlah hari berdasarkan bulan dan tahun yang dipilih.
- **Pilihan Bulan dan Tahun**: Menggunakan JComboBox dan JSpinner untuk input.
- **Integrasi JCalendar**: Memungkinkan pengguna memilih bulan dan tahun melalui antarmuka kalender.
- **Informasi Tambahan**: Menampilkan hari pertama dan terakhir pada bulan tersebut.
- **Selisih Hari**: Fitur untuk menghitung selisih antara dua tanggal.

## Komponen

- GUI menggunakan JFrame, JPanel, JLabel, JComboBox, JSpinner, JButton, JCalendar.
- Logika program mencakup:
  - Penggunaan API tanggal seperti `LocalDate`.
  - Perhitungan tahun kabisat.
  - Validasi input pengguna.
- Event Handling:
  - **ActionListener** untuk tombol "Hitung".
  - **ChangeListener** untuk input tahun melalui JSpinner.

## Cara Menjalankan

1. Clone repositori ini ke perangkat Anda.
2. Jalankan aplikasi dengan memastikan Java Runtime Environment (JRE) terinstal.
3. Pilih bulan dari JComboBox dan masukkan tahun menggunakan JSpinner atau JCalendar.
4. Tekan tombol "Hitung" untuk melihat jumlah hari dalam bulan tersebut.
5. Untuk menghitung selisih hari, masukkan dua tanggal, lalu tekan tombol "Hitung Selisih".
