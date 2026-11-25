# Kasuwa shop (demo website)

A small online shop with a home page, categories, search, product pages with ratings and reviews,
cart, login and sign up, a profile page, a menu drawer and a light/dark switch.
It works on phones and computers.

## How to run it on your computer
1. Unzip the folder.
2. Double-click `index.html`. It opens in your browser. (You need internet once for the Poppins font.)
3. Better: in VS Code install the "Live Server" extension, right-click `index.html`, choose "Open with Live Server".

## What is in the folder
- `index.html` : the page skeleton. It loads everything below.
- `css/style.css` : all colours and layout. The colour palette is the class on the `<html>` tag (`p3` = cream, navy and orange).
- `js/images.js` : the list of pictures. Replace a file in `images/` (same name) to change a picture.
- `js/data.js` : the shop content. Edit this to change products, prices, categories, descriptions and banner slides.
- `js/app.js` : the behaviour of the site (pages, cart, search, login, menu).
- `images/` : all product and banner pictures.

## Common changes
- Change a product price or name: open `js/data.js`, find the product in the `P` list.
- Change a picture: replace the file in `images/` using the same file name.
- Change the shop name: search for `Kasuwa` in `index.html` and `js/app.js`.

## Before you sell for real
This is a front-end demo. Accounts, carts, orders and reviews are saved only in each visitor's own browser.
There is no payment and no server. To take real orders you need a payment service (for example Paystack or
Flutterwave), a database and a small backend.

## Putting it online
Upload the whole folder (not just `index.html`) to a static host such as Netlify, Cloudflare Pages or Vercel.
GitHub Pages is fine for a demo or portfolio, but its rules do not allow running a shop on it.
