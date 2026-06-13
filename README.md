# GİST Raporlama

Tek dosyalı statik React uygulaması. Biyopsi ve rezeksiyon için ayrı giriş ekranı, tıklama ile veri girişi ve kısa patoloji raporu çıktısı üretir.

## Kullanım

1. `index.html` dosyasını GitHub repo ana dizinine koyun.
2. GitHub Pages açın: Settings -> Pages -> Deploy from branch -> main / root.
3. Sayfayı tarayıcıda açın.

Derleme gerektirmez. React, ReactDOM ve Babel CDN üzerinden yüklenir.

## Not

Risk değerlendirmesi CAP GIST risk tablosuna göre otomatik hesaplanır. Tabloda yer almayan anatomik yerleşimler için jejunum/ileum kriterleri kullanılır.


## v5
- Açılışta ve temizlemede tüm alanlar boş gelir.
- Tümör boyutları satırı, boyut girilmedikçe rapora eklenmez.
- 1, 2 veya 3 boyut girilebilir; en büyük tümör boyutu otomatik bulunur.
