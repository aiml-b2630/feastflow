# FeastFlow - Event Catering Marketplace & Quote Calculator

FeastFlow is a fullstack food & catering marketplace web application built with React, Node.js/Express, and Tailwind CSS. It empowers event organizers (student clubs, wedding planners, corporate event teams) to calculate dynamic volume-discounted catering quotes, customize course-by-course menus, compare vendors side-by-side, and request food tasting sessions.

## Project Structure
- `client/`: React 18 SPA (React Router, Context API, Tailwind CSS, Lucide icons)
- `server/`: Node.js Express REST API with SQLite / Mock DB seed datasets

## Quick Start

### 1. Start Backend Server
```bash
cd server
npm install
npm start
```
Server runs on `http://localhost:5000`

### 2. Start Frontend App
```bash
cd client
npm install
npm start
```
Client runs on `http://localhost:3000`

## Core Features
1. **Interactive Catering Services & Package Table**: Flexbox layout displaying curated tiers (Silver, Gold, Platinum) and service capabilities.
2. **Dynamic Catering Quote Calculator**: Live per-plate and total cost recalculation driven by guest count sliders (50 to 500 guests).
3. **Volume-Tiered Discounting Heuristic**:
   - 50-99 guests: 0% discount
   - 100-199 guests: 5% bulk discount
   - 200+ guests: 10% bulk discount
4. **Course-by-Course Menu Selector**: Select Starters, Mains, Breads, Desserts, and Live Food Counters.
5. **Dietary segregator**: Dual headcount calculator for Veg, Non-Veg, and Jain diets.
6. **Side-by-Side Vendor Comparison**: Direct matrix comparing per-plate pricing, ratings, guest capacities, and menu inclusions.
7. **Tasting Session Booking Modal**: Request pre-event tasting appointments with date and venue pickers.
8. **Digital Quotation Exporter**: Print-ready breakdown for college committee and corporate budget approvals.
