# ផ្ទះសូកូឡាំ | The Chocolate Home

Premium beverage ingredient supplier website — Battambang, Cambodia.

**Live site:** [your-domain.com](https://your-domain.com)

## Products
- Cacao Powder · Matcha · Green Tea · Red Tea
- Black Coffee (Robusta) · Durian Coffee · Coconut Coffee
- Cream Cheese Powder · We Creamer

## Contact
📞 085 25 8888 / 012 21 18 29 / 097 402 98 98  
📍 Battambang, Cambodia  
📘 [Facebook Page](https://www.facebook.com/share/1EX751G6xx/?mibextid=wwXIfr)

---

## Deploy to Cloudflare Pages

1. Push this repo to GitHub
2. Go to [Cloudflare Pages](https://pages.cloudflare.com) → Create a Project
3. Connect your GitHub repo
4. Build settings:
   - **Framework preset:** None
   - **Build command:** *(leave empty)*
   - **Build output directory:** `/` (root)
5. Click **Save and Deploy**

## Connect Custom Domain

1. In Cloudflare Pages → your project → **Custom domains**
2. Add your domain (e.g. `chocolatehome.com`)
3. Follow DNS instructions (add CNAME record pointing to `<project>.pages.dev`)
4. SSL is automatic — done!

## File Structure

```
chocolate-home/
├── index.html        ← main website
├── favicon.png       ← site icon
└── images/           ← all product images
    ├── SWC_9X10_10karea_T.jpg   (Cacao Powder)
    ├── SWC_9X10_10karea_Y.jpg   (Matcha)
    ├── SWC_9X10_karea_C.jpg     (Green Tea)
    ├── SWC_9X10_10karea_P.jpg   (Black Coffee)
    ├── SWC_9X10_10karea_J.jpg   (Durian Coffee)
    ├── SWC_9X10_10karea_V__2_.jpg (Cream Cheese 1kg)
    ├── SWC_9X10_10karea_V.jpg   (Cream Cheese 500g)
    ├── SWC_9X10_10karea_X.jpg   (We Creamer)
    ├── SWC_9X10_10karea_Z.jpg   (Red Tea)
    ├── SWC_9X10_20karea_D.jpg   (Coconut Coffee)
    ├── SWC_9x10_11W.jpg         (Brand/About)
    └── photo_2026-06-10_10-26-30.jpg (Logo)
```
