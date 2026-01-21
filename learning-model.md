# Tervo Learning Model (AI-native)

## 1) Core Idea
Tervo bir “video kurs platformu” değildir.  
Tervo, teknisyenlerin hızlı ve doğru öğrenmesi için tasarlanmış **AI-native bir öğrenme motorudur**.

Default öğrenme katmanı:
- **AI Notes (yapılandırılmış notlar)**
- **AI Voice (usta gibi sesli anlatım)**
- **Task-based validation (görevlerle doğrulama)**

Video ve simülasyon:
- her yerde değil,
- **sadece öğrenmeye maksimum etki kattığı yerde** kullanılır.

---

## 2) Learning Components (4 parça)
### A) AI Notes + AI Voice (Default)
- Kısa, net, sahaya dönük
- “Ne?”, “Neden?”, “Nasıl?”, “En sık hata?” şeklinde yapılandırılmış
- Belli bir sıra ile ilerliyor ve temel öğrenme fikri, bu katman olmadan görevlere geçilmez

### B) Video Tasks (Selective)
- Deneyim gerektiren kritik adımlar için
- “Sahada nasıl yapılır?” anlarında devreye girer
- Pasif izleme yerine kullanıcının video çekmesini bekler ve hata bildirimi yapar

### C) Simulation Tasks (High Impact)
- Riskli / kritik hata noktalarında
- Kullanıcıya güvenli hata yapma alanı verir
- İlk versiyonlarda “decision-based” simülasyon da kabul edilir

---

## 3) Task Flow (Örnek Akış)
Bir modül tipik olarak şu sırayla ilerler:

1. **AI Notes + AI Voice**
2. **Mini check (1–2 soru / kısa görev)**
3. **Video Task (gerekliyse)**
4. **Simulation Task (gerekliyse)**
5. **Completion + summary**
6. **Next best step önerisi**

Amaç:
- “bitirdim” hissi
- “neden böyle?” sorusuna cevap
- “şimdi sahada ne yapacağım?” netliği

---


## 4) Homepage Philosophy

Tervo’nun ana sayfası bir kurs listesi veya içerik kataloğu değildir.  
Ana sayfa, kullanıcının öğrenme sürecini yöneten **görev bazlı bir ilerleme merkezidir**.

Ana sayfanın temel amacı:
**Kullanıcıya her an “şu an ne yapmalıyım?” sorusunun tek ve net cevabını vermektir.**

---

### Task-First Experience
Tervo’da öğrenme görevler üzerinden ilerler.  
Ana sayfa görev türlerini (AI not, video, simülasyon) ayırt etmez veya göstermez.

Kullanıcı ana sayfada yalnızca şunları görür:
- aktif görev
- tamamlanan önceki görev
- sıradaki kilitli görev

Görevin nasıl öğretildiği sistemin sorumluluğudur, kullanıcının değil.

---

### Single Primary Action
Ana sayfada **tek bir ana aksiyon** bulunur:

> **Görevi Başlat / Devam Et**

Birden fazla çağrı, görev listeleri veya alternatif yollar ana sayfada yer almaz.  
Bu yaklaşım karar yorgunluğunu azaltır ve öğrenme akışını hızlandırır.

---

### Guided Progress
Ana sayfa kullanıcıdan seçim yapmasını beklemez.  
Sistem, kullanıcının ilerlemesine göre **en doğru sonraki görevi** otomatik olarak belirler.

Kullanıcı, başı ve sonu olan bir öğrenme yolunun üzerinde ilerlediğini hisseder.

---

### Progress Visibility
Ana sayfa içerik miktarını değil, **ilerlemeyi** gösterir.

Ana sayfada:
- aktif modül adı
- toplam ilerleme yüzdesi
- kalan görev sayısı ve yaklaşık süre

yer alır.

Bu bilgiler kullanıcıya kontrol ve motivasyon hissi verir.

---

### Transparency Without Complexity
Kullanıcı:
- nerede olduğunu
- neyi tamamladığını
- sırada ne olduğunu
bilir.

Ancak görev türleri, teknik detaylar ve sistem içi karmaşıklık
ana sayfada gösterilmez.

---

### Intended User Feeling
Ana sayfaya giren bir kullanıcı şunu hissetmelidir:

> “Ne yapacağım belli.  
> Nerede olduğumu biliyorum.  
> Devam edebilirim.”


## 5) Quality Rules (Uyduruk Durmasın Diye)
AI içeriğin kalitesi şu prensiplerle korunur:
- **Teknisyen dili** (usta-çırak tonu)
- **Kısa ve net** anlatım (laf kalabalığı yok)
- **Örnek + hata odaklı** (en sık yapılan hatalar mutlaka)
- **Doğruluk önceliği** (bilinmeyen şeyde “bunu sahada şöyle doğrularız” yaklaşımı)

---

## 6) What Success Looks Like
Bu model başarılıysa kullanıcı şunu der:
- “Video izlemek zorunda kalmadan anladım.”
- “Sahada yapacağım şey netleşti.”
- “Eksik olduğum yeri direkt bulup düzeltti.”

---

## 7) Scope Note
Bu doküman Tervo'nun öğrenme modelini tanımlar.  
