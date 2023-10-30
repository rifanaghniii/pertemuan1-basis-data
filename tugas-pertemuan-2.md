<h2>Membuat Tabel Mahasiswa pada Database polban2</h2>

1. Buka SQL Shell, dan lakukan login.
   ![image](https://github.com/rifanaghniii/pertemuan1-basis-data/assets/148309225/b7ca2109-af16-424f-981d-8faff7f6404b)
   ![image](https://github.com/rifanaghniii/pertemuan1-basis-data/assets/148309225/14ea79e5-e218-4f9b-bbe9-c6fd9e1d2cc2)


3. Buat databse polban2 dengan syntax : CREATE DATABASE polban2;
4. Buat tabel mahasiswa dalam database polban2
   - Masuk ke dalam database polban2 dengan syntax : \c polban2
   - Buat tabel mahasiswa dengan syntax : CREATE TABLE mahasiswa (NIM int, nama varchar(50), gender varchar(3), alamat varchar(50), kota_asal varchar(30), tanggal_lahir varchar(30), tahun_masuk int, nomor_hp varchar(20));
   -  Tampilkan tabel dengan syntax : select * FROM mahasiswa;
     ![image](https://github.com/rifanaghniii/pertemuan1-basis-data/assets/148309225/461d18a6-cb70-4a3c-a3c1-e88f0fbc59a3)

5. Maukan data pada tabel dengan syntax contoh : INSERT INTO mahasiswa (nim,nama,gender,alamat,kota_asal,tanggal_lahir,tahun_masuk,nomor_hp) VALUES (221331058,'Rifan Aghni Al Farisan','L','Kp.Warungbandung, Desa Cibalanarik, Kec.Tanjungjaya, Kab.Tasikmalaya','9 Agustus 2003',2022,'085930305254');
   Ulangi syntax tersebut dengan data satu kelas sampai semua data dari satu kelas terisi.
   ![image](https://github.com/rifanaghniii/pertemuan1-basis-data/assets/148309225/1d252ba5-81a7-4c1f-9388-ae4182181a42)

7. Tampilkan hasil akhir dari tabel mahasiswa
   - Tampilan pada SQL Sheel
     ![image](https://github.com/rifanaghniii/pertemuan1-basis-data/assets/148309225/349e7ee3-dce1-4cd3-9c35-4c19355eaffd)
   - Tampilan pada DBeaver
     ![image](https://github.com/rifanaghniii/pertemuan1-basis-data/assets/148309225/379005ce-12db-4dba-a475-c020b2cb20f9)

