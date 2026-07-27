## 🤖 [Xporience Exhibitor List Scraper](https://apify.com/skython/xporience-exhibitor-list-scraper)

Simple web scraper for extracting exhibitor data from trade show exhibitor lists provided by **Xporience**. Easily scrape company profiles including **company details, websites, social media links, product sectors**. 

Ideal for **B2B lead generation, market research, event networking, and competitive analysis**. Supports multiple **Xporience** exhibition websites with a consistent HTML structure.

> [Apify](https://apify.com/) is a cloud platform and marketplace for web scraping and automation tools.

---

## Contents

- [Features](#features)

- [Use Cases](#use-cases)

- [Supported Website Structure](#supported-website-structure)

- [Supported Xporience Events (Exhibitor Lists)](#supported-xporience-events-exhibitor-lists)

- [Testing Exhibitor List URLs](#testing-exhibitor-list-urls-for-free)

- [Exhibitor List Scraper - All-In-One Version](#exhibitor-list-scraper---all-in-one-version)

- [Data Fields](#data-fields)

- [Example Output](#example-output)

- [My Other Exhibitor List Scrapers](#my-other-exhibitor-list-scrapers)

---

## Features

- Scrape all exhibitor profiles from supported Xporience event websites

- Extract detailed data from every exhibitor profile page

- Company primary information (country, email, website)

- Social media links (LinkedIn, Facebook, Instagram, Twitter, YouTube)

- Two output formats (Single-Row & Multi-Row)

- Multi-Row format for Excel-friendly product sector filtering

- Export to JSON, CSV, and Excel

---

## Use Cases

- **B2B Lead Generation:** Build targeted contact lists for marketing and sales outreach. 

- **Market Research:** Analyze exhibitors by product categories, brands, and sectors.  

- **Event Networking:** Familiarize yourself with exhibitors before attending trade fairs.  

- **Competitive Analysis:** Track competitor participation and product focus areas.

---

## Supported Website Structure

- This scraper is designed to extract data from exhibitor directories with the same HTML structure as the supported Xporience exhibitor lists below.

- Take a look at some of the event websites from the below list. Your event website URL might be in that list.

- If you are not sure about if this actor is capable of scraping your event URL, test it with [**Exhibitor List Scrapers URL Tester**](https://apify.com/skython/exhibitor-list-scrapers-router) actor.

---

## Supported Xporience Events (Exhibitor Lists)

> The following partial list includes Xporience exhibitor directory URLs that have been tested so far. Other Xporience events or different events with the same website structure may also be supported.

> Some event URLs may have been updated or canceled entirely; please check them before using.

### 2026

- [Make It In The Emirates 2026 Exhibitor List – exhibitors.miite.ae](https://exhibitors.miite.ae/make-it-in-the-emirates-2026/Exhibitors)

- [Bharat Electricity Summit 2026 Exhibitor List – exhibitors.big5constructsaudi.com](https://exhibitors.bharatelectricitysummit.com/bharat-electricity-summit-2026/Exhibitor)

- [BIG 5 CONSTRUCT SAUDI 2026 Exhibitor List – exhibitors.big5constructsaudi.com](https://exhibitors.big5constructsaudi.com/big-5-construct-saudi-2026/Exhibitor/)


### 2025

- [BIG 5 GLOBAL 2025 Exhibitor List – exhibitors.big5global.com](https://exhibitors.big5global.com/Big-5-Global-2025/Exhibitor)

- [BIG 5 CONSTRUCT NIGERIA 2025 Exhibitor List – exhibitors.big5constructnigeria.com](https://exhibitors.big5constructnigeria.com/the-big-5-construct-nigeria-2025/Exhibitor)    

- [Big 5 Construct Qatar 2025 Exhibitor List – exhibitors.big5constructqatar.com](https://exhibitors.big5constructqatar.com/big-5-construct-qatar-2025/Exhibitor)

- [BIG 5 CONSTRUCT SAUDI 2025 Exhibitor List – exhibitors.big5constructsaudi.com](https://exhibitors.big5constructsaudi.com/big-5-construct-saudi-2025-first-week/Exhibitor)     

- [FIND Design Fair Asia 2025 Exhibitor List – exhibitors.designfairasia.com](https://exhibitors.designfairasia.com/find-design-fair-asia-2025/Exhibitor)

- [Gifts And Homeware Expo 2025 Exhibitor List – exhibitors.giftshomewareexpoksa.com](https://exhibitors.giftshomewareexpoksa.com/gifts-and-homeware-expo-saudi-arabia-2025/Exhibitor)

- [Global Infrastructure Expo(GIE) 2025 Exhibitor List – exhibitors.globalinfrastructureexpo.com](https://exhibitors.globalinfrastructureexpo.com/global-infrastructure-expo-2025/Exhibitor)

- [Global Water Expo 2025 Exhibitor List – exhibitors.globalwaterexhibition.com](https://exhibitors.globalwaterexhibition.com/global-water-expo-2025/Exhibitor)

- [HVACR WORLD 2025 Exhibitor List – exhibitors.hvacr-world.com](https://exhibitors.hvacr-world.com/hvacr-world-2025/Exhibitor)

- [INDEX Design Qatar 2025 Exhibitor List – exhibitors.index-qatar.com](https://exhibitors.index-qatar.com/index-design-qatar-2025/Exhibitor)

- [INDEX DUBAI 2025 Exhibitor List – exhibitors.indexexhibition.com](https://exhibitors.indexexhibition.com/index-2025/Exhibitor)

- [INDEX SAUDI ARABIA 2025 Exhibitor List – exhibitors.index-saudi.com](https://exhibitors.index-saudi.com/index-saudi-arabia-2025-56/Exhibitor)

- [Interiors Show Jeddah 2025 Exhibitor List – exhibitors.interiors-furnitureshowjeddah.com](https://exhibitors.interiors-furnitureshowjeddah.com/interiors-and-furniture-show-2025/Exhibitor)

- [JEDDAH CONSTRUCT 2025 Exhibitor List – exhibitors.jeddahconstruct.com](https://exhibitors.jeddahconstruct.com/jeddah-construct-2025/Exhibitor/)

- [Kids And Toys Expo 2025 Exhibitor List – exhibitors.kidstoys-expoksa.com](https://exhibitors.kidstoys-expoksa.com/kids-toys-expo-saudi-arabia-2025/Exhibitor)

- [Lighting Design & Technology Expo 2025 Exhibitor List – exhibitors.lightingdesign-techexpo.com](https://exhibitors.lightingdesign-techexpo.com/lighting-design-technology-expo-2025/Exhibitor)

- [LIVEABLE CITIES X 2025 Exhibitor List – exhibitors.liveablecitiesx.com](https://exhibitors.liveablecitiesx.com/liveable-citiesx-2025/Exhibitor)

- [Orgatec Workspace 2025 Exhibitor List – exhibitors.orgatec-workspace-saudi.com](https://exhibitors.orgatec-workspace-saudi.com/orgatec-workspace-saudi-arabia-2025/Exhibitor) 

- [SAUDI WOOD EXPO 2025 Exhibitor List – exhibitors.saudiwoodexpo.com](https://exhibitors.saudiwoodexpo.com/saudi-wood-expo-2025/Exhibitor)

- [Stationery And Paper Expo 2025 Exhibitor List – exhibitors.stationerypaperexpoksa.com](https://exhibitors.stationerypaperexpoksa.com/the-stationery-paper-expo-saudi-arabia-2025/Exhibitor)

- [Big 5 Construct Kenya 2024 Exhibitor List – exhibitors.big5constructkenya.com](https://exhibitors.big5constructkenya.com/the-big-5-construct-kenya-2024/Exhibitor)

- [Big 5 Construct Kenya 2025 Exhibitor List – exhibitors.big5constructkenya.com](https://exhibitors.big5constructkenya.com/the-big-5-construct-kenya-2025/Exhibitor)

- [HVAC R EXPO Saudi 2025 Exhibitor List – exhibitors.big5constructsaudi.com](https://exhibitors.big5constructsaudi.com/hvac-r-expo-saudi-2025/Exhibitor)

- [Windows, Doors & Facades Saudi 2025 Exhibitor List – exhibitors.big5constructsaudi.com](https://exhibitors.big5constructsaudi.com/windows--doors---facades-saudi-2025/Exhibitor)

- [Marble and Stone Saudi 2025 Exhibitor List – exhibitors.big5constructsaudi.com](https://exhibitors.big5constructsaudi.com/marble-and-stone-saudi-2025/Exhibitor)

- [Saudi FM and Clean 2025 Exhibitor List – exhibitors.big5constructsaudi.com](https://exhibitors.big5constructsaudi.com/saudi-fm-and-clean-2025/Exhibitor)

- [Middle East Coatings Show 2024 Exhibitor List – exhibitors.middleeastcoatingsshow.com](https://exhibitors.middleeastcoatingsshow.com/middle-east-coatings-show-2024/Exhibitor)

- [Saudi Signage & Labelling Expo 2025 Exhibitor List – exhibitors.saudisignageexpo.com](https://exhibitors.saudisignageexpo.com/saudi-signage-labelling-expo-2025/Exhibitor)    

- [Saudi Warehousing & Logistics Expo 2025 Exhibitor List – exhibitors.saudilogisticsexpo.com](https://exhibitors.saudilogisticsexpo.com/saudi-warehousing-and-logistics-and-commercial-vehicle-show-2025/Exhibitor)

- [WORKSPACE 2025 Exhibitor List – exhibitors.workspaceexhibition.com](https://exhibitors.workspaceexhibition.com/workspace-2025/Exhibitor)

- [The Hotel Show 2025 Exhibitor List – exhibitors.thehotelshow.com](https://exhibitors.thehotelshow.com/the-hotelshow-dubai-2025/Exhibitor)

- [WAMPEX West Africa 2025 Exhibitor List – exhibitors.wampexwestafrica.com](https://exhibitors.wampexwestafrica.com/wampex-2025/Exhibitor)

- [South Africa Infrastructure & Water Expo 2025 Exhibitor List – exhibitors.big5constructsouthafrica.com](https://exhibitors.big5constructsouthafrica.com/south-africa-infrastructure-water-expo-2025/Exhibitor)

- [The Big 5 Construct South Africa 2025 Exhibitor List – exhibitors.big5constructsouthafrica.com](https://exhibitors.big5constructsouthafrica.com/the-big-5-construct-south-africa-2025-64/Exhibitor)

- [Transport Evolution 2025 Exhibitor List – exhibitors.transportevolution.com](https://exhibitors.transportevolution.com/transport-evolution-african-forum-and-expo-2025/Exhibitor)

- [FSB Sports Show Riyadh 2025 Exhibitor List – exhibitors.fsb-riyadh.com](https://exhibitors.fsb-riyadh.com/fsb-sports-show-riyadh-2025/Exhibitor)

- [International Hardware Fair Saudi Arabia 2025 Exhibitor List – exhibitors.fsb-riyadh.com](https://exhibitors.fsb-riyadh.com/international-hardware-fair-saudi-arabia-2025/Exhibitor)

- [Coatings For Africa 2024 Exhibitor List – exhibitors.coatingsforafrica.com](https://exhibitors.coatingsforafrica.com/Coatings-for-Africa-2024/Exhibitor)

- [Hotel and Hospitality Expo Saudi Arabia 2025 Exhibitor List – exhibitors.thehotelshowsaudiarabia.com](https://exhibitors.thehotelshowsaudiarabia.com/hotel-and-hospitality-expo-saudi-arabia-2025/Exhibitor)

- [Smart Cities Expo 2025 Exhibitor List – exhibitors.smartcitiessaudiexpo.com](https://exhibitors.smartcitiessaudiexpo.com/smart-cities-expo-2025/Exhibitor)

- [HITEC Dubai 2025 Exhibitor List – exhibitors.thehotelshow.com](https://exhibitors.thehotelshow.com/hitec-dubai-2025/Exhibitor)

---

## Testing Exhibitor List URLs for FREE

- Since I have multiple exhibitor list scraper actors for different types of trade event websites, it might be hard to find the correct actor for your exhibitor list URL.

- Use [**Exhibitor List Scrapers URL Tester**](https://apify.com/skython/exhibitor-list-scrapers-router) actor to test your exhibitor list URLs **for FREE** and see which scraper can process them.

---

## Exhibitor List Scraper - All-In-One Version

- I also provide an **All-In-One** version that combines **my 30+ exhibitor list scrapers** into a single actor.

- Instead of searching for the correct scraper for each event URL, simply provide the event URL and the actor automatically selects the appropriate scraper.

- ➡️ [Exhibitor List Scraper - All-In-One](https://apify.com/skython/exhibitor-list-scraper)

---

## Data Fields

<table>
  <thead>
    <tr>
    <th><span style="font-size:14px;">Company</span></th>
    <th><span style="font-size:14px;">Social</span></th>
    <th><span style="font-size:14px;">Additional</span></th>
    </tr>
  </thead>
    <tbody>
        <tr>
            <td>Profile URL</td>
            <td>LinkedIn</td>
            <td>Hall Stands</td>
        </tr>
        <tr>
            <td>Company Name</td>
            <td>Facebook</td>
            <td>Product Sectors</td>
        </tr>
        <tr>
            <td>Country</td>
            <td>Instagram</td>
            <td>Brands</td>
        </tr>
        <tr>
            <td>Website</td>
            <td>Twitter / X</td>
            <td>Description</td>
        </tr>
        <tr>
            <td>Email</td>
            <td>YouTube</td>
            <td></td>
        </tr>
    </tbody>
</table>

---

## Example Output

```json
{
  "___exhibitor_profile_url": "https://exhibitors.saudiwoodexpo.com/saudi-wood-expo-2025/Exhibitor/ExbDetails/Mzg1NTU=",
  "__company_name": "Al Talah Board Manufacturing Company Ltd.",
  "_company_country": "United Arab Emirates",
  "_company_email": "marketing@eccgroup.ae",
  "_company_website": "https://www.desertboard.ae",
  "_hall_stands": "Stand No- 1B100",
  "_social_url_linkedin": "https://www.linkedin.com/company/desertboard/",
  "_social_url_facebook": "https://www.facebook.com/atb.desertboard",
  "_social_url_instagram": "https://www.instagram.com/desertboard/",
  "_social_url_twitter": "https://x.com/desertboard_ae",
  "_social_url_youtube": "https://www.youtube.com/@DesertBoard",
  "company_description": "DesertBoard is the manufacturer of the region’s most sustainable building material...",
  "product_sectors": [
    "Furniture accessories and components",
    "hardwood and softwood",
    "Wood composites",
    "Wood windows and doors",
    "Flooring and decking"
  ]
}
```

---

## My Other Exhibitor List Scrapers

- [Exhibitor List Scraper - All-In-One](https://apify.com/skython/exhibitor-list-scraper)

- [Koelnmesse Exhibitor List Scraper](https://apify.com/skython/koelnmesse-exhibitor-list-scraper)

- [Messe Frankfurt Exhibitor List Scraper](https://apify.com/skython/messe-frankfurt-exhibitor-list-scraper)

- [Map Your Show Exhibitor List Scraper](https://apify.com/skython/map-your-show-exhibitor-list-scraper)

- [Messe Düsseldorf Exhibitor List Scraper](https://apify.com/skython/messe-duesseldorf-exhibitor-list-scraper)

- [Reed Expo Exhibitor List Scraper](https://apify.com/skython/reed-expo-exhibitor-list-scraper)

- [Messe München Exhibitor List Scraper](https://apify.com/skython/messe-muenchen-exhibitor-list-scraper)

- [Xporience Exhibitor List Scraper V2](https://apify.com/skython/xporience-exhibitor-list-scraper-2)

- [Nürnberg Messe Exhibitor List Scraper](https://apify.com/skython/nuernberg-messe-exhibitor-list-scraper)

- [GSMA MWC Exhibitor List Scraper](https://apify.com/skython/gsma-mwc-exhibitor-list-scraper)

- [Messe Berlin Exhibitor List Scraper](https://apify.com/skython/messe-berlin-exhibitor-list-scraper)

- [AFAG Messe Exhibitor List Scraper](https://apify.com/skython/afag-messe-exhibitor-list-scraper)

- [Messe Stuttgart Exhibitor List Scraper](https://apify.com/skython/messe-stuttgart-exhibitor-list-scraper)

- [Messe Essen Exhibitor List Scraper](https://apify.com/skython/messe-essen-exhibitor-list-scraper)

- [Informa Markets Exhibitor List Scraper](https://apify.com/skython/informa-markets-exhibitor-list-scraper)

- [Informa Markets Exhibitor List Scraper V2](https://apify.com/skython/informa-markets-exhibitor-list-scraper-2)

- [Ungerboeck Exhibitor List Scraper](https://apify.com/skython/ungerboeck-exhibitor-list-scraper)

- [A2Z Events Exhibitor List Scraper](https://apify.com/skython/a2z-events-exhibitor-list-scraper)

- [Deutsche Messe Exhibitor List Scraper](https://apify.com/skython/deutsche-messe-exhibitor-list-scraper)

- [Newfront Exhibitor List Scraper](https://apify.com/skython/newfront-exhibitor-list-scraper)

- [Goeshow Exhibitor List Scraper](https://apify.com/skython/goeshow-exhibitor-list-scraper)

- [EasyFairs Exhibitor List Scraper](https://apify.com/skython/easyfairs-exhibitor-list-scraper)

- [IEG Expo Exhibitor List Scraper](https://apify.com/skython/ieg-expo-exhibitor-list-scraper)

- [The Smarter E Exhibitor List Scraper](https://apify.com/skython/the-smarter-e-exhibitor-list-scraper)

- [Schall Messen Exhibitor List Scraper](https://apify.com/skython/schall-messen-exhibitor-list-scraper)

- [Messe München Exhibitor List Scraper V2](https://apify.com/skython/messe-muenchen-exhibitor-list-scraper-2)

- [Comexposium Exhibitor List Scraper](https://apify.com/skython/comexposium-exhibitor-list-scraper)

- [IME Events Exhibitor List Scraper](https://apify.com/skython/ime-events-exhibitor-list-scraper)

- [ANDMORE Exhibitor List Scraper](https://apify.com/skython/andmore-exhibitor-list-scraper)

- [Comexposium Exhibitor List Scraper V2](https://apify.com/skython/comexposium-exhibitor-list-scraper-2)

- [Informa Markets Exhibitor List Scraper V3](https://apify.com/skython/informa-markets-exhibitor-list-scraper-3)