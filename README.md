# Nowhow — nowhow srl

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `nowhow.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/nowhow.mjs`).
> To change the content, edit that file and run `node build.mjs nowhow` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@nowhow.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($€[AMOUNT] / $€[AMOUNT] / $Declined) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
We are Nowhow, an IT consultancy based in Nazareth-De Pinte in East Flanders, working since 2008 on computer consultancy, the management of computer facilities and related information services. Running somebody else's systems means handling their personal data, and two things follow that are worth being precise about. The first is that you remain the controller and we act as your processor, which is not a label either of us chooses: under the data protection rules, a processor that starts deciding what data is used for becomes a controller for that processing, with every obligation attached. So a written processing agreement is not paperwork, it is what keeps the roles where both parties think they are. The second is the clock when something goes wrong. A controller has seventy-two hours to notify the supervisory authority, while a processor must tell the controller without undue delay, which in practice means immediately, because your deadline starts when we tell you. Since October 2024 the Belgian network and information security rules also bring managed service providers into scope, with an early warning inside twenty-four hours and accountability sitting with the management body. Site: nowhow.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
