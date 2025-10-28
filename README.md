# BytaBay Computers Prompt Injection Demo

This mini storefront highlights how hidden instructions can influence AI helpers that browse or summarize web pages. Every page looks like a normal laptop shop, but it also hides malicious or manipulative directives that surface when you use the show/hide buttons.

## Files

- `index.html` – Landing page with the main navigation, laptop grid, and an invisible prompt injection toggle near the hero section.
- `creator-flex-15.html` – Product detail page for the Creator Flex 15 with several show/hide buttons that expose conflicting instructions.
- `about.html` – Explains the demo, why prompt injection matters, and how to present it.
- `checkout-flex-15.html` and `thank-you-flex-15.html` – Checkout flow pages that complete the narrative.

## How to Demo Prompt Injection

1. Open `index.html` in a browser. Use the toggle near the top-right corner to reveal the hidden text instructing an AI to leak customer data.
2. Navigate to the Creator Flex 15 via the laptop grid or the new About page link. Use the show/hide buttons to expose upsell directives and discontinuation notes that contradict the visible marketing copy.
3. Walk through `about.html` to explain the scenario and reinforce that agents should not blindly follow these hidden instructions.
4. Discuss mitigations such as filtering untrusted inputs, isolating browsing contexts, and validating unexpected directives before acting on them.

The demo works offline—just open the HTML files directly from disk or host them with a simple static server if you want clean URLs.

# BytaBay Training Site README

## Purpose  
This repository/website is a **simulation** of a computer-sales company named *BytaBay*. It is built solely for educational purposes to demonstrate prompt injection vulnerabilities and other AI-agent security scenarios.

## What you will find  
- A fake “storefront” website that appears legitimate but is **not** a commercial business.  
- Product pages for computers and accessories.  
- Simulated checkout, support, and FAQ flows that contain intentional vulnerabilities or learning hooks.  
- A debrief section (hidden or restricted) for trainers to explain what to watch for (prompt injection, social engineering, mismatches, etc.).

## How to use this training site  
1. Deploy the site in a controlled environment (internal use only).  
2. Have participants interact with the site, attempt prompt-injection or manipulation of the agent/model behind the site.  
3. After the exercise, walk through the vulnerabilities and mitigation strategies.  
4. Use this site as a safe sandbox — **no real transactions, no real user data**.

## Technical setup  
- Stack: HTML/GitHub Pages  

## Ethical & Legal Notice  
This site is **not** a real business. No financial transactions are permitted. The site is for training only. Misuse (e.g., exposing to unintended users) may violate terms of services or consumer-protection laws depending on jurisdiction. Use responsibly.


