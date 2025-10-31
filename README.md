   # 🕸️ Web Scraping Projects – Glam & Glow | Lisa

A pair of practical web scraping projects showcasing **Python-based data extraction**, **automation**, and **data cleaning** using **Selenium** and **BeautifulSoup**.  
These projects demonstrate my ability to collect, clean, and structure data for analytics and research applications.

---

## 📁 Project 1: Glam & Glow Scraper (Selenium)

**Directory:** `glamandglow/`  
**Technology:** Selenium, Pandas, Requests, BeautifulSoup  

### 🧠 Overview  
The **Glam & Glow Scraper** automates data collection from an e-commerce site, capturing product information such as names, prices, categories, and image URLs.  
It demonstrates how Selenium can be used to navigate dynamic web pages and extract structured datasets for analytics.

### ⚙️ Features  
- ✅ Automated navigation using **Selenium WebDriver**  
- 🛍️ Scrapes product name, brand, price, category, and image URL  
- 🧹 Cleans and preprocesses data with **Pandas**  
- 🖼️ Downloads product images into a local `/images` folder  
- 💾 Exports the final dataset as `glamandglow.csv`  

### 🧩 Tech Stack  
| Component | Library |
|------------|----------|
| Automation | Selenium |
| Data Cleaning | Pandas |
| Export | CSV |
| Storage | Local Directory |

### 📊 Sample Output  
```csv
Product ID	Product Name	Product Type	Category	Brand Name	Product Line Name	Ingredients	Use Instructions	Package Size	Product Description	Product Colour	Country of Origin	Date Added	Barcode (EAN/UPC)	Barcode Type (e.g., EAN-13, UPC-A)	Batch Number	SKU	Benefits	Product Image URL	Hero Ingriedients Match	Key Ingriedients	Key Ingriedients2	Key Ingriedients3	Key Ingriedients4	Key Ingriedients5	Product Images	Verification Status	Verification Date	Notes (For internal use: flags, manual checks, comments, etc.)	Source	Ingredients_From_Description
Vef_GLAMANDGLOW_1	SALTAIR EXOTIC PULP BODY OIL	Skin Care	oil	Saltair Exotic		AROMA, CREAM, SILK, TIN			"ingredients to absorb easily and leave your skin feeling dewy and looking incredible.
EXOTIC PULP SCENT: Sparkling aroma that is juicy, fruity and distinct. Key Notes: Juicy Orange. Succulent Guava. Breezy Musk.
LIGHTWEIGHT MOISTURE: Our Body Oil is a lightweight way to keep your skin moisturized each day, and is easy to layer with your favorite Saltair Moisturizer if you need a little bit of extra moisture on dry days.
MADE FOR ALL SKIN TYPES: Developed for all skin types and suitable for daily use. Helps nourish and improve the overall skin appearance. Lightweight, creamy and leaves skin feeling moisturized and silky, never greasy.
GOOD FOR SKIN. GOOD FOR THE WORLD: All Saltair products are Cruelty Free, Vegan, Paraben Free and Gluten Free. We are a brand built on care, and like our motto says, we truly believe every body is welcome here."			11/09/2025					NOURISH YOUR BODY: Our sensorial body oil is formulated with natural and botanical	https://glamandglowbeautyhub.shop/cdn/shop/files/FullSizeRender_0f9dd191-ffcb-42d3-9d0f-e16f817d6826_2048x.jpg?v=1717598398, https://glamandglowbeautyhub.shop/cdn/shop/files/FullSizeRender_f3c6925c-a1f7-485f-b493-6842a77917d8_2048x.jpg?v=1717598398							Vef_GLAMANDGLOW_1_1.jpg, Vef_GLAMANDGLOW_1_2.jpg				https://glamandglowbeautyhub.shop/collections/all/products/saltair-exotic-pulp-body-oil	, AROMA, CREAM, SILK, TIN

```

---

## 📁 Project 2: Lisa Scraper (BeautifulSoup)

**Directory:** `lisa/`  
**Technology:** BeautifulSoup, Requests, Pandas  

### 🧠 Overview  
The **Lisa Scraper** is a lightweight HTML parser built using **BeautifulSoup** to extract product and review data from static pages.  
It focuses on fast and efficient data gathering without the need for browser automation.

### ⚙️ Features  
- 🌐 Fetches static HTML pages using **Requests**  
- 🧭 Extracts product names, reviews, ratings, and prices  
- 🧹 Cleans and structures the dataset for analysis  
- 💾 Saves output as `lisa_products.csv`  

### 🧩 Tech Stack  
| Component | Library |
|------------|----------|
| HTML Fetching | Requests |
| Parsing | BeautifulSoup |
| Data Cleaning | Pandas |
| Export | CSV |

### 📊 Sample Output  
```csv
product_name,review,rating,price
Hydrating Lotion,"Great texture, absorbs fast",4.5,25.00
Face Wash,"Cleanses deeply, mild scent",4.8,18.99
```

---

## 🧠 Key Learnings
- Built **end-to-end web scrapers** for dynamic (Selenium) and static (BeautifulSoup) sites  
- Applied **data preprocessing** to ensure clean, structured CSV outputs  
- Managed **local image storage and file I/O pipelines**  
- Developed **modular and maintainable Python code** suitable for scaling or automation  

---

## 🚀 How to Run
1. **Clone the repository**
   ```bash
   git clone https://github.com/Pathogenic-cmd/Web-Automation.git
   cd Web-Automation
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run each scraper**
   ```bash
   # Selenium-based scraper
   python glamandglow/scraper.py

   # BeautifulSoup-based scraper
   python lisa/scraper.py
   ```

4. **View output files**
   ```
   glamandglow/glamandglow_products.csv
   lisa/lisa_products.csv
   ```

---

## 👨🏽‍💻 Author
**Daniel Kofi Debrah Awuma**  
Python developer passionate about building data-driven applications and intelligent automation tools.  

🌍 [GitHub: Pathogenic-cmd](https://github.com/Pathogenic-cmd)  
💼 [Portfolio: my-online-store.streamlit.app](https://my-online-store.streamlit.app)

---

## 🪪 License
This project is released under the **MIT License** — free to use, modify, and distribute.
