# Modul-3
Pada langkah pertama, sebuah array dengan nama numbers dibuat dan diinisialisasi dengan sejumlah angka. Array ini akan menjadi data masukan dari mana kita akan menghitung median.
Pengurutan Array:

Setelah inisialisasi array, kita menggunakan metode Arrays.sort(numbers) untuk mengurutkan elemen-elemen dalam array numbers. Ini diperlukan karena median adalah nilai tengah, dan perlu data yang sudah diurutkan.
Penghitungan Median:

Kita kemudian deklarasikan variabel median yang akan menyimpan nilai median.
Hitung indeks tengah dengan membagi panjang array oleh 2 dan simpan dalam variabel middle.
Selanjutnya, kita menggunakan kondisi if untuk memeriksa apakah jumlah elemen dalam array adalah ganjil atau genap.
Jika jumlah elemen ganjil, maka kita langsung menetapkan median ke nilai yang berada di tengah array.
Jika jumlah elemen genap, maka kita menghitung rata-rata dari dua nilai yang berada di tengah array dan mengisinya ke median. Penting untuk mengonversi hasilnya menjadi tipe data double agar rata-rata tidak dibulatkan menjadi bilangan bulat.
Pencetakan Hasil:

Terakhir, hasil perhitungan median dicetak ke layar dengan menggunakan perintah System.out.println(). Hasil median akan ditampilkan sebagai output program.
Dengan demikian, program ini mengambil array angka, mengurutkannya, dan kemudian menghitung median berdasarkan aturan yang tepat, yaitu memilih nilai tengah jika jumlah elemen ganjil, atau rata-rata dari dua nilai tengah jika jumlah elemen genap. Hasilnya kemudian ditampilkan kepada pengguna.
