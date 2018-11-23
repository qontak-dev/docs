---
title: Comparison
parent: Reports
has_children: true
nav_order: 1
---

# Comparisons

## Deals Closed by User (Leaderboard)
Grafik Deals Closed by User menampilkan User dengan peringkat 3 teratas dan 3 terbawah dalam perolehan total besaran Deal dalam periode yang terpilih. Deal yang akan terhitung besarnya adalah yang telah ada dalam stage Won.

Besaran Deal yang terhitung mengacu pada waktu di mana Deal tersebut dipindah ke stage Won. Contoh: Deal 1 dibuat pada tanggal 9 November 2018 lalu diubah ke stage Won pada tanggal 14 Nov 2018, maka Deal tersebut akan masuk ke total besaran deal untuk periode tanggal 14 Nov 2018.

Mata uang yang ditampilkan adalah mata uang default yang dipilih User sehingga bila ada Deal dengan mata uang selain mata uang default, besaran deal akan dikonversi sebelum dijumlahkan.

![Image of deals closed by user graph](https://raw.githubusercontent.com/qontak-dev/docs/master/images/graph_leaderboard.gif)

## Deals Won by User (Count)

Graph Deals Won by User (Count) menampilkan data Count (cacah) Deal yang berada di Stage Won dan dikelompokkan berdasarkan User. Grafik ini ditampilkan dalam bentuk bar.

Cacah Deal yang terhitung mengacu pada waktu di mana Deal tersebut dipindah ke stage Won. Contoh: Deal 1 dibuat pada tanggal 9 September 2018 lalu diubah ke stage Won pada tanggal 14 Nov 2018, maka Deal tersebut akan masuk ke total besaran deal untuk periode 14 Nov 2018.

Jika salah satu bar di-hover, maka akan muncul informasi nama User dan cacah Deal yang berada pada Stage Won.

![Image of deals won by user count graph](https://raw.githubusercontent.com/qontak-dev/docs/master/images/graph_deals_won_by_user.gif)

## Tasks by Status

Grafik Tasks by Status menampilkan data Tasks yang dikelompokkan berdasarkan User dan Status dari Task. Grafik yang ditampilkan berbentuk bar. Grafik ini memiliki filter tambahan yaitu Categories.

Jika salah satu kelompok dari bar di-hover, muncul informasi cacah item dan nama Status dari Task tersebut. Salah satu Status dapat dimunculkan dan disembunyikan dengan klik nama Status di bagian bawah grafik.

![Image of tasks by status graph](https://raw.githubusercontent.com/qontak-dev/docs/master/images/graph_tasks_by_status.gif)
