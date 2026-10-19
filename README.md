# Hi there, I'm Harun Sekmen 👋

Senior WooCommerce Systems & Performance Engineer specializing in high-concurrency e-commerce architectures, database throughput scaling, and zero-downtime integrations.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Harun%20Sekmen-0077b5?style=flat&logo=linkedin)](https://www.linkedin.com/in/harunsekmen/)
[![Upwork](https://img.shields.io/badge/Upwork-Top%20Rated%20Plus-14a800?style=flat&logo=upwork)](https://www.upwork.com/)
[![PHP](https://img.shields.io/badge/PHP-8.1%20%7C%208.2%20%7C%208.3-777bb4?style=flat&logo=php)](https://php.net)
[![WooCommerce](https://img.shields.io/badge/WooCommerce-HPOS%20Ready-7f54b3?style=flat&logo=woocommerce)](https://woocommerce.com)

---

## 🚀 Turnkey Store Launch & Custom Builds
> **High-Converting D2C Storefronts Engineered for Growth**
> 
> Looking to launch a modern e-commerce brand without bloated themes or monthly app fees? I build bespoke, sub-second WooCommerce storefronts optimized for paid traffic (Meta / TikTok Ads) and maximum conversion rates.
> 
> - **Flagship Starter**: Explore **[ApexCommerce D2C Starter Kit](https://github.com/harunsekmen/apex-commerce-d2c-starter)** (Native Slide Cart, 95+ Mobile PageSpeed, Instant Checkout).
> - 📩 **Direct Project Inquiry**: [Hire Harun on Upwork](https://www.upwork.com/freelancers/~01a7a8b58043e6e6d9) | Email: `sekhar38@gmail.com`

---

## ⚡ Flagship Open-Source Engineering Work (WooCommerce Core Reliability)

A suite of enterprise drop-ins engineered to eliminate the most critical bottlenecks in high-volume WooCommerce storefronts:

| Repository & Solution | Problem Solved | Core Architecture |
| :--- | :--- | :--- |
| **[apex-commerce-d2c-starter](https://github.com/harunsekmen/apex-commerce-d2c-starter)**<br>*(Modern D2C Storefront Kit)* | Eliminates bloated multi-purpose themes and slow checkouts for new brand launches | Lightweight bespoke starter with native slide-out cart drawer, free-shipping meter, and 95+ PageSpeed. |
| **[woo-fast-fragments](https://github.com/harunsekmen/woo-fast-fragments)**<br>*(Cart Turbo Engine)* | Eliminates CPU-choking `?wc-ajax=get_refreshed_fragments` calls on every page load | HTML5 LocalStorage DOM hydration + lightweight REST endpoint. Slashes catalog TTFB by ~85%. |
| **[woo-checkout-failover-guard](https://github.com/harunsekmen/woo-checkout-failover-guard)**<br>*(Checkout Circuit Breaker)* | Prevents cart abandonment and double-charges when Stripe/PayPal hit 504 timeouts | Asynchronous client circuit breaker halting infinite spinners with instant non-destructive recovery options. |
| **[woo-deadlock-vacuum](https://github.com/harunsekmen/woo-deadlock-vacuum)**<br>*(Non-Blocking DB Pruner)* | Cleans millions of orphan transients without triggering MySQL Deadlock 1213 on checkouts | Indexed primary key chunking (500 rows) + Action Scheduler automation with 50ms lock-relief pauses. |
| **[woo-hpos-legacy-bridge](https://github.com/harunsekmen/woo-hpos-legacy-bridge)**<br>*(HPOS Migration Shield)* | Shields stores when legacy plugins call `get_post_meta` on HPOS `wp_wc_orders` tables | Transparent WordPress core filter middleware with re-entrancy protection and caller telemetry. |
| **[woo-webhook-resilience](https://github.com/harunsekmen/woo-webhook-resilience)**<br>*(Dead-Letter Queue & Retries)* | Eliminates dropped orders across ERP, HubSpot, Klaviyo, and fulfillment APIs | Action Scheduler exponential backoff (1m, 5m, 15m, 1h, 6h) + WP Admin DLQ Console with 1-click replay. |

---

## 🛠️ Technical Stack & Focus Areas

- **E-Commerce & Core**: WooCommerce HPOS (`custom_order_tables`), Cart & Checkout Blocks, Custom Gateways, Action Scheduler.
- **Backend & Database**: PHP 8.1 - 8.3, MySQL / MariaDB InnoDB optimization, query profiling, index design, deadlock prevention.
- **Front-End & Runtime**: Vanilla ES6+, Core Web Vitals optimization, DOM hydration, REST API & GraphQL client layers.
- **DevOps & Integrity**: Docker, WP-CLI, GitHub Actions CI/CD, PSR-4 / PSR-12 coding standards, PHPStan.

---

## 📬 Let's Connect

- **Upwork / Freelance Inquiries**: Available for turnkey D2C store builds, high-impact performance audits, and HPOS migrations.
- **GitHub**: [github.com/harunsekmen](https://github.com/harunsekmen)
- **LinkedIn**: [linkedin.com/in/harunsekmen](https://www.linkedin.com/in/harunsekmen/)

