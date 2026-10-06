# Raisy.me — Monetization Simulator & Story Generator 🚀

An interactive web simulator built for **Raisy.me** creators in Brazil. This tool allows influencers to calculate their real potential earnings under Raisy's 90/10 revenue split model and immediately export a shareable, custom-styled Instagram Story graphic ($9:16$ ratio) showing their estimated monthly earnings[cite: 1].

---

## ⚡ Key Features

* **Real-time Calculations:** Instant updates on estimated subscriber conversion ($5\%$ baseline of engaged audience), gross monthly earnings, and net creator income ($90\%$ payout)[cite: 1].
* **Platform Fee Breakdown:** Explicitly shows total revenue vs. Raisy's low $10\%$ platform fee[cite: 1].
* **1-Click Instagram Story Export:** Built-in `html2canvas` renderer that converts the dynamic output card into a high-res PNG (`meu-potencial-raisy.png`) optimized for mobile story sharing ($9:16$ aspect ratio)[cite: 1].
* **Pure Client-Side Execution:** No backend server or complex build tools required — operates entirely within a single standalone `index.html` file using Tailwind CSS CDN.

---

## 🛠️ Tech Stack

* **HTML5 / JavaScript (ES6)** — Core logic and real-time DOM manipulation
* **Tailwind CSS** — Utility-first responsive styling
* **html2canvas** — Client-side HTML-to-Image screenshot generation

---

## 📁 Project Structure

```text
├── index.html       # Complete application (UI, Tailwind, JS logic)
└── README.md        # Project documentation & team overview
