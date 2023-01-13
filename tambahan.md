nda dapat selalu memeriksa tipe variabel yang digunakan dengan fungsi type() dan memastikan tipe variabel yang tepat dengan metode isinstance().

Untuk objek yang didefinisikan sendiri, representasi nilai Boolean akan bergantung dari definisi metode (method) khusus bernama __bool__(self). Jika metode ini mengembalikan True maka interpretasi nilai dari objeknya akan True, demikian juga sebaliknya.

ika input merupakan string berisi ekspresi matematika, maka konversi dengan int() atau float() akan menghasilkan error. Anda dapat menggunakan fungsi eval() yang sekaligus juga berfungsi menyelesaikan ekspresi matematika.

-round (membukatkan angka atau menentukan jumlah angka di belakang koma)
