# 🏨 Furnova


Experience the pinnacle of craftsmanship with our curated collection of artisanal furniture. Designed for those who appreciate the finer things in life.
---

## 🌐 Live Demo



Frontend Live    : https://c-fornuva.vercel.app/

---

## 📌 Project Overview

Furnova ia a Furniture Purchasing Website
---

## ✨ Features

* 🛏️ Browse available furnitures with detailed information
* 📅 Seamless booking system
* 🔐 Authentication system (Login/Register)
* 📰 News/blog section with dynamic routing
* 🖼️ Image gallery for furniture showcase
* 📱 Fully responsive design
* ⚡ Fast performance with Next.js
* 🧾 Form validation using React Hook Form + Zod

---

## 🛠️ Tech Stack

### Frontend

* ⚡ Next.js 16
* ⚛️ React 19
* 🔷 TypeScript
* 🎨 Tailwind CSS 4

### State & Data

* 🔄 TanStack Query
* 🧠 React Hook Form
* ✅ Zod Validation

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Configure environment variables

```bash
cp .env.example .env.local
```

Set the following value:

```env
NEXT_PUBLIC_API_URL=http://localhost:5000/api/v1
```

### 4️⃣ Run the development server

```bash
npm run dev
```

Open your browser and visit:
👉 [http://localhost:3000](http://localhost:3000)

---

## 🗺️ Key Routes

| Route          | Description      |
| -------------- | ---------------- |
| `/`            | Home page        |
| `/about`       | About the hotel  |
| `/rooms`       | Browse rooms     |
| `/gallery`     | Image gallery    |
| `/news`        | News/articles    |
| `/news/[slug]` | Single news page |
| `/contact`     | Contact page     |

---

## 🔌 Backend Integration

The frontend communicates with the backend using the base URL:

```env
NEXT_PUBLIC_API_URL
```

### API Endpoints Used

* 🛏️ Rooms → `/rooms`
* 📅 Bookings → `/bookings`
* 🔐 Authentication → `/auth`

💡 Social authentication redirects dynamically use the backend origin.

---

## 📂 Content & Data Sources

Static fallback data is stored in:

* `src/data/rooms.ts`
* `src/data/news.ts`

👉 Update these files to modify demo content.

---

## ✅ Quality Checks

Run the following before production:

```bash
npm run lint
npm run build
```

---


---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

---

## 📄 License

This project is licensed under the MIT License.

---

## 💡 Author

👤 Rahul

---

⭐ If you like this project, consider giving it a star on GitHub!
