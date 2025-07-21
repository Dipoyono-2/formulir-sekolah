
# Formulir Pendaftaran Siswa Baru - SMK Sekolahku

Ini adalah proyek sederhana berbasis HTML yang digunakan sebagai **formulir pendaftaran siswa baru** di SMK Sekolahku. Formulir ini mencakup data calon siswa, data orang tua/wali, serta pilihan jurusan.

## 📝 Fitur Formulir

- Input data siswa (nama, tempat & tanggal lahir, NIK, NISN, alamat, dll.)
- Input data orang tua (ayah dan wali)
- Pilihan jurusan (TKJ, RPL, Multimedia)
- Pernyataan persetujuan sebelum submit

## 📁 Struktur File
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form Pendaftaran</title>
</head>
<body>
    <h2>Form Registrasi SMK Sekolahku</h2>
    <form action="">
        <fieldset>
            <legend>Data calon siswa</legend>
            <p>Nama Calon Siswa : <input type="text" placeholder="Nama Calon Siswa"></p>
            <p>Tempat Lahir     : <input type="text" placeholder="Tempat Lahir"></p>
            <p>Jenis Kelamin    : <input type="radio" name="jenis kelamin"> Laki-Laki <input type="radio" name="jenis kelamin"> Perempuan</p>
            <p>Alamat           : <input type="text" placeholder="Alamat Anda"></p>
            <p>Tanggal Lahir    : <input type="date"></p>
            <p>NIK              : <input type="text" placeholder="No. NIK"></p>
            <p>NISN             : <input type="text" placeholder="No. NISN Anda"></p>
            <p>Agama : <select name="" id="">
                <option value="">Islam </option>
                <option value="">Kristen </option>
                <option value="">Katolik</option>
                <option value="">Hindu</option>
                <option value="">Budha</option>
            </select></p>
            <p>RT               : <input type="text" placeholder="Contoh RT.01"></p>
            <p>RW: <input type="text" placeholder="Contoh RW.02"></p>
            <p>Nama Dusun: <input type="text" placeholder="Nama Dusun Anda"></p>
            <p>Nama Kelurahan: <input type="text" placeholder="Nama Kelurahan Anda"></p>
            <p>Nama Kecamatan: <input type="text" placeholder="Nama Kecamatan ANda"></p>
            <p>No HP: <input type="tel" placeholder="No Handphone Anda"></p>
            
        </fieldset>
        <br>
        <fieldset>
                <legend>Data Ayah</legend>
                <p>Nama Ayah : <input type="text" placeholder="Nama Ayah"></p>
                <p>Tahun Lahir: <input type="text" placeholder="Contoh 1980"></p>
                <p>Jenjang Pendidikan: <select name="" id="">
                    <option value="">SD </option>
                    <option value="">SMP</option>
                    <option value="">SMA</option>
                    <option value="">S1</option>
                    <option value="">S2</option>
                    <option value="">S3</option>
                </select>
                <p>Pekerjaan: <input type="text" placeholder="Pekerjaan Ayah"></p>
                <p>Penghasilan Per Bulan : </p>
                <input type="radio" name="Penghasilan Ayah"> 3-5 juta
                <input type="radio" name="Penghasilan Ayah"> 5-10 juta
                <input type="radio" name="Penghasilan Ayah"> 10-15 juta
                <input type="radio" name="Penghasilan Ayah"> Diatas 15 juta
                <input type="radio" name="Penghasilan Ayah"> Dibawah 3 juta
                        
                                
            
        </fieldset>
        <br>
        <fieldset>
            <legend>Data Wali</legend>
            <p>Nama Wali : <input type="text" placeholder="Nama Wali"></p>
            <p>Tahun Lahir: <input type="text" placeholder="Contoh 1985"></p>
            <p>Jenjang Pendidikan: <select name="" id="">
                <option value="">SD </option>
                <option value="">SMP</option>
                <option value="">SMA</option>
                <option value="">S1</option>
                <option value="">S2</option>
                <option value="">S3</option>
            </select>
            <p>Pekerjaan: <input type="text" placeholder="Pekerjaan Wali"></p>
            <p>Penghasilan Per Bulan : </p>
            <input type="radio" name="Penghasilan Wali"> 3-5 juta
            <input type="radio" name="Penghasilan Wali"> 5-10 juta
            <input type="radio" name="Penghasilan Wali"> 10-15 juta
            <input type="radio" name="Penghasilan Wali"> Diatas 15 juta
            <input type="radio" name="Penghasilan Wali"> Dibawah 3 juta
                    
    </fieldset>
    <p>Pilih Jurusan :
        <select name="" id="">
            <option value="">Teknik Komputer dan Jaringan</option>
            <option value="">Rekayasa Perangkat Lunak</option>
            <option value="">Multimedia</option>
        </select>
    </p>

        <details>
            <summary> pernyataan</summary>
        <input type="checkbox"> Saya menyetakan dengan sesungguhnya bahwa isian data dalam formulir ini adalah benar, 
        apabila ternyata data tersebut tidak benar/palsu saya bersedia menerima sanksi berupa pembatalan 
        sebagai calon peserta 
    </details>
    <button type="submit">Kirim Data</button>
        
    </form>
</body>
</html>
## Authors

- [@Dipoyon0-2](https://www.github.com/Dipoyono-2)


## Installation

Install my-project with Visual Code

```bash
  npm install my-project
  cd my-project
```
    