HARİTA DEFTERİ – PWA

Bu klasörü olduğu gibi HTTPS bir adrese koy (PWA kuralı: localhost veya https gerekir).
En kolay yollar:
  - Netlify Drop: app.netlify.com/drop sayfasına klasörü sürükle.
  - GitHub Pages: dosyaları bir depoya yükle, Settings > Pages'den yayınla.
  - Cloudflare Pages / Vercel: klasörü statik site olarak yayınla.
Yayınlanınca adresi telefonda/bilgisayarda aç:
  - Android/Chrome/Edge: Ayarlar > Uygulama > "Uygulamayı yükle" ya da tarayıcı menüsünden "Yükle".
  - iPhone/iPad: Safari > Paylaş > "Ana Ekrana Ekle".
Yüklendikten sonra internet olmadan da açılır (yazı tipleri ilk açılışta önbelleğe alınır).

Kısayol adresleri: ?mode=fs (tam ekran), ?mode=where (Nerede bul?), ?mode=what (Bu nedir?).
Sürüm güncelleme: yeni dosyaları aynı adrese yükle; service worker sürüm numarası her derlemede değişir, eski önbellek kendiliğinden silinir.
