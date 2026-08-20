# حیسابکەری بڕینی پەرگۆلا — Pergola Kesim Hesabı

```
index.html      سایتەکە — تاکە فایل (React لەناویدایە)
logo-icon.png   ئایکۆنی تابەکە
```

هیچ بیلدێک، هیچ `npm install`ێک، هیچ سێرڤەرێک ناوێت. فایلێکی ستاتیکی
سەربەخۆیە — دەتوانیت ڕاستەوخۆ لە وێبگەڕەکەشدا بیکەیتەوە.
تەنها شتی دەرەکی فۆنتی Zain ـە لە Google Fonts.

## بڵاوکردنەوە لەسەر Cloudflare Pages

1. Cloudflare Dashboard → **Workers & Pages** → **Create** → **Pages** →
   **Connect to Git**
2. ئەم ڕیپۆیە هەڵبژێرە: `wlat_shade-brin-pergola`
3. لە Build settings هیچ مەگۆڕە:
   - Framework preset: **None**
   - Build command: **بەتاڵ**
   - Build output directory: `/`
4. **Save and Deploy**

دوای چەند چرکەیەک لەسەر `<ناوی-پڕۆژە>.pages.dev` دەبێت.
دۆمەینی خۆت لە **Custom domains** زیاد بکە.

## تێبینی

- ئەگەر نەتەوێت گووگڵ ئەم لاپەڕەیە ئیندێکس بکات، ئەم دێڕە زیاد بکە
  لەناو `<head>` ی `index.html`:
  `<meta name="robots" content="noindex" />`
- بۆ نوێکردنەوەی سایتەکە: `index.html` بگۆڕە و push بکە — Cloudflare
  خۆکارانە دووبارە بڵاوی دەکاتەوە.
