# 📊 Threads-Analyzer — Threads GT Takip Denetleyicisi

ThreadAudit, Meta platformlarındaki Threads takipçileriniz ile takip ettiklerinizi karşılaştırarak **sizi geri takip etmeyenleri (GT yapmayanları)** saniyeler içinde tespit eden açık kaynaklı, güvenli bir masaüstü aracıdır.

---

## 🔒 Neden %100 Güvenli?
* **Şifre İstemez:** Hesabınıza giriş yapmanızı veya şifrenizi girmenizi kesinlikle talep etmez.
* **Resmi Meta Verisi:** Doğrudan Meta'nın Threads kendi sağladığı resmi JSON dışa aktarım dosyalarını kullanır.
* **Yerel Analiz:** Tüm işlemler tamamen bilgisayarınızda gerçekleşir; verileriniz hiçbir sunucuya gönderilmez.

---

## 📥 1. Adım: Meta Verilerini İndirme (1 Dakika)

1. Tarayıcınızdan **[Instagram Hesaplar Merkezi](https://accountscenter.instagram.com)** sayfasına gidin.
2. **Bilgilerin ve İzinlerin > Bilgilerini dışa aktar > Dışa aktarım oluştur > Threads** seçeneğine tıklayın. 
3. Sonraki ekranda:
   * **Format:** Mutlaka `JSON` seçin.
3. **Dosya Oluştur** butonuna basın. (Meta birkaç dakika içinde hazır olan ZIP arşivini indirebilmeniz için bildirim/mail gönderecektir). Mail gelince zip dosyanızı indirin.

---

## 🚀 2. Adım: Programı Kullanma

### Yöntem A: Hazır EXE ile Çalıştırma (Windows)
1. [Releases](../../releases) kısmından en güncel **`Threads-Analyzer.exe`** dosyasını indirin.
2. Programı çift tıklayarak açın.
3. **"📦 ZIP Dosyası Seç"** butonuna basarak Meta'dan indirdiğiniz ZIP dosyasını doğrudan seçin (arşivi açmanıza gerek yoktur).
4. İncelemek istediğiniz sekmeyi seçin:
   * 🔴 **GT Yapmayanlar:** Sizin takip ettiğiniz ama sizi takip etmeyenler.
   * 🟢 **Karşılıklı:** Karşılıklı takipleştiğiniz dürüst kullanıcılar.
   * 🔵 **Hayranlar:** Sizi takip eden ama sizin geri takip etmediğiniz hesaplar.
5. Listeden herhangi bir kullanıcıya **çift tıklayarak doğrudan profiline gidebilir** veya **"💾 TXT Olarak Kaydet"** butonuyla tüm listeyi dışa aktarabilirsiniz.
