# labspy02
## PERTEMUAN 7 
**NAMA: OEN SAPUTRA HUTAJULU** <br>
**KELAS: TI. 20. A. 1** <br>
**NIM: 312010155** <br>
--------------------

Pada pertemuan 7 tugas PPT ke-2 ini, saya diberikan beberapa tugas oleh dosen saya yaitu: <br>

![tugas 2](foto/tugaspraktikum2.png)


untuk mencari sebuah nilai maksimal dari 3 data yang sebelumnya telah diinput, dan setelah mendapat nilai maksimalnya.dirubah menjadi dalam sebuah bentuk flowchart. <br>

TUGAS PRAKTIKUM 2 <br>
MENGINPUT DATA DAN MENCARI NILAI MAX <br>
Pertama-tama disini saya akan mencoba untuk menginput 3 data dengan menggunakan syntax berikut terlebih dahulu. <br>

a = int(input("Masukkan bilangan 1: ")) <br>
b = int(input("Masukkan bilangan 2: ")) <br>
c = int(input("Masukkan bilangan 3: ")) <br>
Masukan syntax tersebut dengan angka yang kalian inginkan <br>

Jika sudah mendapat tampilan seperti gambar diatas, maka kalian sudah berhasil menginput ketiga data tersebut. <br>

Langkah selanjutnya adalah mencari tahu nilai terbesar (max) dari ketiga data tersebut. Sebelum memulainya kalian harus memasukan terlebih dahulu berapa jumlah data yang akan kalian kerjakan dari ketiga data tersebut dengan syntax <br>

N=int(input("banyaknya data = ")) <br>
Karena disini saya diberi tugas mencari nilai max dari ketiga data maka saya akan menggunkan semua data diatas. <br>

if N>0:
    i=1
    x=int(input("data ke -"+str(i)+"="))
    max=x;total=x
    for i in range(2,N+1):
        x=int (input("data ke -"+str(i)+"="))
        total+=x
        if max<x:
            max=x

    print("bilangan terbesar =",max)
Selanjutnya kalian bisa langsung memasukan syntax ini untuk melengkapi syntax diatas supaya bisa berjalan dengan baik seperti pada gambar dibawah ini. <br>

![tugas](foto/latihan2.png)


Maka jika digabungkan, cara untuk mencari nilai max dari ketiga data yang diinputkan adalah dengan menggunakan syntax <br>

N=int(input("banyaknya data = "))
if N>0:
    i=1
    x=int(input("data ke -"+str(i)+"="))
    max=x;total=x
    for i in range(2,N+1):
        x=int (input("data ke -"+str(i)+"="))
        total+=x
        if max<x:
            max=x

    print("bilangan terbesar =",max)
Seperti inilah hasil akhirnya

![tugas](foto/hasillatihan1.png)

MERUBAH DATA DIATAS MENJADI DALAM BENTUK FLOWCHART
Setelah kalian mendapatkan semua data diatas langkah selanjutnya adalah mengubahnya menjadi dalam
 bentuk flowchart seperti ini <br>

![tugas](foto/flowchart1.png)

-----------**TERIMA KASIH**-----------