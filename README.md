# Writing BS

100 kunlik, kuniga 25 daqiqalik yozish tizimi (top universitetlar uchun personal statement va umumiy yozish mahorati).

## Imkoniyatlar
- 100 kunlik reja (Dushanba-Yakshanba), har kuni vazifa + bugungi dars (48 ta ichki dars, misollar va mini mashqlar bilan)
- 25 daqiqalik taymer (tovush, tebranish, bildirishnoma)
- Yozuv Banki, matn tahlilchisi: statistika + tuzilma tekshiruvi (inglizcha matn uchun)
- Har kunga 1-10 ball; tracking: zanjir, xarita, grafiklar, maslahatlar
- Tashqi feedback so'rovi va baholash aniqligi tahlili
- Zaxira: nusxalash, faylga saqlash (.json), fayldan tiklash
- Oflayn ishlaydi (PWA)

## GitHub Pages
1. Repository ildiziga yuklang: `index.html`, `manifest.webmanifest`, `sw.js`, `icons/` (papka bilan).
2. Settings > Pages > Deploy from a branch > `main` / root.
3. `https://<username>.github.io/<repo>/` manzilida oching.

## Android'ga o'rnatish
1. Havolani **Chrome**'da oching (Telegram/Instagram ichki brauzerida emas).
2. Sahifani bir marta yangilang (service worker faollashishi uchun).
3. Menyu (3 nuqta) > **Install app** yoki **Add to Home screen** > ochilgan oynada **Install** ni tanlang (Create shortcut emas).
4. Oldin yorliq qo'shilgan bo'lsa, uni o'chirib, qaytadan o'rnating.

## Tekshiruv
O'rnatish chiqmasa, `https://<username>.github.io/<repo>/diag.html` ni Chrome'da oching: qaysi shart bajarilmayotgani ko'rsatiladi.

## Muhim
- Ma'lumotlar faqat shu qurilma brauzerida saqlanadi. "Natija" sahifasidagi zaxirani vaqti-vaqti bilan oling.
- Yangilangandan keyin eski versiya ko'rinsa, `sw.js` ichidagi `wbs-v8` nomini oshiring.
