```markdown
# Strateji Kuleleri

Bu depo, Hanoi Kuleleri mantığı üzerine kurgulanmış, ancak "Asal Sayı Gücü" mekaniği ile zenginleştirilmiş **3B stratejik bir bulmaca oyununu** içerir. **Three.js** kullanılarak geliştirilen uygulama, tarayıcı üzerinde yüksek kaliteli, etkileşimli ve aşamalı bir oyun deneyimi sunar.

---

## Özellikler

### 1. 3B Oyun Motoru (Three.js)
- **Sürükleyici Atmosfer:** Dinamik ışıklandırma, gölgeler ve sis efektleriyle donatılmış fütüristik karanlık tema.
- **Etkileşimli Kamera:** **OrbitControls** desteği (Döndürme, yakınlaştırma ve kaydırma hareketleri).
- **Akıcı Animasyonlar:** Seviye geçişlerinde sinematik kamera hareketleri ve zafer anında parçacık (particle) efektleri.

### 2. Oyun Mekanikleri
- **Temel Hedef:** Diskleri başlangıç kulesinden **ışık saçan hedef kuleye**, büyükten küçüğe kusursuz bir piramit oluşturacak şekilde taşımak.
- **Asal Kadim Güç:** **2, 3, 5 ve 7** numaralı diskler asaldır. Bu diskler boyut fark etmeksizin her diskin üzerine yerleştirilebilir, stratejik köprü görevi görürler.
- **Standart Kural:** Asal diskler dışındaki büyük bir disk, kendisinden küçük bir diskin üzerine konulamaz.

### 3. İlerleme ve Puanlama
- **8 Zorluk Seviyesi:** 3 diskli başlangıç seviyesinden 10 diskli efsanevi zorluğa kadar uzanan akış.
- **Dinamik Puanlama:** Hamle sayısı ve kalan süreye göre hesaplanan akıllı puan sistemi.
- **Seviye Çarpanları:** Üst seviyelerde kazanılan puanlar zorluk katsayısı ile katlanarak artar.

### 4. Teknik Arayüz (UI/UX)
- **Glassmorphism Tasarımı:** **Tailwind CSS** ile hazırlanmış, bulanıklık efektli ve neon detaylı modern kullanıcı arayüzü.
- **Mobil Optimizasyon:** Tam dokunmatik desteği ve en iyi deneyim için **Yatay Ekran Uyarısı** sistemi.
- **Ses Sistemi:** Web Audio API ile üretilen etkileşimli sesler (tıklama, hata, başarı) ve açılıp kapatılabilir arka plan müziği.

---

## 🛠️ Kullanılan Teknolojiler
- **Three.js** (3B Görüntüleme ve Animasyon)
- **Tailwind CSS** (Modern Arayüz Tasarımı)
- **jQuery** (DOM ve Olay Yönetimi)
- **Web Audio API** (Süreci Ses Üretimi)

---

## Başlangıç

1. Repoyu klonlayın:
   ```bash
   git clone [https://github.com/miyigun/strateji_kuleleri.git](https://github.com/miyigun/strateji_kuleleri.git)

2. index.html dosyasını herhangi bir modern tarayıcıda açın.

3. Not: Seslerin ve 3B varlıkların en sağlıklı şekilde yüklenmesi için yerel bir sunucu (örneğin VS Code Live Server) üzerinden çalıştırmanız önerilir.

### 📜 Lisans
    Bu proje MIT lisansı altında sunulmaktadır.