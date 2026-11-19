# EMA Agencies

Static storefront built with HTML, CSS and JavaScript. Serve this directory with any static web server, for example:

```sh
python3 -m http.server 3000 --bind 0.0.0.0
```

## Product imagery

- 30 product/style listings across uniforms, professional coats, PPE and footwear.
- 20 listings use fixed external product-only image URLs. Hero uses a fixed navy scrub flat-lay URL; About and slideshow also use product-only images.
- No random image APIs, model photos, or people imagery are used.
- External image sources are recorded in `assets/image-sources.json`. They are visual references, not proof of EMA stock or brand affiliation. Confirm reproduction permission with the rights holders, or replace with owned/supplier-authorized images before commercial launch.
- External hosting can change or block hotlinking. Failed images show a neutral placeholder directing customers to WhatsApp, never an unrelated photo.
- Local AI-generated product references are retained for the existing ten listings and slideshow. Actual photos, price, sizes, PPE specifications and availability should be confirmed before ordering.

## Logo

The requested `assets/Ema Agencies Medical Wear Banner.png` has not been supplied. Once added at that exact path, the script replaces the text brand with the logo automatically.
