# Lead Search Full Scraper
>This scraper helps you find targeted business leads based on keywords and locations, collecting emails whenever available. It’s designed for fast, flexible lead discovery across cities, regions, countries, or even worldwide. If you’re building outreach lists or powering sales automation, this tool simplifies the heavy lifting.

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
  If you are looking for <strong>Lead Search Scraper</strong> you've just found your team — Let's Chat. 👆👆
</p>

## Introduction
The tool searches for businesses that match your keywords and locations, then extracts relevant contact details and basic profile information. It supports broad or highly granular searches, making it useful for agencies, sales teams, marketers, and anyone who needs accurate, location-specific leads.

### Why People Use It
- Searches globally across unlimited locations.  
- Gathers leads tied to your specific keywords.  
- Extracts emails when available on the source page.  
- Allows exclusion of unwanted names or irrelevant results.  
- Delivers structured output suitable for CRMs, campaigns, or analytics.

---
## Features
| Feature | Description |
|---------|-------------|
| Keyword-Based Lead Discovery | Finds leads based on your business-related search terms. |
| Location Targeting | Supports any city, region, country, or global search. |
| Email Extraction | Retrieves emails when visible or discoverable. |
| Exclusion Filters | Removes results containing unwanted keywords. |
| Multi-Search Support | Accepts multiple keywords and multiple locations in one run. |
| Scalable Output | Generates large lists without location restrictions. |

---
## What Data This Scraper Extracts
| Field Name | Field Description |
|------------|-------------------|
| name | Name of the business or lead. |
| address | The lead’s listed address or location. |
| phone | Business or contact phone number. |
| email | Extracted email if available. |
| website | Linked website. |
| keywordMatched | The keyword that triggered the match. |
| locationMatched | The location used for the query. |
| sourceUrl | Original page where the lead data was found. |
| ... | Additional fields depending on the source page. |

---
## Example Output
    
    [
      {
        "name": "City Wellness Clinic",
        "address": "Los Angeles, CA",
        "phone": "+1 310-555-9321",
        "email": "contact@citywellnessclinic.com",
        "website": "https://citywellnessclinic.com",
        "keywordMatched": "medical",
        "locationMatched": "Los Angeles",
        "sourceUrl": "https://example.com/lead/citywellness"
      }
    ]

---
## Directory Structure Tree
    
    Lead Search Full/
    ├── src/
    │   ├── main.js
    │   ├── scraper/
    │   │   ├── lead_parser.js
    │   │   ├── keyword_filter.js
    │   │   └── exclusion_handler.js
    │   ├── utils/
    │   │   ├── logger.js
    │   │   └── request_helper.js
    │   └── config/
    │       └── settings.example.json
    ├── data/
    │   ├── sample_input.json
    │   └── sample_output.json
    ├── package.json
    └── README.md

---
## Use Cases
- **Sales teams** use it to build targeted outreach lists for campaigns.  
- **Agencies** use it to discover local or global business leads for clients.  
- **Marketers** use it to find niche businesses for partnership or promo opportunities.  
- **Researchers** use it to gather city- or region-specific business information.  
- **CRM managers** import structured results directly into their systems.  

---
## FAQs

**Can I search multiple keywords and locations at once?**  
Yes, the tool accepts arrays for both fields and runs all combinations.

**Does it always return emails?**  
Emails are included when they’re publicly visible or extractable on the source site.

**Can I exclude certain businesses?**  
Yes, add unwanted names or keywords to the exclusion list.

**Is there a limit on countries or cities?**  
No. You can search worldwide without restrictions.

---
### Performance Benchmarks and Results

**Primary Metric:**  
Processes hundreds of keyword–location combinations per minute depending on network conditions.

**Reliability Metric:**  
Maintains consistent accuracy thanks to structured filtering and multi-source validation.

**Efficiency Metric:**  
Uses lightweight requests to keep latency low even during large runs.

**Quality Metric:**  
Produces clean, de-duplicated lead lists with reliably extracted contact data.


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

