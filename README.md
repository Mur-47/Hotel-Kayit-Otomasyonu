# Otel Kayıt Otomasyonu — eksik kaynak yüklemesi

Otel kayıt otomasyonu için açılmış, uygulama kaynakları henüz yüklenmemiş depo.

**Durum: bu depo şu haliyle derlenemez ve çalıştırılamaz.** İncelenen yüklemede `.cs`, `.csproj` ve `.sln` dosyaları bulunmuyor. Önceki içerik, Visual Studio arama dizini ve pencere düzeni önbelleklerinden oluşuyordu. Bu dosyalar kaynak kod değildir; Git takibinden çıkarıldı. Önceki commit'lerde erişilebilirler.

## Projeyi tamamlamak için gerekenler

1. Asıl proje klasöründen `.sln`, `.csproj`, `.cs`, `.Designer.cs`, `.resx` ve gerekli kaynak dosyalarını bulun.
2. `bin`, `obj`, `.vs`, kişisel ayarlar ve derlenmiş uygulama dosyalarını yüklemeyin.
3. Veritabanı gerekiyorsa kişisel veri içermeyen şema/kurulum betiği ve sentetik örnek veri ekleyin. Gerçek veritabanı veya yedek yüklemeyin.
4. Bağımlılık sürümlerini ve kurulum adımlarını kaynaklara göre belgeleyin.
5. Temiz bir kopyadan derleyip sonucu bu belgeye ekleyin.

Bu adımlar tamamlanmadan çalışır sürüm, tamamlanmış ürün veya indirilip kurulabilen uygulama olarak sunulmamalıdır.

## Doğrulama

Depodaki dosya türleri kontrol edildi. Kaynak kod bulunmadığı için derleme, uygulama ve veritabanı testleri çalıştırılmadı.

## Geliştirici

**Murat AKTAŞ** · [GitHub](https://github.com/Mur-47)
