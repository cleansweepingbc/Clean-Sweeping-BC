# Clean Sweeping Parrott — Website

Premium cleaning services website for **Clean Sweeping Parrott**, serving the Lower Mainland, BC.

---

## Pages

| File | Page | Description |
|------|------|-------------|
| `index.html` | Home | Main landing page with services, eco options, and property management info |
| `booking.html` | Book a Service | Client booking form with calendar and email submission |
| `reviews.html` | Reviews | Display existing reviews and submit new ones |
| `join.html` | Join Our Team | Cleaner application form for outsourcing partnerships |

---

## How to Publish (Free — GitHub Pages)

### Step 1 — Create a GitHub Account
Go to [github.com](https://github.com) and sign up for a free account if you don't have one.

### Step 2 — Create a New Repository
1. Click the **+** icon in the top right → **New repository**
2. Name it something like `cleansweepingparrott` (no spaces)
3. Set it to **Public**
4. Leave everything else as default
5. Click **Create repository**

### Step 3 — Upload Your Files
1. On your new repository page, click **Add file** → **Upload files**
2. Drag and drop all 5 files:
   - `index.html`
   - `booking.html`
   - `reviews.html`
   - `join.html`
   - `README.md`
3. Scroll down and click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to your repository **Settings** (tab at the top)
2. In the left sidebar, click **Pages**
3. Under **Source**, select **Deploy from a branch**
4. Under **Branch**, select `main` and click **Save**
5. Wait 1–2 minutes, then your site will be live at:

```
https://yourusername.github.io/cleansweepingparrott/
```

---

## How Booking & Applications Work

Both the booking form (`booking.html`) and the cleaner application form (`join.html`) send their data directly to your email using the device's default mail app. No backend or monthly service required.

When a client or applicant submits a form, their mail app will open with a pre-filled email addressed to your inbox. They simply hit **Send**.

> **Note:** This approach works best on desktop. On mobile, it will open the default mail app (Gmail, Apple Mail, etc.). If you'd like a fully automated no-click submission in the future, services like [Formspree](https://formspree.io) offer a free tier that can handle this without monthly fees.

---

## Custom Domain (Optional)

Your site works for free at `yourusername.github.io/cleansweepingparrott`. If you'd like a custom domain like `cleansweepingparrott.com`:

1. Purchase a domain from [Namecheap](https://namecheap.com) or [Google Domains](https://domains.google) (~$15–20 CAD/year)
2. In your GitHub Pages settings, enter your custom domain under **Custom domain**
3. Follow the DNS instructions GitHub provides — your registrar's support team can help

---

## Reviews Storage

Client reviews submitted on `reviews.html` are saved in the visitor's browser (`localStorage`). This means:

- Reviews show up immediately for the person who submitted them
- Reviews persist across sessions on the same browser/device
- They are **not** shared across different visitors

If you'd like reviews to be visible to all site visitors, a free backend like [Supabase](https://supabase.com) or a form service like [Formspree](https://formspree.io) can be added in the future.

---

## Making Updates

To edit any page in the future:
1. Open the HTML file in any text editor (Notepad, TextEdit, VS Code)
2. Make your changes
3. Go back to your GitHub repository
4. Click the file → click the **pencil (edit) icon** → paste updated content, or
5. Use **Add file → Upload files** to replace the file

---

## Contact & Business Info

- **Business:** Clean Sweeping Parrott
- **Phone:** (778) 239-5750
- **Service Area:** Lower Mainland, BC
- **Email submissions go to:** *(configured in forms)*

---

## Tech Stack

- Pure HTML5, CSS3, and vanilla JavaScript — no frameworks, no dependencies
- Google Fonts (Cormorant Garamond + Jost) loaded via CDN
- No monthly fees, no subscriptions, no databases required
- Fully mobile responsive

---

*Website built for Clean Sweeping Parrott · Lower Mainland, BC*
