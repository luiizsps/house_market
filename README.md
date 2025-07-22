# House Market

Imagine you're a real estate investor in King County, USA. You want to buy a house and resell it, aiming for the highest possible profit. In this project, we will explore house sales data from the region to answer the following questions:

- Which house should you buy? What is the estimated purchase cost?
- When should you sell the house? For how much?
- Should you renovate the house to increase its selling price? What changes are recommended? How much value does each renovation option add?

## Dataset

Our dataset contains the following information:

| Column             | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| **id**             | Unique identifier for the property.                                         |
| **date**           | Date of the property's sale record.                                         |
| **price**          | Sale price of the property (in USD).                                        |
| **bedrooms**       | Number of bedrooms in the house.                                            |
| **bathrooms**      | Number of bathrooms (may include fractions, such as 1.5).                   |
| **sqft_living**    | Usable indoor living area in square feet (1 ft² ≈ 0.093 m²).                |
| **sqft_lot**       | Total lot area in square feet.                                              |
| **floors**         | Number of floors in the house.                                              |
| **waterfront**     | Indicates if the property has a waterfront view (0 = no, 1 = yes).          |
| **view**           | View quality index (scale from 0 to 4).                                     |
| **condition**      | Overall condition index (scale from 1 to 5).                                |
| **grade**          | Property's construction and design quality (scale from 1 to 13).            |
| **sqft_above**     | Square footage of the area above ground level.                              |
| **sqft_basement**  | Square footage of the basement area.                                        |
| **yr_built**       | Year the property was built.                                                |
| **yr_renovated**   | Year of the last renovation (0 if never renovated).                         |
| **zipcode**        | Zip code of the property's location.                                        |
| **lat**            | Latitude of the property's geographical location.                           |
| **long**           | Longitude of the property's geographical location.                          |
| **sqft_living15**  | Average indoor living area of the 15 nearest houses, in square feet.        |
| **sqft_lot15**     | Average lot area of the 15 nearest houses.                                  |

---

## 🧱 Project Structure

house_market/
│

├── datasets/

├── house_market.ipynb

├── README.md

└── requirements.txt

---

## 🚀 Installation

Follow these steps to set up the project locally:

1. **Clone the repository**
```bash
git clone https://github.com/luiizsps/house_market.git
cd house_market/
```

---

## Create a virtual environment

```bash
python -m venv venv
source venv/bin/activate 
```

---

## Install dependencies

```bash
pip install -r requirements.txt
```

