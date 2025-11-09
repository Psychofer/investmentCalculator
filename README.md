# 💰 Yatırım Hesaplayıcısı (Investment Calculator)

Kullanıcının belirlediği yatırım tutarı, yıllık ek yatırım, beklenen getiri oranı ve yatırım süresine göre **yıllar içerisindeki yatırım değerini hesaplayan** React tabanlı bir web uygulaması.

**🔗 Canlı Demo:** [https://psychofer.github.io/investmentCalculator/](https://psychofer.github.io/investmentCalculator/)

---

## 🚀 Özellikler

- ✅ Başlangıç yatırım tutarına göre hesaplama
- ✅ Yıllık yatırım ekleme desteği
- ✅ Faiz getirisi ve toplam yatırımın yıllık gösterimi
- ✅ Türk Lirası formatında sonuçlandırma
- ✅ Gerçek zamanlı güncelleme
- ✅ Form doğrulama (minimum 1 yıl)
- ✅ Responsive tasarım

---

## 🛠️ Kullanılan Teknolojiler

| Teknoloji | Açıklama |
|-----------|----------|
| **React** | Component tabanlı UI geliştirme |
| **Vite** | Hızlı geliştirme ortamı ve build aracı |
| **JavaScript** | Uygulama mantığı |
| **CSS** | Arayüz stil tasarımı |

---

## 📦 Kurulum

### 1️⃣ Projeyi Klonlayın

```bash
git clone https://github.com/Psychofer/investmentCalculator.git
cd investmentCalculator
```

### 2️⃣ Gerekli Paketleri Kurun

```bash
npm install
```

### 3️⃣ Geliştirme Ortamını Başlatın

```bash
npm run dev
```

### 4️⃣ Production Build Alın

```bash
npm run build
```

### 5️⃣ GitHub Pages'e Deploy Edin

```bash
npm run deploy
```

---

## 🧮 Hesaplama Mantığı

Uygulama, her yıl için aşağıdaki hesaplamaları yapar:

1. **Faiz Getirisi** → `mevcut değer × (getiri oranı / 100)`
2. **Yeni Yatırım** → Yıllık yatırım tutarı eklenir
3. **Yeni Toplam** → Önceki değer + faiz + yeni yatırım

Tüm para değerleri `Intl.NumberFormat` ile **Türk Lirası (₺)** formatında gösterilir.

---

## 📁 Proje Yapısı

```
investmentCalculator/
├── src/
│   ├── components/
│   │   ├── Header.jsx
│   │   ├── UserInput.jsx
│   │   └── Results.jsx
│   ├── util/
│   │   └── investment.js
│   ├── assets/
│   │   └── investment-calculator-logo.png
│   ├── App.jsx
│   └── index.jsx
├── public/
│   └── index.html
├── package.json
├── vite.config.js
└── README.md
```

---

## 📝 Lisans

Bu proje **eğitim amaçlı** geliştirilmiştir ve herkes tarafından özgürce kullanılabilir. ✅

---

## ✨ Geliştirici

**👤 Ferhat ÖLMEZ**  
🎓 Atatürk Üniversitesi — Yazılım Mühendisliği  
📌 Vite + React Projesi

---

