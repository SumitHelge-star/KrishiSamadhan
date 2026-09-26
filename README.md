# 🌾 KrishiSamadhan (कृषि समाधान)

> **Transforming Imperfect Harvests into Sustainable Profits**  
> A circular agri-tech platform connecting farmers with commercial food processors, animal feed centers, and composting partners to eliminate food waste and maximize farmer revenue.

---

## 🌟 Overview

Every year, over **30% of agricultural produce** is discarded or sold at heavy losses due to cosmetic imperfections, size variations, or market gluts (Grade B & C crops). 

**KrishiSamadhan** creates a direct, transparent circular supply chain network:
- 🧑‍🌾 **Farmers** can list surplus, non-standard, or Grade B/C harvests directly.
- 🏭 **Buyers** (Food processing industries, juice/puree manufacturers, livestock feed suppliers, and composting units) can procure quality produce at cost-effective bulk rates.
- ♻️ **Environment & Society** benefits from reduced landfill waste, lower carbon emissions, and circular resource recovery.

---

## ✨ Key Features

### 🚜 1. Farmer Portal
- **Intuitive Produce Listing:** Quick onboarding with crop details, grade classification (Grade B / Grade C), quantity, harvest date, and expected price.
- **Smart Grading & Pricing Guidance:** Categorize harvest suitability (e.g., pulp/juice extraction vs. animal feed vs. composting).
- **Listing Management:** Real-time dashboard to monitor listings, offers, and pickup statuses.

### 🏢 2. Buyer Marketplace
- **Direct B2B Sourcing:** Browse verified farmer batches with transparent pricing and volume discounts.
- **Category & Grade Filtering:** Filter by intended use (Juice/Pulp Processing, Puree/Dehydration, Animal Feed, Bio-Energy, Organic Compost).
- **Secure Procurement Pipeline:** Direct connection with local agricultural clusters, reducing transportation time and preserving freshness.

### 📊 3. Impact & Sustainability Tracker
- **Real-Time Carbon & Waste Metrics:** Visualizing metric tons of food waste diverted from landfills.
- **Economic Upliftment Stats:** Tracking incremental income generated for smallholder farming communities.
- **Emissions Reduction:** Demonstrating localized circular logistics impact.

### 🎨 4. Modern Glassmorphism UI & Experience
- Fluid micro-animations and page transitions powered by **Framer Motion**.
- Tailored color palette with dynamic dark glass aesthetics.
- Fully responsive across desktop, tablet, and mobile devices.

---

## 🛠️ Tech Stack

### Frontend (`/client`)
- **Core:** [React 19](https://react.dev/) + [Vite](https://vitejs.dev/)
- **Routing:** [React Router v7](https://reactrouter.com/)
- **Animations:** [Framer Motion](https://www.framer.com/motion/)
- **Styling:** Custom Modular CSS / Glassmorphism Design System
- **Linting & Code Quality:** ESLint 9

### Backend (`/server`)
- **Environment:** Node.js

---

## 📁 Project Structure

```text
krushisamadhan/
├── client/
│   ├── public/              # Static assets & icons
│   ├── src/
│   │   ├── assets/          # Images and SVGs
│   │   ├── components/      # Reusable UI components
│   │   │   ├── AnimatedBackground.jsx
│   │   │   ├── AnimatedCounter.jsx
│   │   │   ├── Footer.jsx
│   │   │   ├── GlassCard.jsx
│   │   │   ├── Navbar.jsx
│   │   │   └── PageTransition.jsx
│   │   ├── pages/           # Application views/routes
│   │   │   ├── BuyerPortal.jsx    # B2B buyer marketplace & order flow
│   │   │   ├── FarmerPortal.jsx   # Farmer listing & inventory management
│   │   │   ├── HowItWorks.jsx     # End-to-end circular flow visualization
│   │   │   ├── Impact.jsx         # Sustainability & environmental metrics
│   │   │   └── Landing.jsx        # Interactive hero & platform highlights
│   │   ├── App.css          # Core platform styling & utilities
│   │   ├── App.jsx          # Route declarations & navigation transitions
│   │   ├── index.css        # Typography, CSS tokens & global variables
│   │   └── main.jsx         # React application entry point
│   ├── package.json
│   ├── vercel.json          # Client SPA routing configuration for Vercel
│   └── vite.config.js
├── server/
│   └── package.json
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites
Make sure you have [Node.js](https://nodejs.org/) (version 18+ recommended) and `npm` installed.

### 1. Clone the Repository
```bash
git clone https://github.com/SumitHelge-star/KrishiSamadhan.git
cd KrishiSamadhan/client
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Run Development Server
```bash
npm run dev
```
Open your browser and navigate to `http://localhost:5173`.

### 4. Build for Production
```bash
npm run build
```

---

## 🌐 Deployment

The frontend includes a pre-configured `vercel.json` for single-page routing:

1. Import the repository into [Vercel](https://vercel.com/).
2. Set the **Root Directory** to `client`.
3. Framework Preset: **Vite**.
4. Click **Deploy**.

---

## 🤝 Contributing

Contributions are welcome! If you'd like to improve KrishiSamadhan:
1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m "Add some AmazingFeature"`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 💬 Contact & Support

Developed by **[Sumit Helge](https://github.com/SumitHelge-star)**  
Feel free to open an issue or connect for collaborations!
