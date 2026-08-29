# 🎵 Melody - iOS Kurulum Rehberi

Spotify tarzı, açık kaynak (GPL-3.0) müzik uygulaması.

## ✨ Özellikler

- 🎧 **En iyi ses kalitesi** — platforma göre en iyi akışı seçer (Android/PC: Opus öncelikli, ~160 kbps; iPhone: her zaman çalabilen en iyi AAC); ses asla transkode edilmez
- ✨ **Premium arayüz** — çalan şarkının kapağına göre değişen aurora arka plan
- ⬇️ **Çevrimdışı dinleme** — şarkı/liste indir, internetsiz dinle
- 🔍 **Sınırsız müzik** — milyonlarca şarkıyı ara ve çal
- 📝 **Şarkı sözleri** — eş zamanlı söz görüntüleme
- 🎧 **Spotify içe aktarma** — Spotify listelerini tek tıkla taşı
- 📻 **Radyo istasyonları** — sevdiğin şarkılardan sonsuz radyo
- 🎤 **Sanatçı sayfaları** — sanatçı diskografisine göz at
- 🎚️ **Ekolayzır** — bass/vokal ayarları ve hazır profiller
- ⏰ **Uyku zamanlayıcısı**
- 📊 **Zaman Makinesi** — dinleme istatistikleri
- 🎨 **Tema desteği** — dinamik renk + saf siyah (AMOLED)
- 🔗 **Çalma listesi paylaşımı** — tek linkle paylaş
- 🌍 **Türkçe dahil çoklu dil**

## ⬇️ İndirme Linkleri

| Dosya | Link |
|-------|------|
| 🤖 APK (Android) | [Melody.apk indir](../../releases/latest/download/Melody.apk) |
| 📦 IPA (iOS) | [Melody.ipa indir](../../releases/latest/download/Melody.ipa) |
| 🐧 DEB (Linux Mint/Ubuntu) | [melody_1.0.3_amd64.deb indir](../../releases/latest/download/melody_1.0.3_amd64.deb) |
| 🐧 Tar.gz (taşınabilir) | [Melody-linux.tar.gz indir](../../releases/latest/download/Melody-linux.tar.gz) |
| 🌐 Tanıtım sayfası | [arise1881.github.io/melody-dist](https://arise1881.github.io/melody-dist/) |

## 📲 iPhone'a Kurulum — 4 Yol

> 🎬 **Video rehber:** Türkçe sesli anlatımlı, bilgisayarsız kurulum videosu (4:50 dk): [Melody-iOS-Kurulum.mp4 indir](../../releases/download/kurulum-videolari-v1/Melody-iOS-Kurulum.mp4)

### Yol A: PC'siz Kurulum (SideStore) — önerilen, bilgisayar gerekmez
Apple, QR/tarayıcıdan inen `.ipa`'nın direkt kurulmasına izin vermez; bu yüzden cihaza önce bir "imzalayıcı" (SideStore) kurulur. Kurulunca Melody ve güncellemeleri tamamen PC'siz:
1. **iOS 27+:** Tarayıcıdan [SideInstaller](https://frizzlem.github.io/SideInstaller/) → uygulamayı kur → Apple ID ile gir → **Install SideStore**
   **iOS 26 ve altı (gri alan):** [AppleJr](https://applejr.net) ile **ESign** kur, SideStore IPA'sını cihazdan imzala (sertifika iptalleri yaşanabilir)
2. SideStore → **Settings → Sources** → ekle:
   `altstore://source?url=https://raw.githubusercontent.com/Arise1881/melody-dist/main/apps.json`
3. Kaynak listesinden **Melody** → **Install** → Apple ID onayı ✅
4. Sonrasında 7 günlük imza yenilemesi SideStore tarafından WiFi üzerinden otomatik yapılır

### Yol B: PC'siz (gri alan) — ESign/Scarlet gibi cihaz-içi imzalayıcılar
İnternetteki imza servisleri cihazda imzalar, "Profil/cihaz yönetimi" ile kurarsın. PC gerekmez ama ticari/kırık sertifika kullanır; Apple zaman zaman iptal eder → **güvenilir değil ve iOS 26'da çalışması garanti edilemez.**

### Yol C: AltStore ile (ilk kurulumda tek seferlik bilgisayar)
1. Telefonunda **AltStore** kuruluysa: bu linki aç →
   `altstore://source?url=https://raw.githubusercontent.com/Arise1881/melody-dist/main/apps.json`
2. Kaynak eklenince listede **Melody** görünür → **Free** → **Install**
3. Apple ID'nle onayla, biter ✅

### Yol D: Sideloadly ile (Windows/Mac + USB)
1. [sideloadly.io](https://sideloadly.io) indir
2. iPhone'u USB ile bağla
3. `Melody.ipa` dosyasını pencereye sürükle
4. Apple ID gir → **Start** → biter ✅

### Yol E: TrollStore (iOS 14.0–16.6.1 / 17.0)
İmzasız IPA olduğu gibi kurulur: dosyayı TrollStore ile aç.

## 🐧 Masaüstü Kurulum (Linux)

- **Linux Mint/Ubuntu**: `.deb` dosyasına çift tıkla → **Kur** (veya: `sudo apt install ./melody_1.0.3_amd64.deb`)
- Menüde "Melody" olarak görünür, ses için sistemde mpv kütüphanesi yeterlidir (Mint/Ubuntu'da hazır gelir)

## ❓ Sık Sorulanlar

**Ücretli mi?** Hayır. Ücretsiz Apple ID ile kurulur.
**Ne kadar geçerli?** Ücretsiz imza 7 gün geçerlidir; SideStore/AltStore aynı WiFi'dayken otomatik yeniler.
**Geliştirici Modu?** iOS 16+ cihazlarda ilk kurulumda: Ayarlar → Gizlilik ve Güvenlik → Geliştirici Modu → Aç.

---


