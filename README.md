# Chittagong Real Estate Data and Analysis (August 2025)

This repository contains a curated dataset of commercial real estate listings in Chittagong, Bangladesh. The dataset was collected and enriched in August 2025. It includes structured property details, pricing, location metadata, proximity to amenities, and scoring metrics to support decision-making for real estate investors, analysts, or urban planners.

---

## 📂 File Included

- **Chittagong_Real_Estate_Data_2025(August).xlsx**  
  Contains 31 columns with enriched commercial property listings.

---

## 📊 Data Dictionary

| Column | Description |
|--------|-------------|
| `sku` | Unique listing ID for internal tracking. |
| `price_value` | Listed price (in BDT). |
| `category` | Main type of property (e.g. commercial). |
| `subcategories` | Specific sub-type (e.g. shops, offices). |
| `floor_area_sqft` | Floor area in square feet. |
| `bedrooms` | Number of bedrooms (may be blank for commercial). |
| `bathrooms` | Number of bathrooms (may be blank for commercial). |
| `occupancy_status` | Whether the property is currently vacant or occupied. |
| `geo_point` | Combined `longitude,latitude` for spatial mapping. |
| `link_url` | Direct link to the listing page. |
| `title` | Listing title as shown online. |
| `address` | Full address of the property. |
| `description` | Text description from the original listing. |
| `longitude` | Geographic longitude coordinate. |
| `latitude` | Geographic latitude coordinate. |
| `price_per_sqft` | Price divided by total floor area. |
| `invalid_data_flag` | Marks if the listing has missing or inconsistent data. |
| `area_zone` | Name of the neighborhood or zone in Chittagong. |
| `nearest_hospital` | Closest hospital to the listing. |
| `dist_to_hospital_km` | Distance to that hospital (in km). |
| `nearest_school` | Closest school to the property. |
| `dist_to_school_km` | Distance to the school (in km). |
| `nearest_shopping` | Nearest shopping mall or center. |
| `dist_to_shopping_km` | Distance to that shopping location (in km). |
| `nearest_station` | Closest major transport terminal (bus/train). |
| `dist_to_station_km` | Distance to that station (in km). |
| `walkability_score` | Whether the property is pedestrian-friendly:  
  `1` = walkable (close to daily needs),  
  `0` = not walkable. |
| `population_density_band` | Indicates how crowded the surrounding area is:  
  - `Low` = sparsely populated  
  - `Medium` = moderate density  
  - `High` = heavily populated |
| `competitive_price_score` | Compares price to nearby similar listings:  
  - `1` = competitively priced or cheaper  
  - `0` = above local market value |
| `popularity_score` | Relative demand signal based on user interactions (e.g. views, interest). Higher = more popular. |
| `lead_hotness_score` | Composite score (0 to 1) predicting how quickly this property may attract leads. Higher = hotter lead. |

---

## 🧠 Example Use Cases

- **Market analysis**: Compare listing prices across zones.
- **Mapping**: Visualize property locations using `latitude` & `longitude`.
- **Dashboards**: Build Power BI or Tableau dashboards for stakeholders.
- **Lead Scoring**: Use `lead_hotness_score` to prioritize outreach.
- **Competitor Benchmarking**: Use `competitive_price_score` to flag overpriced assets.

---

## 🛠 Recommended Tools

- **Python**: pandas, seaborn, folium, scikit-learn  
- **Excel / Power BI / Tableau**  
- **GIS tools**: QGIS, ArcGIS (for mapping using `geo_point`)

---

## 📬 Contact

**Fahmid Al Jaber**  
📧 fahmidaljaber2025@gmail.com  
🔗www.linkedin.com/in/fahmid-al-jaber

