# Exploratory-Data-Analysis-EDA---Customer-Personality-Analysis
by : Jeffrey Junior T

## Latar Belakang

Electronic commerce (e-commerce) mengacu pada perusahaan dan individu yang melakukan transaksi jual beli barang atau jasa melalui Internet.

Source :
https://www.investopedia.com/terms/e/ecommerce.asp

Segmentasi adalah membagi pelanggan ke dalam berbagai cara, seperti berdasarkan demografi, perilaku, gaya hidup, dan lain-lain.
Manfaat segmentasi pelanggan dalam pemasaran adalah kita dapat menargetkan orang yang tepat dengan pesan yang tepat tentang produk Anda. Hal ini akan meningkatkan keberhasilan kampanye pemasaran.

Source :
https://www.emerald.com/insight/content/doi/10.1108/SJME-06-2019-0036/full/pdf

## Define Problem

Menambah customer dengan melakukan segmentasi berdasarkan perilaku

## Business Goals

Melakukan segmentasi customer agar pemasaran tepat sasaran

## Data Understanding

### People

- ID: Identitas unik Customer
- Year_Birth: Tahun Lahir Customer
- Education: Tingkat pendidikan Customer
- Marital_Status: Status pernikahan customer
- Income: Pendapatan rumah tangga tahunan customer
- Kidhome: Jumlah anak dalam rumah tangga customer
- Teenhome: Jumlah remaja dalam rumah tangga customer
- Dt_Customer: Tanggal pelanggan berlangganan dengan perusahaan
- Recency: Jumlah hari sejak pembelian terakhir customer
- Complain: 1 jika customer mengeluh dalam 2 tahun terakhir, 0 sebaliknya

### Products

- MntWines: Jumlah uang yang dihabiskan untuk anggur dalam 2 tahun terakhir
- MntFruits: Jumlah uang yang dihabiskan untuk buah dalam 2 tahun terakhir
- MntMeatProducts: Jumlah uang yang dihabiskan untuk daging dalam 2 tahun terakhir
- MntFishProducts: Jumlah uang yang dihabiskan untuk ikan dalam 2 tahun terakhir
- MntSweetProducts: Jumlah uang yang dihabiskan untuk permen dalam 2 tahun terakhir
- MntGoldProds: Jumlah uang yang dihabiskan untuk emas dalam 2 tahun terakhir

### Promotion

- NumDealsPurchases: Number of purchases made with a discount
- AcceptedCmp1: 1 jika customer menerima penawaran pada promosi ke-1, 0 sebaliknya
- AcceptedCmp2: 1 jika customer menerima penawaran pada promosi ke-2, 0 sebaliknya
- AcceptedCmp3: 1 jika customer menerima penawaran pada promosi ke-3, 0 sebaliknya
- AcceptedCmp4: 1 jika customer menerima penawaran pada promosi ke-4, 0 sebaliknya
- AcceptedCmp5: 1 jika customer menerima penawaran pada promosi ke-5, 0 sebaliknya
- Response: 1 jika pelanggan menerima penawaran pada promosi terakhir, 0 sebaliknya

### Place

- NumWebPurchases: Jumlah pembelian yang dilakukan melalui situs web perusahaan
- NumCatalogPurchases:Jumlah pembelian yang dilakukan melalui katalog
- NumStorePurchases: Jumlah pembelian yang dilakukan langsung di toko
- NumWebVisitsMonth: Jumlah kunjungan ke situs web perusahaan dalam sebulan terakhir

## Business Question

### 1. Bagaimana pengaruh kelompok umur terhadap customer dalam berbelanja melalui web? 

![](https://github.com/JeffreyJuinior/Exploratory-Data-Analysis-EDA---Customer-Personality-Analysis/blob/main/Screenshot/1.%20Web%20Comparison.PNG)

Insight:
Customer yang belanja secara online lebih loyal dibandingkan yang langsung belanja di Toko.

Source :
https://www.candyindustry.com/articles/90056-online-grocery-shoppers-more-loyal-to-brands-stores-than-in-store-shoppers

Dapat dilihat pada pie chart visit web total bahwa Customer middle age merupakan pengunjung web terbanyak yaitu sebanyak 58.13% dari total customer.
Dari tempat pembelian item berdasarkan kategori umur juga, Middle age merupakan pembeli melalui web terbanyak yaitu sebesar 33.85%. Sehingga customer Middle age merupakan customer yang paling potensial dalam pembelian item melalui web.

Recomendation :

Tim marketing dapat memberikan promo dalam pembelian item terhadap pengguna baru aplikasi, campaign tersebut dapat disebarkan melalui ads sosial media dengan target umur middle age yaitu 31-50 tahun.

Salah satunya adalah melalui ads instagram, tim marketing dapat mengadakan giveaway untuk mendapatkan lebih banyak customer. Dikutip dari jmango360.com akun instagram yang melakukan giveaway cenderung mengalami pertumbuhan follower 70% lebih cepat dalam 3 bulan.

Source :
https://jmango360.com/blog/11-app-marketing-ideas-ecommerce-stores/

### 2. Item wines cocok untuk customer yang seperti apa?

![](https://github.com/JeffreyJuinior/Exploratory-Data-Analysis-EDA---Customer-Personality-Analysis/blob/main/Screenshot/2.%20Spent%20on%20Wine.PNG)

Insight :

Dapat dilihat dari kelompok umur bahwa senior age memiliki potensi karena 62% memiliki higher spent pada pembelian wines.

Recomendation :

Faktanya wine memiliki khasiat untuk senior age, dikutip dari thesummitretirement.com beberapa khasiat wine yaitu adalah menurunkan risiko penyakit alzheimer, mengurangi peluang terkena kanker,dan mengurangi peradangan dalam tubuh dengan kadar secukupnya yaitu 2 gelas sehari.

Source :
https://www.thesummitretirement.com/senior-retirement-blog/what-are-the-benefits-of-drinking-red-wine-for-seniors/

Sehingga tim marketing dapat membuat campaign berisi khasiat dari wines untuk senior age dan dapat dipasarkan di panti jompo, seperti sage home care yang membolehkan penghuni untuk meminum wine dengan kadar yang cukup dan merupakan jenis wine yang aman dikonsumsi untuk usia senja seperti Pinot Noir, Rose, Merlot, atau Malbec yang dapat dibeli di toko ini.

Source :
https://www.sagehomecare.com/a-senior-adults-cheatsheet-for-healthy-wines

### 3. Item permen cocok untuk customer yang seperti apa? 

![](https://github.com/JeffreyJuinior/Exploratory-Data-Analysis-EDA---Customer-Personality-Analysis/blob/main/Screenshot/3.%20Spent%20on%20Sweet.PNG)

Insight :

Dapat dilihat dari kelompok umur bahwa adult dan senior age memiliki potensi karena  memiliki higher spent yang besar pada pembelian permen.

Dikutip dari comfortkeepers.com, banyak nya orang lanjut usia dalam mengonsumsi permen karena semakin bertambahnya usia maka indra pengecap akan semakin berkurang, hal ini yang memicu customer Senior memakan makanan yang terasa lebih manis atau asin.

Source : 
https://www.comfortkeepers.com/articles/info-center/seniors-and-nutrition/controlling-sweet-and-salty-cravings-in-seniors

Recomendation :

Menurut penelitan oleh Elżbieta Bojanowska di University in Warsaw, aktivitas customer Senior banyak dihabiskan dalam kegiatan keagamaan, bersama keluarga, dan aktivitas sosial/komunitas.

Source :
http://www.repozytorium.uni.wroc.pl/Content/58907/PDF/16_Elzbieta_Bojanowska.pdf

Sehingga tim marketing dapat memasarkan produk permen yang rendah kalori yang tersedia di toko ini pada kegiatan sosial yang banyak melibatkan orang dengan usia senja (senior age), salah satu contoh nya adalah kegiatan sosial Alzheimer's Society - Memory Walk di UK yang bertujuan untuk menggalang dana untuk dementia research.

Source :
https://tfn.scot/lists/the-UKs-25-biggest-fundraising-events

Tim marketing juga dapat memasarkan produk melalui ads social media dengan kategori umur adult, hal itu dapat dilakukan karena menurut penelitian yang dilakukan oleh Kevin Norton di University of South Australia, orang dewasa(Adult) menghabiskan 39% kegiatan sehari harinya dengan duduk dan menonton.

Source :
https://www.researchgate.net/figure/The-typical-adult-pattern-of-daily-activities-percentage-of-a-24-h-day-when-categorised_fig1_40683002

### 4. Item daging cocok untuk customer yang seperti apa? 

![](https://github.com/JeffreyJuinior/Exploratory-Data-Analysis-EDA---Customer-Personality-Analysis/blob/main/Screenshot/4.%20Spent%20on%20Meat.PNG)

Insight :

Dapat dilihat dari kelompok umur bahwa senior age memiliki potensi karena  memiliki higher spent yang besar pada pembelian daging

Recomendation:

Dikutip dari foodmanufacture.co.uk di toko-toko negara eropa sudah banyak menjual daging halal, sehingga tim marketing dapat memasarkan produk daging halal seperti daging sapi, kambing, atau domba di daerah yang banyak penduduk muslim jika toko terletak di negara barat atau eropa. 
Hal ini dikarenakan menurut penelitian yang dilakukan oleh Luis Guerrero di IRTA Monells, produksi daging sapi di negara maju jauh lebih rendah dibandingkan negara berkembang yang menyebabkan tingginya demand warga muslim terhadap daging halal. sehingga tim marketing dapat memberikan brosur terkait penjualan daging halal pada Customer terutama yang termasuk kategori umur senior age.

Source :
https://www.foodmanufacture.co.uk/Article/2016/06/17/Halal-range-launches-with-16-lines-on-Amazon-Fresh#:~:text=Meanwhile%2C%20the%20halal%20brand%2C%20whose,range%20lamb%20and%20beef%20cuts.

Font-i-Furnols, M. and Guerrero, L., 2014. Consumer preference, behavior and perception about meat and meat products: An overview. Meat science, 98(3), pp.361-371.

### 5. Item emas cocok untuk customer yang seperti apa? 


