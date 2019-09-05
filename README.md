# Tugas-1-Pemrograman-Jaringan_1301188565
Sella Tresnasari / 1301188565

## nomor 1

![image](https://user-images.githubusercontent.com/54678313/64269392-017a9200-cf64-11e9-9ab4-6afd7911d941.png)

Finite State Machine adalah sebuah metode perancangan system control yang menggambarkan prinsip kerja system dengan menggunakan state (keadaan), event (kejadian), action (aksi).

Cara kerja pada Server
-	Server dimulai pada Starting Point
-	Server menerima SYN dan mengirim SYN, ACK ke SYN RCVD
-	Server menerima ACK di Connection Estabilished
-	Server menerima FIN dan mengirim ACK ke Close Wait
-	Server mengirim FIN ke Last ACK
-	Server menerima ACKlalu server CLOSE


Cara kerja pada Client
-	Client mulai pada Starting Point
-	Client mlakukan Active Open
-	Client mengirim SYN ke SYN SENT
-	Client menerima SYN, ACK dan mengirim ACK ke Connection Estabilished
-	Clinet close dan mengirim FIN  ke FIN WAIT 1
-	Client menerima ACK di FIN Wait 2
-	Client menerima FIN dan mengirim ACK ke Time Wait
-	Client Time Out lalu ke CLOSE (berakhir)

## nomor 2
Hasil Screenshoot:

FOR
-	Melakukan perulangan dengan kondisi yang ditentukan (i=1)
-	Selama i <= 3 program melakukan looping
-	Perulangan berhenti ketika kondisi false
-	Perulangan dapat dihentikan menggunakan break dan dilanjutkan dengan continue

ELSE
-	Jika IF memiliki kondisi true/ benar makan program dijalankan
-	Jika kondisi berbeda maka program akan menjalankan kondisi di else

## nomor 3
Hasil Screenshoot:

Array
-	Array merupakankumpulan data bertipe sama, yang disimpan dalam sebuah variabel
-	Array juga dapat digunakan untuk mengukur suatu panjang dari array tersebut

Function
-	Fuction/fungsi sekumpulan blok kode yang dibungkus dengan nama tertentu, seperti function plus akan menjalankan perintah a+b sedangkan function plusPlus akan menjalankan perintah a+b+c

## nomor 4
Hasil Screenshoot:

Struct
-	Struct merupakan kumpulan definisi dari variabel dan fungsi, yang dibungkus sebagai tipe data baru dengan nama tertentu
-	Variabel dalam struct dapat memiliki tipe data yang bervariasi.
-	Pada function main terdapat beberapa perintah yang bias menampilkan 2 tipe data yg berbeda seperti:
fmt.Println(person{“Bob”, age: 30})
output : {Bob 20}

Method
-	Method adalah suatu fungsi yang menempel pada tipe data seperti struct atau tipe data lainnya
-	Method bisa diakses lewat variabel objek.
-	Method memiliki akses ke property struct.
-	Pada soal kedua struct telah membuat inisialisasi pada variabel width dan height, dan method memanggil struct.
-	Pada soal yang kedua method memanggil “rect” pada struct untuk menjalankan method perkalian width dengan height (line 39-41)

## nomor 5
Hasil Screenshoot:

Multiple Return
-	Multiple Return merupakan sebuah fungsi yang bisa mengembalikan lebih dari 1 nilai yang dilakukan sebuah fungsi.
-	Pada func vals () (int,int) {return 3,7} lalu pada func main() nilai 3 dan 7 diambil lalu ada pengembalian nilai c maka mengeluarkan output an 3 7 7

Command Line (flag)
-	Command line dapat mendeklarasi flag yang berupa string, integer, dan Boolean
-	Flag di deklarasi kan di dalam sebuah function
-	Pada soal kedua terdapat beberapa jenis flag yaitu : string, integer, Boolean
-	Pada pemanggilan program menampilkan output yang sesuai dengan jenis flag seperti pada line 53 flag membuat perintah string dan meampilkan output “numb: 42”

## nomor 6
Program pada soal nomor 6 terdapat program client server dimana program yang berjalan sebagai server menunggu client request untuk mengakses program melalui localhost:8000. Terdapat function di dalam function, yang bekerja untuk pemanggilan 
Client memanggil localhost:8000 sebagai berikut:
