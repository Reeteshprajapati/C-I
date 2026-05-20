# 🎓 Career Infra Edu Overseas

A premium, high-performance web platform for **Career Infra Edu Overseas**, a leading overseas education consultancy since 2014. This platform is designed to provide students with a seamless journey from discovering study destinations to booking their first free counseling session.

## ✨ Key Features

- **Dynamic Study Carousel:** Infinite scrolling carousel showcasing top study destinations like the UK, Canada, Germany, Italy, and more.
- **Smart Enquiry Flow:** High-conversion enquiry forms that capture student details for better consulting.
- **WhatsApp Integration:** Built-in floating WhatsApp widget for instant, seamless communication.
- **Comprehensive Services:** Dedicated pages for IELTS preparation, MBBS abroad, PG courses, and studying by country.
- **Modern & Premium Design:** Built with a premium aesthetic using **Tailwind CSS**, highly interactive animations via **Framer Motion**, and accessible components from **Shadcn UI**.
- **Responsive Layout:** Perfectly optimized for all devices, from mobile phones to high-resolution desktops.

---

## 🛠️ Tech Stack & Versions

This project leverages a modern React ecosystem for maximum performance and developer experience.

### Core Architecture
- **Framework:** [React.js](https://reactjs.org/) (`v18.3.1`)
- **Build Tool:** [Vite](https://vitejs.dev/) (`v5.4.19`)
- **Language:** [TypeScript](https://www.typescriptlang.org/) (`v5.8.3`)
- **Routing:** [React Router DOM](https://reactrouter.com/) (`v6.30.1`)

### Styling & UI
- **Styling:** [Tailwind CSS](https://tailwindcss.com/) (`v3.4.17`)
- **UI Components:** [Shadcn UI](https://ui.shadcn.com/) (built on Radix UI)
- **Animations:** [Framer Motion](https://www.framer.com/motion/) (`v12.38.0`)
- **Icons:** [Lucide React](https://lucide.dev/) (`v1.8.0`) & [React Icons](https://react-icons.github.io/react-icons/) (`v5.6.0`)
- **Carousels:** Swiper (`v12.1.3`) & Embla Carousel (`v8.6.0`)

### State Management & Forms
- **Form Handling:** React Hook Form (`v7.61.1`)
- **Schema Validation:** Zod (`v3.25.76`)
- **Data Fetching:** TanStack React Query (`v5.83.0`)

---

## 📂 Project Structure

```text
📦 CI-frontend
 ┗ 📂 career-infra-main
    ┣ 📂 src
    ┃ ┣ 📂 components   # Reusable UI sections (Navbar, Footer, HeroSection, VisaSection, etc.)
    ┃ ┣ 📂 pages        # Route components (Index, About, Services, Contact, Blog, etc.)
    ┃ ┣ 📂 hooks        # Custom React hooks
    ┃ ┣ 📂 lib          # Utility functions and configurations
    ┃ ┣ 📂 assets       # Static images and icons
    ┃ ┣ 📜 App.tsx      # Main application routing and context providers
    ┃ ┗ 📜 index.css    # Global Tailwind styles & CSS variables
    ┣ 📜 package.json
    ┣ 📜 tailwind.config.ts
    ┗ 📜 vite.config.ts
```

---

## 📦 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/sakshiudmtechno/CI-frontend.git
cd CI-frontend/career-infra-main
```

### 2. Install dependencies
```bash
npm install
```

### 3. Run development server
```bash
npm run dev
```

### 4. Build for production
```bash
npm run build
```

---

Developed with ❤️ for **Career Infra Edu Overseas** by **UDM Techno Solutions**.
