# iTrustAI Tech

Open-source-first, privacy-minded local AI setup guides and storefront starter for iTrustAI.

Original source in this repository is licensed under Apache-2.0; see `LICENSE` and `NOTICE`. That license does not apply to third-party software, model files, or marks described in product materials.

## Product lineup

| Offer | Price | What it is |
|---|---:|---|
| DIY System Download | $9.99 | The same iTrustAI setup as a download for people who want to install it themselves. |
| Standard Setup USB | $29.99 | The same core setup on a standard USB drive, shipped to the customer. |
| Premium Setup USB | $49.99 | The same core setup on a more premium-looking USB package, shipped to the customer. |

All three offers contain the same core setup—Parrot OS, Hermes, Ollama, n8n, and instructions for a first agentic workflow. The difference is delivery format and presentation. Instructions are included with every offer. Shipping charges, delivery time, supported computer requirements, final included software versions, and refund terms must be confirmed before accepting orders.

## Repository contents

- `site/` — responsive product landing page, ready to preview locally or deploy as a static site.
- `docs/product-and-delivery.md` — offer definitions and fulfillment checklist.
- `docs/software-licensing.md` — notes for distributing third-party software and models responsibly.

## Preview

Open `site/index.html` in a browser. The page is a storefront preview; it does not collect payments or deliver downloads yet. Purchase actions stay disabled until the owner connects a real payment provider and uploads the finished, license-cleared download packages.

## Before launch

1. Confirm the final system image/package and verify it installs on supported hardware.
2. Confirm exactly which software and model versions are included and their licenses.
3. Add a secure HTTPS domain and WordPress/WooCommerce or another supported checkout.
4. Connect the owner’s payment-provider account and payout details directly in that provider.
5. Upload and protect the $9.99 download; test a purchase, receipt, refund, and download from a customer account.
6. Publish shipping, delivery, support, privacy, refund, and terms information.

Do not put payment secrets, API keys, customer information, or server credentials in this repository.

## Status

This is the initial source repository and product specification. It is not a finished operating-system image, an automated installer, a live store, or a payment integration.
