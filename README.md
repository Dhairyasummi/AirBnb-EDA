# 🏙️ Airbnb NYC 2019 Data Analysis & Visualization

This project delivers exploratory data analysis (EDA), cleaning, visualization, and business insights using the publicly available **Airbnb New York City 2019** dataset. The objective is to uncover trends in pricing, availability, and listing behaviour that can drive smarter, data‑informed decision‑making for Airbnb.

---

## 📌 Project Objective
- **Quantify** listing and pricing patterns across NYC boroughs and neighbourhoods.  
- **Identify** high‑performing room types and availability strategies.  
- **Surface** opportunities for growth in under‑served areas.  
- **Recommend** tactics that improve bookings, host success, and guest satisfaction.

---

## 📁 Dataset
| Field | Description |
|-------|-------------|
| `id`, `name`, `host_id` | Listing & host identifiers |
| `neighbourhood_group` / `neighbourhood` | Borough & neighbourhood names |
| `room_type` | Entire home/apt, private room, shared room |
| `price`, `minimum_nights` | Core pricing & stay requirements |
| `number_of_reviews`, `reviews_per_month` | Demand / engagement metrics |
| `availability_365` | Days available for booking |

Source: **Inside Airbnb** (http://insideairbnb.com/) – NYC 2019 snapshot.

---

## 🧰 Tech Stack
```python
pandas       # data wrangling
numpy        # numeric utilities
matplotlib   # plotting basics
seaborn      # statistical visualisations
warnings     # tidy notebook output
