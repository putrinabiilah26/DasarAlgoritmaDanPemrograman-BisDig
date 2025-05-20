<h1> MENJELASKAN ALUR CODE DAN MENJAWAB PERTANYAAN</h1>

Nama: Putri Nabiilah 
NIM: 24110310063 
Kelas: 2A 
Program Studi: Bisnis Digital 
Uts: Dasar Algoritma dan Pemograman

# Studi Kasus: Faktorial dengan Fungsi Rekursif
# Alur Pengerjaan Fungsi Rekursif Menghitung Faktorial:
1. Buat fungsi faktorial yang menerima 1 parameter bilangan.
2. Gunakan kondisi dasar saat bilangan 0 atau 1.
3. Jika bukan kondisi dasar, fungsi akan memanggil dirinya sendiri (rekursif).
4. Minta input dari user, simpan di dalam variabel.
5. Cetak hasil faktorial dengan memanggil fungsi tersebut.
   
# Penjelasan Kode:
1. def faktor(n): untuk mendeklarasikan fungsi faktorial dengan parameter n.
2. if n == 0 or n == 1: ialah kondisi dasar. Jika n 0 atau 1, maka akan langsung dikembalikan 1 (karena faktorial 0 dan 1 adalah 1).
3. return n * faktorial(n - 1) untuk menyebut fungsi faktorial lagi dengan n - 1 (rekursi) sampai mencapai kondisi dasar.
4. angka = int(input(...)) untuk menerima input dari pengguna dan mengubahnya ke tipe integer.
5. hasil = faktorial(angka) untuk menyimpan hasil perhitungan dari fungsi ke variabel hasil.

# Penjelasan:
Manfaat fungsi mempermudah pemrograman modular, memudahkan pemeliharaan, dan memungkinkan penggunaan ulang kode. Dan rekursi bekerja dengan memamggil dirinya sendiri sehingga mencapai kondisi dasar (base case). Jika dalam kasus faktorial, maka:       n! = n x (n-1)! dan 1! = 1.

# Studi Kasus: Input Nilai 5 Siswa dan Cari Nilai Tertinggi
# Penjelasan:
Array (list) digunakan untuk menyimpan nilai dari tiap siswa dalam satu variabel, sedangkan perulangan (for) digunakan menginput banyak data secara efisien dan melakukan pengecekan secara otomatis.
