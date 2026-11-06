# Personal-Portfolio
Full-stack developer portfolio website built with React, Tailwind CSS, and Supabase backend, featuring an automated contact pipeline and a secure custom CRUD CMS admin dashboard.
# 🚀 Full-Stack Developer Portfolio & CMS

A modern, production-ready, fully responsive developer portfolio website. This platform features a public-facing project showcase and professional timeline, completely driven by a dynamic backend and a secure, private administrative control center.

Built autonomously using the agentic engineering capabilities of **Google Antigravity IDE**.

---

## ✨ Features

### 🎨 Frontend & User Experience
*   **Dynamic Showcase Grid:** Automatically pulls and renders live projects and work experiences from the database with clean loading skeletons.
*   **Responsive Multi-Surface Design:** Optimized for pixel-perfect presentation across mobile, tablet, and ultra-wide desktop monitors.
*   **Adaptive Theme System:** Integrated light/dark mode configuration matching system preferences with manually toggled states.
*   **Secure Communications Pipeline:** Validation-checked contact portal that pushes user inquiries directly to the cloud architecture.

### ⚙️ Backend & Administration
*   **Relational Cloud Database:** Architectural tables managing project content, professional employment structures, and user communications via Supabase.
*   **Secure Identity Management:** Guarded admin route protected by cryptographically secure email/password and OAuth authentication layers.
*   **Granular Data Control (CMS):** A private administrative dashboard providing full CRUD capabilities (Create, Read, Update, Delete) to modify live website content instantly without writing code.
*   **Data Integrity (RLS):** Strict Row-Level Security parameters protecting critical backend logic—allowing public read-only clearance while locking administrative mutations.

---

## 🛠️ Built With

*   **Frontend Framework:** React.js
*   **Styling Engine:** Tailwind CSS
*   **Database & Auth Layer:** Supabase (PostgreSQL)
*   **Icons Framework:** Lucide React
*   **Development Workspace:** Google Antigravity IDE

---

## 🚀 Getting Started

### Prerequisites
Ensure you have the following installed locally on your system:
*   [Node.js](https://nodejs.org) (v18 or higher recommended)
*   An active [Supabase](https://supabase.com) cloud project account

### Local Installation Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd YOUR_REPO_NAME
   ```

2. **Install project dependencies:**
   ```bash
   npm install
   ```

3. **Configure environment settings:**
   Create a `.env` file in the root directory and append your specific database API endpoints:
   ```env
   VITE_SUPABASE_URL=your_supabase_project_url
   VITE_SUPABASE_ANON_KEY=your_supabase_anonymous_public_key
   ```

4. **Launch the local development environment:**
   ```bash
   npm run dev
   ```

---

## 🔒 Security & Database Layout
The database engine runs on PostgreSQL, leveraging RLS policies to safeguard tables. Visitors possess `SELECT` access for presentation states, while `INSERT`, `UPDATE`, and `DELETE` actions are strictly walled off behind authorized administrative sessions.
