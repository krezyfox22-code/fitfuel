# 📲 FitFuel — Samsung Telefoningizga O'rnatish

## 🚀 1-qadam: GitHub'ga yuklash (bepul hosting)

### GitHub accountingiz bo'lsa:

1. **GitHub.com** ga kiring
2. **"New repository"** bosing → nomini `fitfuel` qiling
3. `daily-calory` papkadagi barcha fayllarni yuklang:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icons/` papkasi (barcha rasmlar bilan)

4. **Settings** → **Pages** → Source: `main` branch → **Save**
5. 1-2 daqiqada saytingiz tayyor bo'ladi: `https://SIZNING_USERNAME.github.io/fitfuel/`

---

## 📱 2-qadam: Samsung telefoningizga o'rnatish

1. Samsung telefoningizda **Chrome** brauzerini oching
2. Yuqoridagi havolani kiriting
3. Chrome avtomatik ravishda **"Ilovani o'rnating"** degan banner ko'rsatadi
4. Yoki Chrome menyusidan (⋮) → **"Bosh ekranga qo'shish"** bosing
5. **"O'rnatish"** bosing

✅ **Tayyor!** Endi FitFuel telefoningizda alohida ilova sifatida ishlaydi:
- Brauzer ko'rinmaydi
- O'z ikonkasi bilan
- Offline ham ishlaydi
- Ovqat vaqtlarida notification keladi
- Vibration bilan eslatadi

---

## 📂 Fayllar

```
daily-calory/
├── index.html      ← Asosiy ilova
├── manifest.json   ← PWA sozlamalari
├── sw.js           ← Offline ishlash uchun
└── icons/
    ├── icon-72.png
    ├── icon-96.png
    ├── icon-128.png
    ├── icon-144.png
    ├── icon-152.png
    ├── icon-192.png
    ├── icon-384.png
    └── icon-512.png
```
