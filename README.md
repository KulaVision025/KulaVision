# 🎬 Kula Vision Prime

Kula Vision Prime, film, dizi, belgesel ve canlı yayın panellerini tek bir modern ve kullanıcı dostu arayüzde bir araya getiren Windows masaüstü uygulamasıdır.

> **Platform:** Windows 10 / 11 • .NET 8 • WPF • WebView2

---

# ✨ Özellikler

- 🎥 Film, dizi, belgesel, spor ve canlı TV panelleri
- 🔍 Çoklu panel desteği
- 🌐 Global arama
- ⭐ Favoriler sistemi
- 🕒 İzleme geçmişi
- ▶️ Dahili WebView2 medya oynatıcısı
- 🖼️ TMDB poster ve içerik bilgileri
- 📺 Trakt entegrasyonu
- 🌙 Modern koyu tema
- ⚡ Hızlı açılış (Splash Screen)
- 📂 Portable kullanım (Kurulum gerektirmez)

---

# 🖥️ Sistem Gereksinimleri

- Windows 10 veya Windows 11
- 64-bit işletim sistemi
- .NET 8 Desktop Runtime *(Self-Contained sürüm kullanılmıyorsa)*
- Microsoft Edge WebView2 Runtime

---

# 📦 Kurulum

1. **KulaVisionPrime-vX.Y.Z.zip** dosyasını indirin.
2. Dosyaları istediğiniz klasöre çıkarın.
3. **KulaVisionPrime.exe** dosyasını çalıştırın.

Kurulum sihirbazı gerekmez.

---

# 📁 Kullanıcı Verileri

Uygulama ayarları ve yapılandırma dosyaları aşağıdaki klasörde saklanır.

```text
%AppData%\KulaVisionPrime\
```

Örnek:

```text
C:\Users\<KullanıcıAdı>\AppData\Roaming\KulaVisionPrime\
```

---

# 🔑 TMDB ve Trakt API Yapılandırması

Kula Vision Prime ilk çalıştırıldığında aşağıdaki dosyaları **otomatik olarak oluşturur**.

| Dosya | Açıklama |
|-------|----------|
| tmdb-api-key.txt | TMDB API Key'inizi bu dosyanın içine yazın. |
| trakt-client-id.txt | Trakt Client ID'nizi bu dosyanın içine yazın. |

Dosya oluşturmanız gerekmez.

Yapmanız gereken tek işlem kendi API anahtarlarınızı ilgili dosyaların içine eklemektir.

Örnek:

**tmdb-api-key.txt**

```text
YOUR_TMDB_API_KEY
```

**trakt-client-id.txt**

```text
YOUR_TRAKT_CLIENT_ID
```

## API anahtarlarını neden eklemeliyim?

TMDB ve Trakt API anahtarlarının eklenmesi önerilir.

Bu sayede uygulama;

- 🎬 Daha doğru film ve dizi bilgileri alır.
- 🖼️ Poster ve arka plan görsellerini eksiksiz yükler.
- ⭐ Güncel IMDb/TMDB puanlarını gösterir.
- 👤 Oyuncu, tür ve açıklama bilgilerini daha doğru getirir.
- 🔍 Arama sonuçlarını iyileştirir.
- 🚀 Genel performansı ve kullanıcı deneyimini artırır.

> **Not:** Dosyaların içine yalnızca API anahtarınızı yazmanız yeterlidir.

---

# 🖼️ Ekran Görüntüleri

## 🎬 Filmler

Film keşfet ekranı, kategori filtreleri ve popüler filmler.

![Filmler](screenshots/movies.png)

---

## 📺 Diziler

Modern dizi keşfet ekranı.

![Diziler](screenshots/series.png)

---

## 🌍 Belgeseller

Film, dizi ve doğa belgesellerini tek ekranda keşfedin.

![Belgeseller](screenshots/documentaries.png)

---

## 🔎 Panel Seçimi

Bir filmin veya dizinin bulunduğu yayın panellerini tek ekranda görüntüleyin.

![Panel Seçimi](screenshots/panels.png)

---

## ▶️ Dahili Medya Oynatıcısı

WebView2 tabanlı modern medya oynatıcısı.

### Desteklenen Özellikler

- ▶️ Oynat / Duraklat
- ⏩ İleri / Geri Sarma
- 🔊 Ses Kontrolü
- 💬 Altyazı Desteği
- 🖥️ Tam Ekran
- ⚡ Akıcı Oynatma

![Player](screenshots/player.png)

---

# 🛠️ Kullanılan Teknolojiler

- C#
- .NET 8
- WPF
- WebView2
- JSON
- TMDB API
- Trakt API

---

# 🚀 Yol Haritası

Planlanan özellikler:

- ✅ Gelişmiş arama
- ✅ Favori listeleri
- ✅ İzleme geçmişi
- ⏳ Kullanıcı profilleri
- ⏳ Otomatik güncelleme sistemi
- ⏳ Çoklu dil desteği
- ⏳ Performans iyileştirmeleri

---

# 👨‍💻 Geliştirici

**Mustafa Kula**

📧 **mustafakula@proton.me**

---

# ⚠️ Sorumluluk Reddi

Kula Vision Prime herhangi bir medya içeriğini barındırmaz, depolamaz veya dağıtmaz.

Uygulama yalnızca üçüncü taraf web içeriklerine erişim sağlayan bir istemci uygulamasıdır.

Kullanıcılar, eriştikleri içeriklerin kullanım şartlarına ve kendi ülkelerindeki telif hakkı mevzuatına uymaktan kendileri sorumludur.

---

# 📄 Lisans

© 2026 Mustafa Kula

Tüm hakları saklıdır.

Bu proje özel olarak geliştirilmiştir.

Geliştiricinin yazılı izni olmadan kopyalanamaz, değiştirilemez, yeniden dağıtılamaz veya ticari amaçla kullanılamaz.

---

## ⭐ Destek

Kula Vision Prime'ı beğendiyseniz GitHub deposuna ⭐ vererek projeyi destekleyebilirsiniz.

Geri bildirim, öneri ve hata bildirimleri için:

📧 **mustafakula@proton.me**
