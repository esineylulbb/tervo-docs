# Content Template – Görev (Task)

Bu doküman, Tervo’da her görevin (task) hangi yapı ve sırayla oluşturulacağını tanımlar.
Amaç; tüm görevlerde tutarlı, sahaya dönük ve AI ile uyumlu bir öğrenme deneyimi sağlamaktır.

---

## 1) Görev Tanımı
Her görev:
- Tek bir saha becerisine veya probleme odaklanır
- 10–20 dakika içinde tamamlanabilir
- Bitirildiğinde kullanıcı şunu diyebilmelidir:
  > “Bunu sahada yaparım.”

---

## 2) Görev Bilgileri (Metadata)
Her görev aşağıdaki bilgilerle tanımlanır:

- Görev Adı  
- Bağlı Modül (Yetkinlik Alanı)  
- Tahmini Süre (dk)  
- Zorluk Seviyesi (başlangıç / orta / ileri)  
- Görev Türleri:
  - AI Note
  - Video Görev (opsiyonel)
  - Simulation Görev (opsiyonel)

---

## 3) AI Notes Yapısı (Default)
AI Notes, görevin temel öğrenme katmanıdır ve şu sırayla ilerler:

### a) Ne?
- Bu görevde ne öğrenilecek?
- Hangi problemi çözüyor?

### b) Neden?
- Bu neden önemli?
- Sahada yapılmazsa ne olur?

### c) Nasıl?
- Adım adım temel mantık
- Detaya boğmadan, sahaya dönük

### d) En Sık Yapılan Hata
- Gerçek hayatta en çok nerede hata yapılıyor?
- Bu hatanın sonucu ne olur?

### AI Notes – Visual Usage Rule
- AI Notes görsel içerebilir
- Görseller yalnızca fiziksel veya karışan noktalar için kullanılır
- Her AI Note için maksimum 1–2 görsel eklenir
- Görseller öğrenmeyi destekler, süs amaçlı kullanılmaz

AI Notes kısa, net ve teknisyen diliyle yazılmalıdır.

---

## 4) AI Voice
- AI Notes’un sesli anlatım özelliğidir
- 30–90 saniyelik parçalara bölünebilir
- Okuma zorunlu değildir, dinleyerek ilerlenebilir

---

## 5) Mini Check (Zorunlu)
AI Notes sonrası kısa kontrol adımıdır.

- 1–2 soru veya mini karar görevi
- Amaç: temel kavrayış var mı?
- Puanlama veya geçme/kalma yoktur

Yanlış cevapta:
- AI kısa açıklama yapar
- Gerekirse ilgili AI Note bölümüne geri döndürür

---

### Video Görev (Active, AI-Evaluated)

Video görevler, Tervo’da pasif izleme amacıyla kullanılmaz.  
Bu görevler, kullanıcının sahadaki uygulamasını **kanıtlaması** için tasarlanmıştır.

Video görevlerde süreç şu şekilde ilerler:

- AI, kullanıcıya net ve adım adım talimat verir
- Kullanıcı, bu talimatlara göre kendi videosunu çeker ve yükler
- AI, yüklenen videoyu analiz eder
- Uygulamadaki hata, eksik veya riskli adımlar tespit edilir
- Kullanıcıya açıklayıcı geri bildirim sunulur

Amaç:
- “Bunu izledin mi?” değil  
- **“Bunu yapabiliyor musun?”** sorusuna cevap vermektir.


---

## 7) Simulation Görev (Gerekliyse)
Hikayeleştirilmiş
Simülasyonlar riskli veya kritik hata noktalarında kullanılır.

- Kullanıcıya güvenli hata yapma alanı sunar
- İlk versiyonlarda decision-based simülasyon kabul edilir
- Amaç: refleks kazandırmak

---

## 8) Completion + Summary (Zorunlu)
Görev tamamlandığında gösterilir.

Bu ekranda:
- 1–2 cümlelik “ne öğrendin” özeti
- En kritik dikkat noktası
- Bu bilginin sahadaki karşılığı

Yeni bilgi verilmez, öğrenme pekiştirilir.

---

## 9) Next Best Step
Görev sonrası sistem:
- bir sonraki uygun görevi önerir
- kullanıcıyı ana sayfaya geri yönlendirir

Kullanıcı seçim yapmak zorunda bırakılmaz.

---

## 10) Kalite Kuralları
- Teknik ama sade dil
- Akademik anlatım yok
- Usta–çırak tonu
- Gereksiz uzunluk yok
- Bilinmeyen noktada uydurma yok

