KİŞİSEL ANTRENÖR — KURULUM TALİMATLARI
========================================

Bu klasördeki dosyalar, telefonunda bağımsız bir uygulama gibi çalışacak
"Kişisel Antrenör" web uygulamasını oluşturuyor. Claude'a giriş yapman
gerekmiyor; kendi Anthropic API anahtarınla çalışıyor.

İçerik:
- index.html      -> uygulamanın kendisi
- manifest.json    -> Android'de "ana ekrana ekle" desteği için
- icon-192.png / icon-512.png -> uygulama ikonu

ADIM 1 — GitHub'da ücretsiz barındırma (GitHub Pages)
------------------------------------------------------
1. github.com adresinde bir hesap aç (yoksa).
2. Sağ üstten "+" > "New repository" ile yeni bir repo oluştur.
   İsim önerisi: kisisel-antrenor
   "Public" seçili kalsın.
3. Oluşan repo sayfasında "Add file" > "Upload files" de.
4. Bu klasördeki 4 dosyayı (index.html, manifest.json, icon-192.png,
   icon-512.png) sürükleyip bırak, "Commit changes" ile kaydet.
5. Repo sayfasında üstteki "Settings" sekmesine gir, sol menüden "Pages"
   seçeneğine tıkla.
6. "Branch" kısmından "main" ve "/ (root)" seçip "Save" de.
7. Birkaç dakika bekle, sayfa yenilendiğinde yukarıda bir link belirecek:
   https://KULLANICI_ADIN.github.io/kisisel-antrenor/
   İşte uygulamanın adresi bu.

ADIM 2 — Telefona kurulum
---------------------------
iPhone (Safari):
1. Yukarıdaki linki Safari'de aç.
2. Alt ortadaki paylaş ikonuna (kare + ok) dokun.
3. "Ana Ekrana Ekle" seçeneğini seç.
4. Artık uygulama diğer uygulamalar gibi ana ekranında duruyor.

Android (Chrome):
1. Linki Chrome'da aç.
2. Sağ üstteki üç nokta menüsüne dokun.
3. "Ana ekrana ekle" / "Uygulamayı yükle" seçeneğini seç.

ADIM 3 — API anahtarını gir
-----------------------------
Uygulamayı ilk açtığında otomatik olarak ayarlar ekranı açılacak.
Oradaki kutuya console.anthropic.com'dan aldığın API anahtarını
(sk-ant-... ile başlayan) yapıştır ve "Kaydet" de.

Bu anahtar SADECE telefonunun kendi tarayıcı hafızasında saklanır,
hiçbir sunucuya, hiçbir yere gönderilmez. İstersen sağ üstteki
dişli ikonundan istediğin zaman değiştirebilir ya da silebilirsin.

NOT
---
- Uygulama verileri (günlük kayıtların, antrenman programın, sohbet
  geçmişin) de aynı şekilde sadece telefonunda saklanıyor.
- Tarayıcı geçmişini/verilerini temizlersen bu veriler de silinir —
  o yüzden Safari/Chrome'un "site verilerini temizle" gibi
  ayarlarını bu uygulama için kullanmamaya dikkat et.
- Fotoğraftan kalori tahmini yaklaşık bir tahmindir, kesin ölçüm değildir.
