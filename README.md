# Queue Decoder · v0.1.0

A lightweight, single-file browser tool for decoding virtual queue data from retail websites. When you're stuck in a Walmart, Best Buy, Costco, or Sam's Club online queue, Queue Decoder translates the raw network payload into something actually useful — your position, estimated wait time, admission odds, and how fast the queue is really moving.

## Supported Retailers
Walmart · Best Buy · Costco · Sam's Club · Queue-it · Cloudflare Waiting Room · Ticketmaster

## Features
- **Decode Single Snapshot** — paste one queue response for an instant read on your position and countdown
- **Compare Two Snapshots** — paste an earlier and later response to calculate real queue velocity, tickets admitted, and a projected turn time
- Works entirely offline — no data ever leaves your browser
- Auto-detects the queue provider from the payload

## Usage
Open `QueueDecoder.html` in any browser. No install, no dependencies, no server required.

> **Note:** This app has only been tested with Walmart thus far. Other supported retailers may work but results could vary.

For step-by-step instructions on how to pull queue data from your browser's DevTools and get the most out of both modes, see the **Help tab** inside the app.

---
Created by **RockPaperPirate**
