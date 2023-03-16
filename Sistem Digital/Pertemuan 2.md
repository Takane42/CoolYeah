TL;DR : Sistem Bilangan Biner, Oktal, Desimal, Hexadesimal dan Cara Konversinya
###### Tags : #Biner #Oktal #Desimal #Hexadesimal #Konversi

Sistem Bilangan : 
- Biner :
	Memiliki 2 Basis / Radix -> { 0,1 }
- Oktal :
	Memiliki 8 Basis / Radix -> { 0,1,2,3,4,5,6,7 }
- Desimal
	Memiliki 10 Basis / Radix -> { 0,1,2,3,4,5,6,7,8,9 }
- Hexadesimal
	Memiliki 16 Basis / Radix -> { 0,1,2,3,4,5,6,7,8,9,A,B,C,D,E,F }

Konversi :

1. Desimal Ke Sistem Selain Desimal
	Caranya yaitu dengan Membagi Bilangan Desimal dengan Radix sistem bilangan yang akan digunakan hingga pembagian akhir berada pada basis sistem bilangan yang akan digunakan. Lalu baca dari bawah ke atas

>Contoh 1 : Mengubah Bilangan Desimal ke Biner
>(75)<sub>10</sub> = ( ... )<sub>2</sub> 

	75 : 2 = 37  sisa 1  ^
	37 : 2 = 18  sisa 1  |
	18 : 2 =  9  sisa 0  |
	9 : 2  =  4  sisa 1  |
	4 : 2  =  2  sisa 0  |
	2 : 2  =  1  sisa 0  |  Maka hasilnya adalah 1001011

>Contoh 2 : Mengubah Bilangan Desimal ke Oktal
>(75)<sub>10</sub> = ( ... )<sub>8</sub>

	75 : 8 = 9 sisa 3   ^
	9 : 8  = 1 sisa 1	  | Maka hasilnya adalah 113

> Contoh 3 : Mengubah Bilangan Desimal Ke Hexadesimal
> (75)<sub>10</sub> = ( ... )<sub>16</sub>

	75 : 16 = 4 sisa 11 | Maka Hasilnya adalah 4 11. Dikonversi ke Hexadesimal menjadi 4B

2. Sistem Selain Desimal ke Desimal
	Caranya yaitu mengalikan bilangan sistem lain tersebut dengan Radix bilangan tersebut dipangkatkan dengan letak digitnya dan kemudian dijumlahkan

> Contoh 1 : Mengubah Bilangan Biner ke Desimal
> (1001011)<sub>2</sub> = ( ... )<sub>10</sub>

	1 x 2^0 =  1
	1 x 2^1 =  2
	0 x 2^2 =  0
	1 x 2^3 =  8
	0 x 2^4 =  0
	0 x 2^5 =  0
	1 x 2^6 = 64
	          --- +
	          75 -> Bilangan Desimal dari 1001011 adalah 75


> Contoh 2 : Mengubah Bilangan Oktal ke Desimal
> (113)<sub>8</sub> = ( ... )<sub>10</sub>

	3 x 8^0 =   3
	1 x 8^1 =   8
	1 x 8^2 =  64
	          --- +
	          75 -> Bilangan Desimal dari 113 adalah 75

> Contoh 3 : Mengubah Bilangan Hexadesimal ke Desimal
> (4B)<sub>16</sub> = ( ... )<sub>10</sub>

	Ubah Menjadi Angka Terlebih dahulu -> 4B -> 4 11 
	11 x 16^0 =  11
	 4 x 16^1 =  64
	          --- +
	          75 -> Bilangan Desimal dari 4B adalah 75

3. Sistem selain Desimal
	Untuk konversi antara sistem selain desimal. Gunakan Tabel Kebenaran.

- Biner
	Sistem bilangan Biner memiliki Radix 2, apabila diubah menjadi pangkat 2 maka akan berubah menjadi 2<sup>1</sup>. Sehingga tabel kebenarannya adalah sebagai berikut
	
	| Angka | Biner | 
	| ----- | ----- |
	| 0 | 0 |
	| 1 | 1 |

- Oktal
	Sistem bilangan Oktal memiliki Radix 8, apabila diubah menjadi pangkat 2 maka akan berubah menjadi 2<sup>3</sup>. Sehingga tabel kebenarannya adalah sebagai berikut

	| Angka | Biner | Angka | Biner |
	| ----- | ----- | ----- | -----|
	| 0 | 000 | 4 | 100 |
	| 1 | 001 | 5 | 101 |
	| 2 | 010 | 6 | 110 |
	| 3 | 011 | 7 | 111 |
 
- Hexadesimal
	Sistem bilangan Hexadesimal memiliki Radix 16, apabila diubah menjadi pangkat 2 maka akan berubah menjadi 2<sup>4</sup>. Sehingga tabel kebenarannya adalah sebagai berikut

	| Angka | Biner | Angka | Biner|
	| ----- | ----- | -----| ---- |
	| 0 | 0000 | 8 | 1000 |
	| 1 | 0001 | 9 | 1001 |
	| 2 | 0010 | A | 1010 |
	| 3 | 0011 | B | 1011 |
	| 4 | 0100 | C | 1100 |
	| 5 | 0101 | D | 1101 |
	| 6 | 0110 | E | 1110 |
	| 7 | 0111 | F | 1111 |

> Contoh 1 : Mengubah Hexadesimal ke Oktal
> (4B)<sub>16</sub> = ( ... )<sub>8</sub>

	> Angka 4 Memiliki Biner 0100
	> Huruf B Memiliki Biner 1011
	----------------------------
	> Digabung menjadi 01001011
	> Pisah menjadi kelompok berisi 3 sehingga menjadi 01 001 011
	> Dikarenakan 01 hanya memiliki 2 anggota dalam kelompoknya. Tambahkan 0 dibelakang menjadi 001
	> Biner yang kita dapat adalah 001 001 011
	----------------------------
	> 011 Merupakan Biner dari Angka 3
	> 001 Merupakan Biner dari Angka 1
	> 001 Merupakan Biner dari Angka 1
	----------------------------
	Angka Oktal dari 4B adalah 113
 	
> Contoh 2 : Mengubah Biner ke Hexadesimal
> (01001011)<sub>2</sub> = ( ... )<sub>16</sub>

	> Pisah menjadi kelompok berisi 4 sehingga menjadi 0100 1011
	> Biner yang kita dapat adalah 0100 1011
	----------------------------
	> 0100 Merupakan Biner dari Angka 4
	> 1011 Merupakan Biner dari Huruf B
	----------------------------
	Angka Hexadesimal dari 01001011 adalah 4B
