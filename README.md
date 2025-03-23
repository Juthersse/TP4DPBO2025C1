# TP4DPBO2025C1

# Janji
Saya Muhammad Ichsan Khairullah dengan NIM 2306924 mengerjakan Tugas Praktikum 4 dalam mata kuliah Desain dan Pemograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

# Desain Program
Program ini adalah aplikasi berbasis GUI menggunakan Java Swing yang memungkinkan pengguna untuk menampilkan, menambahkan, mengedit, dan menghapus data mahasiswa (CRUD).
Setiap mahasiswa memiliki atribut:
1. NIM
2. Nama
3. Jenis Kelamin
4. Umur
Program ini menggunakan JTable untuk menampilkan data mahasiswa dan memungkinkan pengguna mengubah atau menghapus data yang dipilih.

Desain GUI:
![Screenshot 2025-03-23 205140](https://github.com/user-attachments/assets/ee6fa953-209e-4f86-b3b1-ee8fb872ac76)

Komponen Utama dalam Menu.java:
JFrame: Frame utama aplikasi
JTable: Menampilkan daftar mahasiswa dalam bentuk tabel
JTextField: Input untuk NIM dan nama mahasiswa
JComboBox: Input dropdown untuk jenis kelamin mahasiswa
JSpinner: Input untuk umur mahasiswa
JButton: Tombol add/update, cancel, dan delete
ArrayList<Mahasiswa>: List untuk menyimpan data mahasiswa

# Penjelasan Alur
1. Program dimulai, membuat window GUI menggunakan JFrame dan menampilkan tabel mahasiswa.
2. Data awal mahasiswa diisi ke dalam listMahasiswa dan ditampilkan di JTable.
3. Pengguna dapat melakukan operasi berikut:
   - Tambah Data:
     - Isi NIM, Nama, Jenis Kelamin, dan Umur.
     - Klik tombol 'Add' untuk memasukkan data ke listMahasiswa
   - Update Data:
     - Pilih mahasiswa dari tabel.
     - Data mahasiswa yang dipilih muncul di form, tombol 'add' akan berubah menjadi 'Update'.
     - Ubah data, lalu klik 'Update' untuk memperbarui data mahasiswa
   - Hapus Data:
     - Pilih mahasiswa dari tabel.
     - Klik 'Delete', lalu akan muncul window konfirmasi penghapusan
     - Klik 'Yes' untuk mengonfirmasi penghapusan data
   - Cancel Input:
     - Klik tombol 'Cancel' untuk reset form
5. Setiap perubahan diperbarui di JTable secara otomatis.
6. Program terus berjalan hingga pengguna menutup window.

# Dokumentasi
![dokumentasi (1)](https://github.com/user-attachments/assets/c4b4adab-ee17-49df-bff5-dc2705819aa7)
