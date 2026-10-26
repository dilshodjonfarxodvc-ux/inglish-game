# 🐝 Bee English

Bolalar uchun ingliz tilini o'yin orqali o'rganish sayti (React + Vite).
Ranglar: qora, sariq, oq.

## Ishga tushirish

```bash
npm install
npm run dev      # sinov uchun (http://localhost:5173)
npm run build    # tayyor sayt dist/ papkasiga chiqadi
```

## O'yinlar

1. **Rasmni top** — rasmga mos inglizcha so'zni tanlash
2. **Eshit va tanla** — so'zni eshitib, to'g'ri rasmni topish
3. **Xotira o'yini** — rasm va so'z juftlarini topish
4. **So'z tuz** — aralash harflardan so'z yig'ish

Yutuqlar (⭐ yulduzlar va daraja) brauzerda saqlanadi.

## Yangi so'z qo'shish

`src/data.js` faylini oching va kerakli mavzuga qator qo'shing:

```js
{ en: "tiger", uz: "yo'lbars", e: "🐯" },
```

## Deploy

`npm run build` dan keyin `dist/` papkasini Netlify, Vercel yoki GitHub Pages ga yuklang.
