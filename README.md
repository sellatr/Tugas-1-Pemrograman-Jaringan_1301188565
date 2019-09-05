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
