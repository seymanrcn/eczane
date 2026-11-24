# Eczane Otomasyonu

Veri Tabanı Sistemleri dersi dönem projesi .
Bir eczanenin hasta, ilaç, güvence ve satış süreçlerini yöneten masaüstü uygulaması
için hazırlanmış veritabanı tasarımı ve proje dokümantasyonu.

## Özellikler
- Hasta kaydı, listeleme, arama, güncelleme ve silme (Durum alanı ile mantıksal silme)
- İlaç kaydı, listeleme, barkod ile arama, güncelleme ve silme
- Güvence (sigorta) kaydı ve yönetimi
- Hasta ve ilaç seçilerek satış oluşturma

## Kullanılan Teknolojiler
- **Uygulama:** C#, Windows Forms
- **Veritabanı:** Microsoft Access (OleDb)
- **Tasarım:** Varlık-ilişki şemaları, 3. Normal Forma kadar normalizasyon

## Veritabanı Yapısı
Hastalar, İlaçlar, Güvenceler ve Satışlar olmak üzere 4 tablo.
- Güvenceler 1 - N Hastalar
- Hastalar 1 - N Satışlar
- İlaçlar 1 - N Satışlar

## Dokümantasyon
Gereksinim analizi, ER şemaları, işlevsel bağımlılıklar, normalizasyon adımları,
DDL komutları, SQL sorguları ve uygulama ekran görüntüleri için:
**[Proje Raporu (PDF)](docs/Veritabani_Sistemleri_Rapor.pdf)**

