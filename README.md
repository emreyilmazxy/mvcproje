# Müşteri Siparişleri Uygulaması (ASP.NET MVC)

Bu proje, basit bir müşteri ve sipariş yönetim sistemi örneğidir. MVC mimarisi kullanılarak hazırlanmıştır.

## Özellikler

- Müşteri bilgilerini görüntüleme
- Müşteriye ait siparişlerin liste halinde tablo olarak gösterimi
- Sipariş ID, ürün adı, fiyat ve miktar bilgileri

## Kullanılan Teknolojiler

- ASP.NET Core MVC
- Razor View Engine
- C#

## Ekran Görüntüsü (Örnek)

| Sipariş ID | Ürün Adı | Fiyat (₺) | Adet |
|------------|-----------|-----------|------|
| 1          | Kulaklık  | 450       | 1    |
| 2          | Webcam    | 850       | 1    |

## Başlangıç

Proje `CustomerOrdersController` üzerinden çalışır. `Index` action'ı, `CustomerOrderViewModel` kullanarak hem müşteri hem sipariş bilgilerini `View`'a taşır.
