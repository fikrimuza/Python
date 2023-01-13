- Number

     Tipe numerik pada Python dibagi menjadi 3: int, float, complex.

- String

     String adalah urutan dari karakter unicode yang dideklarasikan dengan petik tunggal atau ganda. String > 1 baris dapat ditandai dengan tiga petik tunggal atau ganda ''' atau """
     
- Boolean

     Tipe data bool atau Boolean merupakan turunan dari bilangan bulat (integer atau int) yang hanya punya dua nilai konstanta: True dan False.
    
- List

     List adalah jenis kumpulan data terurut (ordered sequence), elemen List pada Python tidak harus memiliki tipe data yang sama. Mendeklarasikan List cukup mudah dengan kurung siku dan elemen yang dipisahkan dengan koma. List menggunakan index ,dimulai dari 0.
     
     Pengambilan index list
  
      x = [5,10,15,20,25,30,35,40]
      print(x[5])
      print(x[-1])
      print(x[3:5])
      print(x[:5])
      print(x[-3:])
      print(x[1:7:2])
     
     Merubah elemen list

      x = [1,2,3]
      x[2]=4
      print(x)

     
     Menambahkan list dengan append
     
      x = [1,2,3]
      x[2]=4
      x.append(5)
      print(x)
      
     Menambahkan list dengan insert
      
      insert(0, value)
      
     Mengambil isi list
     
      list.pop(index)
     
     Menghapus list menggunakan fungsi del
     
      binatang = ['kucing', 'rusa', 'badak', 'gajah']
      del binatang[2]
      print(binatang)
      
     Menghapus list menggunakan remove
     
      list.remove(value)
    
- Tuple

     Tuple adalah jenis dari list yang tidak dapat diubah elemennya. Umumnya tuple digunakan untuk data yang bersifat sekali tulis, dan dapat dieksekusi lebih cepat. Tuple didefinisikan dengan kurung biasa dan elemen yang dipisahkan dengan koma.
     
      t = (5,'program', 1+3j)
     
- Set

     Set adalah kumpulan item bersifat unik dan tanpa urutan (unordered collection). Didefinisikan dengan kurawal dan elemennya dipisahkan dengan koma. Pada Set kita dapat melakukan union dan intersection, sekaligus otomatis melakukan penghapusan data duplikat.
     
      a = {1,2,2,3,3,3}
      print(a)
     
- Dictionary

     Dictionary pada Python adalah kumpulan pasangan kunci-nilai (pair of key-value) yang bersifat tidak berurutan. Dictionary dapat digunakan untuk menyimpan data kecil hingga besar. Untuk mengakses datanya, kita harus mengetahui kuncinya (key). Pada Python, dictionary didefinisikan dengan kurawal dan tambahan definisi berikut:

     - Setiap elemen pair key-value dipisahkan dengan koma (,).
     - Key dan Value dipisahkan dengan titik dua (:).
     - Key dan Value dapat berupa tipe variabel/obyek apapun.

      d = {1:'value','key':2}
      print(type(d))
      print("d[1] = ", d[1])
      print("d['key'] = ", d['key'])
    
- Konversi (conversion, cast) antar tipe data

     Kita dapat melakukan konversi tipe data bawaan dengan menggunakan fungsi konversi tipe bawaan (standard type) misalnya: int(), float(), str(), dll.
