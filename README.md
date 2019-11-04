<h1> Program Sederhana Python Perulangan </h1>

Setelah saya posting "Labpy-2", sekarang saya ingin memposting cara membuat program sederhana.
Yang di butuhkan for dan while.

Struktur Algoritma MP3 Prepare 1(Latihan 1)
1. Mulai
2. Tampilkan **n** bilangan acak yang lebih kecil dari 0.5
3. Nilai **n** diisi pada saat runtime
4. Anda bisa menggunakan kombinasi **while** dan **for** untuk menyelesaikannya.
5. Gunakan fungsi random() yang dapat diimport terlebih dahulu.
6. Selesai

***Step pada source code MP3 Prepare 1***

    import random
    jumlah = int (input("Masukkan jumlah n:"))
    for i in range(jumlah):

     i=random.uniform(0.0,0.5)
     print("Data Ke:", i) 
    print("Selesai")

***Screenshoot Code MP3 Prepare 1***

![Prepare 1](https://user-images.githubusercontent.com/46983614/68128286-0949b900-ff4a-11e9-936f-dd3e4b35facc.png)

Struktur Algoritma MP3 Prepare 2(Latihan 2)
1. Mulai
2. Inisiasi bil1,bil2,bil3 sebagai integer.
3. Baca bil1.
4. Baca bil2.
5. Baca bil3.
6. Jika bil1 > bil2 dan bil1 > bil3 maka kerjakan langkah 8, selain itu
7. Jika bil2 > bil1 dan bil2 > bil3 maka kerjakan langkah 9, selain itu kerjakan langkah 10.
8. Cetak “Bilangan Terbesar Bilangan Pertama”.
9. Cetak “Bilangan Terbesar Bilangan Kedua”.
10. Cetak “Bilangan Terbesar Bilangan Ketiga”.
11. Selesai

***Step pada source code MP3 Prepare 2***

print ('program untuk menentukan bilangan terbesar dan terkecil')

def pengulangan():

    print ('masukkan 3 bilangan yang diinginkan!')
    a=int(input('bilangan1 = '))
    b=int(input('bilangan2 = '))
    c=int(input('bilangan3 = '))

    if a>b and a>c:
        if b>c:
            print (a, 'terbesar dan', c, 'terkecil')
        else:
            print (a, 'terbesar dan', b, 'terkecil')
    elif b>a and b>c:
        if a>c:
            print (b, 'terbesar dan', c, 'terkecil')
        else:
            print (b, 'terbesar dan', a, 'terkecil')
    else:
        if a>b:
            print (c, 'terbesar dan', b, 'terkecil')
        else:
            print (c, 'terbesar dan', a, 'terkecil')

    print ('')
    print ('ingin coba lagi? (ya/tidak)')
    x=input()
    if x=='ya':
        return pengulangan()
    if x=='tidak':
        print('terimakasih telah menggunakan program ini.')

pengulangan()

***Gambaran Flowchart***

![2013-01-17_082540](https://user-images.githubusercontent.com/46983614/67663464-2bff2f00-f998-11e9-9af4-8b55e2346a7d.jpg)

***Screenshoot Code MP3 Prepare 2***

![Prepare 2](https://user-images.githubusercontent.com/46983614/68128589-90972c80-ff4a-11e9-9236-b310fcb1b24d.png)


<h2> Oke Sekian Terima Kasih Dan Tunggu Update an Nextnya Ya !!! </h2>
