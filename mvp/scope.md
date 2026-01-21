# MVP Scope

Bu doküman, Tervo’nun ilk versiyonunda (MVP)  
**hangi özelliklerin dahil olduğunu ve hangilerinin bilinçli olarak dışarıda bırakıldığını** tanımlar.

Amaç:
- Hızlı ve odaklı MVP çıkarmak
- Öğrenme modelini gerçek kullanıcıyla test etmek
- Scope creep’i engellemek

---

## MVP’DE VAR (IN SCOPE)

### 1) Öğrenme Yapısı
- İki meslek
- İki modül (yetkinlik alanı)
- Görev bazlı ilerleme modeli
- Görev sıralaması sistem tarafından belirlenir

---

### 2) Görev Türleri
- AI Notes + AI Voice (default)
- Video Görev (gerekli olan yerde)
- Simulation Görev (decision-based kabul edilir)

Kullanıcı görev türlerini ana sayfada görmez.

---

### 3) Ana Sayfa
- Görev bazlı ilerleme ekranı
- Tek ana CTA: **Görevi Başlat / Devam Et**
- Önceki görev (tamamlandı)
- Aktif görev
- Sonraki görev (kilitli)
- İlerleme yüzdesi ve kalan görev sayısı

---

### 4) Kullanıcı Deneyimi
- Basit login (email / geçici auth kabul)
- Kısa başlangıç değerlendirmesi (seviye yoklama)
- Değerlendirme sonucuna göre başlangıç görevinin belirlenmesi
- Görev tamamlama durumu (completed / locked)
- Completion + summary ekranı, tek CTA: sonraki göreve geç(görev bitiminde)
- Ayrı bir AI sayfası (yardım ve açıklama amaçlı, sınırlı kapsamda)
- Basit profil sayfası (Kullanıcının öğrenme özeti ve ilerleme durumu , mini ayarlar, kullanıcı bilgisi)
- AI tarafından üretilen kısa kişisel geri bildirim
- Henüz açılmamış iş ilanları sayfası(yakında)


---

### 5) Teknik Kapsam
- Flutter mobile app
- Backend API (progress, görev durumu)
- AI entegrasyonu (not, ses, feedback)
- Basic analytics (görev başlatıldı / tamamlandı)
- Chatbot sayfası

---

## MVP’DE YOK (OUT OF SCOPE)

### 1) İçerik & Eğitim
- İkiden fazla meslek
- İkiden fazla modül
- Sertifika / rozet / seviye sistemi
- Fiziksel eğitim kitleri

---

### 2) Ürün Özellikleri
- Ödeme sistemi
- Abonelik / pricing
- Offline kullanım
- Gelişmiş profil ekranı

---

### 3) Teknoloji & Scale
- Gerçek zamanlı simülasyon motoru
- Gelişmiş AI değerlendirme skorları
- Admin panel
- B2B özel dashboard

---

## MVP Başarı Kriteri

MVP başarılı sayılır eğer:
- Kullanıcı bir modülü baştan sona tamamlayabiliyorsa
- “Ne yapacağım belli” hissi oluşuyorsa
- En az 30–50 gerçek kullanıcıdan geri bildirim alınıyorsa
- AI not + görev yapısı anlaşılır bulunuyorsa

---

## Scope Değişikliği Kuralı
Bu dokümanda olmayan hiçbir özellik,
MVP tamamlanmadan eklenemez.
