# Ujian Akhir Semester
<br> Mata Kuliah : Dasar Pemrograman
<br> Nama        : Balqis Salabillah Azzahra
<br> NIM         : 1227050028
<br> Jurusan     : [Teknik Informatika] (http://if.uinsgd.ac.id/) [UIN Sunan Gunung Djati Bandung](https://uinsgd.ac.id/) 

## Deskripsi Umum

<br> Array adalah sebuah variabel yang punya kemampuan untuk menyimpan lebih dari 1 nilai yang memiliki tipe yang sama. Atau dalam kata lain array adalah sekumpulan data dengan tipe data yang sama. 
<br> Kali ini kita akan mengubah letak nilai yang sebelumnya baris menjadi kolom dan letak nilai yang sebelumnya kolom menjadi baris menggunakan array C++.
<br> Algoritma dari Source Code ini yaitu :
<br> 1. User menginputkan jumlah baris pada array.
<br> 2. User menginputkan jumlah kolom pada array.
<br> 3. User menginputkan nilai tiap baris dan kolom.
<br> 4. Nilai ditampilkan sesuai aturan matriks.
<br> 5. Kemudian ditampilkan nilai yang letaknya telah diubah.

## Source Code

<br> #include 
<br> using namespace std;
<br>
<br> int main (){
    <br> int data [50][50];
    <br> int b, k, i, j;

    <br> cout << "Masukkan Jumlah Baris : "; cin >> b;
    <br> cout << "Masukkan Jumlah Kolom : "; cin >> k;
    <br> cout << endl;

    <br> for (i=0; i<b; i++){
        <br> for (j=0; j<k; j++){
            <br> cout << "Baris " << i+1 << ", Kolom " << j+1 << ": "; cin >> data [i][j];
        }
        << br> cout << endl;
    }
    <br> cout << "Letak Nilai Sebelum diubah : " << endl;
    <br> for (i=0; i<b; i++){
        <br> for (j=0; j<k; j++){
            <br> cout << " " << data [i][j];
        }
        cout << endl;
    }
    <br> cout << endl;
    <br> cout << "=====================================\n\n";
    <br> cout << "Letak Nilai Setelah diubah : \n"
    <br> for (i=0; i<k; i++){
        <br> for (j=0; j<b; j++){
            <br> cout << " " << data [j][i];
        }
        <br> cout << endl;
    }
}

## Output

![matriks](https://user-images.githubusercontent.com/121304572/209414398-750ce903-219c-445f-9938-407c723314d3.jpg)
