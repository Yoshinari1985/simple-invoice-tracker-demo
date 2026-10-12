# Simple Invoice & Payment Tracker — Demo

**DEMO VERSION — For evaluation only. Do not enter real customer or financial information.**

Live demo: https://yoshinari1985.github.io/simple-invoice-tracker-demo/

A small quote, invoice and payment tracker for freelancers and small service businesses,
published here as a hands-on demo (works on iPhone Safari and desktop browsers).

## How the demo handles data

- Everything you enter is saved **only in your own browser on your own device** (IndexedDB).
- Nothing is sent to a server. There are no accounts, no analytics, no API keys and no external services.
- Other visitors cannot see what you type.
- To remove your data: *Settings & backup → Delete all data*, or clear this website's data in your browser.

## What this demo is not

- Not accounting, bookkeeping or tax software. It does not file taxes or provide tax advice.
- No bank connections and no real payments.
- Sample data is fictional (names, companies and `example.com` emails are made up).

## Contents of this repository

This repository contains only the built demo page. The application source code is not published here.

| File | Purpose |
|---|---|
| `index.html` | The whole demo app (single self-contained page) |
| `third-party-licenses.txt` | License texts of the open-source libraries included in the page |
| `robots.txt` | Asks search engines not to index the demo |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

Open-source components are used under their own licenses (MIT, ISC, Apache-2.0, MPL-2.0/Apache-2.0);
see `third-party-licenses.txt`. The demo application itself is provided for evaluation only;
all other rights reserved.
