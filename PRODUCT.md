# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

- **Primary: couples getting married and event organizers** (confirmed). They are planning a wedding or event in Costa Rica and are deciding which extras are worth paying for. Their job: find out how live same-day magnets work at an event, trust that it will look good, and book a conversation to get a quote.
- **Secondary (from the catalog and Instagram, not ranked by the owner):** people buying a personal gift (anniversaries, Valentine's Day, Mother's Day); people who want their own photos of family, pets or a baby on the fridge; parents who buy the Dinofabeto or Matesaurios for children who are learning.
- **How they arrive** (confirmed): mostly from Instagram (@vinculos_eternos_cr), on a phone. Expect a phone, a short attention span, and a visitor who has already seen the product in a post.

## Product Purpose

Vínculos Eternos turns photos into objects that stay in sight: photo magnets, metal shapes, lithophane lamps, and calendars with music. The concept, which is binding:

> Vivimos en una época donde acumulamos miles de fotografías, pero dedicamos cada vez menos tiempo a recordar. Vínculos Eternos existe para devolver presencia a los momentos que realmente importan. No vendemos imanes. Ayudamos a las personas a detenerse un momento y recordar lo que realmente importa.

Success on the website means three things:
- A couple asks for a wedding meeting or quote.
- A catalog visitor sends a complete order (products plus delivery) to WhatsApp.

## Positioning

**Live magnets at weddings** (confirmed as the main differentiator). At the wedding they photograph the guests or the couple. Each person picks the photo where they look best, and minutes later they hold their magnet. No days, no weeks: the same day, at the event. The key line: the whole wedding is for everyone else, so what is left for the couple? The couple must take theirs home.

## Operating Context

- **Ordering:** visitors build an order in a cart on the site. The cart opens WhatsApp (+506 7182 1161) with the summary already written, and the photos are sent there in HD or as files.
- **Payment:** SINPE Móvil or bank transfer.
  - A 50 % deposit is required. The order does not start without it.
  - The rest is paid on delivery, or before shipping by Correos or Uber.
- **Delivery:**
  - Free in San Pedro and Barrio Dent.
  - Anywhere else goes by Correos de Costa Rica or Uber, and the shipping cost is charged.
  - Orders take about 1 week.
- **Events:** quoted one by one. A meeting is requested from the site, Monday to Friday, 6–8 p.m. A Google Calendar booking page is planned but not created yet (`BOOKING_URL` in `index.html`).
- **Photos:** clear and square, or able to be cropped square.

## Capabilities and Constraints

- **Code:** a single static file, `index.html`, with hash routes for its pages:
  - `#inicio`
  - `#catalogo`, with product detail dialogs and the 3 steps to order
  - `#ideas`
  - `#eventos`
  - `#nosotros`
  - `#preguntas`, with contact
- **Hosting and payments:** no domain or hosting yet. No online payments or photo uploads; both were discussed and deferred.
- **Prices** are set in the `PRODUCTS` array in `index.html`:

  | Product | Price |
  |---|---|
  | Photo magnets | 1–4 ₡1 700 each · 5–9 ₡1 500 · 10–19 ₡1 300 · 20+ ₡1 200 |
  | Gift wrap (optional) | ₡1 000, one per order |
  | Dinofabeto | ₡22 500 |
  | Matesaurios | ₡13 000 / ₡18 000 / ₡27 500 |
  | Metal shapes | Heart ₡10 000 · Cat ₡5 000 |
  | Lithophane lamps | ₡25 000 / ₡30 000 / ₡37 000 |
  | Annual calendar | ₡3 500 |
  | Monthly calendar | ₡800, minimum 4 |
  | Songs on calendars (optional) | ₡500 each |
  | Weddings and events | Quoted per event |

- **Language:** Spanish (Costa Rica). Informal "tú" with customers; "ustedes" for couples.

## Brand Commitments

- **Name and tagline:** "Vínculos Eternos · Fotografía encapsulada". Mascot: **Kipi** (one P). Do not use the nickname "Sparky".
- **Concepts to express, not copy literally:** "La chispa que nos une" and "Recuerdos que brillan".
- **Brand manual:** `brand-kit/`, guide in `brand-kit/BRANDING-VINCULOS-ETERNOS.md`.
  - Colors: Rosa Vínculo #825050, Aura #F5D6D3, Destello #F9F0E8, Recuerdo #3F1E1E, Conexión #913F3F.
  - Fonts: Poppins (titles in ExtraBold) and ZT Otez (subtitles).
  - Kipi contrast rule: red beret on light backgrounds, pink beret with a cream body on dark ones. Never Kipi on a background of its own color.
- **Voice:** warm and close. Do not repeat "hecho a mano", "uno por uno" or "Costa Rica" often; they are not the main message.

## Evidence on Hand

- **Photos:**
  - `assets/img/`: wedding (couple holding their magnet), Dinofabeto, husky puppy magnet, graduation, gift.
  - `assets/brand/`: brand assets (Kipi, logos, packaging mockup).
  - Most catalog and idea cards still use Kipi placeholders. The owner will send more product photos later. Do not fabricate product imagery.
- **Real reviews:** six of them, on the "Sobre nosotros" page and in the brand guide. Karo, Kattya, Dani (a wedding guest, on Instagram), María Paula, Tami and Katia. Do not invent more.
- **Founder story:** Mary started in 2025. The approved text is on the "Sobre nosotros" page.
- **Pending:** a wedding explainer video from the owner, a photo of Dani's magnet, and the Google Calendar booking link.

## Product Principles

1. Weddings first. The live, same-day magnet is what nobody else offers; it should be easy to find and easy to book.
2. Remembering, not merchandise. Every page should feel like it is about the moment, not the object.
3. Phone first. Visitors come from Instagram on a phone; everything must work one-handed and fast.
4. No dead ends. Every page leads to WhatsApp, the cart, or a booking request.
5. Honest placeholders. Missing photos stay visibly "próximamente" until real ones arrive.
