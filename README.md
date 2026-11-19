# lunar-base
# Understanding the Moon

A short, phone-friendly explainer: why we need ground measurements before anyone builds on the Moon.

**Play it:** https://landalft.github.io/lunar-base/

## What it does

Anyone planning to build on the Moon asks three questions:

1. Will the ground hold my base?
2. Is it hollow underneath?
3. Is there water here?

The page shows what orbit data can tell us today, what it cannot, and lets you build the same module three times on the same ground: with no data, with poor data, and with good data.

## What is real, and what is not

- **Real, from NASA (public data):** the Aristarchus photo (LROC), terrain and slope (LOLA), gravity (GRAIL) and south-pole hydrogen (Lunar Prospector).
- **Our own model:** the 3D density blocks, calculated from GRAIL gravity. One possible answer, not the only one.
- **Invented for the demo:** the ground under every square, what each map shows, and the ten-year timeline. They show what can go wrong. They are not predictions for these places.
- **Rigged on purpose:** the first two builds always fail, wherever you tap. With no ground data, nobody could tell you otherwise. The page says so at the end.

## How it is built

One self-contained file, `index.html`. No install, no server, no tracking. The 3D view loads three.js from a public CDN, so it needs an internet connection.

## Disclaimer

An explainer, not a product. Made for an Imperial College Business School EMBA capstone project. It is a student concept, not an offering or statement from any company, and not an engineering tool.

## Data credits

NASA / GSFC / Arizona State University (LROC), NASA LOLA Science Team (south pole grid: Barker et al. 2023, [PGDA product 90](https://pgda.gsfc.nasa.gov/products/90)), NASA GRAIL, NASA Lunar Prospector.
