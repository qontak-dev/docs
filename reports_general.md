---
title: General
parent: Reports
nav_order: 1
---

# General

## Sales Performance
Grafik Sales Performance menampilkan data Deals yang dikelompokkan berdasarkan periode yang terpilih. Grafik yang ditampilkan berbentuk line. Periode grafik ini tidak mengikuti filter waktu pada filter bar, namun memiliki periode khusus yaitu Daily (harian), Weekly (mingguan), dan Monthly (Bulanan).

Jika salah satu kelompok dari line di-hover, muncul informasi total besarnya Deal dalam satu periode. Total besar Deal dikonversikan ke mata uang default yang dipilih user.

![Image of sales performance graph](https://raw.githubusercontent.com/qontak-dev/docs/master/images/graph_sales_performance.gif)

## YTD Yearly Sales Comparison

Grafik YTD Yearly Sales Comparison menampilkan total besaran Deals yang dikelompokkan berdasarkan tahun. Grafik yang ditampilkan berbentuk bar. Periode grafik ini tidak mengikuti filter waktu pada filter bar, namun memiliki periode khusus yaitu dari awal tahun hingga bulan saat grafik ditampilkan. Contoh apabila grafik ditampilkan tanggal 23 November 2018, maka periode nya adalah dari 1 Januari hingga 23 November tiap tahunnya.

Jika salah satu bar pada grafik di-hover, muncul informasi periode dan total besaran Deal pada periode tersebut. Total besar Deal dikonversikan ke mata uang default yang dipilih user.

![Image of yearly sales comparison graph](https://raw.githubusercontent.com/qontak-dev/docs/master/images/graph_yearly_sales_comparison.gif)

## Deals Won
Grafik Deals Won menampilkan data Deals yang dikelompokkan berdasarkan User pembuat Deal dan periodenya. Grafik yang ditampilkan berbentuk line. Data Deals yang masuk ke grafik ini hanya yang berada pada stage Won. Periode grafik ini tidak mengikuti filter waktu pada filter bar, namun memiliki periode sendiri yaitu Daily (harian), Weekly (mingguan), dan Monthly (Bulanan).

Kemunculan item pada grafik ini mengacu pada waktu di mana Deal tersebut dipindah ke stage Won. Contoh: Deal 1 dibuat pada tanggal 9 November 2018 lalu diubah ke stage Won pada tanggal 14 Nov 2018, maka Deal tersebut akan ditampilkan pada grafik untuk periode tanggal 14 Nov 2018.

Jika salah satu titik dari grafik di-hover, muncul informasi nama user, periode, dan cacah Deal yang berada di stage Won. User pada grafik dapat ditampilkan dan disembunyikan dengan klik nama user tersebut di bagian bawah grafik.

![Image of deals won graph](https://raw.githubusercontent.com/qontak-dev/docs/master/images/graph_deals_won.gif)

## Summary Report
Summary Report menampilkan perubahan-perubahan yang dilakukan oleh User atau Team yang terpilih. Perubahan-perubahan yang dicatat adalah Create (pembuatan), Update (pembaruan), dan Delete (penghapusan). Item-item yang akan tercatat perubahannya adalah User, Deal, Task, Company, Contact, Note, Meeting, Ticket, Pipeline, Target, Email, Properties, Product, dan Stage.

Item-item pada Summary Report diurutkan berdasarkan waktu pencatatan perubahan. Item-item yang tampil dibatasi 100 item terakhir. Jika salah satu baris memiliki informasi yang terlalu panjang sehingga terpotong, maka baris tersebut dapat di-hover untuk memunculkan informasi lengkapnya.

![Image of summary report graph](https://raw.githubusercontent.com/qontak-dev/docs/master/images/graph_summary_report.gif)

## Deals by Stage
Grafik Deals by Stage menampilkan data Deals yang dikelompokkan berdasarkan Stage. Grafik yang ditampilkan berbentuk corong. 

Jika salah satu kelompok dari grafik di-hover, muncul informasi cacah Deal, total besar Deal dan persentase-nya terhadap keseluruhan grafik. Persentase dihitung berdasarkan cacah Deal, bukan total besar Deal.

![Image of deals by stage graph](https://raw.githubusercontent.com/qontak-dev/docs/master/images/graph_deals_by_stage.gif)

## Sources

Grafik Sources menampilkan data Contacts, Companies, dan Deals yang dikelompokkan berdasarkan Source/Sumber. Grafik yang ditampilkan berbentuk pie. Jika ada Contact, Company, atau Deal yang tidak memiliki Source, maka akan dikelompokkan sebagai "Undefined Source". 

Grafik Source untuk data Deals memiliki filter tambahan yaitu Stage.

Jika salah satu kelompok dari pie di-hover, muncul informasi cacah item dan persentase-nya terhadap keseluruhan grafik.

![Image of sources graph](https://raw.githubusercontent.com/qontak-dev/docs/master/images/graph_sources.gif)

## Lost Reasons

Grafik Lost Reasons menampilkan data Deals yang dikelompokkan berdasarkan Lost Reason. Grafik yang ditampilkan berbentuk pie. Jika ada Deal yang tidak memiliki Lost Reason, maka akan dikelompokkan sebagai "Undefined Lost Reason". Deal yang masuk ke grafik ini adalah Deal yang berada di stage Lost.

Jika salah satu kelompok dari pie di-hover, muncul informasi cacah item dan persentase-nya terhadap keseluruhan grafik.

![Image of lost reasons graph](https://raw.githubusercontent.com/qontak-dev/docs/master/images/graph_lost_reason.gif)
