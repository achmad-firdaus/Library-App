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

# Documentation Photo


  Dashboard
<p align="center">
  <img src="https://user-images.githubusercontent.com/77251566/125040721-2b51f200-e0c2-11eb-9589-b7f5596393fc.png">
</p>
  Members
<p align="center">
  <img src="https://user-images.githubusercontent.com/77251566/125040980-70762400-e0c2-11eb-84f2-1f38b8e1441b.png">
</p>
  Officer
<p align="center">
  <img src="https://user-images.githubusercontent.com/77251566/125041073-8be12f00-e0c2-11eb-9a9f-44d85d5edd1f.png">
</p>
Books
<p align="center">
  <img src="https://user-images.githubusercontent.com/77251566/125041167-a87d6700-e0c2-11eb-9a2c-1468cd81b475.png">
</p>
Loan
<p align="center">
  <img src="https://user-images.githubusercontent.com/77251566/125041408-ee3a2f80-e0c2-11eb-8684-f4b4c47d6548.png">
</p>
Return
<p align="center">
  <img src="https://user-images.githubusercontent.com/77251566/125041564-188bed00-e0c3-11eb-9745-aee10a8a97f4.png">
</p>
Loan Report
<p align="center">
  <img src="https://user-images.githubusercontent.com/77251566/125041695-3d806000-e0c3-11eb-9168-82b6b088b6c3.png">
</p>
Loan Report Pdf
<p align="center">
  <img src="https://user-images.githubusercontent.com/77251566/124894093-88d43900-e005-11eb-9564-1f54af2bb9d3.png">
</p>
Returned Report
<p align="center">
  <img src="https://user-images.githubusercontent.com/77251566/125041824-643e9680-e0c3-11eb-9b6c-3da7f22fba3b.png">
</p>
Returned Report Pdf
<p align="center">
  <img src="https://user-images.githubusercontent.com/77251566/125042800-75d46e00-e0c4-11eb-9c45-ab31ff4cb0c8.png">
</p>
Setting
<p align="center">
  <img src="https://user-images.githubusercontent.com/77251566/125042077-a7006e80-e0c3-11eb-861c-dba9a5e0077f.png">
  <img src="https://user-images.githubusercontent.com/77251566/125042117-b089d680-e0c3-11eb-822e-223f8a2f2d69.png">
</p>


User:<br>
Admin

    User: Admin1A0014 
    Password: Admin1A0014TS 
Staff (Officer)

    User: Officer1A0018 
    Password: Officer1A0018TS 
Member

    User: Member1M0012 
    Password: Member1M0012TS 
if the user is not activate than you can do enable user in application use user admin </br>
Password default in application (username + TS) if username Member1M0012 and your password Member1M0012TS </br>
(Untuk demo tidak bisa Export Pdf dan Upload Foto) </br>
Link Demo: https://thirtyseven-v1.herokuapp.com/Officer
