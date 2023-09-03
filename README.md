# Sales Performance Analysis : Project Overview
- Berperan sebagai Business Intelligence Analyst di sebuah perusahaan untuk menganalisis aspek yang berkaitan dengan performa penjualan perusahaan tersebut.
- Terdapat 4 table berekstensi <i>csv</i> yaitu : Customers, Products, ProductCategory dan Orders [here](https://github.com/bumianugrahhh/Sales_Performance_Analysis/tree/main/Data%20Source)
- Membuat master table [orders_detail](https://github.com/bumianugrahhh/Sales_Performance_Analysis/blob/main/Data%20Source/orders_detail.csv) dari hasil gabungan dari ke-4 table tersebut dengan melakukan [query](https://github.com/bumianugrahhh/Sales_Performance_Analysis/blob/main/Query%20orders_detail.docx)
- Membuat dashboard
- Menganalisa dan buat rekomendasi bisnis

## Tujuan 
Membuat Dashboard dari data mentah untuk meningkatkan <i>Sales Perfomance</i> perusahaan.

## Tools
- Google Bigquery
- Looker Studio

# Dashboard
![alt text](https://github.com/bumianugrahhh/Sales_Performance_Analysis/blob/main/Fig/Dashboard.png)

# # Insight/Analisis
![alt text](https://github.com/bumianugrahhh/Sales_Performance_Analysis/blob/main/Fig/Analysis%20Entire%20Total%20Sales%20%26%20Quantity%20Sold.png)
Terlihat bahwa trend total sales dan Quantity Sold dari Tahun 2020 – 2021 mengalami penurunan. Hal itu disebabkan karena jumlah order di Tahun 2021 juga mengalami penurunan dibandingkan Tahun 2020.

![alt text](https://github.com/bumianugrahhh/Sales_Performance_Analysis/blob/main/Fig/Analysis%20Total%20Sales%20%26%20Qty%20Sold%20by%20Category%20Product.png)
Secara keselurahan dari January 2020 – Desember 2021, Robots merupakan Category Product dengan Total Sales tertinggi sedangkan Blueprint yang terendah.
Berdasarkan Quantity Sold, eBooks diurutan pertama, diikuti Training Videos, Blueprints, Drone Kits dan Drones. Disini justru Robots dan Robot Kits category product yang paling sedikit terjual tetapi memiliki total sales tertinggi. Hal ini terjadi karena Robots memiliki Price yang tinggi.

![alt text](https://github.com/bumianugrahhh/Sales_Performance_Analysis/blob/main/Fig/Analysis%20Total%20Sales%20%26%20Qty%20Sold%20by%20City.png)
Washington kota dengan Total Sales dan Quantity Sold terbanyak dengan $55,38k Total sales dan 308 Quantity Sold, diikuti Houston dengan $33,76k Total Sales dan 249 Quantity Sold. 
Hal lain yang menarik untuk diperhatikan disini adalah Sacramento dan Albany memiliki jumlah Quantity Order yang cenderung lebih sedikit tetapi memiliki Total Sales yang tinggi. Hal ini mungkin terjadi karena Category Product yang dipesan itu mayoritas Robots/Drones, yang mana memiliki Price yang tinggi.

# Business Recommendation
- Mengadakan promo, mempromosikan product dalam bentuk paket, misalnya semua product dalam category Robots dibundling.  Bisa juga dilakukan penawaran produk pada orang yang akan membeli barang secara satuan, sehingga dapat dikatakan lebih efektif daripada menawarkannya pada konsumen yang sama sekali belum tertarik.
- Untuk kota dengan angka penjualan terbanyak, kita dapat menawarkan promo / paket spesial dan terus meningkatkan kualitas layanan sehingga dapat menjaga tingkat kepuasan dan loyalitas customer, sedangkan untuk kota – kota dengan penjualan yang terbilang rendah kita bisa beriklan serta melakukan trial and error agar pemasaran dapat diekplorasi dan diterapkan dengan cermat, misalnya memberikan potongan harga istimewa atau promo lainnya.
- Memberikan garansi produk, ini dapat mengakibatkan pelanggan merasa lebih aman saat membeli produk kita. Dengan adanya garansi akan menjadi nilai lebih dari produk dan membangun kepercayaan pelanggan.
- Menyediakan berbagai macam metode pembayaran, misalnya dengan cash on delivery atau berkolaborasi dengan dompet digital (eWallet) / mobile banking. Sehingga bisa lebih menyesuaikan dengan berbagai kebutuhan dan kebiasaan konsumen.








