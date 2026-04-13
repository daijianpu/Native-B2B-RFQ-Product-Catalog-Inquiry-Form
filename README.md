# Native-B2B-RFQ-Product-Catalog-Inquiry-Form
I developed this plugin to empower more people to quickly build high-performance B2B product catalogs and inquiry systems on WordPress.
***
This plugin has undergone multiple code reviews and rigorous audits to ensure it is secure, lightweight, and fully compliant with WordPress.org standards. If you encounter any bugs during use, please let me know, and I will perform a prompt fix to maintain peak performance.
https://eezz.net/contact/
***
=== Native B2B: RFQ Product Catalog & Inquiry Form ===
Contributors: leadsentinel
Tags: b2b, catalog, rfq, inquiry, woocommerce-alternative, product-showcase, wholesale, lead-generation
Requires at least: 6.0
Tested up to: 6.7
Requires PHP: 8.4
Stable tag: 1.1.5
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

High-speed B2B Product Catalog & RFQ System. Native-first, zero-bloat architecture. The definitive WooCommerce alternative for professional wholesale and lead generation.

<img width="1544" height="500" alt="image" src="https://github.com/user-attachments/assets/07c81305-250d-430f-be09-82ec09b71078" />
<img width="1112" height="907" alt="2c6a4142397e156eb7f902866a7fc962_screenshot-01_raw=true" src="https://github.com/user-attachments/assets/47a0cd3d-1904-46ab-b1c9-18bc731b1f23" />
<img width="1544" height="889" alt="625d87ca6be3cb14cb281f0845d01cbd_screenshot-03_raw=true" src="https://github.com/user-attachments/assets/eca4723b-e98e-4fe1-8bb4-60d55805f946" />
<img width="1253" height="768" alt="b4289fb63a320d1a199b6bcd638d4483_screenshot-04_raw=true" src="https://github.com/user-attachments/assets/7c5f4998-90a9-432c-ab67-282154168543" />
<img width="1505" height="707" alt="27a376cd6feca851a3e8ed6386b3d945_screenshot-05_raw=true" src="https://github.com/user-attachments/assets/e2e23814-741e-45b9-a122-69fe486feb37" />
<img width="1544" height="889" alt="cfb87648633380cbe771b244e7a71493_screenshot-08_raw=true" src="https://github.com/user-attachments/assets/04b3599b-e1bd-494a-9054-f3fa282ae85e" />
<img width="1544" height="889" alt="34c8277014a1503be732dfb83ac427b3_screenshot-09_raw=true" src="https://github.com/user-attachments/assets/008812f5-efc5-4c7c-82a4-884c952b59d7" />
<img width="1544" height="889" alt="67cbdbc4e8c7adec52347196589addea_screenshot-10_raw=true" src="https://github.com/user-attachments/assets/034173ec-062f-445e-a9f8-534bee768c77" />
<img width="1544" height="889" alt="1da4ded83a45f2448f79eb50e776f950_screenshot-11_raw=true" src="https://github.com/user-attachments/assets/8b9c0794-dd26-4a6d-82a6-ff468d2a3911" />
== Description ==

**The Anti-Bloat Manifesto**
In B2B trade, do you truly need a massive shopping cart, complex tax calculations, and a bloated checkout flow? If your goal is simply to showcase products and capture high-quality leads, then WooCommerce is a burden on your server performance.

NativeB2B is designed for high-performance B2B enterprises. We abandoned the e-commerce framework and built a high-speed product catalog system directly on the WordPress core. This means faster loading times, simpler configuration, and a cleaner database.

== Key Features ==

* Native Product Engine: Independent custom post type (CPT) with support for multi-level categories, specifications, and tiered pricing.
* High-Speed Gallery: Built-in performance-optimized product gallery with Lightbox preview and smooth zoom.
* Global RFQ System: Request For Quote functionality accessible from product pages, posts, or any custom page via shortcodes.
* Instant Multi-Channel Push: Real-time notifications via Email, Slack, Discord, Telegram, Feishu, and Google Sheets.
* Iron-Clad Anti-Spam: Advanced protection using Math Challenge and invisible Honeypot technology to block fake leads.
* Activity Analytics: Exclusive Hotspot Analysis charts to visualize lead activity trends and optimize your staffing.
* Data Liquidity: Professional one-click CSV export for all inquiry records, ready for your CRM.

== Installation ==

1. Upload the ezb2b-gallery folder to the /wp-content/plugins/ directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Go to NativeB2B -> Settings to configure your notification gateways (Slack, Telegram, etc.).
4. Start adding products under the NativeB2B menu.
5. Use the shortcode [ezls_gallery] on any page to display your products.

== Usage ==

### 1. Displaying Products
Place the following shortcode on any page or post:
`[ezls_gallery columns="4" limit="12"]`

* columns: Number of columns (1-4).
* limit: Number of products to show (-1 for all).

### 2. Inquiry Buttons
* Global use: [ezls_inquiry_btn text="Inquiry Now"] (Defaults to current page).
* Target specific product: [ezls_inquiry_btn id="123" text="Inquire Product 123"].

### 3. Analytics & Lead Management
Navigate to Inquiries to view the unified dashboard. Use the Hotspot Analysis to track peak inquiry times.

== FAQ ==

= Does this plugin support WooCommerce? =
No. This is a dedicated lightweight alternative for B2B manufacturers who do not need a checkout system but require enterprise-grade inquiry management.

= How is the performance? =
Zero-Bloat. Assets are only loaded on pages containing product elements, ensuring elite Google PageSpeed scores.

= Is my data secure? =
Yes. We utilize AES-256-GCM encryption for all sensitive notification tokens and full XSS protection.

== Screenshots ==

1. High-speed native product catalog layout.
2. Enterprise tiered pricing matrix.
3. Unified inquiry dashboard with real-time status LED.
4. Multi-channel push notification settings (Slack, Feishu, etc.).

== Changelog ==

= 1.1.5 =
* ENHANCED: Renamed to NativeB2B for better compliance and SEO.
* ADDED: Support for Global Push Gateways (Slack, Discord, Telegram, Feishu).
* ADDED: AES-256-GCM encryption for all sensitive API keys.
* ADDED: CSV Export functionality in the inquiry dashboard.
* ADDED: Inquiry Hotspot Analysis chart for lead timing optimization.
* FIXED: Template override system for developers.

= 1.0.0 =
* Initial release.
