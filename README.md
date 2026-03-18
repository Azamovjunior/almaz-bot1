# 🎮 Free Fire Almaz Bot — To'liq qo'llanma

## 📦 Fayllar
- `bot.py` — Asosiy bot kodi
- `.env` — Barcha kalitlar (TOKEN, API KEY, ADMIN ID)
- `firebase_key.json` — Firebase kalit (siz qo'shishingiz kerak!)
- `requirements.txt` — Kutubxonalar

---

## 🔥 Firebase sozlash (BIR MARTA)

1. https://console.firebase.google.com ga kiring
2. **"Add project"** → Nom bering (masalan: freefire-almaz-bot)
3. **Firestore Database** → "Create database" → "Start in production mode" → "next" → "Enable"
4. **Project Settings** (⚙️ belgisi) → **Service accounts** → **"Generate new private key"** → **"Generate key"**
5. Yuklab olingan `.json` faylni `firebase_key.json` deb o'zgartiring
6. Bot papkasiga qo'ying

---

## 🚀 Ishga tushirish

```bash
# 1. Kutubxonalar o'rnatish
pip install -r requirements.txt

# 2. Botni ishga tushirish
python bot.py
```

---

## 🤖 Bot funksiyalari

### Foydalanuvchilar uchun:
| Funksiya | Tavsif |
|----------|--------|
| 📱 Ro'yxat | Telefon raqam bilan |
| 📢 Obuna | 2 ta majburiy kanal |
| 💎 Almaz ishlash | Har 5 daqiqada +0.2 |
| 👥 Referal | Har do'st = +3 almaz |
| 🏆 Reyting | Top 10 |
| 🤖 AI Maslahat | Free Fire bo'yicha |
| 📱 Telefon sozlamalari | Model yozilsa AI sozlaydi |

### Admin uchun (`/admin`):
| Buyruq | Tavsif |
|--------|--------|
| 📊 Statistika | Jami/aktiv/banned/almaz |
| 📣 Broadcast | Barcha userlarga xabar |
| 🚫 Ban | ID bo'yicha bloklash |
| ✅ Unban | Blokdan chiqarish |
| 💎 Almaz qo'shish | `<user_id> <miqdor>` |
| 👥 Foydalanuvchilar | So'nggi 5 ta |

---

## 🤖 Groq AI nima qiladi?

1. **🎮 O'yin maslahatlari** — Taktika, qurol, pozitsiya
2. **📱 Telefon sozlamalari** — Foydalanuvchi model yozadi → AI optimal sozlamalar beradi
3. **💎 Almaz haqida** — Bot tizimi tushuntiradi
4. **💬 Erkin chat** — Har qanday Free Fire savoli

---

## ⚠️ Muhim

- `.env` va `firebase_key.json` ni **GitHub ga yuklamang!**
- Bot kanallarga **admin** bo'lishi kerak (obuna tekshirish uchun)
