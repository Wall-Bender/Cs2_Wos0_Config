<div align="center">
  <img src="https://github.com/Wall-Bender/Cs2_Wos0_Config/blob/main/resource/game-icon.bmp alt="Wos0 CS2 Config Logo" width="150"/>
  
  # 💜 WOS0 CS2 PROFESSIONAL CONFIG SET
  **Counter-Strike 2 için özel olarak tasarlanmış, taktiksel avantaj sağlayan "Director Wos0" yapılandırması.**
</div>

---

## 🌟 Neden Bu Config?
Bu yapılandırma sadece sıradan tuş atamaları değil; CS2 oyun motorunun (Source 2) izin verdiği yasal ve gelişmiş taktiksel komutları bir araya getiren özel bir settir. Göz yormayan **Mor (Purple)** arayüzden, duvar arkası ekipman görmeye, tek tuşla takımı susturmaktan havada strafe kolaylığına kadar her şey en ince ayrıntısına kadar düşünülmüştür.

---

## 🎯 Öne Çıkan Özellikler

### 🎨 1. Pro HUD ve Gelişmiş Radar (Purple Edition)
* **Mor Tema:** Göz yormayan, crosshair ile karışmayan şık mor arayüz (`cl_hud_color 5`).
* **Akıllı Radar (TAB Genişlemesi):** Normalde sadece yakın çevrenizi gösteren radar, **TAB (Skor Tablosu)** tuşuna basılı tuttuğunuzda anında devasa bir kareye dönüşerek tüm haritayı gösterir.
* **Duvar Arkası "Röntgen":** Takım arkadaşlarınızın canını, silahını ve **bombalarını** duvarların arkasından görebilirsiniz (`cl_teamid_overhead_mode 3`).
* **Focus Modu:** Rakip takımın sohbeti ve radyo mesajları tamamen kapatılarak dikkatinizin dağılması engellenir.
* **Temiz Ekran:** Gereksiz Steam avatarları gizlenir, sadece hayatta kalan oyuncu sayıları gösterilir.

### ⌨️ 2. Taktiksel Tuş Atamaları (Pro Binds)
Fiziksel tuş tarama (Scancode) teknolojisi kullanılarak klavye dilinden bağımsız, gecikmesiz tepki süreleri sağlanmıştır.
* **Hızlı Bomba Çekme:** Mouse Yan Tuş (Geri) anında **Flashbang**, Mouse Yan Tuş (İleri) anında **Smoke**, `[C]` tuşu anında **Molotof** çeker. Silahlar arası geçişte saniye kaybetmezsiniz.
* **Walk Boost (Sessiz ve Net):** `[SHIFT]` tuşuna basıp yavaş yürüdüğünüzde, oyunun genel ses seviyesi otomatik olarak artar. Böylece uzak mesafedeki düşman ayak seslerini çok daha net duyarsınız. Koşmaya başladığınızda ses normale döner.
* **Clutch Modu:** 1vX durumlarında `[K]` tuşuna basarak tüm takım arkadaşlarınızı anında susturabilir, round bitince tekrar açabilirsiniz.
* **Numpad Hızlı Satın Alma:** Zırh, bomba ve silah setlerini sadece saniyeler içinde Numpad üzerinden alabileceğiniz eksiksiz şablon.

### 🚀 3. Gelişmiş Scriptler ve Hareket (Movement)
* **Scroll Strafe:** Havada farenin orta tuşuna (Mouse3) basılı tutup fareyi çevirdiğinizde hava direncini kırarak inanılmaz keskin dönüşler ve bunnyhop (strafe) yapmanızı sağlar.
* **Mevlana (Fast Spin):** Mouse tekerleğini aşağı kaydırdığınızda anında 360 derece ultra hızlı dönüş moduna girersiniz. Tekrar kaydırdığınızda normale döner.
* **Hızlı Bomba Bırakma:** Elinizde C4 varken başka silaha geçmeye çalışmadan anında yere atmanızı sağlayan özel alias kodlaması.
* **Konsol Kısayolları:** Konsola sadece `d` (disconnect), `q` (quit), `rs` (restart) veya `fix` (kan/mermi izi silme) yazarak hızlı işlemler yapabilirsiniz.
* **Wos0 İmza Sanatı:** Konsola `woso_heart` yazdığınızda özel Director Wos0 görseli ve ses efekti çıkar.

### 🌐 4. Özelleştirilmiş Oyun İkonu (Custom Desktop Icon)
Proje içerisinde standart CS2 ikonunu değiştirebileceğiniz, özel tasarlanmış **Kırmızı Temalı Wos0 İkonu** bulunmaktadır. Masaüstündeki CS2 kısayolunuzu bu ikon ile çok daha kişisel ve "tehlikeli" bir görünüme kavuşturabilirsiniz.

---

## 🛠️ Nasıl Kurulur?

1. **İndirin:** Bu depodaki tüm dosyaları (`Code -> Download ZIP` veya git clone ile) bilgisayarınıza indirin.
2. **Dosyaları Taşıyın:** İndirdiğiniz klasörün içindeki `autoexec.cfg` dosyasını ve `woso` klasörünü aşağıdaki dizine kopyalayın:
   > `C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg`
3. **Başlatma Seçenekleri (Launch Options):** Steam'i açın, CS2'ye sağ tıklayıp `Özellikler` (Properties) deyin. Başlatma seçenekleri kısmına şunu ekleyin:
   > `+exec autoexec.cfg`
4. **İkonu Değiştirme (İsteğe Bağlı):** Masaüstündeki CS2 kısayoluna sağ tıklayın `Özellikler -> Simge Değiştir` diyerek klasörün içindeki `.ico` veya `.png` formatlı Wos0 ikonunu seçin.
5. **Oyuna Girin:** Oyuna girdiğinizde konsolu açın ve kurulumu doğrulamak için `exec autoconfig.cfg` yazın. Artık hazırsınız!

---
> *Tasarlayan ve Geliştiren:* **Director Wos0** > *Bu config sürekli güncel tutulmaktadır.*