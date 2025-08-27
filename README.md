# VO ENT Official Website

This repo powers the **VO ENT** website: [https://voonline.shop](https://voonline.shop)

---

## 🔹 File Structure
---

## 🔹 How the Site Works

- **index.html**  
  The **welcome page**. Visitors can either:
  - **Sign Up** → goes to `signup.html`
  - **Enter Site** → goes to `main.html`

- **main.html**  
  The full VO ENT site:
  - Displays your songs from the inline manifest or `/tracks/manifest.json`
  - Embeds Apple Music and links to your YouTube channel
  - Merch section with items & prices
  - Signup section (JotForm embed)

- **signup.html**  
  Standalone signup form page.

- **home2.html**  
  Alternative homepage design (you can keep or remove).

---

## 🔹 Updating Songs

1. Upload MP3s to the `/tracks` folder in the repo.
2. Update either:
   - The **inline manifest** in `main.html` (inside `<script id="tracks-manifest">`), OR
   - Add/update `/tracks/manifest.json` like this:
     ```json
     [
       { "title": "Focus Full", "file": "focus_full.mp3", "price": "1.29", "cover": "logo1small.png" },
       { "title": "Vito R8", "file": "vito_r8.mp3", "price": "1.29", "cover": "logo3small.png" }
     ]
     ```
   3. Commit and push changes. Your songs will appear live.

---

## 🔹 Updating Merch

In `main.html`, find the **Merch** section and edit:
- Item title
- Price
- Image source (`whitehoodiesmall.jpeg`, etc.)
- Button links (`Buy Now`)

---

## 🔹 Signup Form

The signup is embedded from **JotForm**:  
```html
<iframe src="https://form.jotform.com/252085628910156"></iframe>
