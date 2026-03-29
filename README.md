# 📝 eexamapp - Advanced EdTech SaaS for Automated Exam Paper Generation

> 🔒 **Confidentiality Notice:** The source code is private. This repository serves as a technical architectural showcase for the EdTech SaaS platform I engineered to solve manual examination challenges for schools, colleges, and coaching centers in Bangladesh.

## 🚀 System Overview
eexamapp is a highly scalable SaaS platform that automates the entire process of exam paper creation. It features a massive database of verified questions (Class 1-12, Board & Top Schools), a high-performance customization engine with LaTeX support, and a flexible subject-based subscription model.

## 🛠️ Tech Stack & Infrastructure
* **Frontend:** React (Vite), Tailwind CSS, Shadcn UI.
* **Backend & Auth:** Supabase (PostgreSQL) with Google OAuth integration.
* **Math Rendering:** **LaTeX Support** for complex mathematical and scientific equations.
* **Content Editing:** Rich Text Editor with Table and Image support.
* **Tracking & SEO:** Meta CAPI (Server-side) & GA4 with event deduplication.
* **Infrastructure:** Vercel (Hosting), Cloudflare (DNS/Security).

---

## 🧠 Core Engineering & SaaS Highlights

### 1. 1-Click "Smart Paper" Generator
* **Granular Selection:** Teachers can select Program, Class (1-12), Subject, and Question Type (MCQ, CQ, Descriptive, Short Question).
* **Massive Database:** Instant access to an categorized library of board and premier institution questions across all chapters and groups.
* **A-Z Print Customization:** * **Editing Mode:** Real-time editing of specific questions/topics.
    * **Branding:** Instant institution logo/text watermarking and custom headers (Institution Name, Marks, Time).
    * **Typography:** Multiple font options, text alignment, and layout optimization.
    * **Answer Sheets:** Toggleable option to print complete answer keys alongside the exam paper.

### 2. Flexible SaaS Subscription Engine
* **Micro-Bundles:** Teachers can subscribe to a whole class or specific subjects (e.g., Math for Class 5-10 only), optimizing their costs.
* **Validity Management:** Integrated 1-year subscription cycles with real-time status tracking on the dashboard.
* **Demo Mode:** Admins can flag specific chapters as "Demo," allowing potential customers to test the full generation flow before purchasing.

### 3. Enterprise Content Management (Admin Powerhouse)
* **LaTeX Integrated CMS:** A robust Rich Text Editor for adding questions with complex math symbols, tables, and images.
* **Dynamic Hierarchy:** Admins can dynamically manage the tree: **Class -> Subject -> Chapter -> Topic -> Question Type**.
* **Status Control:** Chapters can be toggled between Active, Inactive (Maintenance), or Demo.
* **Automated Feedback Loop:** "Report Question" system where teachers report errors, admins resolve them, and status is communicated back via a dynamic feedback page.

### 4. Advanced RBAC & User Management
* **Granular Permissions:** Super Admins can assign specific moderators to manage only certain classes or specific chapters, ensuring data integrity.
* **Financial Tracking:** Centralized view of all institutional sign-ups and active subscription revenue.
* **Dynamic Pricing:** Admins can manage packages and pricing on the fly, including "Coming Soon" tags for upcoming modules.

### 5. Data Privacy & Technical SEO
* **Hybrid Tracking:** Implementation of both Browser and Server-Side tracking (Meta CAPI) with deduplication to ensure data accuracy.
* **Security:** `robots.txt` configuration to shield the administrative and creation engine from crawlers.
* **Indexing:** Dynamic `sitemap.xml` generation for all public-facing education modules.

---

## 🤝 Let's Connect
I build scalable, mission-critical SaaS platforms that solve real-world problems.
* 🌐 **Portfolio:** [shahnabil.com](https://shahnabil.com)
* ✉️ **Email:** hello@shahnabil.com
