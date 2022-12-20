# Ujian Akhir Semester
<br>Mata Kuliah         : Dasar Pemrograman
<br> Nama               : Nazwa Revalina Azzahra Djuarsah
<br>NIM         : 1227050104
<br>Jurusan             : [Teknik Informatika] (http://if.uinsgd.ac.id/) [UIN Sunan Gunung Djati Bandung] (https://uinsgd.ac.id/)

## Deskripsi Umum
<br>Array 2 dimensi adalah suatu array yang analoginya seperti baris dengan jumlah tertentu dan kolom dengan jumlah tertentu yang didalamnya terdapat nilai atau data.
## Source Code
<br> Berikut source code array 2 dimensi pada c++:
<br> 1. Baris-kolom menjadi kolom-baris

#include <iostream>
using namespace std;

int main(){
	int baris, kolom;
	int i, j;
	
	cout<<"UAS 1 DASAR PEMROGRAMAN";
	cout<<"\nNama\t: Nazwa Revalina Azzahra D.";
	cout<<"\nNIM\t: 1227050104";
	cout<<"\nJurusan\t: IF-1C";
	cout<<"\n========================"<<endl;
	
	cout<<"Masukkan jumlah baris : ";
	cin>>baris;
	cout<<"Masukkan jumlah kolom : ";
	cin>>kolom;
	cout<<"========================"<<endl;
	
	int data[baris][kolom];
	for(i=0; i<baris; i++){
		for(j=0; j<kolom; j++){
		cout<<"Masukkan nilai baris ke-"<<i<<" dan kolom ke-"<<j<<" : ";
		cin>>data[i][j];
		}
	}
	cout<<"========================"<<endl;
	
	cout<<"Baris-Kolom"<<endl;
	for(i=0; i<baris; i++){
		for(j=0; j<kolom; j++){
		cout<<data[i][j]<<" ";
		}
		cout<<endl;
	}
	cout<<"========================"<<endl;
	
	cout<<"Kolom-Baris"<<endl;
	for(i=0; i<kolom; i++){
		for(j=0; j<baris; j++){
		cout<<data[j][i]<<" ";
		}
		cout<<endl;
	}
	
	return 0;
}
  
<br>2. Mencari nilai yang habis dibagi 3, 5, dan 7

#include <iostream>
using namespace std;

int main(){
	int baris, kolom;
	int i, j;
	
	cout<<"UAS 1 DASAR PEMROGRAMAN";
	cout<<"\nNama\t: Nazwa Revalina Azzahra D.";
	cout<<"\nNIM\t: 1227050104";
	cout<<"\nJurusan\t: IF-1C";
	cout<<"\n========================"<<endl;
	
	cout<<"Masukkan jumlah baris : ";
	cin>>baris;
	cout<<"Masukkan jumlah kolom : ";
	cin>>kolom;
	cout<<"========================"<<endl;
	
	int data[baris][kolom];
	for(i=0; i<baris; i++){
		for(j=0; j<kolom; j++){
		cout<<"Masukkan nilai ["<<i<<"."<<j<<"] : ";
		cin>>data[i][j];
		}
	}
	cout<<"========================"<<endl;
	
	for(i=0; i<baris; i++){
		for(j=0; j<kolom; j++){
			if((data[i][j]%3==0) && (data[i][j]%5==0) && (data[i][j]%7==0)){
				cout<<"Nilai yang habis dibagi 3, 5, dan 7 adalah "<<data[i][j]<<endl;
				}
		}
	}
	
	return 0;
}
  
## Output
  <br>Output dari kedua source code di atas adalah sebagai berikut:
  <br>1. Baris-kolom menjadi kolom-baris
  ![Screenshot (306)](https://user-images.githubusercontent.com/119474745/208703760-c0044fb1-bb52-4403-8d31-a9144183ee21.png)
  <br>
<br>2. Mencari nilai yang habis dibagi 3, 5. dan 7
  ![Screenshot (307)](https://user-images.githubusercontent.com/119474745/208704106-43b3d4e6-06bf-4a42-a679-fca5dee7ba21.png)
