# Studi-Kasus-6-Alya-Shofa

Nama : Alya Shofa

Nim : 2609116077

Diawali dengan 2 data mahasiswa 

<img width="730" height="431" alt="image" src="https://github.com/user-attachments/assets/5c54408e-f7ca-4119-85eb-07a47531d947" />

PENJELASAN CODE

<img width="672" height="205" alt="image" src="https://github.com/user-attachments/assets/adda85c2-e40d-448f-8ca8-1ed5cea3a100" />

Bagian ini digunakan untuk mengimpor json dan menentukan file yang akan digunakan, yaitu data.json. Setelah itu file dibuka dengan mode "r" untuk membaca data yang sudah ada, kemudian datanya dimasukkan ke dalam daftar_nilai.

<img width="576" height="180" alt="image" src="https://github.com/user-attachments/assets/9594876f-d366-4fad-afa9-ec1f1588956d" />

Bagian ini membuat function tambah_nilai() yang digunakan untuk memasukkan data mahasiswa. Pengguna diminta mengisi nama, NIM, mata kuliah, dan nilai ujian.

<img width="512" height="236" alt="image" src="https://github.com/user-attachments/assets/762ac082-5c40-45af-b597-6e0c22a8ca65" />

Data yang sudah dimasukkan tadi dibuat menjadi dictionary. Setelah itu append() digunakan untuk menambahkan data mahasiswa tersebut ke dalam daftar_nilai.

<img width="720" height="111" alt="image" src="https://github.com/user-attachments/assets/a58233c4-b558-4734-8861-3369fef55224" />

Bagian ini digunakan untuk menyimpan data yang sudah ditambahkan ke dalam data.json. Mode "w" digunakan untuk menulis data ke file, sedangkan json.dump() digunakan untuk memasukkan data ke file JSON.

<img width="780" height="255" alt="image" src="https://github.com/user-attachments/assets/0ecfdc9b-1c4c-4489-849e-2131dad74496" />

Function lihat_nilai() digunakan untuk menampilkan data nilai mahasiswa. Kalau belum ada data, program akan menampilkan "Belum ada data nilai.". Kalau sudah ada, data ditampilkan menggunakan for dan diberi nomor dengan enumerate().

<img width="637" height="210" alt="image" src="https://github.com/user-attachments/assets/613f556a-f4e2-4a47-8919-fe4fd20941b2" />

Bagian ini membuat menu yang akan terus muncul menggunakan while True. Pengguna bisa memilih untuk melihat data, menambahkan data, atau keluar dari program.

<img width="534" height="401" alt="image" src="https://github.com/user-attachments/assets/6018b5d9-7a23-4c2f-90db-708987feefb8" />

Bagian terakhir digunakan untuk menentukan pilihan pengguna. Jika memilih 1, program menampilkan nilai. Jika memilih 2, program meminta data nilai baru. Jika memilih 3, program berhenti menggunakan break. Kalau pilihannya tidak sesuai, akan muncul "Menu tidak tersedia."
