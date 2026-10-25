# Avocam

The website of Avocam, a nursery in Dschang, Cameroon that sells premium
grafted fruit seedlings (Hass avocado, citrus and more) and offers orchard
management advice. Live at [avocam.cm](https://avocam.cm).

The site is a single static page with sections for the plants on offer,
services, common planting mistakes, an FAQ, and a contact section that opens a
WhatsApp chat. It includes schema.org structured data and meta tags for search
engines.

## Tech

- One `index.html` with inline CSS and a small inline script
- Google Fonts and Font Awesome from their CDNs
- No framework, no build step

## Run it locally

```bash
git clone https://github.com/NinjaShadowBoy/avocam.git
cd avocam
```

Open `index.html` in a browser, or serve the folder so paths behave exactly as
in production:

```bash
python3 -m http.server 8000      # then visit http://localhost:8000
```

## Files

```
index.html                     the whole site
assets/images/                 logo and hero image
googled360c42a59a356ae.html    Google Search Console verification, keep it
```

## Deploying

Any static host works: upload the repository contents as they are.
