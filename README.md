# Library-App Codeigniter - Mysql
Welcome documentation for library app

![1628255470](https://user-images.githubusercontent.com/77251566/129654763-35529622-9963-4d3e-9e54-e768634bed82.png)

Berisi tentang:

    o	Page: Dashboard, Members, Officer, Books, Loan, Return, Report, Setting, Log Out
            Dashboard : Berisi total pada setiap tabel dan top 5 teratas data yang terbaru,
            Member    : Management user dan disable enable member active,
            Officer   : Management user dan disable enable officer active,
            Book      : Management books,
            Loan      : Peminjaman buku maksimal 3 buku, dilengkapi dengan tanggal pengembalian,
            Return    : Pengembalian buku, dan melihat denda berhari bila melewati jatuh tempo,
            Report
              Loan    : Melihat buku yang sudah dipinjam dan estimasi berapa lama serta denda (export pdf),
              Returned: Melihat buku yang sudah dikembalikan dan estimasi peminjaman buku serta denda (export pdf),
            Setting   : Setting profile perpustakaan, setting denda perhari berapa, mereset password
            Log Out   : keluar applikasi,
    o	Memiliki management user role yang cukup baik,
    o	Export Pdf.

Menu List and Role user access

<p align="center">
  <img src="https://user-images.githubusercontent.com/77251566/124707214-b5fbeb00-df22-11eb-9f9b-b067c19b3580.png">
</p>


Structure Databse, this only pk and index unique, iam not use pk
<p align="center">
  <img src="https://user-images.githubusercontent.com/77251566/124686783-e67d5e00-defd-11eb-858f-785989e17f85.png">
</p>

User Admin:

    User: Admin1A0014 
    Password: Admin1A0014TS 
User Staff (Officer):

    User: Officer1A0018 
    Password: Officer1A0018TS 
User Member:

    User: Member1M0012 
    Password: Member1M0012TS 
if the user is not activate than you can do enable user in application use user admin </br>
Password default in application (username + TS) if username Member1M0012 and your password Member1M0012TS </br>
(Untuk demo tidak bisa Export Pdf dan Upload Foto) </br>
Link demo: https://thirtyseven-v1.herokuapp.com/Officer
