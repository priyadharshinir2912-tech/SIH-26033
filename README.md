# Smart India Hackathon Workshop
# Date:24/11/2026
## Reference Number:26018305
## Name: PRIYADHARSHINI R

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.

• Provides logistics support.

• Uses AI for demand forecasting and route optimization.

**Benefits:**

• Better prices for farmers.

• Lower prices for consumers.

• Reduced supply chain inefficiencies.

## Proposed Solution

**1. Detailed explanation**
FarmLink is a digital marketplace (web + mobile app) where farmers and FPOs list their produce directly, and consumers and bulk buyers (restaurants, retailers, hostels, canteens) purchase it without middlemen.

  1.Farmer/FPO side: Easy listing with photos, quantity, and expected harvest date. Available in regional languages with voice support.
  
  2.Buyer side: Direct buying, bulk orders, subscription baskets (weekly vegetables), and price comparison.
  
  3.Logistics: Pickup from village collection points, shared transport, and cold-chain partners.
  
  4.AI layer: Demand forecasting, price suggestion, and route optimization.

  **2. How it addresses the problem**
  
  1.Removes multiple intermediaries (agent, wholesaler, retailer), so the farmer gets a larger share of the final price.
  
  2.Consumers get fresher produce at a lower price.
  
  3.Forecasting tells farmers what to grow and sell, which reduces wastage and distress selling.
  
  4.Route optimization and pooled shipments cut transport cost.

**3. Innovation and uniqueness**

  1.Price transparency: each order shows a breakdown of farmer share vs logistics vs platform fee.
  
  2.AI-based fair price suggestion using mandi rates, season, and demand.
  
  3.Demand-based pre-booking, so farmers know the buyer before harvest.
  
  4.Voice-based listing in Tamil, Hindi, and other languages for low-literacy users.
  
  5.FPO dashboard for aggregation and bulk deals.
  
## Technical Approach

**1. Technologies**

1.Frontend: React.js (web), Flutter or React Native (mobile)

2.Backend: Node.js (Express) or Python (FastAPI)

3.Database: PostgreSQL (orders, users), MongoDB (listings)

4.AI/ML: Python, scikit-learn, Prophet/LSTM for demand forecasting; Google OR-Tools for route optimization

5.Maps and tracking: Google Maps API or OpenStreetMap

6.Payments: UPI / Razorpay

7.Cloud: AWS / Azure

8.Others: Speech-to-text API for voice listing, SMS/WhatsApp alerts

**2. Methodology and process**

1.Farmer/FPO registers and lists produce.

2.The platform suggests a fair price using the AI model.

3.Buyer browses, orders, and pays online.

4.The system assigns the nearest pickup point and the best delivery route.

5.Produce is delivered, payment is released to the farmer, and ratings are collected.

6.Order data feeds back into the forecasting model.

## Technical Flow Diagram

```
+--------------------------+
| Farmers and FPOs         |
+--------------------------+

             |
             v
             
+--------------------------+
| Crop and Harvest Details |
+--------------------------+

             |
             v
             
+--------------------------+
| Buyer Demand Booking     |
+--------------------------+

             |
             v
             
+--------------------------+
| Demand and Supply        |
| Matching System          |
+--------------------------+

             |
             v
             
+--------------------------+
| Village Collection Hub   |
+--------------------------+

             |
             v
+--------------------------+
| Retailers, Hotels and    |
| Other Buyers             |
+--------------------------+
```

## Feasibility and Viability

**1. Feasibility**

1.Technical: Uses mature, widely available technologies.

2.Operational: Can start as a pilot with one district and a few FPOs.

3.Economic: Revenue from a small commission (2-5%), logistics margin, and premium analytics for FPOs.

4.Policy fit: Aligns with Digital India, eNAM, and government FPO schemes.

**2. Challenges and risks**

1.Farmers' low digital literacy

2.Trust and quality assurance

3.Last-mile logistics in rural areas

4.Perishable goods and spoilage

5.Limited internet connectivity

**3. Strategies to overcome**

1.Voice-based, regional-language UI plus local "Kisan Mitra" agents

2.Quality grading, ratings, and photo verification

3.Local collection hubs and pooled delivery

4.Cold-chain partnerships and demand-based harvesting

5.Offline-friendly app with SMS fallback


## Impact and Benefits

**1. Impact on target audience**

1.Farmers/FPOs: Higher income, faster payment, market access

2.Consumers: Fresh produce at lower prices

3.Bulk buyers: Reliable supply and transparent pricing

4.Government: Better visibility of supply-demand data

**2. Benefits**

1.Social: Empowers small farmers and women-led FPOs, and encourages rural entrepreneurship

2.Economic: Reduced intermediary margins, increased farmer income, stable consumer prices

3.Environmental: Less food wastage and fewer transport emissions through optimized routes

## Research and References

1. Smart India Hackathon Problem Statement Repository: https://github.com/selvasachein/SIH-26033
2. Django Documentation: https://docs.djangoproject.com/
3. Ministry of Agriculture and Farmers Welfare: https://agriwelfare.gov.in/
4. OpenStreetMap: https://www.openstreetmap.org/
