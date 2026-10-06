# 🎨 AI Prompt Challenge — Portfolio Case Study & Showcase

<div align="center">

![AI-Powered](https://img.shields.io/badge/AI-Realtime_Image_Generation-8A2BE2?style=for-the-badge&logo=openai&logoColor=white)
![Frontend](https://img.shields.io/badge/Frontend-Vanilla_JS_&_CSS3-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Design](https://img.shields.io/badge/Design-Cyberpunk_Glassmorphism-00FFFF?style=for-the-badge&logo=figma&logoColor=black)
![Backend](https://img.shields.io/badge/Backend-PHP_8.2_REST_API-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Precision](https://img.shields.io/badge/Algorithm-Milimetric_Scoring_00.00%25-10b981?style=for-the-badge)

<p align="center">
  <b>Yapay Zeka Görsel Eşleştirme, Prompt Mühendisliği ve Rekabetçi Oyunlaştırma Deneyimi</b>
</p>

</div>

---

## 📌 Proje Özeti (Executive Summary)

**AI Prompt Challenge**, kullanıcıların yaratıcı prompt yazma becerilerini gerçek zamanlı yapay zeka modelleriyle test eden etkileşimli bir web platformudur. 

Yarışmacılar, sunulan yüksek çözünürlüklü hedef görselleri inceleyerek **120 saniye** içinde en isabetli betimlemeyi yazar. Sistem, promptu anlık olarak difüzyon modellerine iletir, gerçek zamanlı görsel üretir ve hedef görsel ile üretilen görsel arasındaki anlamsal, kompozisyonel ve renk uyumunu **%00.00 hassasiyetinde** puanlayarak lider tablosunda listeler.

---

## 📸 Arayüz & Oyun Deneyimi Vitrini (UI Walkthrough)

### 1. Karşılama & Kurallar Ekranı
Yarışma mekaniklerini, 120 saniyelik zaman sınırını ve yapay zeka puanlama sistemini tanıtan modern açılış ekranı.

![Karşılama Ekranı](assets/screenshots/01_welcome_hero.png)

---

### 2. Canlı Yarışma & 120s SVG Geri Sayım Sayacı
Kullanıcının hedef görseli incelediği, kelime ve karakter sınırlarını takip ettiği ve anlık SVG dairesel geri sayım sayacıyla yarıştığı ana oyun arayüzü.

![Oyun Arayüzü](assets/screenshots/02_gameplay_round.png)

---

### 3. Gerçek Zamanlı AI Görsel Üretimi & Yan Yana Karşılaştırma Modalı
Yazılan promptun yapay zekaya aktarılmasıyla üretilen özgün görselin, hedef görsel ile yan yana getirildiği ve **Kompozisyon**, **Renk & Işık**, **Detay & Obje** uyumunun milimetrik hesaplandığı sonuç ekranı.

![Karşılaştırma Modalı](assets/screenshots/03_ai_comparison_modal.png)

---

### 4. İleri Düzey Tematik Turlar (Steampunk & Cyberpunk)
Farklı sanatsal akımlara (Cyberpunk, Büyülü Fantastik Ada, Steampunk Barista) sahip çoklu tur yapısı.

![Steampunk Turu](assets/screenshots/04_gameplay_steampunk.png)

---

### 5. Yarışma Sonu Başarı & Kümülatif Skor Ekranı
3 turun toplam benzerlik puanının (`300.00` üzerinden) hesaplandığı, yapay zeka unvanının verildiği ve lider tablosuna isim kaydının yapıldığı final ekranı.

![Final Skor Ekranı](assets/screenshots/05_final_score_summary.png)

---

### 6. Top 10 Lider Tablosu (Leaderboard)
En yüksek benzerlik oranına ulaşan yarışmacıların altın 🥇, gümüş 🥈 ve bronz 🥉 rozetlerle sıralandığı, tur bazlı puan dağılımlarını içeren dinamik sıralama tablosu.

![Lider Tablosu](assets/screenshots/06_leaderboard_top10.png)

---

## 🎯 Hedef Görsel Galerisi (Target Showcase)

<div align="center">
<table>
  <tr>
    <td align="center"><b>Hedef 1: Siber Kedi (Neo-Tokyo)</b></td>
    <td align="center"><b>Hedef 2: Büyülü Uçan Ada</b></td>
    <td align="center"><b>Hedef 3: Steampunk Robot Barista</b></td>
  </tr>
  <tr>
    <td><img src="assets/images/target_1.jpg" width="280"></td>
    <td><img src="assets/images/target_2.jpg" width="280"></td>
    <td><img src="assets/images/target_3.jpg" width="280"></td>
  </tr>
</table>
</div>

---

## 🏗️ Sistem Mimarisi & Çalışma Mantığı

```mermaid
flowchart TD
    A[🎮 Oyuncu Prompt Girişi] -->|120s Dinamik Sayaç| B[🌐 Otomatik Çeviri Köprüsü]
    B -->|İngilizce Semantik Vektör| C[⚡ AI Difüzyon Motoru]
    C -->|Görsel Sentezleme| D[🖼️ Base64 Data URI / Yerel Önbellek]
    A & B --> E[🔬 5 Eksenli Milimetrik Benzerlik Motoru]
    E -->|Karakter + Stil + Ortam + Detay + Renk| F[📊 2 Haneli Ondalık Skor %00.00]
    D & F --> G[🪟 Yan Yana Karşılaştırma Modalı]
    G -->|3 Tur Kümülatif Toplam| H[🏆 Top 10 Lider Tablosu]
```

---

## 💡 Öne Çıkan Mühendislik Çözümleri

1. **Bilişsel Çeviri Köprüsü (Multilingual Prompt Bridge):**  
   Difüzyon modelleri ağırlıklı olarak İngilizce eğitildiği için, Türkçe girilen doğal ifadeleri arka planda anlık olarak İngilizce semantik vektörlere dönüştürerek yanlış üretimleri (hallucination) engeller.
2. **Milimetrik Skorlama Algoritması (%00.00 Hassasiyet):**  
   Basit kelime eşleştirmesi yerine; Ana Karakter (%30), Sanatsal Stil (%25), Ortam (%20), Detay & Aksesuar (%15) ve Renk Paletini (%10) ağırlıklandıran deterministik 2 basamaklı ondalık puanlama motoru.
3. **Sıfır Gecikmeli Base64 İletimi:**  
   Üretilen görseller istemciye doğrudan Base64 Data URI olarak aktarılır; harici ağ kesintilerinde veya CORS kısıtlamalarında dahi kırık görsel ihtimali tamamen ortadan kaldırılmıştır.

---

## ⚙️ Teknoloji Yığını

- **Frontend:** Vanilla JavaScript (ES6+ SPA State Machine), HTML5 Semantic Architecture.
- **Styling & Estetik:** Vanilla CSS3 (Custom Properties, Glassmorphism, Responsive Grid, Neon Glow).
- **Backend / API:** PHP 8.2 (RESTful Endpoints, cURL Proxy, GD Graphics Processing).
- **Veri Depolama:** JSON File-based High Performance Storage (`scores.json`).
- **Yapay Zeka:** Pollinations Diffusion Engine & Real-time Translation API.

---

<div align="center">
  <sub>Geliştirici: <b>Sevcan Koç</b> • Yıl: <b>2026</b></sub>
</div>
