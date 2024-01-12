# Supermarket Customers Analysis
* Project ini merupakan tugas capstone module 2 dari Purwadhika sebagai penilaian siswa dalam pemahaman mengenai Data Analysis.Pada project ini, saya melakukan analisa pada data supermarket customers.
* File project berupa file .ipynb
* Dataset didownload dari google drive yang disediakan oleh mentor, namun dataset juga dapat di download dari link ini : [https://www.kaggle.com/datasets/rodsaldanha/arketing-campaign]
* Library yang digunakan yaitu:
  * Pandas
  * Numpy
  * Seaborn
  * Matplotlib
  * Random
  * Scipy
 
## Data Description
* Dataset ini memuat informasi pribadi dan data belanja dari customer sebuah supermarket.Dataset ini memiliki 2240 baris data dengan 29 kolom, yaitu:
  * ID: Unique id tiap customer
  * Year_Birth: Tahun kelahiran customer
  * Education: Tingkat pendidikan customer
  * Marital_Status: Status pernikahan customer
  * Income: Income customer per tahun
  * Kidhome: Jumlah anak kecil yang tinggal di rumah customer
  * Teenhome: Jumlah anak remaja yang tinggal di rumah customer
  * Dt_Customer: Tanggal pertama kali customer terdaftar di supermarket
  * Recency: Total hari sejak transaksi terakhir customer
  * Complain: Komplain customer, 1 jika customer pernah komplain dalam 2 tahun terakhir, dan 0 jika sebaliknya
  * MntWines: Jumlah uang yang dikeluarkan untuk membeli wine dalam 2 tahun terakhir
  * MntFruits: Jumlah uang yang dikeluarkan untuk membeli buah dalam 2 tahun terakhir
  * MntMeatProducts: Jumlah uang yang dikeluarkan untuk membeli daging dalam 2 tahun terakhir
  * MntFishProducts: Jumlah uang yang dikeluarkan untuk membeli ikan dalam 2 tahun terakhir
  * MntSweetProducts: Jumlah uang yang dikeluarkan untuk membeli permen dalam 2 tahun terakhir
  * MntGoldProds: Jumlah uang yang dikeluarkan untuk membeli emas dalam 2 tahun terakhir
  * NumDealsPurchases: Jumlah transaksi menggunakan diskon
  * AcceptedCmp1: 1 jika customer menerima tawaran pada kampanye ke-1, dan 0 jika sebaliknya
  * AcceptedCmp2: 1 jika customer menerima tawaran pada kampanye ke-2, dan 0 jika sebaliknya
  * AcceptedCmp3: 1 jika customer menerima tawaran pada kampanye ke-3, dan 0 jika sebaliknya
  * AcceptedCmp4: 1 jika customer menerima tawaran pada kampanye ke-4, dan 0 jika sebaliknya
  * AcceptedCmp5: 1 jika customer menerima tawaran pada kampanye ke-5, dan 0 jika sebaliknya
  * Response: 1 jika customer menerima tawaran pada kampanye terakhir, dan 0 jika sebaliknya(kolom target)
  * NumWebPurchases: Jumlah pembelian melalui website perusahaan
  * NumCatalogPurchases: Jumlah pembelian melalui katalog
  * NumStorePurchases: Jumlah pembelian langsung dari toko
  * NumWebVisitsMonth: Jumlah kunjungan ke website perusahaan

## Teknik Analisa
Pada project ini saya menggunakan beberapa teknik analisis, yaitu:
* Descriptive Statistics
  * Data Visualization - Menampilkan statistika deskriptif melalui grafik seperti barchart,histogram,boxplot, dan piechart.
  * Describe(Pandas Method) - Menampilkan statistika deskriptif data dalam bentuk tabel.
* Inferential Statistics
  * Normaltest
  * Mannwhitneyu
  * Chi2_contingency

## Analisa
Beberapa insight yang saya dapatkan diantaranya adalah:
* Customer dengan tingkat pendidikan lebih tinggi cenderung menerima tawaran kampanye.
* Terdapat perbedaan income yang signifikan antara customer yang menerima dan menolak tawaran kampanye.
* Customer dengan jumlah anak kecil maupun remaja yang sedikit, lebih banyak menerima tawaran kampanye.

## Kesimpulan dan Saran
* Dari analisa yang dilakukan kita bisa melihat customer supermarket mayoritas berasal dari kelompok usia yang sudak cukup berumur, namun proporsi customer yang menerima kampanye tergolong masih sangat kecil $\pm$ 20%.Rekomendasi yang dapat dilakukan:
    * Penawaran promo kampanye bisa lebih banyak dilakukan melalui koran, tv, radio, atau flyer dengan tulisan yang mudah dibaca dan jelas agar dapat lebih mudah menjangkau customer yang berusia lebih tua karena mayoritas customer sudah cukup berumur. 
    * Kampanye juga bisa lebih difokuskan pada penekanan dari sisi kesehatan yang tentunya menarik bagi seluruh kalangan usia khususnya usia yang lebih tua. Halaman website supermarket juga bisa dibuat lebih user friendly dan juga disediakan tech support untuk mempermudah mayoritas customer dalam mengakses website.
    * Aktivitas kampanye bisa dilakukan pada pagi hari karena kalangan usia yang lebih tua cenderung berbelanja dan beraktivitas pada pagi hari
* 98% customer berasal dari kalangan sarjana, kita bisa meningkatkan acceptance ratio kampanye dengan menunjukkan kualitas, value yang ditawarkan produk.Karena mayoritas customer adalah kaum terpelajar, apabila kita menekankan aspek kesehatan saat kampanye kita bisa sertakan research yang dapat mendukung klaim kita untuk meningkatkan kepercayaan customer.
* Customer dengan jumlah anak yang lebih banyak cenderung menolak kampanye yang diberikan, kita bisa menawarkan paket keluarga.
* Banyak kampanye yang tidak diterima berasal dari customer yang memang sudah tidak aktif berbelanja di supermarket tersebut,hal ini mungkin saja karena customer telah berbelanja di supermarket lain dengan penawaran yang lebih menarik. Kita bisa melakukan research lebih lanjut untuk pesaing-pesaing dan mengirimkan penawaran khusus bagi customer yang sudah tidak aktif berbelanja.

