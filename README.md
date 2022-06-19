# Project-Visualisasi-Data
Dokumentasi mengenai perancangan dan pengembangan dashboard informasi fasilitas pendidikan di Indonesia

Dalam perancangan dan pengembangan dashboard serta klasterisasi terdapat beberapa step yang dilakukan, yaitu sebagai berikut :
1. Pengumpulan dan pengolahan data
2. Perancangan visualisasi data
3. Perancangan dashboard
4. Klasterisasi provinsi berdasarkan Jumlah Fasilitas Pendidikan

## 1. Pengumpulan dan pengolahan Data
  Data yang digunakan dalam perancangan dashboard ini adalah data jumlah fasilitas pendidikan di Indonesia menurut provinsi pada tahun 2021 yang diperoleh dari website Badan Pusat Statistik (BPS)  (<https://bps.go.id/>).  
  Data yang diperoleh dari website merupakan data publikasi statistik pendidikan dimana data tersebut juga berasal dari Kementerian Pendidikan dan Kebudayaan RI.
  Kemudian setelah pengolahan dan pemilihan variabel yang akan digunakan untuk perancangan dashboard memiliki 9 variabel. Variabel tersebut terdiri dari nama provinsi, Jumlah SD, Jumlah SMP, Jumlah SMA, Jumlah SMK, Jumlah Guru SD, Jumlah Guru SMP, Jumlah Guru SMA dan Jumlah Guru SMK dengan rincian sebagai berikut.
  1. Variabel provinsi
     Variabel tersebut menjelaskan nama 34 provinsi yang ada di Indonesia.
  2. Variabel jumlah SD
     Variabel tersebut menjelaskan Jumlah Sekolah Dasar yang ada di 34 provinsi pada tahun 2021.
  3. Variabel jumlah SMP
     Variabel tersebut menjelaskan Jumlah Sekolah Menengah Pertama yang ada di 34 provinsi pada tahun 2021.
  4. Variabel jumlah SMA
     Variabel tersebut menjelaskan Jumlah Sekolah Menengah Atas yang ada di 34 provinsi pada tahun 2021.
  5. Variabel jumlah SMK
     Variabel tersebut menjelaskan Jumlah Sekolah Menengah Kejuruan yang ada di 34 provinsi pada tahun 2021.
  6. Variabel jumlah Guru SD
     Variabel tersebut menjelaskan Jumlah Guru Sekolah Dasar yang ada di 34 provinsi pada tahun 2021.
  7. Variabel jumlah Guru SMP
     Variabel tersebut menjelaskan Jumlah Guru Sekolah Menengah Pertama yang ada di 34 provinsi pada tahun 2021.
  8. Variabel jumlah SMA
     Variabel tersebut menjelaskan Jumlah Guru Sekolah Menengah Atas yang ada di 34 provinsi pada tahun 2021.
  9. Variabel jumlah SMK
     Variabel tersebut menjelaskan Jumlah Guru Sekolah Menengah Kejuruan yang ada di 34 provinsi pada tahun 2021.

 ## 2. Perancangan visualisasi data
  Setelah melakukan pengolahan dan pemodelan data, proses selanjutnya membuat visualisasi data dengan menggunakan bantuan software Tableau Desktop. Langkah awal setelah software tersebut dibuka adalah pemilihan data source, kemudian membuat visualisasi sesuai dengan list dan kebutuhan.Visualisasi tersebut nantinya akan digunakan sebagai rancangan dashboard. 
  Berikut jenis visualisasi yang dirancang untuk membangun dashboard.
  1. *Peta Persebaran Fasilitas Pendidikan di Indonesia*  
    Visualisasi data yang pertama dirancang dengan jenis visualisasi yang digunakan adalah cloropleth map yang dimana perbedaan warna yang semakin gelap menunjukkan jumlah yang sangat banyak atau tinggi. Visualisasi tersebut bertujuan untuk menampilkan informasi mengenai persebaran jumlah fasilitas pendidikan di Indonesia.

  2. *Top 6 Provinsi dengan Jumlah Fasilitas Pendidikan Terbanyak*  
    Pada visualisasi ini menggunakan buble chart karena ingin menunjukkan provinsi mana saja yang memilik fasilitas pendidikan terbanyak di Indonesia
    
  3.	*Grafik Fasilitas Pendidikan di Indonesia*  
    Pada visualisasi ini menggunakan bar chart dimana yang disajikan hampir sama seperti pada peta persebaran fasilitas pendidikan di Indonesia.
  
 

## 3. Perancangan Dashboard
  Setelah melakukan visualisasi, hasil visualisasi tersebut dilanjutkan untuk perancangan dashboard system informasi. Perancangan dashboard terdiri dari 3 visualisasi ditambah dengan keterangan seperti color legend. Pada dashboard tersebut memiliki beberapa format seperti warna background hijau , font style title nya yaitu tableau mediaum dengan ukuran 14 dan font color nya yaitu hitam. Dan terdapat juga filter yang berguna untuk membuat dashboard tersebut menjadi lebih interaktir. Berikut filter yang tersedia.
  1.	Filter Provinsi 
    Filter tersebut digunakan pada visualisasi data yang pertama dan ketiga. Dimana filter tersebut berisi  nama 34 provinsi di Indonesia. Sehingga visualisasi data yang pertama dan ketiga dapat di filter berdasarkan nama provinsi di Indonesia.

  2.	Filter Fasilitas Pendidikan 
   Selanjutnya untuk filter fasilitas pendidikan, filter tersebut digunakan pada visualisasi data yang pertama  dan ketiga. Dengan pilihan yang disediakan chart yaitu 8 jenis fasilitas pendidikan atau 8 variabel yang sudah di jelaskan di atas. Sehingga chart tersebut dapat menampilkan informasi yang sesuai dengan filter yang dipilih.  
  
Filter-filter tersebut telah dilakukan penyesuaian agar 1 filter dapat berfungsi untuk beberapa chart dan beberapa filter dapat dikombinasikan untuk menampilkan informasi pada chart yang diinginkan

## 4. Klasterisasi provinsi berdasarkan Jumlah Fasilitas Pendidikan
 Pada proses ini menggunakan pemograman R dengan metode K-Means Clustering dimana tujuannya agar memudahkan dalam mengelompokka provinsi-provinsi berdasarkan jumlah fasilitas pendidikan agar nantinya diketahui mana saja provinsi yang termasuk kedalam kelompok rendah, sedang dan tinggi dalam jumlah fasilitas pendidikan.

