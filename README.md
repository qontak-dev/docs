# Reports

![Image of dashboard index](https://raw.githubusercontent.com/qontak-dev/docs/master/images/dashboards_index.png)

Grafik reports pada Qontak ditampilkan pada laman https://www.qontak.com/dashboards. Pada bagian atas, terdapat filter bar untuk memilih parameter-parameter apa saja yang akan diterapkan pada grafik yang sedang ditampilkan.

![Image of filter bar](https://raw.githubusercontent.com/qontak-dev/docs/master/images/filter_bar.gif)

Terdapat 4 pilihan parameter pada filter bar, yaitu Pipeline, Team, User, dan Time. Setelah memilih filter, klik tombol Submit untuk menerapkan filter pada grafik. Kemunculan suatu item pada grafik mengacu pada waktu dibuatnya item pada grafik tersebut, kecuali disebutkan acuan lain. Contoh : Deal 1 dibuat pada tanggal 14 Nov 2018, maka Deal 1 akan ditampilkan pada grafik untuk periode tanggal 14 Nov 2018.

## Sales Performance
Grafik Sales Performance menampilkan data Deals yang dikelompokkan berdasarkan periode yang terpilih. Grafik yang ditampilkan berbentuk line. Periode grafik ini tidak mengikuti filter waktu pada filter bar, namun memiliki periode khusus yaitu Daily (harian), Weekly (mingguan), dan Monthly (Bulanan).

Jika salah satu kelompok dari line di-hover, muncul informasi total besarnya Deal dalam satu periode. Total besar Deal dikonversikan ke mata uang default yang dipilih user.

![Image of filter bar](https://raw.githubusercontent.com/qontak-dev/docs/master/images/graph_sales_performance.gif)

## Sources
Grafik Sources menampilkan data Contacts, Companies, dan Deals yang dikelompokkan berdasarkan Source/Sumber. Grafik yang ditampilkan berbentuk pie. Jika ada Contact, Company, atau Deal yang tidak memiliki Source, maka akan dikelompokkan sebagai "Undefined Source". 

Grafik Source untuk data Deals memiliki filter tambahan yaitu Stage.

Jika salah satu kelompok dari pie di-hover, muncul informasi jumlah item dan persentase-nya terhadap keseluruhan grafik.

![Image of sources graph](https://raw.githubusercontent.com/qontak-dev/docs/master/images/graph_sources.gif)

## Deals by Stage
Grafik Deals by Stage menampilkan data Deals yang dikelompokkan berdasarkan Stage. Grafik yang ditampilkan berbentuk corong. 

Jika salah satu kelompok dari grafik di-hover, muncul informasi cacah Deal, total besar Deal dan persentase-nya terhadap keseluruhan grafik. Persentase dihitung berdasarkan cacah Deal, bukan total besar Deal.

![Image of sources graph](https://raw.githubusercontent.com/qontak-dev/docs/master/images/graph_deals_by_stage.gif)

## Deals Won
Grafik Deals Won menampilkan data Deals yang dikelompokkan berdasarkan User dan periodenya. Grafik yang ditampilkan berbentuk line. Data Deals yang masuk ke grafik ini hanya yang berada pada stage Won. Periode grafik ini tidak mengikuti filter waktu pada filter bar, namun memiliki periode sendiri yaitu Daily (harian), Weekly (mingguan), dan Monthly (Bulanan).

Kemunculan item pada grafik ini mengacu pada waktu di mana Deal tersebut dipindah ke stage Won. Contoh: Deal 1 dibuat pada tanggal 9 November 2018 lalu diubah ke stage Won pada tanggal 14 Nov 2018, maka Deal tersebut akan ditampilkan pada grafik untuk periode tanggal 14 Nov 2018.

Jika salah satu titik dari grafik di-hover, muncul informasi nama user, periode, dan cacah Deal yang berada di stage Won. User pada grafik dapat ditampilkan dan disembunyikan dengan klik nama user tersebut di bagian bawah grafik.

![Image of sources graph](https://raw.githubusercontent.com/qontak-dev/docs/master/images/graph_deals_won.gif)

## Summary Report
Summary Report menampilkan perubahan-perubahan yang dilakukan oleh User atau Team yang terpilih. Perubahan-perubahan yang dicatat adalah Create (pembuatan), Update (pembaruan), dan Delete (penghapusan). Item-item yang akan tercatat perubahannya adalah User, Deal, Task, Company, Contact, Note, Meeting, Ticket, Pipeline, Target, Email, Properties, Product, dan Stage.

Item-item pada Summary Report diurutkan berdasarkan waktu pencatatan perubahan. Item-item yang tampil dibatasi 100 item terakhir. Jika salah satu baris memiliki informasi yang terlalu panjang sehingga terpotong, maka baris tersebut dapat di-hover untuk memunculkan informasi lengkapnya.

![Image of sources graph](https://raw.githubusercontent.com/qontak-dev/docs/master/images/graph_summary_report.gif)

## Deals Closed by User (Leaderboard)
Deals Closed by User menampilkan User dengan peringkat 3 teratas dan 3 terbawah dalam perolehan total besaran Deal dalam periode yang terpilih. Deal yang akan terhitung besarnya adalah yang telah ada dalam stage Won.

Besaran Deal yang terhitung mengacu pada waktu di mana Deal tersebut dipindah ke stage Won. Contoh: Deal 1 dibuat pada tanggal 9 November 2018 lalu diubah ke stage Won pada tanggal 14 Nov 2018, maka Deal tersebut akan masuk ke total besaran deal untuk periode tanggal 14 Nov 2018.

Mata uang yang ditampilkan adalah mata uang default yang dipilih User sehingga bila ada Deal dengan mata uang selain mata uang default, besaran deal akan dikonversi.

![Image of sources graph](https://raw.githubusercontent.com/qontak-dev/docs/master/images/graph_leaderboard.gif)

##### Top 20 Customers
##### Deals Closed by User (Leaderboard)
##### Targets by Month by Value
##### GPS Checkin
##### Tasks by Status
##### Revenues by Time
##### User Traction by Time
##### Funding Status by Time
##### Yearly Sales Comparison
##### Top Companies
##### Top Products
##### Targets by Month
##### Achievement by User by Time
##### Activities by User by Time
##### Deals by Stage by Time
##### Tasks
##### Customer Geolocation Map
##### Sales Representatives KPIs
##### Lead Converter
##### Project Manager
##### Drafter
##### Estimators
##### Designers
##### Mortgage Targets by Month
##### Deals by Stage by User
##### Deals Won by User
##### Win Rate
##### Sales Activity by User
##### User Targets
##### Product Sales Trends
##### Customer Sales Trends
##### Targets by Month by Count
##### New Contacts and Companies Created by Source
##### No. of Vehicles Targets
##### Customer Service
