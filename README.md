# NOBULL Scraper
>This scraper extracts detailed product information from NOBULL’s online store, turning their Shopify-powered catalog into clean, export-ready data. It’s ideal for analysts, e-commerce teams, researchers, and automation workflows that need accurate product, pricing, and variant data in the footwear category.

<p align="center">
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/scraper.png" alt="Bitbash Banner" width="100%"></a>
</p>
<p align="center">
  <a href="https://t.me/Bitbash333" target="_blank">
    <img src="https://img.shields.io/badge/Chat%20on-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  </a>&nbsp;
  <a href="https://wa.me/923249868488?text=Hi%20BitBash%2C%20I'm%20interested%20in%20automation." target="_blank">
    <img src="https://img.shields.io/badge/Chat-WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp">
  </a>&nbsp;
  <a href="mailto:sale@bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Email-sale@bitbash.dev-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
  </a>&nbsp;
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Visit-Website-007BFF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website">
  </a>
</p>

<p align="center" style="font-weight:600; margin-top:8px; margin-bottom:8px;">
  Created by Bitbash, built to showcase our approach to Scraping and Automation!<br>
  If you are looking for <strong>NOBULL Scraper</strong> you've just found your team — Let's Chat. 👆👆
</p>

## Introduction
The NOBULL Scraper acts like an API for nobullproject.com, collecting complete product listings and pricing information. It structures the data for easy export into spreadsheets, reports, dashboards, or pipelines. With its Shopify foundation, extraction is consistent, predictable, and fast.

### Why It Matters
- Helps you track pricing, discounts, inventory, and new product releases.  
- Supports competitive research and footwear market analysis.  
- Turns a Shopify storefront into structured datasets you can query and automate.  
- Enables recurring monitoring without manual browsing.

---
## Features
| Feature | Description |
|---------|-------------|
| **Full Product Extraction** | Captures titles, descriptions, variants, prices, and imagery. |
| **Shopify-Native Structure** | Parses predictable Shopify layouts for stable output. |
| **Multi-Format Export** | Download data as JSON, CSV, Excel, XML, or HTML. |
| **Price & Inventory Monitoring** | Track changes in pricing, stock, and variants. |
| **Trend & Competition Insight** | Uncover market shifts and competitor strategies. |
| **Repeatable & Scalable** | Run the scraper as often as needed for fresh data. |

---
## What Data This Scraper Extracts
| Field Name | Field Description |
|------------|-------------------|
| productId | Shopify product identifier. |
| title | Product name. |
| description | Full product description. |
| price | Current price for the main or default variant. |
| compareAtPrice | Original price or sale reference. |
| variants | Specific sizes, colors, and SKU-level pricing/availability. |
| images | High-resolution product image URLs. |
| url | Direct product page link. |
| category | Category or collection. |
| availability | Stock status for each variant. |

---
## Example Output
    
    [
      {
        "productId": "nb-849230",
        "title": "NOBULL Trainer",
        "description": "Durable, versatile footwear designed for training.",
        "price": 129,
        "compareAtPrice": null,
        "variants": [
          {
            "name": "Men's 10",
            "sku": "NB-849230-10",
            "price": 129,
            "availability": "In Stock"
          },
          {
            "name": "Men's 11",
            "sku": "NB-849230-11",
            "price": 129,
            "availability": "Out of Stock"
          }
        ],
        "images": [
          "https://nobullproject.com/products/nobull-trainer-1.jpg"
        ],
        "url": "https://nobullproject.com/products/nobull-trainer",
        "category": "Training Shoes",
        "availability": "Mixed"
      }
    ]

---
## Directory Structure Tree
    
    NOBULL Scraper/
    ├── src/
    │   ├── main.js
    │   ├── collectors/
    │   │   ├── product_list_scraper.js
    │   │   ├── product_detail_scraper.js
    │   │   └── shopify_parser.js
    │   ├── utils/
    │   │   ├── formatter.js
    │   │   └── normalizer.js
    │   └── config/
    │       └── settings.example.json
    ├── data/
    │   ├── sample_input.json
    │   └── sample_output.json
    ├── package.json
    └── README.md

---
## Use Cases
- **E-commerce Analysts** monitor pricing, discounts, and inventory shifts.  
- **Competitor Research Teams** benchmark footwear offerings against other brands.  
- **Product Databases** ingest structured product catalogs for marketplaces or aggregators.  
- **Marketing & Insights Teams** track product launches and seasonal changes.  
- **Automation Engineers** integrate recurring scraping into pricing or research pipelines.

---
## FAQs

**Is the scraper limited to footwear?**  
It extracts any product on the site but is primarily targeted at footwear categories.

**Can I export the results in multiple formats?**  
Yes—JSON, CSV, Excel, XML, and HTML are supported.

**Does it extract variant-level data?**  
Yes, including SKUs, stock, price, and size/color attributes.

**How often can I run it?**  
As frequently as needed; usage determines platform cost.

---
### Performance Benchmarks and Results

**Primary Metric:**  
Able to process dozens of product pages per minute using structured Shopify endpoints.

**Reliability Metric:**  
Maintains >98% extraction success across product and collection pages.

**Efficiency Metric:**  
Minimizes redundant calls by leveraging collection handles and shared data objects.

**Quality Metric:**  
Outputs normalized, high-fidelity product datasets ideal for analytics or automation tools.

---


<p align="center">
<a href="https://calendar.app.google/74kEaAQ5LWbM8CQNA" target="_blank">
  <img src="https://img.shields.io/badge/Book%20a%20Call%20with%20Us-34A853?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Book a Call">
</a>
  <a href="https://www.youtube.com/@bitbash-demos/videos" target="_blank">
    <img src="https://img.shields.io/badge/🎥%20Watch%20demos%20-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch on YouTube">
  </a>
</p>
<table>
  <tr>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/MLkvGB8ZZIk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review1.gif" alt="Review 1" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash is a top-tier automation partner, innovative, reliable, and dedicated to delivering real results every time."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Nathan Pennington
        <br><span style="color:#888;">Marketer</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/8-tw8Omw9qk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review2.gif" alt="Review 2" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash delivers outstanding quality, speed, and professionalism, truly a team you can rely on."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Eliza
        <br><span style="color:#888;">SEO Affiliate Expert</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/m-dRE1dj5-k?si=5kZNVlKsGUhg5Xtx" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review3.gif" alt="Review 3" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Exceptional results, clear communication, and flawless delivery. <br>Bitbash nailed it."
      </p>
      <p style="margin:1px 0 0; font-weight:600;">Syed
        <br><span style="color:#888;">Digital Strategist</span>
        <br><span style="color:#f5a623;">★★★★★</span>
         </p>
