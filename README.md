Menggunakan Role Admin: 
buka http://sispakdurian.herokuapp.com/login
1. Masukan email admin@gmail.com
2. Masukan password admin
3. Manage Data penyakit
    1. Penyakit
    2. Gejala Penyakit
    3. Basis Pengetahuan
        - fungsi tambah data, memilih data penyakit dan gejala sesuai yang ada pada database.
        - fungsi edit data, hanya bisa memasukkan nilai certainty factor saja.
    4. Data Latih
        - setelah menambahkan data Penyakit atau Basis Pengetahuan, perlu menambahkan data latih penyakit
        - namun untuk saat ini belum tersedia fungsi CRUD nya, silahkan tambah pada database
4. Manage Data Hama
    1. Hama
    2. Gejala Hama
    3. Basis Pengetahuan
        - fungsi tambah data, memilih data Hama dan gejala sesuai yang ada pada database.
        - fungsi edit data, hanya bisa memasukkan nilai certainty factor saja.
    4. Data Latih
        - setelah menambahkan data Hama atau Basis Pengetahuan, perlu menambahkan data latih hama
        - fungsi tambah data dapat menambah lebih dari 1 gejala.
5. Info Penyakit
    - Admin dapat melihat hubungan antar penyakit dan gejala
7. Info Hama
    - Admin dapat melihat hubungan antar hama dan gejala


Menggunakan Role Member:
untuk dapat menggunakan role member silahkan register terlebih dahulu pada http://sispakdurian.herokuapp.com/register
setelah registrasi berhasil, silahkan login pada http://sispakdurian.herokuapp.com/login
1. Diagnosa
    - pilih gejala
    - klik tombol diagnosa dan tunggu proses
    - jika tidak ada gejala yang dipilih maka akan mengembalikan ke page diagnosa dan menampilkan error
    - jika terdapat id penyakit yang belum ada di data latih maka akan mengembalikan ke page diagnosa dan menampilkan error
    - jika berhasil di proses, akan menampilkan hasil diagnosa berupa gejala yang dipilih dan informasi terkait penyakit yang terdiagnosa serta nilai keyakinannya
    - hasil diagnosa akan disimpan di data latih dan data riwayat
2. riwayat
    - menampilkan seluruh riwayat diagnosa yang terhubung oleh id user
3. info penyakit dan hama
    - menampilkan informasi terkait hubungan antara penyakit dan gejala pada penyakit
