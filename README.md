<div align="center">

# 🎓 Orzane

**Yapay zeka destekli dijital dil öğrenme çalışma alanı**

Poliglotların kullandığı kanıtlanmış teknikleri yapay zeka ile birleştiren,
tamamen bilgisayarınızda çalışan masaüstü uygulaması.

[📥 Windows için İndir](https://github.com/berkeyigit/orzane-releases/releases/latest/download/Orzane_0.1.0_x64-setup.exe) · [🌐 orzane.com](https://orzane.com)

</div>

---

## Orzane Nedir?

Orzane, dil öğrenme sürecinizi tek bir çalışma alanında toplayan masaüstü uygulamasıdır. Günlük yazma, dinleme pratiği, okuma, not tutma ve ilerleme takibi gibi farklı teknikleri yapay zeka desteğiyle bir araya getirir.

Duolingo gibi oyunlaştırılmış bir test uygulaması değil — gerçek hayatta kullanacağınız becerileri geliştiren, poliglotların yıllardır uyguladığı yöntemleri modern AI ile destekleyen bir araçtır.

## ✍️ Günlük Yazma (Daily Diary)

Her gün öğrendiğiniz dilde günlük yazın. Groq'un yapay zekası yazınızı analiz eder:

- **Gramer puanı** — 100 üzerinden anlık değerlendirme
- **Hata sınıflandırması** — Zaman uyumsuzluğu, özne-yüklem uyumu, kelime seçimi, yazım hataları
- **Skill tree entegrasyonu** — Bildiğiniz konulardaki hatalar "error", bilmediğiniz konulardakiler "warning" olarak işaretlenir
- **Türkçe kelime tespiti** — İngilizce içinde kullandığınız Türkçe kelimeler çevirisiyle gösterilir
- **Hata trendi grafiği** — Zaman içinde gelişiminizi takip edin

## 🎧 Podcast Dinleme

Seviyenize uygun metinler AI tarafından üretilir ve doğal ses ile okunur:

- **Dinle & Özetle** — Metni dinleyin, kendi kelimelerinizle özetleyin, AI özetinizi değerlendirsin
- **Dinle & Cevapla** — Metni dinleyin, anlama sorularını sesli cevaplayın
- **Dinle & Tekrarla** — Shadowing tekniği ile eş zamanlı tekrarlayın

A1'den C1'e seviyeye uyarlanmış içerik. Microsoft Edge Neural Voices ile doğal TTS.

## 📖 Okuma Pratiği

Seviyenize göre üretilmiş İngilizce metinleri okuyup Türkçeye çevirin. AI çevirinizi değerlendirir.

## 📝 Sokratik Notebook

Öğrenirken not tutun, AI notlarınızdan soru üretsin:

- Konu bazlı klasör yapısı
- 💡 Sokratik Analiz — notlarınızı ne kadar anladığınızı test eden sorular
- Takip soruları — yanlış cevapladığınızda derinleştirici sorular

## 📊 Seviye Testi

15 adaptif soruyla A1'den C2'ye seviyenizi belirleyin. Sonuçlar skill tree'yi şekillendirir — güçlü ve zayıf konularınız otomatik belirlenir.

## 📚 Kütüphane & Medya Takibi

- Okuduğunuz kitapları sürükle-bırak raflarla düzenleyin
- İzlediğiniz film, dizi ve animeleri takip edin, puanlayın
- İlerlemenizi görselleştirin

## 🔒 Gizlilik & Güvenlik

- **Tamamen lokal** — Sunucuya veri gönderilmez, tüm verileriniz bilgisayarınızda kalır
- **BYOK (Kendi Anahtarını Getir)** — Kendi Groq API anahtarınızı kullanırsınız
- **Açık mimari** — Backend ve frontend bilgisayarınızda çalışır, arada sunucu yoktur

## 🔧 Teknik Detaylar

| Bileşen | Teknoloji |
|---------|-----------|
| Masaüstü | Tauri v2 (Rust) |
| Frontend | React + Vite |
| Backend | FastAPI + SQLite |
| Yapay Zeka | Groq API — Llama 3.3 70B |
| Ses | Microsoft Edge Neural Voices (edge-tts) |
| Güncelleme | Tauri auto-updater (imzalı) |

## 📥 Kurulum

1. [Orzane_0.1.0_x64-setup.exe](https://github.com/berkeyigit/orzane-releases/releases/latest/download/Orzane_0.1.0_x64-setup.exe) dosyasını indirin
2. Installer'ı çalıştırın (EULA kabul edin)
3. Orzane'ı açın → hesap oluşturun
4. Ayarlar → Groq API anahtarınızı girin ([console.groq.com](https://console.groq.com/keys) adresinden ücretsiz alabilirsiniz)
5. Günlük yazmaya başlayın!

## 🗓 Gereksinimler

- Windows 10 (21H2+) veya Windows 11
- İnternet bağlantısı (Groq API + TTS için)
- Groq API anahtarı (ücretsiz)

## 📄 Lisans

Tüm haklar saklıdır. Kişisel kullanım için lisanslanmıştır.

---

<div align="center">

**[orzane.com](https://orzane.com)** · Berke tarafından geliştirildi

</div>
