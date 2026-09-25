# Tindahan POS — Print Waybill Clone

Ginaya mula sa http://printwaybill.lovable.app/ pero mas kumpleto.

## Features
- ✅ POS Terminal (search, cart, checkout)
- ✅ Products CRUD (localStorage)
- ✅ Waybill Printer 100x150mm — J&T, Flash, LBC, Shopee, TikTok, Lazada, Ninja Van
- ✅ Real Barcode (JsBarcode) + QR Code
- ✅ COD / NON-COD badge
- ✅ Receipt 58mm/80mm thermal print
- ✅ From/To sender/receiver layout
- ✅ No backend — pure frontend, GitHub Pages ready

## Paano i-upload sa GitHub para unli edit

1. **Download ZIP** na binigay ni Meta AI (o save `index.html` as file)
2. Punta sa https://github.com/new
   - Repository name: `printwaybill-clone`
   - Public → Create repository
3. Click **Add file → Upload files** → drag `index.html` + `README.md`
4. **Commit**
5. Punta sa **Settings → Pages**
   - Branch: `main` → `/ (root)` → Save
6. After 1-2 minutes live na sa `https://USERNAME.github.io/printwaybill-clone/`

## Paano mag-edit ng unli?

- Sa GitHub mismo: Click file → pencil icon (Edit) → Commit changes
- O i-clone sa VS Code:
```bash
git clone https://github.com/USERNAME/printwaybill-clone.git
cd printwaybill-clone
# edit index.html
git add .
git commit -m "update"
git push
```

## Printing Tips

- **Receipt**: Use 80mm thermal printer, Chrome → Print → Paper: 80mm
- **Waybill**: Use 100x150mm sticker printer (thermal). Sa Chrome print dialog, set Paper size to 100x150mm or A6, margins: None.

## Tech
- Tailwind CDN
- JsBarcode for real scannable barcode
- QRCode.js
- Vanilla JS + localStorage (no build step)

Made with ❤️ for PH sellers.
