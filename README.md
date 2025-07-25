# 🏠 New Home Dashboard – Frontend

This is the **frontend** for a real estate listing web application inspired by the layout of [NewHomeSource](https://www.newhomesource.com/plan/2-story-loudermilk-homes-atlanta-ga/3175090). The project replicates a Power BI-style dashboard using React with dummy JSON data (no backend integration yet).

> 🚧 **Work in Progress**: This application is under active development and is part of an assignment for Panthera Infotech.

---

## 🔗 Live Demo

👉 [View Deployed App on Vercel](https://panthera-sigma-pied.vercel.app/)

---

## 📌 Features

- Responsive React-based UI
- Listing card grid layout
- Static top navigation bar
- Sidebar filter panel (UI only)
- Sort dropdown (UI only)
- Static chatbot widget (bottom-right corner)
- Dummy data powered from local JSON
- Fully mobile-friendly

---

## 🧱 Tech Stack

- **Frontend**: React (Vite or CRA)
- **Styling**: Tailwind CSS
- **Icons**: React Icons
- **Routing**: React Router DOM
- **Deployment**: Vercel

---

## 📁 Folder Structure

```

src/
├── components/
│   ├── ListingCard.jsx
│   ├── Navbar.jsx
│   ├── FilterPanel.jsx
│   ├── ChatbotWidget.jsx
│   └── SortDropdown.jsx
├── pages/
│   └── Home.jsx
├── data/
│   └── listings.json
├── App.jsx
└── main.jsx

````

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/newhome-dashboard-frontend.git
cd newhome-dashboard-frontend
````

### 2. Install dependencies

```bash
npm install
```

### 3. Run the development server

```bash
npm run dev
```

### 4. Build for production

```bash
npm run build
```

---

## 🗂️ Dummy Data Format (Sample)

```json
{
  "id": 1,
  "planName": "2-Story Craftsman",
  "builder": "Loudermilk Homes",
  "community": "Meadowbrook Estates",
  "city": "Atlanta",
  "state": "GA",
  "price": "$1,289,000",
  "beds": 4,
  "baths": 3.5,
  "sqft": 3247,
  "lotSize": "0.42 acres",
  "status": "Available"
}
```

---

## 📬 Contact

If you have any questions or feedback about the project, feel free to reach out:

**Atharve Agrawal**
📧 [atharve@example.com](mailto:atharve@example.com)
📱 +91-XXXXXXXXXX

---

## 📄 License

This project is for educational/demo purposes only and not for production use.

```

---

Let me know if you're using **Create React App** instead of Vite or want a version tailored to a **monorepo** (with backend later). I can also help you write a matching README for the backend repo when you're ready.
```
