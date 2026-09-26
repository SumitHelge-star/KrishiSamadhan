# 🌾 KrishiSamadhan

### Transforming Imperfect Harvests into Sustainable Profits

**KrishiSamadhan** is a full-stack circular AgriTech platform that connects farmers with food-processing industries, animal-feed suppliers, and composting partners to create value from **surplus and non-standard agricultural produce**.

Instead of allowing Grade B/C or cosmetically imperfect crops to be wasted or sold at extremely low prices, the platform enables farmers to directly list their produce and allows relevant buyers to discover, procure, and utilize it for alternative applications.

---

## 🎯 Problem Statement

A significant amount of agricultural produce is wasted or sold at heavily discounted prices because of:

* Cosmetic imperfections
* Size and quality variations
* Excess production
* Market gluts
* Limited access to suitable buyers

This creates both **economic losses for farmers** and **environmental problems caused by agricultural waste**.

### 💡 Our Solution

KrishiSamadhan creates a **circular agricultural marketplace** where:

```text
        👨‍🌾 FARMER
           │
           │ Lists surplus / Grade B-C produce
           ▼
   ┌─────────────────────┐
   │   KRISHISAMADHAN    │
   │   B2B MARKETPLACE   │
   └─────────────────────┘
           │
     ┌─────┼─────────┬──────────┐
     ▼     ▼         ▼          ▼
   🏭 Food   🐄 Feed   ♻️ Compost  ⚡ Bio-energy
   Processing
```

This helps convert **waste into economic value** while building a more sustainable agricultural supply chain.

---

## ✨ Key Features

### 👨‍🌾 Farmer Portal

Farmers can:

* Create produce listings
* Specify crop/produce details
* Select Grade B or Grade C classification
* Enter available quantity
* Add harvest date
* Set expected price
* Track active listings
* Monitor offers and pickup status

### 🏭 Buyer Marketplace

Businesses can:

* Browse available agricultural produce
* Discover farmer batches
* Filter produce based on grade
* Filter according to intended use
* View quantity and pricing information
* Procure produce directly from farmers

Supported use cases include:

* 🧃 Juice & Pulp Processing
* 🥫 Puree & Dehydration
* 🐄 Animal Feed
* ⚡ Bio-Energy
* ♻️ Organic Compost

### 📊 Impact & Sustainability Dashboard

KrishiSamadhan also focuses on measuring the impact created by the circular supply chain.

The platform can visualize:

* Food waste diverted from landfills
* Additional economic value generated
* Farmer income upliftment
* Estimated environmental benefits
* Circular resource recovery

### 🎨 Modern User Experience

The platform uses a modern **glassmorphism-inspired UI** with:

* Responsive design
* Dark glass aesthetics
* Animated components
* Smooth page transitions
* Interactive dashboards
* Mobile, tablet and desktop support

---

# 🏗️ System Architecture

```text
                    ┌─────────────────────┐
                    │       USER          │
                    │ Farmer / Buyer      │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │   React Frontend    │
                    │      + Vite         │
                    └──────────┬──────────┘
                               │
                        HTTP / REST
                               │
                               ▼
                    ┌─────────────────────┐
                    │   Node.js Server    │
                    │      Backend        │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Business Logic /    │
                    │ API Layer           │
                    └─────────────────────┘
```

The project is organized into separate frontend and backend layers:

```text
KrishiSamadhan/
│
├── client/                 # React frontend
│   ├── public/
│   └── src/
│       ├── assets/
│       ├── components/
│       ├── pages/
│       ├── App.jsx
│       ├── App.css
│       ├── index.css
│       └── main.jsx
│
├── server/                 # Backend
│   └── package.json
│
└── README.md
```

---

# 🛠️ Tech Stack

## Frontend

| Technology          | Purpose                               |
| ------------------- | ------------------------------------- |
| **React 19**        | Frontend application                  |
| **Vite**            | Development & build tooling           |
| **React Router v7** | Client-side routing                   |
| **Framer Motion**   | Animations & transitions              |
| **CSS**             | Responsive styling & glassmorphism UI |
| **ESLint**          | Code quality & linting                |

## Backend

| Technology     | Purpose          |
| -------------- | ---------------- |
| **Node.js**    | Backend runtime  |
| **Express.js** | Server/API layer |

---

# 📂 Frontend Structure

```text
client/
│
├── public/
│   └── Static assets
│
├── src/
│   │
│   ├── assets/
│   │   └── Images and SVGs
│   │
│   ├── components/
│   │   ├── AnimatedBackground.jsx
│   │   ├── AnimatedCounter.jsx
│   │   ├── Footer.jsx
│   │   ├── GlassCard.jsx
│   │   ├── Navbar.jsx
│   │   └── PageTransition.jsx
│   │
│   ├── pages/
│   │   ├── Landing.jsx
│   │   ├── FarmerPortal.jsx
│   │   ├── BuyerPortal.jsx
│   │   ├── HowItWorks.jsx
│   │   └── Impact.jsx
│   │
│   ├── App.jsx
│   ├── App.css
│   ├── index.css
│   └── main.jsx
│
├── package.json
├── vercel.json
└── vite.config.js
```

---

# 🚀 Getting Started

## Prerequisites

Make sure you have installed:

* **Node.js 18+**
* **npm**
* **Git**

Check your versions:

```bash
node --version
npm --version
git --version
```

---

## 1. Clone the Repository

```bash
git clone https://github.com/SumitHelge-star/KrishiSamadhan.git
```

Navigate into the project:

```bash
cd KrishiSamadhan
```

---

## 2. Install Frontend Dependencies

```bash
cd client
npm install
```

---

## 3. Start the Development Server

```bash
npm run dev
```

The application will be available at:

```text
http://localhost:5173
```

---

## 4. Build for Production

```bash
npm run build
```

To preview the production build:

```bash
npm run preview
```

---

# 🌐 Deployment

The frontend is configured for deployment using **Vercel**.

### Deployment Steps

1. Import the repository into Vercel.
2. Set the root directory to:

```text
client
```

3. Select **Vite** as the framework.
4. Deploy the application.

The repository includes a `vercel.json` configuration for SPA routing.

---

# 🔄 Core Workflow

### Farmer Side

```text
Farmer
   ↓
Create Account
   ↓
Add Produce
   ↓
Specify Grade / Quantity / Price
   ↓
Publish Listing
   ↓
Receive Buyer Interest
   ↓
Complete Procurement
```

### Buyer Side

```text
Buyer
   ↓
Browse Marketplace
   ↓
Filter Produce
   ↓
View Farmer Listing
   ↓
Select Required Quantity
   ↓
Procurement
   ↓
Pickup / Delivery
```

### Circular Economy

```text
        Surplus Produce
              ↓
        ┌─────┴─────┐
        ↓           ↓
   Food Processing  Animal Feed
        ↓           ↓
     Products      Feed
        │           │
        └─────┬─────┘
              ↓
       Reduced Waste
              ↓
      Circular Economy
```

---

# 🌱 Impact

KrishiSamadhan aims to create value across three major dimensions:

### 💰 Economic Impact

* Provides additional revenue opportunities for farmers
* Creates direct B2B sourcing channels
* Gives value to produce that may otherwise be discarded

### ♻️ Environmental Impact

* Reduces agricultural food waste
* Promotes resource recovery
* Supports circular agricultural supply chains
* Reduces unnecessary disposal of usable produce

### 🤝 Social Impact

* Connects farmers with alternative markets
* Encourages sustainable agricultural practices
* Creates opportunities for local processing and procurement businesses

---

# 🔮 Future Scope

The platform can be extended with:

* 🤖 AI-based crop grading
* 📈 Dynamic pricing recommendations
* 🗺️ Location-based buyer matching
* 🚚 Logistics and route optimization
* 📦 Real-time order tracking
* 💳 Online payments
* 🔔 Real-time notifications
* 📊 Advanced analytics
* 🌐 Multilingual farmer interface
* 📱 Dedicated Android/iOS application
* 🔐 Advanced authentication and role-based access control
* 🤝 Integration with agricultural marketplaces and government data sources

---

# 🤝 Contributing

Contributions are welcome.

### 1. Fork the repository

```bash
git fork https://github.com/SumitHelge-star/KrishiSamadhan.git
```

### 2. Create a feature branch

```bash
git checkout -b feature/your-feature
```

### 3. Commit your changes

```bash
git add .
git commit -m "Add: your feature"
```

### 4. Push the branch

```bash
git push origin feature/your-feature
```

### 5. Open a Pull Request

---

# 📄 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Author

### Sumit Helge

**Computer Science & Engineering**

Interested in:

* Full-Stack Development
* Generative AI
* Software Engineering
* System Design
* AI-powered applications

### GitHub

[SumitHelge-star](https://github.com/SumitHelge-star?utm_source=chatgpt.com)

### Project Repository

[KrishiSamadhan on GitHub](https://github.com/SumitHelge-star/KrishiSamadhan?utm_source=chatgpt.com)

---

## 🌾 KrishiSamadhan

> **Turning imperfect harvests into sustainable opportunities.**

Built with ❤️ to create a more sustainable and connected agricultural ecosystem.
