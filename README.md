# Tom Malfait — advocaat tom malfait bv

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `advocaattommalfait.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/advocaattommalfait.mjs`).
> To change the content, edit that file and run `node build.mjs advocaattommalfait` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@advocaattommalfait.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($€[AMOUNT] / $€[AMOUNT] / $Prohibited) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
We are the practice of Tom Malfait, a lawyer in Ghent working since 2010. The rules on what a lawyer may say publicly exclude success rates, comparisons with other practitioners, client testimonials and any promise about an outcome, so what belongs on a page like this is the arithmetic nobody sets out before a case starts. When you win in Belgium, the losing party pays a procedural indemnity towards your legal costs. It is a lump sum fixed by royal decree according to the value of the dispute, within a range the court can move inside on a reasoned request, and it is a contribution rather than reimbursement. It rarely equals what a case actually cost, which means winning and still being out of pocket is an ordinary outcome rather than a surprise. The same figure runs the other way and matters more: if you lose, you pay the other side's indemnity on top of your own lawyer. That number ought to be in front of you before a decision to litigate, not after. Two other things get said at the first meeting: whether you may qualify for legal aid, and whether your legal expenses insurance covers this, in which case you choose the lawyer, not the insurer. Site: advocaattommalfait.shop
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
