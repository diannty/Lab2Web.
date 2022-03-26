**#PEMOGRAMAN WEB**


**BELAJAR CSS**

Nama 			= Dian Tri Handayani 

NIM		    	= 312010041
    
Kelas			= TI 20 D1

Mata Kuliah		= Pemrograman Web

Dosen Pengajar	= Agung Nugroho, S. Kom., M. Kom


**MEMBUAT DOKUMEN HTML**

Pertama - tama disini membuat sebuah dokumen dasar Html seperti dibawah ini terlebih dahulu, yang nantinya akan dimodifikasi.

![satu](https://user-images.githubusercontent.com/101880835/160219386-a1fe9514-6842-46db-aba1-361e6b6af878.png)

Dari kodingan berikut :

![langkah 1](https://user-images.githubusercontent.com/101880835/160219458-10737d75-dba8-4f3f-a16c-6518de6040e9.png)



**MENDEKLARASIKAN CSS INTERNAL**

![dua](https://user-images.githubusercontent.com/101880835/160219640-70c12c38-7725-4677-83e4-2d7cf9eec607.png)

Dan untuk dapat menambahkan sebuah deklarasi tersebut, bisa menggunakan codingan dibawah, yang bisa ditambahkan dibagian head dari codingan dokumen sebelumnya.

![langkah 2](https://user-images.githubusercontent.com/101880835/160219630-8310ac7f-4c51-444d-9d64-59667272caa8.png)



**MENAMBAHKAN INLINE CSS**

Setelah menambahkan deklarasi internal seperti diatas, selanjutnya menambahkan sebuah Inline CSS pada deklarasi tersebut seperti dibawah ini.

![tiga](https://user-images.githubusercontent.com/101880835/160219906-7c404e79-a2fb-4c31-986f-2f76cc9ffe91.png)

Cara untuk menambahkan sebuah inline pada deklarasi sebelumnya kalian hanya perlu menambahkan sebuah tag < P > berikut pada sebuah awal kalimat yang diinginkan agar menampilkan sebuah warna yang diinginkan.

![langkah 3](https://user-images.githubusercontent.com/101880835/160219896-b53f4ec3-d214-473d-ace2-31e9b7b65996.png)


**MEMBUAT CSS EKSTERNAL**

Langkah selanjutnya, disini membuat sebuah file baru terlebih dahulu dengan judul style_eksternal.css yang kemudian nantinya akan dideklarasikan kembali seperti dibawah ini.

![empat](https://user-images.githubusercontent.com/101880835/160220937-a184ab34-100e-4de5-9332-98e7af6b07d2.png)

Selanjutnya, kembali pada Html dan kemudian kita tambahkan sebuah tag < link > untuk dapat merujuk ke file CSS yang sudah dibuat pada bagian seperti ini.

![langkah 4 1](https://user-images.githubusercontent.com/101880835/160220952-046dcd78-5871-48c7-925c-c2e14807b90d.png)

![langkah 4](https://user-images.githubusercontent.com/101880835/160220942-c358f2e2-8a4a-4b6a-a8a7-be2a8f3f3f3c.png)



**MENAMBAHKAN CSS SELECTOR**

Langkah terakhir yaitu diakhiri dengan menambahkannya sebuah CSS Selector yang menggunakan ID dan Class Selector pada file style_eksternal.css sebelumnya.

![langkah 5](https://user-images.githubusercontent.com/101880835/160220962-dccc182d-47a1-499a-afad-538ff805543a.png)

Dan untuk dapat menambahkan sebuah CSS Selector maka kalian hanya perlu menambahkan kode berikut pada codingan di file style_eksternal.css seperti dibawah ini.

![lima](https://user-images.githubusercontent.com/101880835/160221408-0367a6e4-a5d3-4a50-a72c-54e935703f43.png)






**PERTANYAAN DAN TUGAS**


**1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.**

![lima](https://user-images.githubusercontent.com/101880835/160221408-0367a6e4-a5d3-4a50-a72c-54e935703f43.png)

![langkah 5](https://user-images.githubusercontent.com/101880835/160220962-dccc182d-47a1-499a-afad-538ff805543a.png)

**2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!**

 
Elemen h1 {...} yang dideklarasikan pada CSS mengacu pada style atau gaya teks saja yang ada di halaman awal web (sebagai header) atau memberi style CSS pada elemen HTML yang diingikan. Elemen h1 {...} mengacu pada Internal CSS yaitu menyisipkan CSS pada file HTML.

Elemen #intro h1 {...} memiliki id maka penggunaan pada css dengan pagar (#) dan di dalam file index.html dalam pemanggilannya menggunakan id=" ". Elemen tersebut mengacu pada tampilan selector yang terdiri dari ID dan Class dimana ID selector ditandai dengan tanda pagar (#) di depannya.


**3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!**

Jika ketiganya di deklarasikan secara bersamaan maka yang muncul di browser hanyalah hasil deklarasian Inline CSS. Karena Inline memiliki prioritas terkuat dibandingkan dengan internal ataupun eksternal.

![CONTOH](https://user-images.githubusercontent.com/101880835/160222319-09d704ab-5d2f-4aef-8a22-9ddf0afb3a1f.png)

![tigaaa](https://user-images.githubusercontent.com/101880835/160222369-4ee9a381-fa57-408b-a41a-05ba73547372.png)

![contoh 3](https://user-images.githubusercontent.com/101880835/160222621-c664be43-40d4-4124-8fb5-7bd149280720.png)


**4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya**


Yang akan ditampilkan pada bworser dari keduanya adalah ID.

![empat](https://user-images.githubusercontent.com/101880835/160222627-59d6f5de-8d63-4e30-bf6a-0762aff21635.png)

Seperti yang dilihat, ID memiliki properti {color:rgb(154, 110, 140); text-align:center} karena lebih unik dibandingkan CLASS.



