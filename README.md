# AlışverişDünyası Web Uygulaması

CS391 Dersi için hazırlanmış basit bir web alışveriş uygulaması.

## Proje Hakkında

Bu proje, sadece HTML, CSS, Bootstrap ve JavaScript kullanılarak geliştirilmiş basit bir e-ticaret web uygulamasıdır. JQuery, React gibi ek kütüphaneler kullanılmamıştır.

## Özellikler

- Ürün listeleme ve arama
- Kategori bazlı filtreleme
- Fiyata göre sıralama
- Ürün detayı görüntüleme
- Sepete ürün ekleme
- Sepetteki ürünleri düzenleme ve silme
- Sipariş tamamlama

## Proje Yapısı

- **products.js**: Ürün verilerini içeren JavaScript dosyası
- **products.html**: Ana sayfa, tüm ürünleri listeler
- **product-detail.html**: Ürün detay sayfası
- **shopping-cart.html**: Alışveriş sepeti sayfası
- **README.md**: Proje dokümantasyonu

## Kurulum ve Çalıştırma

1. Projeyi bilgisayarınıza indirin
2. Dosyaları bir web sunucusuna yükleyin veya doğrudan tarayıcınızda açın:
   - `products.html` dosyasını açarak başlayın

Not: Proje tarayıcı localStorage özelliğini kullandığı için herhangi bir veritabanı veya sunucu kurulumuna gerek yoktur.

## Kullanım

1. Ana sayfada tüm ürünleri görüntüleyebilirsiniz
2. Ürünleri kategoriye göre filtreleyebilir, metne göre arayabilir veya fiyata göre sıralayabilirsiniz
3. Bir ürünün resmine veya "Detayları Gör" butonuna tıklayarak ürün detaylarını görebilirsiniz
4. Ürün detay sayfasında miktarı belirleyip "Sepete Ekle" butonuna tıklayarak ürünü sepetinize ekleyebilirsiniz
5. Sağ üstteki sepet simgesine tıklayarak sepet sayfasına gidebilirsiniz
6. Sepet sayfasında ürün miktarlarını güncelleyebilir, ürünleri kaldırabilir veya siparişi tamamlayabilirsiniz

## Teknolojiler

- HTML5
- CSS3
- Bootstrap 5
- JavaScript (ES6+)
- localStorage (Sepet verilerini saklamak için) 