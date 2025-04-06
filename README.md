BallinOnABudget is a full-stack web application that helps users save time and money while grocery shopping. Based on the user's location and grocery list, the app scrapes current prices and deals from nearby stores, then generates three optimized shopping strategies:

🔍 Features
Money Saver – Minimizes total cost by shopping across multiple stores.
Balanced Saver – Recommends the best route based on a mix of cost and travel time.
Time Saver – One-stop shop strategy with the lowest total price.
⚙️ Tech Stack
Frontend: React, TypeScript, Tailwind, Vite
Backend: Node.js, Express
Database: MongoDB Atlas via Mongoose
Scraping: Puppeteer (for JavaScript-heavy grocery websites)
AI Parsing: Gemini API (to extract structured item/price data from scraped content)
Location Services: Google Maps Distance Matrix API
📦 How It Works
Users create a grocery list in the app.
The backend uses Google Maps API to find nearby grocery stores.
For each store:
Puppeteer scrapes the weekly ad or pricing page
Gemini API extracts item names, prices, and deals into structured JSON
Data is stored in MongoDB Atlas
The app uses pricing and distance data to return three optimized strategies.
