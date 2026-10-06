# Farmlink-360

### Connecting Farmers to Digital Platforms, Markets & Financial Insights

FarmLink 360 is a digital agricultural platform designed to connect **farmers and buyers** while helping farmers manage their agricultural businesses more effectively.

The platform provides farmers with a place to showcase their products, connect with potential buyers, and keep track of their **earnings and expenses** through a digital Farmer Ledger.

---

##  The Problem

Many farmers face challenges such as:

* Difficulty accessing reliable markets for their products
* Limited connections with potential buyers
* Poor access to digital platforms
* Difficulty tracking farm income and expenses
* Lack of a simple way to determine whether their farming activities are generating profit or loss

FarmLink 360 aims to bring these needs together in one simple digital platform.

---

## Our Solution

FarmLink 360 provides a centralized platform where:

**Farmers can:**

* Create a digital farmer profile
* List their agricultural products
* Provide information about quantity, price, location and availability
* Connect with potential buyers
* Record their earnings
* Record their farming expenses
* Calculate and monitor their profit or loss

**Buyers can:**

* Discover available agricultural products
* Search for products
* View farmer and product information
* Find products based on location and availability
* Contact farmers directly

---

# Key Features

##  Home Page

The home page introduces FarmLink 360 and provides quick access to the main areas of the platform.

It highlights:

* The purpose of FarmLink 360
* Available agricultural products
* Farmer and buyer access
* The Farmer Ledger
* The platform's mission of connecting farmers to digital opportunities

---

##  Farmers

The Farmers section allows farmers to create a digital presence and showcase their agricultural products.

Farmers can provide information such as:

* Farmer name
* Location
* Contact information
* Farm information
* Products available
* Quantity
* Price
* Harvest/availability date

This makes it easier for potential buyers to discover farmers and their products.

---

##  Buyers

The Buyers section is designed to help customers find agricultural products.

Buyers can:

* Browse available products
* Search for products
* Filter products
* View product details
* View farmer information
* Contact farmers

This creates a direct connection between farmers and potential markets.

---

#  Farmer Ledger

One of the key features of FarmLink 360 is the **Farmer Ledger**.

The ledger helps farmers keep track of their agricultural finances.

### Earnings

Farmers can record income generated from selling their products.

Example:

| Source             |         Amount |
| ------------------ | -------------: |
| Tomatoes           |     KSh 15,000 |
| Kale               |      KSh 8,000 |
| Onions             |      KSh 7,000 |
| **Total Earnings** | **KSh 30,000** |

### Expenses

Farmers can also record expenses such as:

| Expense            |        Amount |
| ------------------ | ------------: |
| Seeds              |     KSh 4,000 |
| Fertilizer         |     KSh 3,000 |
| Transport          |     KSh 2,000 |
| **Total Expenses** | **KSh 9,000** |

### Profit/Loss

The system calculates:

```text
Profit = Total Earnings - Total Expenses
```

For the example above:

```text
KSh 30,000 - KSh 9,000 = KSh 21,000 Profit
```

This gives farmers a simple way to understand their financial performance.

---

#  Technology Stack

FarmLink 360 is built using modern web technologies.

### Frontend

* React
* Vite
* JavaScript
* HTML
* CSS

### Backend / Database

* Supabase
* PostgreSQL

### Development Tools

* Visual Studio Code
* Git
* GitHub
* Supabase CLI

### Deployment

* Netlify

---

#  Database

Supabase is used to provide the backend and database functionality.

The planned database structure includes areas such as:

```text
FarmLink 360
│
├── Farmers
│
├── Buyers
│
├── Products
│
├── Earnings
│
└── Expenses
```

The relationship between these components allows the platform to connect farmers with their products and financial records.

---

#  How FarmLink 360 Works

```text
                    FARM LINK 360
                          │
             ┌────────────┼────────────┐
             │            │            │
           Farmers      Buyers       Ledger
             │            │            │
             │            │            │
         Products     Find Products   Earnings
             │            │           Expenses
             │            │             │
             └────────────┼─────────────┘
                          │
                       Supabase
                          │
                       Database
```

---

#  Getting Started

## 1. Clone the repository

```bash
git clone <your-repository-url>
```

Navigate into the project:

```bash
cd farmlink-360
```

---

## 2. Install dependencies

```bash
npm install
```

---

## 3. Install Supabase

The Supabase JavaScript client can be installed with:

```bash
npm install @supabase/supabase-js
```

For local Supabase development, the CLI can be installed as a development dependency:

```bash
npm install supabase --save-dev
```

---

## 4. Configure environment variables

Create a `.env.local` file in the root of the project:

```env
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_PUBLISHABLE_KEY=your_supabase_publishable_key
```

Do not commit your `.env.local` file to GitHub.

---

## 5. Start the development server

```bash
npm run dev
```

The application will normally be available at:

```text
http://localhost:5173
```

---

#  Security

Environment variables containing Supabase credentials should not be committed to the repository.

The `.gitignore` file should include:

```text
.env
.env.local
```

Only the Supabase **publishable key** should be exposed in the frontend. Secret keys should never be placed in client-side React code.

---

#  Future Improvements

FarmLink 360 can be expanded with additional features such as:

*  Farmer and buyer authentication
*  Mobile-responsive design
*  Notifications
*  Digital payments
*  Financial analytics
*  Farm performance dashboards
*  Location-based product discovery
*  Farmer/buyer ratings
*  Order management
*  Digital receipts
*  AI-powered agricultural insights
* Weather information for farmers

---

#  Vision

Our vision is to create a digital ecosystem where farmers can access markets, manage their agricultural businesses, and make better financial decisions using simple digital tools.

> **"Connecting Farmers to Digital Platforms. Growing Opportunities."**

---

#  Team

**FarmLink 360 Team**

Developed as an Innovation Week project.

---

##  License

This project is developed for educational and innovation purposes.
