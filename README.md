<div align="center">

# Harun Sekmen

### Senior WooCommerce Systems & Performance Engineer
**Bespoke D2C Storefronts • HPOS Custom Order Tables • Database Throughput & High-Concurrency Scaling**

<p align="center">
  <a href="https://www.upwork.com/freelancers/~01a7a8b58043e6e6d9"><img src="https://img.shields.io/badge/Upwork-Top%20Rated%20Plus-14a800?style=for-the-badge&logo=upwork&logoColor=white" alt="Upwork"></a>
  <a href="https://www.linkedin.com/in/harunsekmen/"><img src="https://img.shields.io/badge/LinkedIn-Harun%20Sekmen-0077b5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://woocommerce.com"><img src="https://img.shields.io/badge/WooCommerce-HPOS%20Certified-7f54b3?style=for-the-badge&logo=woocommerce&logoColor=white" alt="WooCommerce"></a>
  <a href="https://php.net"><img src="https://img.shields.io/badge/PHP-8.1%20%7C%208.2%20%7C%208.3-777bb4?style=for-the-badge&logo=php&logoColor=white" alt="PHP"></a>
</p>

---

</div>

## 🚀 Turnkey Store Builds & Technical Inquiries
> ### **Direct Inbound for Founders, Operators & High-Volume Store Owners**
> 
> Looking to launch a sub-second D2C brand or engineer your existing WooCommerce architecture for enterprise scale?
> - **Turnkey D2C Storefronts**: Bespoke builds with native slide-out AJAX cart, 95+ Mobile PageSpeed, and zero monthly app fees.
> - **Shopify-to-WooCommerce Migrations**: Full product, customer, and historical order migration with 0% platform transaction cuts.
> - **Enterprise Scaling & HPOS**: Eliminating checkout deadlocks, optimizing database throughput, and resolving 504 gateway drops.
> 
> 📩 **Direct Consultation**: [Book a Project on Upwork](https://www.upwork.com/freelancers/~01a7a8b58043e6e6d9) • Direct Email: `sekhar38@gmail.com`

---

## ⚡ Flagship Open-Source Engineering Suite

Production-grade drop-ins and architectures built to eliminate the most critical bottlenecks in modern WooCommerce:

| Repository & Solution | Focus & Impact | Architecture & Tech Stack | Release |
| :--- | :--- | :--- | :---: |
| **[apex-commerce-d2c-starter](https://github.com/harunsekmen/apex-commerce-d2c-starter)**<br>*(Modern D2C Storefront Kit)* | Turnkey conversion-tested D2C storefront replacing bloated visual page builders. Guaranteed 95+ Mobile PageSpeed. | Native slide-out AJAX drawer, dynamic free-shipping progress meter, and sticky checkout. | [`v1.0.0`](https://github.com/harunsekmen/apex-commerce-d2c-starter/releases) |
| **[shopify-dawn-woocommerce-twin](https://github.com/harunsekmen/shopify-dawn-woocommerce-twin)**<br>*(Shopify-to-Woo Engine)* | Replicates Shopify Dawn’s modern UX on self-hosted WooCommerce with 0% transaction fees and $0 recurring app bills. | Dawn design tokens, native drawer cart, variant swatch pills, and direct gateway routing. | [`v1.0.0`](https://github.com/harunsekmen/shopify-dawn-woocommerce-twin/releases) |
| **[figma-to-woo-blocks-system](https://github.com/harunsekmen/figma-to-woo-blocks-system)**<br>*(Figma Component Blocks)* | Converts high-fidelity Figma UI kits into native WordPress blocks without Elementor bloat or Cumulative Layout Shift. | 15 modular Gutenberg blocks mirroring Figma auto-layout flexbox with guaranteed 0.00 CLS. | [`v1.0.0`](https://github.com/harunsekmen/figma-to-woo-blocks-system/releases) |
| **[woo-fast-fragments](https://github.com/harunsekmen/woo-fast-fragments)**<br>*(Cart Turbo Engine)* | Eliminates CPU-choking `?wc-ajax=get_refreshed_fragments` calls on every catalog page load. Slashes TTFB by ~85%. | Client-side HTML5 LocalStorage DOM hydration + lightweight `/wff/v1/fragments` REST endpoint. | [`v1.0.0`](https://github.com/harunsekmen/woo-fast-fragments/releases) |
| **[woo-checkout-failover-guard](https://github.com/harunsekmen/woo-checkout-failover-guard)**<br>*(Checkout Circuit Breaker)* | Prevents cart abandonment and duplicate authorization charges when Stripe or PayPal experience 504 timeouts. | Asynchronous client circuit breaker halting infinite spinners with instant non-destructive recovery. | [`v1.0.0`](https://github.com/harunsekmen/woo-checkout-failover-guard/releases) |
| **[woo-deadlock-vacuum](https://github.com/harunsekmen/woo-deadlock-vacuum)**<br>*(Non-Blocking DB Pruner)* | Cleans millions of orphan transients and postmeta rows without triggering MySQL Deadlock 1213 on live checkouts. | Indexed primary key chunking (500 rows) via Action Scheduler with mandatory 50ms lock-relief pauses. | [`v1.0.0`](https://github.com/harunsekmen/woo-deadlock-vacuum/releases) |
| **[woo-hpos-legacy-bridge](https://github.com/harunsekmen/woo-hpos-legacy-bridge)**<br>*(HPOS Migration Shield)* | Shields stores when legacy plugins call `get_post_meta` on HPOS `wp_wc_orders` tables, stopping silent data loss. | Transparent WordPress core filter middleware with re-entrancy protection and caller backtrace telemetry. | [`v1.0.0`](https://github.com/harunsekmen/woo-hpos-legacy-bridge/releases) |
| **[woo-webhook-resilience](https://github.com/harunsekmen/woo-webhook-resilience)**<br>*(Dead-Letter Queue & Retries)* | Eliminates dropped orders across ERP, HubSpot, Klaviyo, and fulfillment APIs during third-party downtime. | Action Scheduler exponential backoff (1m, 5m, 15m, 1h, 6h) + WP Admin DLQ Console with 1-click replay. | [`v1.0.0`](https://github.com/harunsekmen/woo-webhook-resilience/releases) |

---

## 🛠️ Engineering Disciplines & Technical Stack

<table>
  <tr>
    <td width="33%" valign="top">
      <h4>⚡ Core Architecture</h4>
      <ul>
        <li>WooCommerce HPOS (<code>wp_wc_orders</code>)</li>
        <li>Action Scheduler Queueing</li>
        <li>Custom Payment Gateways</li>
        <li>Checkout & Cart Blocks</li>
        <li>Zero-Downtime Data Migrations</li>
      </ul>
    </td>
    <td width="33%" valign="top">
      <h4>🗄️ Database & Backend</h4>
      <ul>
        <li>PHP 8.1 / 8.2 / 8.3 (Strict Types)</li>
        <li>MySQL / MariaDB InnoDB Tuning</li>
        <li>Query Profiling & Index Design</li>
        <li>Deadlock 1213 Elimination</li>
        <li>WP REST API & Webhooks</li>
      </ul>
    </td>
    <td width="33%" valign="top">
      <h4>🎯 Performance & Front-End</h4>
      <ul>
        <li>Core Web Vitals (90+ Mobile)</li>
        <li>Zero Cumulative Layout Shift (CLS)</li>
        <li>LocalStorage State Hydration</li>
        <li>Vanilla ES6+ Event Loops</li>
        <li>Figma Auto-Layout Translation</li>
      </ul>
    </td>
  </tr>
</table>

---

## 📈 Engineering Standards

- **Code Quality**: PSR-4 autoloading, PSR-12 formatting, strict type declarations (`declare(strict_types=1)`).
- **Continuous Integration**: GitHub Actions testing across matrix PHP 8.1, 8.2, and 8.3 environments.
- **Verification**: Headless Chromium end-to-end browser test suites verifying DOM states and AJAX lifecycles.
- **Open Standards**: 100% GPL-3.0 compatible with zero vendor lock-in.

---

<div align="center">
  <p><strong>Available for selective high-impact WooCommerce builds, audits, and migrations.</strong></p>
  <p>
    <a href="https://www.upwork.com/freelancers/~01a7a8b58043e6e6d9"><strong>Hire on Upwork</strong></a> • 
    <a href="https://www.linkedin.com/in/harunsekmen/"><strong>Connect on LinkedIn</strong></a> • 
    <a href="mailto:sekhar38@gmail.com"><strong>sekhar38@gmail.com</strong></a>
  </p>
</div>

