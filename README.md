# Paystack Frontend Demo (HTML + JavaScript)

This demo shows how to integrate **Paystack payments and donations** using **only HTML and JavaScript**, with **no backend required**.

---

## 🚀 Features

- Product checkout (₦2,500 T-shirt example)
- Donation form (user enters custom amount)
- Uses Paystack Inline Popup with your **public key**
- Optional webhook logging (using [Webhook.site](https://webhook.site))

---

## 📂 Files

- `index.html` — main demo file containing the full Paystack integration

---

## 🧩 Setup Instructions

1. Open **index.html** in a text editor.  
2. Replace the line:

   ```js
   const PAYSTACK_PUBLIC_KEY = 'pk_test_xxxxxxxxxxxxxxxxxxxxx';
   ```

   with your **Paystack public key** (start with `pk_test_...` for testing).

3. Open the file in your browser or host it online (GitHub Pages, Netlify, etc.).

4. Enter your email and click **Buy Now** or **Donate** to test.

5. To log successful transactions, create a free webhook URL at [https://webhook.site](https://webhook.site), copy the URL, and paste it into the input box on the page.

---

## 🧪 Testing

- Use Paystack test public key (`pk_test_...`).
- Use test card numbers from the [Paystack Docs](https://paystack.com/docs/payments/test-payments).
- The popup will simulate successful and failed payments.

---

## ⚠️ Security Notes

- Do **not** put your secret key (`sk_live_...`) in this file.
- This demo is meant for **testing, learning, and low-risk donations** only.
- For real e-commerce websites, you must verify transactions **server-side** using Paystack’s Verify API.

---

## ✅ Hosting

- Works on **GitHub Pages**, **Netlify**, **Vercel**, or any static hosting.  
- Just upload the file and open your site URL.

---

### Created by: Awwal Malik Olamilekan  
For educational purposes — © 2025
