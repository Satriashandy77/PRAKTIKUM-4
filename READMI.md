NAMA  : SHANDY SATRIA MANDALA
KELAS : TI.22.B1
NIM   : 312210173

#TUGAS PRAKTIKUM BAHASA PEMROGRAMAN

#LATIHAN STRUKTUR KONDISI DAN PERULANGAN PADA PYTHON

1. Buat folder Buat folder dengan nama Praktikum 4 lalu didalamnya kita buat dua folder yaitu struktur-kondisi & perulangan dan didalamnya buat file Latihan1.py dan Latihan2.py dimasing masing folder . berikut contohnya :

Note: Kalian bebas memberi nama folder dan filenya

https://user-images.githubusercontent.com/115520278/199703936-2120656b-696f-47b8-8a4d-27b773aa7065.PNG

2. Selanjutnya buka file struktur-kondisi > Latihan1.py... lalu isikan codingan berikut :

https://user-images.githubusercontent.com/115520278/199704279-1a53f770-010f-4529-a9fa-855d42e771c6.PNG

Jika sudah lalu kita jalankan dengan cara ketikan diterminal yaitu python Latihan1.py !!! perlu diingat kita harus berada didirektor struktur-kondisi. Lalu akan tampil hasilnya seperti dibawah ini

https://user-images.githubusercontent.com/115520278/199704663-5c883aad-0eed-48de-b80b-0326db81bad0.PNG

3. Selanjutnya buka Latihan2.py pada folder struktur-kondisi lalu ketikan codingan berikut :

https://user-images.githubusercontent.com/115520278/199705435-b40cb2d2-c095-4feb-b740-17fcd576b8a4.PNG

Jika sudah lalu kita jalankan dengan cara ketikan diterminal yaitu python Latihan2.py !!! perlu diingat kita harus berada didirektor struktur-kondisi. Lalu akan tampil hasilnya seperti dibawah ini

https://user-images.githubusercontent.com/115520278/199705570-87fd713f-bbc3-4ea7-8c9b-3f20e60251b9.PNG

4. Selanjutnya buka Latihan1.py pada folder perulangan lalu ketikan codingan berikut :

https://user-images.githubusercontent.com/115520278/199705850-126c71d2-8ee4-4a32-8b9b-3302f489e46c.PNG

Jika sudah lalu kita jalankan dengan cara ketikan diterminal yaitu python Latihan1.py !!! perlu diingat kita harus berada didirektor perulangan. Lalu akan tampil hasilnya seperti dibawah ini

https://user-images.githubusercontent.com/115520278/199706112-44e41684-060e-4654-9263-479d5b474c01.PNG

5. Selanjutnya buka Latihan2.py pada folder perulangan lalu ketikan codingan berikut :

# import module random untuk mengenerate angka acak 0.3222...dst
  from random import random

  # variable jumlahNilai menampung input masukan lalu diconvert ke integer
  jumlahNilai = int(input('Masukan jumlah nilai yang ingin dicari : '))

  # variable nilaiRandom & kurangDariNolKomaLima berupa array/list untuk menyimpan data yang diperlukan nanti.
  nilaiRandom = []
  kurangDariNolKomaLima = []

  # looping data berdasarkan jumlahNilai,
  for i in range(0, jumlahNilai):
      # variable n = menyimpan angka random contoh: 0.9905112793033766
      n = random()

      # menambahkan n ke variable nilaiRandom
      # fungsi append() untuk menambahkan data ke dalam variable yang type datanya berupa array/list
      nilaiRandom.append(n)

      # apakah n < dari 0.5 ? jika iya tampilkan lalu break dan memulai ke angka random selanjutnya
      while n < 0.5:

          # menambahkan n jika kurang dari 0.5 ke variable kurangDariNolKomaLima
          kurangDariNolKomaLima.append(n)

          # menampilkan output n
          print("data ke -", str(i+1), " => ", n)
          break

  print()
  # menampilkan output keseluruhan nilai random
  print("Berikut keseluruhan nilai Random dari total ", jumlahNilai,
        "yaitu ", nilaiRandom)

  print()
  # menampilkan output keseluruhan nilai n < 0.5
  print("Berikut nilai yang kurang dari 0.5 berjumlah ", len(kurangDariNolKomaLima),
        "yaitu ", kurangDariNolKomaLima)

Jika sudah lalu kita jalankan dengan cara ketikan diterminal yaitu python Latihan2.py !!! perlu diingat kita harus berada didirektor perulangan. Lalu akan tampil hasilnya seperti dibawah ini

https://user-images.githubusercontent.com/115520278/199706539-8a7601b3-b98d-491b-97ba-fc3ca74322fc.PNG

Sekian penjelasan dari saya semoga bermanfaat, terimakasih 
