# Mozaik theme documentation

Mozaik is an Online Store 2.0 theme for **fashion and apparel** stores. It is built without third-party JavaScript libraries and ships with English and Turkish translations.

## 1. Getting started

1. In the Shopify admin, go to **Online Store → Themes** and add Mozaik.
2. Click **Customize** to open the theme editor.
3. Create your menus in **Content → Menus**: `main-menu` for the header and `footer` for the footer. A menu with three levels becomes a mega menu automatically.
4. Set up the pages listed in the checklist below.

### Setup checklist

- **Contact page:** create a page and assign the `page.contact` template.
- **FAQ page:** create a page and assign the `page.faq` template.
- **Size guide:** create a page with your size chart and select it in the product page **Size guide** block. To use a different chart for one product, set the `custom.size_guide` product metafield.
- **Personalized products:** assign the `product.personalized` template to products that accept a custom text (for example embroidery or printing).
- **Gift wrap:** create a product named "Gift wrap" and select it in **Theme settings → Cart**.
- **Filters:** install the Shopify **Search & Discovery** app and add filters such as size, color and price. Add complementary products there to fill the "Pairs well with" block.

## 2. Product information (metafields)

Define these product metafields in **Settings → Custom data → Products**. Empty fields are hidden on the storefront.

| Metafield | Type | Shown in |
|---|---|---|
| `custom.material` | Single line text | Product page tab and product card |
| `custom.fit` | Multi-line text | Product page tab |
| `custom.care_instructions` | Multi-line text | Product page tab |
| `custom.size_guide` | Page reference | Size guide drawer |

## 3. Theme settings

| Group | What it controls |
|---|---|
| Colors | Color schemes used by every section |
| Typography | Heading and body fonts, font scale |
| Layout | Page width, section spacing, corner radius, reveal on scroll |
| Product cards | Image ratio, card style, second image on hover, vendor, rating, color swatches, quick add, material line, sale and "New" badges |
| Cart | Drawer or page, free shipping threshold, order note, gift wrap, recommendations collection |
| Pricing and payments | "Taxes included" note, installment message |
| Search | Predictive search |
| Recently viewed products | Turn product tracking on or off |
| WhatsApp | Floating button and "order on WhatsApp" product button |
| Privacy (KVKK / GDPR) | Cookie consent banner, connected to the Shopify Customer Privacy API |
| Social media | Profile links used in the footer and menu drawer |
| Favicon and misc | Favicon, default social share image, back-to-top button |

## 4. Sections

Every section below can be added from **Add section** in the theme editor.

- **Hero and campaigns:** Slideshow, Image banner, Promo grid, Countdown / campaign, Announcement bar
- **Products:** Featured collection, Featured product, Product recommendations, Recently viewed, Shoppable image, Comparison table
- **Content:** Rich text, Image with text, Multicolumn / USP, Video, Testimonials, FAQ, Logo list / brands, Blog posts, Collection list, Newsletter, Contact form
- **Developer:** Custom Liquid, Apps

### Product page blocks

Vendor, Title, SKU, Rating, Price (with Shop Pay Installments), Variant picker (buttons, swatches or dropdown), Size guide, Inventory status, Quantity selector, Buy buttons (dynamic checkout, gift card recipient form, local pickup availability), Delivery estimate, Trust badges, Description, Material and care, Collapsible tab, Custom field, Share, Custom Liquid, and app blocks.

## 5. Images

All image settings support the focal point you set in **Content → Files**. Recommended sizes:

| Section | Size |
|---|---|
| Slideshow and Image banner | 2400 × 1200 px |
| Product images | 1600 × 2000 px (4:5) |
| Collection images | 1200 × 1500 px |

## 6. Languages

The theme includes English (`en.default.json`) and Turkish (`tr.json`). Add a language in **Settings → Languages**; theme texts switch automatically. You can edit any text in **Online Store → Themes → … → Edit default theme content**.

## 7. Support

Open a support request at https://github.com/fatihhkaya/mozaik-theme-docs/issues/new/choose. Please include your store URL, the theme version and steps to reproduce the issue. We answer within two business days.

Support covers theme setup and bugs in the theme code. It does not cover custom code changes or third-party apps.
