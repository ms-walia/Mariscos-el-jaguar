# Mariscos el Jaguar — demo website

A demo ordering website for Mariscos el Jaguar, a Mexican seafood food truck at Sunset on the 'Rise food truck park, 1 Indian Meadows Dr, Round Rock, Texas. Built by Mehtab Singh Ahluwalia as a pitch.

One HTML file plus an `images` folder, no build step. Open `index.html` in a browser, or turn on **Settings → Pages** (branch `main`, root) to host it.

## What it does
- Menu with **Add** buttons and a pickup cart, with 15-minute time slots inside the truck's real hours (US Central time; Mondays blocked)
- **Aguachile builder**: salsa (verde, rojo, negro), seafood, size up to a party tray, and heat, with a live drawing of a molcajete bowl
- Live open/closed badge: Tue–Thu 11–8, Fri–Sat 11–9, Sun 2–7, closed Mondays
- Party tray and catering request form
- Device checks (`is-phone` / `is-laptop` on `<html>`) so the same design adjusts for phones and laptops

## Demo status
- Prices show `$ —` until the truck shares its menu prices
- Orders and forms are not sent anywhere yet; the plan is card payment and orders to the truck's tablet or by text
- The logo and truck photo belong to Mariscos el Jaguar. Food and drink photos are Unsplash placeholders (see `CREDITS.md`)

Based on the free burger restaurant template by 8B (MIT). See `LICENSE`.
