# PBO-2
Berikut adalah pennjelasan untuk code yang telah saya jabarkan sebelumnya:

Kelas Mahasiswa:

Kelas Mahasiswa digunakan untuk merepresentasikan seorang mahasiswa dengan atribut nama, nim, dan jurusan.
Atribut nama menyimpan nama lengkap mahasiswa.
Atribut nim menyimpan nomor induk mahasiswa.
Atribut jurusan adalah objek dari kelas Jurusan yang menampung informasi jurusan mahasiswa.
Metode tampilkan_info() digunakan untuk menampilkan informasi lengkap mahasiswa, yaitu nama, nim, dan nama jurusan.
Kelas Jurusan:

Kelas Jurusan digunakan untuk merepresentasikan jurusan di sebuah universitas dengan atribut NamaJurusan dan DaftarMahasiswa.
Atribut NamaJurusan menyimpan nama jurusan.
Atribut DaftarMahasiswa adalah daftar objek Mahasiswa yang terdaftar di jurusan ini.
Metode tambah_mahasiswa(mahasiswa) digunakan untuk menambahkan objek Mahasiswa ke daftar mahasiswa jurusan.
Metode tampilkan_daftar_mahasiswa() digunakan untuk mencetak daftar mahasiswa yang terdaftar di jurusan ini dengan memanggil metode tampilkan_info() dari setiap objek Mahasiswa dalam daftar.
Kelas Universitas:

Kelas Universitas digunakan untuk merepresentasikan sebuah universitas dengan atribut NamaUniversitas dan DaftarJurusan.
Atribut NamaUniversitas menyimpan nama universitas.
Atribut DaftarJurusan adalah daftar objek Jurusan yang ada di universitas ini.
Metode tambah_jurusan(jurusan) digunakan untuk menambahkan objek Jurusan ke daftar jurusan universitas.
Metode tampilkan_daftar_jurusan() digunakan untuk mencetak daftar jurusan yang ada di universitas ini.
Dalam implementasi utama:

Objek Universitas dengan nama "XYZ University" dibuat menggunakan kelas Universitas.

Objek Jurusan dengan nama "Teknik Informatika" dibuat menggunakan kelas Jurusan. Objek Jurusan ini kemudian ditambahkan ke dalam objek Universitas "XYZ University" menggunakan metode tambah_jurusan().

Objek Mahasiswa dengan nama "Akram Analis", NIM "G1A022004" dibuat menggunakan kelas Mahasiswa. Objek Mahasiswa ini diberikan objek Jurusan "Teknik Informatika" sebagai parameter. Selanjutnya, objek Mahasiswa ditambahkan ke dalam objek Jurusan "Teknik Informatika" menggunakan metode tambah_mahasiswa().

Metode tampilkan_daftar_jurusan() pada objek Universitas "XYZ University" dipanggil untuk mencetak daftar jurusan yang ada di universitas tersebut.

Metode tampilkan_daftar_mahasiswa() pada objek Jurusan "Teknik Informatika" dipanggil untuk mencetak daftar mahasiswa yang terdaftar di jurusan tersebut.

Dengan menggunakan kelas-kelas objek ini, Andi dapat dengan mudah mengelola data mahasiswa dan jurusan di Universitas XYZ, seperti menambahkan mahasiswa ke jurusan, menampilkan daftar jurusan, dan menampilkan daftar mahasiswa dalam jurusan tertentu.
