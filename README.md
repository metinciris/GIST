# GIST Raporlama - Statik React

Bu depo, Excel tabanlı GIST raporlama dosyasının yerine geçmek üzere hazırlanmış statik React uygulamasıdır.

## Özellikler

- Biyopsi ve rezeksiyon için ayrı giriş ekranı
- Tıklama ile hızlı veri girişi
- Girilen alanlarda yeşil arka plan vurgusu
- Otomatik histolojik grade hesaplama
- Otomatik GIST risk değerlendirmesi
- Rezeksiyon için otomatik pT hesaplama
- Kopyalanabilir sinoptik rapor
- Tek dosyalı `index.html`; derleme gerekmez

## Kullanım

1. Bu depodaki eski Excel dosyası yerine `index.html` dosyasını yükleyin.
2. GitHub Pages kullanacaksanız repository ayarlarından Pages bölümünde `main` branch ve root klasörünü seçin.
3. Sayfa açıldığında biyopsi veya rezeksiyon sekmesini seçip alanları doldurun.
4. Oluşan raporu `Raporu kopyala` butonu ile panoya alın.

## Kaynak

CAP GIST biyopsi, rezeksiyon ve biyobelirteç protokolleri temel alınmıştır. Mide risk değerlendirmesinde güncel düzeltme kullanılmıştır: düşük mitoz ve >10 cm mide GIST için orta risk %12.
