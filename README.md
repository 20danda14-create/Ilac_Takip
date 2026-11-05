# İlaç Takip Asistanı

Fotoğraftaki günlük akışı büyük yazılı, erişilebilir bir PWA'ya dönüştürür.

## GitHub Pages kurulumu
1. GitHub'da yeni bir repository oluşturun (ör. `ilac-takip`).
2. Bu klasördeki tüm dosyaları deponun kök dizinine yükleyin.
3. **Settings → Pages → Build and deployment** bölümünde **Deploy from a branch** seçin.
4. Branch `main`, klasör `/ (root)` seçip **Save** deyin.
5. Birkaç dakika sonra `https://KULLANICI-ADINIZ.github.io/ilac-takip/` adresinde açılır.

## Telefona ekleme
- iPhone: Safari'de siteyi açın → Paylaş → Ana Ekrana Ekle.
- Android: Chrome menüsü → Uygulamayı yükle / Ana ekrana ekle.

## Düzenleme
`app.js` başındaki `scheduleData` listesini düzenleyin. Her kayıt için benzersiz `id`, `time`, `name`, `detail`, `note`, `tag` alanları vardır.

## Özellikler ve sınırlar
- Büyük, yüksek kontrastlı arayüz; yazı büyütme; sesli okuma.
- Tek dokunuşla alındı işaretleme ve günlük ilerleme.
- Tarayıcı bildirimi sayfa açıkken çalışır; arka planda veya uygulama kapalıyken garanti değildir.
- İşaretlemeler cihazın tarayıcısında tutulur; cihazlar arasında eşitlenmez.
- Service Worker ile temel çevrimdışı erişim.
- Tıbbi karar vermez. Fotoğraftaki plan hekim/eczacı tarafından doğrulanmalıdır. Özellikle Gaviscon dozları, mide koruyucu ürün seçimi, tiroid ilacının zamanlaması ve “Antisepsin” adı/uygulama yolu kontrol edilmelidir.
- Fotoğraftaki “gece su dahil hiçbir şey tüketmeyin” ifadesi uygulamaya alınmamıştır; genel su kısıtlaması olarak uygulanmamalıdır.
