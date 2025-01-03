1. Fungsi Keanggotaan 
dingin, sejuk, hangat, dan panas: Fungsi ini menentukan derajat keanggotaan untuk suhu tertentu dalam masing-masing kategori fuzzy   (dingin, sejuk, hangat, panas).

2. Fungsi Kecepatan Kipas
kecepatan_lambat, kecepatan_sedang, kecepatan_cepat, dan kecepatan_sangat_cepat: Fungsi ini menghitung kecepatan kipas dalam rentang tertentu sesuai dengan derajat keanggotaan.

3. Input Suhu
Misal suhu input adalah 25°C, kode ini menghitung derajat keanggotaan untuk kategori fuzzy berdasarkan suhu tersebut.

4. Inferensi
Berdasarkan aturan fuzzy, nilai keluaran dihitung menggunakan metode min pada derajat keanggotaan.

5. Defuzzifikasi
Metode rata-rata tertimbang (weighted average) digunakan untuk menghitung nilai keluaran akhir, yaitu kecepatan kipas (dalam RPM).

6. Hasil
Untuk suhu_input = 25°C:
Derajat keanggotaan dihitung untuk semua kategori.
Inferensi dilakukan untuk menentukan kecepatan kipas berdasarkan aturan.
Defuzzifikasi menghasilkan nilai akhir, misalnya: 30.00 RPM.
