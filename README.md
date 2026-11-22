# Smart India Hackathon Workshop
# Date:22.11.2026
## Reference Number:26010031
## Name:Dharshini.S

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

Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution
Detailed explanation

KisanLink is a digital marketplace that connects farmers and Farmer Producer Organizations (FPOs) directly with consumers and bulk buyers. Its key feature is that farmers can use it by voice, in their own language. A farmer sends a voice note or makes a call, such as "200 kg tomatoes, ready in two days." The system converts the speech to text and creates a product listing automatically. Buyers browse the listings on a web app, place orders and pay by UPI, and the money goes directly to the farmer. Produce is collected at a village hub and delivered using AI-planned routes.

How it addresses the problem

1.Farmers sell directly, so the commission taken by middlemen is removed.

2.The AI engine shows today's mandi price and a suggested fair price, so farmers are not underpaid.

3.Demand forecasting tells farmers what buyers will need, which reduces unsold stock and wastage.

4.Village hubs combine produce from many small farmers, making bulk delivery cheap.

5.Consumers get fresher produce at lower prices because the supply chain is shorter.

**Innovation and uniqueness**

1.Voice-first access in local languages, so farmers with low digital literacy can use it without learning an app.

2.Village collection hubs that make logistics affordable for small and marginal farmers.

3.One platform combining direct selling, AI price guidance, demand forecasting and route optimization.
## Technical Approach
Technologies to be used

1.Farmer interface: WhatsApp voice notes and IVR phone calls

2.Speech-to-text: Bhashini or OpenAI Whisper (supports Indian languages)

3.Buyer interface: React web application

4.Backend: Python (FastAPI) or Node.js

5.Database: PostgreSQL

6.AI/ML: Time-series forecasting (Prophet or LSTM) for demand and price prediction

7.Route optimization: Google OR-Tools with Google Maps API

8.Payments: UPI integration (e.g. Razorpay)

9.Hosting: Cloud platform (AWS or Azure)

Methodology and process for implementation

1.The farmer sends a voice note or calls to list produce.

2.The speech-to-text module converts it into text in the local language.

3.The listing (crop, quantity, date) is stored in the database.

4.The AI engine suggests a fair price and forecasts demand.

5.The buyer browses the web app and places an order.

6.The buyer pays by UPI and the amount is credited directly to the farmer.

7.The route planner assigns pickup from the village hub and plans the delivery route.

8.The produce is delivered from the hub to the buyer.

<img width="853" height="745" alt="Screenshot 2026-11-22 174619" src="https://github.com/user-attachments/assets/e5a44549-2cd4-4336-a687-582765954e49" />



## Feasibility and Viability
Analysis of the feasibility of the idea

The idea is realistic with existing tools. WhatsApp and UPI are already widely used in rural India. Speech-to-text for Indian languages is available through government and open-source platforms, and the AI components use proven libraries. A small pilot can start in one district with a few FPOs.

Potential challenges and risks

1.Perishable produce can spoil during transport.

2.Farmers may not trust a new platform.
3.Rural internet connectivity can be weak.

4.Last-mile delivery is costly.

5.Speech recognition may struggle with local accents.

Strategies for overcoming these challenges

1.Use village hubs with basic storage and fast pickup schedules.

2.Work with trusted FPOs and local agriculture officers to build confidence.

3.Offer IVR phone calls so the system works without internet.

4.Combine many small orders at the hub to reduce delivery cost.

5.Keep improving the speech model with local-language samples, and confirm each listing back to the farmer by voice.

## Impact and Benefits
Potential impact on the target audience

1.Farmers: Higher income, faster payment and fair price information.

2.Consumers: Fresher produce at lower prices.

3.Bulk buyers and retailers: Reliable direct supply with transparent pricing.

Benefits of the solution

1.Social: Includes farmers who are less educated or less tech-savvy, and strengthens FPOs and rural communities.

2.Economic: Farmers keep a larger share of the final price, and value lost in the supply chain is reduced.

3.Environmental: Demand forecasting reduces food waste, and optimized routes save fuel and cut emissions.

## Research and References
1.SIH 26033 problem statement, Ministry of Consumer Affairs, Food & Public Distribution

2.Agmarknet (mandi price data): https://agmarknet.gov.in

3.eNAM, National Agriculture Market: https://enam.gov.in

4.Bhashini, Government of India language platform: https://bhashini.gov.in

5.Google OR-Tools documentation (route optimization)
