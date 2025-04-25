# Tugas-Fuzzy

Soal <tb>
Sebuah sistem fuzzy digunakan untuk menentukan status gizi bayi berdasarkan tiga variabel input:

1. Berat Badan (kg) <tb>
Rendah: fungsi segitiga (a = 2, b = 3, c = 4)
Normal: fungsi segitiga (a = 3.5, b = 5, c = 6.5)
Tinggi: fungsi segitiga (a = 6, b = 7.5, c = 9)

2. Tinggi Badan (cm)
Pendek: fungsi segitiga (a = 45, b = 50, c = 55)
Normal: fungsi segitiga (a = 52, b = 60, c = 68)
Tinggi: fungsi segitiga (a = 65, b = 70, c = 75)

3. Kesehatan (dari hasil observasi)
Tidak Sehat: fungsi trapesium (a = 0, b = 0, c = 2, d = 4)
Sehat: fungsi trapesium (a = 3, b = 5, c = 7, d = 7)
Skor kesehatan dinilai dari 0 (sangat tidak sehat) hingga 7 (sangat sehat).

Output: Status Gizi
Kurang Gizi
Normal
Gizi Lebih

pertanyaan :
1. Gambar kurva setiap Fungsi Keanggotaan
2. Hitung nilai keanggotaan untuk berat badan = 4.2 kg, tinggi badan = 56 cm, dan kesehatan = 3.5.
3. 3 aturan  berdasarkan logika berikut:
R1 = Jika berat badan rendah dan tinggi badan pendek dan kesehatan tidak sehat, maka status gizi = kurang gizi.
R2 = Jika berat badan normal dan tinggi badan normal dan kesehatan sehat, maka status gizi = normal.
R3 = Jika berat badan tinggi dan tinggi badan tinggi dan kesehatan sehat, maka status gizi = gizi lebih.
