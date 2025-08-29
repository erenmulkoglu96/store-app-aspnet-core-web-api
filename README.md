### Store App – ASP.NET Core Web API


ASP.NET Core Web API projesi. Katmanlı mimari ile geliştirildi; EF Core, AutoMapper, loglama, doğrulama ve global hata yönetimi uygulandı. Postman üzerinden CRUD işlemleri test edildi. Asenkron programlama, sayfalama, arama, sıralama, filtreleme, veri şekillendirme, HATEOAS, versiyonlama, caching ve JWT tabanlı kimlik doğrulama özellikleri eklendi.

(ASP.NET Core Web API project built with layered architecture. Implemented EF Core, AutoMapper, logging, validation, and global error handling. CRUD operations tested via Postman. Features include asynchronous programming, pagination, searching, sorting, filtering, data shaping, HATEOAS, versioning, caching, and JWT-based authentication.)



Bu projede amaç, modern web servis geliştirme prensiplerini öğrenmek ve uygulamaktır.


## Uygulanan Başlıca Konular:

- Yazılım Mimarisi: Katmanlı mimari yaklaşımı

- Veritabanı İşlemleri: Entity Framework Core

- Nesne Eşleme: AutoMapper ile DTO–Entity dönüşümleri

- Loglama: NLog entegrasyonu

- Asenkron Programlama: Async / Await ile Task tabanlı işlemler

- HTTP ve REST: CRUD operasyonları (GET, POST, PUT, DELETE)

- İleri API Özellikleri:

    - Global hata yönetimi

    - Doğrulama (Validation)

    - Action Filters

    - İçerik pazarlığı (Content Negotiation)

    - Sayfalama, filtreleme, arama, sıralama, veri şekillendirme

    - HATEOAS, HEAD, OPTIONS desteği

    - API versiyonlama

    - Caching, rate limiting, throttling

- Kimlik Doğrulama: JWT, Identity ve Refresh Token

- API Dokümantasyonu: Swagger

<br></br>

The goal is to practice and implement modern web service development principles.


## Key Implemented Features

- Software Architecture: Layered architecture

- Database Operations: Entity Framework Core

- Object Mapping: DTO–Entity mapping with AutoMapper

- Logging: NLog implementation

- Asynchronous Programming: Task-based operations with Async / Await

- HTTP & REST: CRUD operations (GET, POST, PUT, DELETE)

- Advanced API Features:

    - Global error handling

    - Validation

    - Action Filters

    - Content Negotiation

    - Pagination, filtering, searching, sorting, data shaping

    - HATEOAS, HEAD, OPTIONS support

    - API versioning

    - Caching, rate limiting, throttling

- Authentication: JWT, Identity, Refresh Token

- API Documentation: Swagger



## Kurulum ve Çalıştırma (Installation & Run)


## Gereksinimler
.NET 6 SDK veya üzeri

SQL Server 

Postman (isteğe bağlı, API testleri için)



1. Repoyu klonla:
   
```
git clone https://github.com/erenmulkoglu96/store-app-aspnet-core-web-api.git
 ```

3. Bağımlılıkları yükle:

 ```
dotnet restore
 ```

3. Migration’ları çalıştır ve veritabanını oluştur:

 ```
dotnet ef database update
 ```

4. Uygulamayı başlat:

 ```
dotnet run
 ```

















