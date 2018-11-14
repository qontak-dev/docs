# Reports

![Image of dashboard index](https://raw.githubusercontent.com/qontak-dev/docs/master/images/dashboards_index.png)

Grafik reports pada Qontak ditampilkan pada laman https://www.qontak.com/dashboards. Pada bagian atas, terdapat filter bar untuk memilih parameter-parameter apa saja yang akan diterapkan pada grafik yang sedang ditampilkan.

![Image of filter bar](https://raw.githubusercontent.com/qontak-dev/docs/master/images/filter_bar.gif)

Terdapat 4 pilihan parameter pada filter bar, yaitu Pipeline, Team, User, dan Time. Setelah memilih filter, klik tombol Submit untuk menerapkan filter pada grafik.
Kemunculan suatu item pada grafik mengacu pada waktu dibuatnya item pada grafik tersebut, kecuali disebutkan acuan lain. Contoh : Deal 1 dibuat pada tanggal 14 Nov 2018, maka Deal 1 akan ditampilkan pada grafik untuk periode tanggal 14 Nov 2018.

## Sales Performance
Grafik Sales Performance menampilkan data Deals yang dikelompokkan berdasarkan periode yang terpilih. Grafik yang ditampilkan berbentuk line. Periode grafik ini tidak mengikuti filter waktu pada filter bar, namun memiliki periode khusus yaitu Daily (harian), Weekly (mingguan), dan Monthly (Bulanan).

Jika salah satu kelompok dari line di-hover, muncul informasi total besarnya Deal dalam satu periode. Total besar Deal dikonversikan ke mata uang default yang dipilih user.

![Image of filter bar](https://raw.githubusercontent.com/qontak-dev/docs/master/images/graph_sales_performance.gif)

## Deals by Stage
Grafik Deals by Stage menampilkan data Deals yang dikelompokkan berdasarkan Stage. Grafik yang ditampilkan berbentuk corong. 

Jika salah satu kelompok dari grafik di-hover, muncul informasi cacah Deal, total besar Deal dan persentase-nya terhadap keseluruhan grafik. Persentase dihitung berdasarkan cacah Deal, bukan total besar Deal.

![Image of sources graph](https://raw.githubusercontent.com/qontak-dev/docs/master/images/graph_deals_by_stage.gif)

## Deals Won
Grafik Deals Won menampilkan data Deals yang dikelompokkan berdasarkan User pembuat Deal dan periodenya. Grafik yang ditampilkan berbentuk line. Data Deals yang masuk ke grafik ini hanya yang berada pada stage Won. Periode grafik ini tidak mengikuti filter waktu pada filter bar, namun memiliki periode sendiri yaitu Daily (harian), Weekly (mingguan), dan Monthly (Bulanan).

Kemunculan item pada grafik ini mengacu pada waktu di mana Deal tersebut dipindah ke stage Won. Contoh: Deal 1 dibuat pada tanggal 9 November 2018 lalu diubah ke stage Won pada tanggal 14 Nov 2018, maka Deal tersebut akan ditampilkan pada grafik untuk periode tanggal 14 Nov 2018.

Jika salah satu titik dari grafik di-hover, muncul informasi nama user, periode, dan cacah Deal yang berada di stage Won. User pada grafik dapat ditampilkan dan disembunyikan dengan klik nama user tersebut di bagian bawah grafik.

![Image of sources graph](https://raw.githubusercontent.com/qontak-dev/docs/master/images/graph_deals_won.gif)

## Summary Report
Summary Report menampilkan perubahan-perubahan yang dilakukan oleh User atau Team yang terpilih. Perubahan-perubahan yang dicatat adalah Create (pembuatan), Update (pembaruan), dan Delete (penghapusan). Item-item yang akan tercatat perubahannya adalah User, Deal, Task, Company, Contact, Note, Meeting, Ticket, Pipeline, Target, Email, Properties, Product, dan Stage.

Item-item pada Summary Report diurutkan berdasarkan waktu pencatatan perubahan. Item-item yang tampil dibatasi 100 item terakhir. Jika salah satu baris memiliki informasi yang terlalu panjang sehingga terpotong, maka baris tersebut dapat di-hover untuk memunculkan informasi lengkapnya.

![Image of sources graph](https://raw.githubusercontent.com/qontak-dev/docs/master/images/graph_summary_report.gif)

## Deals Closed by User (Leaderboard)
Grafik Deals Closed by User menampilkan User dengan peringkat 3 teratas dan 3 terbawah dalam perolehan total besaran Deal dalam periode yang terpilih. Deal yang akan terhitung besarnya adalah yang telah ada dalam stage Won.

Besaran Deal yang terhitung mengacu pada waktu di mana Deal tersebut dipindah ke stage Won. Contoh: Deal 1 dibuat pada tanggal 9 November 2018 lalu diubah ke stage Won pada tanggal 14 Nov 2018, maka Deal tersebut akan masuk ke total besaran deal untuk periode tanggal 14 Nov 2018.

Mata uang yang ditampilkan adalah mata uang default yang dipilih User sehingga bila ada Deal dengan mata uang selain mata uang default, besaran deal akan dikonversi sebelum dijumlahkan.

![Image of sources graph](https://raw.githubusercontent.com/qontak-dev/docs/master/images/graph_leaderboard.gif)

## Targets by Month by Value
Grafik Targets by Month by Value menampilkan grafik yang berisi perbandingan antara jumlah besaran Deal yang sudah dalam stage Won dengan target besaran Deal pada bulan yang terpilih dan dikelompokkan berdasarkan User pembuat Deal. Periode grafik ini tidak mengikuti filter waktu pada filter bar, namun memiliki periode khusus yaitu bulan-bulan pada tahun ini.

Grafik yang ditampilkan berbentuk bar. Jika salah satu bar di-hover, akan muncul informasi persentase bar tersebut dan besaran Deal yang terasosiasi dengan bar tersebut.

Besaran Deal yang terhitung mengacu pada waktu di mana Deal tersebut dipindah ke stage Won. Contoh: Deal 1 dibuat pada tanggal 9 September 2018 lalu diubah ke stage Won pada tanggal 14 Nov 2018, maka Deal tersebut akan masuk ke total besaran deal untuk periode tanggal Nov 2018.

Mata uang yang ditampilkan adalah mata uang default yang dipilih User sehingga bila ada Deal dengan mata uang selain mata uang default, besaran deal akan dikonversi.

![Image of sources graph](https://raw.githubusercontent.com/qontak-dev/docs/master/images/graph_target_by_month_by_value.gif)

## GPS Check In

GPS Check In menampilkan peta Google Maps yang menunjukkan lokasi Check In dari User yang terpilih dalam periode waktu tertentu. Lokasi Check In dapat di-klik untuk menampilkan nama User, alamat lokasi check in, dan waktu check in. Berbeda dari grafik lainnya, lokasi check in yang ditampilkan adalah untuk semua pipeline, bukan pipeline yang terpilih di filter bar.

![Image of sources graph](https://raw.githubusercontent.com/qontak-dev/docs/master/images/graph_gps_checkin.gif)

## Sources
Grafik Sources menampilkan data Contacts, Companies, dan Deals yang dikelompokkan berdasarkan Source/Sumber. Grafik yang ditampilkan berbentuk pie. Jika ada Contact, Company, atau Deal yang tidak memiliki Source, maka akan dikelompokkan sebagai "Undefined Source". 

Grafik Source untuk data Deals memiliki filter tambahan yaitu Stage.

Jika salah satu kelompok dari pie di-hover, muncul informasi cacah item dan persentase-nya terhadap keseluruhan grafik.

![Image of sources graph](https://raw.githubusercontent.com/qontak-dev/docs/master/images/graph_sources.gif)

## Lost Reasons

Grafik Lost Reasons menampilkan data Deals yang dikelompokkan berdasarkan Lost Reason. Grafik yang ditampilkan berbentuk pie. Jika ada Deal yang tidak memiliki Lost Reason, maka akan dikelompokkan sebagai "Undefined Lost Reason". Deal yang masuk ke grafik ini adalah Deal yang berada di stage Lost.

Jika salah satu kelompok dari pie di-hover, muncul informasi cacah item dan persentase-nya terhadap keseluruhan grafik.

![Image of sources graph](https://raw.githubusercontent.com/qontak-dev/docs/master/images/graph_lost_reason.gif)


## Tasks by Status

Grafik Tasks by Status menampilkan data Tasks yang dikelompokkan berdasarkan User dan Status dari Task. Grafik yang ditampilkan berbentuk bar. Grafik ini memiliki filter tambahan yaitu Categories.

Jika salah satu kelompok dari bar di-hover, muncul informasi cacah item dan nama Status dari Task tersebut. Salah satu Status dapat dimunculkan dan disembunyikan dengan klik nama Status di bagian bawah grafik.

![Image of sources graph](https://raw.githubusercontent.com/qontak-dev/docs/master/images/graph_tasks_by_status.gif)

## Achievements by User by Time

Grafik Achievements by User by Time menampilkan data Deals yang dikelompokkan berdasarkan bulan pada tahun ini ditambah prakiraan 6 bulan tahun berikutnya. Grafik yang ditampilkan berbentuk bar. Grafik ini membandingkan besaran Deal yang berada di stage Won dengan Targets.

Besaran Deal yang terhitung mengacu pada waktu di mana Deal tersebut dipindah ke stage Won. Contoh: Deal 1 dibuat pada tanggal 9 September 2018 lalu diubah ke stage Won pada tanggal 14 Nov 2018, maka Deal tersebut akan masuk ke total besaran deal untuk periode Nov 2018.

Pada bagian forecast, data Deal yang ditampilkan pada grafik adalah Deal yang memiliki Close Date (Tanggal Berakhir) di tahun berikutnya.

Jika salah satu kelompok dari bar sebelah kiri di-hover, muncul informasi persentase perbandingan besaran Deal dengan Target. Jika bar pada bagian forecast di-hover, akan muncul informasi besaran Deal yang terkelompokkan berdasarkan Stage.

![Image of sources graph](https://raw.githubusercontent.com/qontak-dev/docs/master/images/graph_achievements_by_user_by_time.gif)
