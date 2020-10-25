# .Net Core 3 MVC Login with Identity and EntityCore Product Management

# Kendi Veritabanınızı Bağlamak için;

Context/MyContext ve ProductsContext dosyalarının içindeki;

@"Data Source=DESKTOP-J78NGJL\TEW_SQLEXPRESS;Initial Catalog=database;Integrated Security=True" 

veritabanı bağlantı linkinde bulunan Source kısmına kendi mssql veritabanını yolunu yazınız.

Veritabanlanını migration ile oluşturmak için;

1- Visual Studio 201*'in Araçlar->NuGet Paket Yönetici -> Paket Yöneticisi consolunu açın,
2- Konsola "add-migration Initial1 -context MyContext" ve "add-migration Initial2 -context ProductsContext" kodlarını teker teker yazın ve çalıştırın.
3- Build Success yazdıktan sonra "update-database" komutu çalıştırın. 
4- Veritabanınızı Sql Server Management'tan veya Vs'dan kontrol edin. 


Talha Tosya
