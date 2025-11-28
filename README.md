# Kütüphane Otomasyonu (Library Automation)

### Proje Hakkında
Bu proje, C# ve Visual Studio kullanılarak yapılmış bir kütüphane uygulamasıdır. Veritabanı olarak **MSSQL** kullılmıştır.
Kullanıcılar **Personel** ve **Öğrenci** olarak ikiye ayrılır. Kütüphane işlemlerini bu uygulama üzerinden takip edebilirsiniz.

### Özellikler
* **Kullanıcılar:** Öğrenci ve Personel girişleri ayrıdır.
* **Kayıt:** Kullanıcıların Ad, Soyad, TC, Tel, Mail gibi bilgileri veritabanına kaydedilir.
* **Kitap İşlemleri:** Kitap ekleme, silme, güncelleme ve listeleme yapılabilir.
* **Ödünç Alma:** Kimin hangi kitabı ne zaman aldığı ve ne zaman geri vereceği takip edilir.
* **Ceza Sistemi:** İade tarihi geçen kitaplar için sistem otomatik ceza hesaplar.
* **Hatalar:** Yanlış işlem yapıldığında (örneğin boş alan bırakıldığında) uyarı verir.

### Kullanılan Teknolojiler
* C#
* .NET Framework
* MSSQL (Veritabanı)
* Visual Studio 2022

---

### [English] About Project
This is a Library Automation project made with C# and Visual Studio. I used **MSSQL** for the database.
There are 2 user types: **Staff** and **Student**.

### Features
* **User System:** Student and Staff logins are different.
* **Database:** It saves User ID, Name, Phone, Email etc. to the database.
* **Book Operations:** You can Add, Delete, Update and List books.
* **Borrowing:** The system tracks who took which book and the return dates.
* **Penalty:** If the book is late, the system calculates a penalty automatically.
* **Warnings:** It shows warning messages for wrong inputs.
