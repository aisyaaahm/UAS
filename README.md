# Ujian Akhir Semester 
<br>Mata Kuliah : Dasar Pemograman
<br>Nama		    : Aisyah Muthmainnah
<br>NIM		      : 1227050012	
<br>Jurusan		  :[Teknik Informatika](http://if.uinsgd.ac.id/) [UIN Sunan Gunung Djati Bandung](https://uinsgd.ac.id/) 

## Deskripsi Umum
Source code yang digunakan untuk membuat array dua dimensi. Program yang mengubah letak nilai yang sebelumnya sebuah baris menjadi sebuah kolom, dan sebaliknya. 
Dengan algoritma :
1. User menginputkan berapa banyak baris pada array
2. User menginputkan berapa banyak kolom dari baris pada array
3. User menginputkan satu persatu nilai array
4. Output nilai array sesuai dengan matriks juga ditampilkan nilai yang sudah dibalik

## Source Code
	#include <iostream>
	#include <iomanip>
	using namespace std;
	int main()
	{
 	int matriks[100][100];
	 int baris, kolom, i, j;
	 cout << "Input jumlah baris : ";
	 cin >> baris;
	 cout << "Input jumlah kolom : ";
	 cin >> kolom;
	 cout << endl;

	 for(i = 0; i < baris ; i++){
	 for(j = 0; j < kolom; j++){
	 cout << "Baris " << i+1 <<", kolom " << j+1 << " = ";
	 cin >> matriks[i][j];
	 }
	 Cout << endl;
	 }
	 cout << "Hasil matriks: " << endl;
	 for(i = 0; i < baris ; i++){
	 for(j = 0; j < kolom; j++){
	 cout << setw(3) << matriks[i][j] << " ";
	 }
	 cout << endl;
	 }

	 cout << "-------------------------" << endl;

	 for (i = 0; i < kolom; i++) {
	 for (j = 0; j < baris; j ++) {
	 cout << " " << matriks[j][i];
	 }
	 cout << endl;
	 }
	 return 0;
	}

## Output
![image](https://user-images.githubusercontent.com/121163710/208883576-ad702867-8301-4ac2-8b99-95e561a0823e.png)
