# MamdaniFuzzyPHP
Fuzzy Logic Mamdani Method

```
DISCLAIMER : RUMUS YANG ADA PADA DI SOURCE CODE INI TIDAK BERDASARKAN PAPER APAPUN, SOURCE CODE YANG DIBUAT SEMATA-MATA UNTUK MEMENUHI TUGAS KULIAH
```
Durasi : 
![durasi](https://user-images.githubusercontent.com/56243910/80447093-a65a3d00-8942-11ea-9826-785aba668972.JPG)
<br>Gejala :
![gejala](https://user-images.githubusercontent.com/56243910/80447223-0650e380-8943-11ea-8f99-1647e3bf62e6.JPG)
<br>Intensitas Keluar Rumah :
![intensitas](https://user-images.githubusercontent.com/56243910/80447240-14066900-8943-11ea-8788-03c20fb1ee06.JPG)

<br>Output :
![output](https://user-images.githubusercontent.com/56243910/80447292-39937280-8943-11ea-90b0-c761f079eb06.JPG)

Knowledge Base (Rule) :

```
1.	IF DURASI = BARU and GEJALA = RENDAH and INTENSITAS = RENDAH then STATUS = NEGATIF
2.	IF DURASI = BARU and GEJALA = RENDAH and INTENSITAS = SEDANG then STATUS = NEGATIF
3.	IF DURASI = BARU and GEJALA = RENDAH and INTENSITAS = TINGGI then STATUS = NEGATIF
4.	IF DURASI = BARU and GEJALA = BURUK and INTENSITAS = RENDAH then STATUS = NEGATIF
5.	IF DURASI = BARU and GEJALA = BURUK and INTENSITAS = SEDANG then STATUS = ODP
6.	IF DURASI = BARU and GEJALA = BURUK and INTENSITAS = TINGGI then STATUS = ODP
7.	IF DURASI = BARU and GEJALA = SANGAT BURUK and INTENSITAS = RENDAH then STATUS = ODP
8.	IF DURASI = BARU and GEJALA = SANGAT BURUK and INTENSITAS = SEDANG then STATUS = ODP
9.	IF DURASI = BARU and GEJALA = SANGAT BURUK and INTENSITAS = TINGGI then STATUS = PDP
10.	IF DURASI = SEDANG and GEJALA = RENDAH and INTENSITAS = RENDAH then STATUS = NEGATIF
11.	IF DURASI = SEDANG and GEJALA = RENDAH and INTENSITAS = SEDANG then STATUS = ODP
12.	IF DURASI = SEDANG and GEJALA = RENDAH and INTENSITAS = TINGGI then STATUS = ODP
13.	IF DURASI = SEDANG and GEJALA = BURUK and INTENSITAS = RENDAH then STATUS = ODP
14.	IF DURASI = SEDANG and GEJALA = BURUK and INTENSITAS = SEDANG then STATUS = ODP
15.	IF DURASI = SEDANG and GEJALA = BURUK and INTENSITAS = TINGGI then STATUS = PDP
16.	IF DURASI = SEDANG and GEJALA = SANGAT BURUK and INTENSITAS = RENDAH then STATUS = ODP
17.	IF DURASI = SEDANG and GEJALA = SANGAT BURUK and INTENSITAS = SEDANG then STATUS = ODP
18.	IF DURASI = SEDANG and GEJALA = SANGAT BURUK and INTENSITAS = TINGGI then STATUS = PDP
19.	IF DURASI = LAMA and GEJALA = RENDAH and INTENSITAS = RENDAH then STATUS = NEGATIF
20.	IF DURASI = LAMA and GEJALA = RENDAH and INTENSITAS = SEDANG then STATUS = ODP
21.	IF DURASI = LAMA and GEJALA = RENDAH and INTENSITAS = TINGGI then STATUS = ODP
22.	IF DURASI = LAMA and GEJALA = BURUK and INTENSITAS = RENDAH then STATUS = ODP
23.	IF DURASI = LAMA and GEJALA = BURUK and INTENSITAS = SEDANG then STATUS = PDP
24.	IF DURASI = LAMA and GEJALA = BURUK and INTENSITAS = TINGGI then STATUS = PDP
25.	IF DURASI = LAMA and GEJALA = SANGAT BURUK and INTENSITAS = RENDAH then STATUS = PDP
26.	IF DURASI = LAMA and GEJALA = SANGAT BURUK and INTENSITAS = SEDANG then STATUS = PDP
27.	IF DURASI = LAMA and GEJALA = SANGAT BURUK and INTENSITAS = TINGGI then STATUS = PDP

```

:fire::fire::fire:
