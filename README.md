# Tugas-Fuzzy

Soal
Sebuah sistem fuzzy digunakan untuk menentukan status gizi bayi berdasarkan tiga variabel input:

1. Berat Badan (kg)
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

Jawaban :
2. Perhitungan Nilai Keanggotaan
Berikut adalah perhitungan nilai keanggotaan untuk input yang diberikan:

- Berat Badan = 4.2 kg
1) Rendah: Fungsi segitiga (a=2, b=3, c=4)
Karena nilai c = 4 < x = 4.2 , maka derajat keanggotaan = 0
2) Normal: Fungsi segitiga (a=3.5, b=5, c=6.5)
Karena nilai x = 4.2 berada antara a=3.5 dan b=5 maka,
a < x <= b --> 3.5 < 4.2 <= 5
(x-a)/(b-a) = (4.2-3.5)/(5-3.5) = 0.7/1.5 = 0.467
3) Tinggi: Fungsi segitiga (a=6, b=7.5, c=9)
Karena nilai x = 4.2 < a = 6 , maka derajat keanggotaan = 0

- Tinggi Badan = 56 cm
1) Pendek: Fungsi segitiga (a=45, b=50, c=55)
Karena nilai x = 56 > c = 55, maka derajat keanggotaan = 0
2) Normal: Fungsi segitiga (a=52, b=60, c=68)
Karena nilai x = 56 berada antara a=52 dan b=60
a < x <= b --> 52 < 56 <= 60
(x-a)/(b-a) = (56-52)/(60-52) = 4/8 = 0.5
4) Tinggi: Fungsi segitiga (a=65, b=70, c=75)
Karena nilai x = 56 < a = 65, maka derajat keanggotaan = 0

- Kesehatan = 3.5
1) Tidak Sehat: Fungsi trapesium (a=0, b=0, c=2, d=4)
Karena nilai x = 3.5 berada antara c=2 dan d=4
c <= x <= d --> 2 <= 3.5 <= 4
(d-x)/(d-c) = (4-3.5)/(4-2) = 0.5/2 = 0.25
3) Sehat: Fungsi trapesium (a=3, b=5, c=7, d=7)
Karena nilai x = 3.5 berada antara a=3 dan b=5
a < x <= b --> 2 < 3.5 <= 4
(x-a)/(b-a) = (3.5-3)/(5-3) = 0.5/2 = 0.25
