# VikBooking Türkçe Çeviri Dosyası (Yapay Zeka Destekli)

Bu depo, WordPress otel ve rezervasyon eklentisi olan **VikBooking**'in güncel sürümü için hazırlanmış Türkçe dil dosyasını (`.po`) içermektedir.

Geliştirdiğim otel sitesi projesinde ihtiyacım olduğu için eklentiyi yapay zeka araçları kullanarak Türkçeye çevirdim. Benzer projeler geliştiren, yerel sunucularda veya canlı ortamda çalışan diğer web tasarımcıların ve site sahiplerinin de faydalanabilmesi için açık kaynak olarak paylaşıyorum.

## 🚀 Özellikler
* En güncel VikBooking eklentisi ile uyumludur.
* Yapay zeka ile çevrildiği için oldukça kapsamlı ve anlaşılırdır.
* Hem yönetici paneli (backend) hem de kullanıcı arayüzü (frontend - rezervasyon formları vb.) metinlerini kapsar.

## 🛠️ Kurulum & Kullanım Talimatları

Çeviri dosyalarını sitenize eklemek oldukça basittir. Lütfen aşağıdaki adımları sırasıyla izleyin:

1. Bu depodaki `vikbooking-tr_TR.po`  dosyasını bilgisayarınıza indirin.
2. Sitenizin dosyalarına (FTP, cPanel veya yerel sunucu kullanıyorsanız htdocs/www klasörü üzerinden) erişin.
3. Dosyaları tam olarak şu dizine kopyalayın:
   `wp-content/languages/plugins/`
4. WordPress genel ayarlarından site dilinizin **Türkçe** olarak seçili olduğundan emin olun.

**⚠️ ÖNEMLİ NOT:** Dosyaları doğrudan eklentinin kendi klasörüne (`wp-content/plugins/vikbooking/languages/`) **ATMAYIN**. Eğer oraya atarsanız, VikBooking eklentisine güncelleme geldiğinde Türkçe çeviri dosyalarınız silinir. Yukarıda belirtilen `wp-content/languages/plugins/` dizinine koyduğunuzda çevirileriniz her zaman güvende ve kalıcı olacaktır.

## 🤝 Katkıda Bulunma
Çeviri büyük oranda yapay zeka ile yapıldığı için bazı sektörel terimlerde ufak tefek kaymalar olabilir. Eğer kendi sitenizde kullanırken bir düzeltme yaparsanız veya daha iyi bir çeviri öneriniz varsa, *Pull Request* göndererek bu projeye katkıda bulunabilirsiniz.
