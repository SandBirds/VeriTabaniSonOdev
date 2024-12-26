VeriTabanıÖdevi

Proje Amacı
Bu proje, ASP.NET Core ve Entity Framework Core kullanarak basit bir ürün yönetim sistemi yapmayı hedefliyor. Kullanıcılar, ürünleri listeleyebilir, ekleyebilir, güncelleyebilir ve silebilir. Amaç, CRUD işlemleri ve veritabanı bağlantılarını öğrenmek.

Kullanılan Teknolojiler
ASP.NET Core: Web uygulamaları geliştirmek için kullanıyoruz.
Entity Framework Core (EF Core): Veritabanı işlemleri için ORM (Veritabanı ile nesneler arasındaki bağlantıyı sağlayan araç).
SQL Server: Veritabanı yönetim sistemi olarak kullanılıyor.
Visual Studio 2022: Proje geliştirme ortamı.

Kurulum ve Çalıştırma

Gereksinimler
Visual Studio 2022
SQL Server
.NET SDK

Adımlar
Projeyi İndirip Visual Studio’da Açın
NuGet Paketlerini Yükleyin
Veritabanı Bağlantısı: appsettings.json dosyasına veritabanı bilgilerinizi ekleyin.
Migration ve Veritabanı Güncelleme:

dotnet ef migrations add InitialCreate
dotnet ef database update

Projeyi Çalıştırın: Visual Studio üzerinden çalıştırabilirsiniz.
