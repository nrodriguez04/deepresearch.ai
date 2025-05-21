
# Deep Research  
**AI-Powered Custom Course Generator**  
*Your personal learning assistant — free, flexible, and made for autodidacts.*

---

## Overview

**Deep Research** is a free, AI-powered web application that helps users generate custom courses on any topic they want to learn. By leveraging OpenAI's GPT-4, Deep Research builds structured learning paths that include modules, timelines, goals, and curated free + optional paid resources.

It’s designed for self-learners, students, professionals, and curious minds who want a personalized and structured way to learn — without spending hours researching where to begin.

---

## Features (MVP)

- **Single Input Prompt**  
  Just tell us what you want to learn (e.g., “Learn AI development” or “Understand world history”).

- **Custom Course Generator**  
  GPT-4 builds a course with:
  - Course title + target outcome  
  - Timeline (e.g. 6-week, 3-month, or deep-dive)  
  - 5–10 course modules with learning objectives  
  - Free learning resources (YouTube, blogs, PDFs, GitHub repos)  
  - Optional paid resources (Udemy, Coursera, Amazon books)

- **Output Formatting**  
  - Beautiful, scrollable roadmap format  
  - Organized modules, clear objectives, clickable resources

- **Export Options**  
  - Copy to clipboard  
  - Markdown download  
  - Optional PDF export (in development)

- **Light Monetization**  
  - Affiliate links for optional paid resources  
  - “Buy Me a Coffee” support link (optional)

---

## Tech Stack

| Layer         | Technology                       |
|---------------|----------------------------------|
| Frontend      | Next.js + Tailwind CSS           |
| Backend/API   | Next.js API Routes / Vercel      |
| AI Engine     | OpenAI GPT-4 API                 |
| Hosting       | Vercel (free tier)               |
| Export Tools  | Markdown / jsPDF (planned)       |
| Database (Optional) | Supabase / Firebase (future) |

---

## Usage

1. Clone the repo or open in Replit.
2. Set up your `.env` file with your OpenAI API key:
``OPENAI_API_KEY=your_api_key_here``

3. Run the development server:
```bash
npm install
npm run dev
```
4. Visit http://localhost:3000 or your Replit public URL.

5. Enter a learning topic and generate your custom course!

## Prompt structure
You are an intelligent education assistant. Based on the user's topic, build a structured course with the following:

- Course Title
- Target Outcome
- Estimated Duration (weeks/months)
- Number of Modules (5–10 ideally)
- For each Module:
   - Title
   - Objective
   - Recommended Free Resources (videos, blogs, PDFs)
   - Optional Paid Resources (online courses, books)
- Bonus Tips (study habits, accountability, apps)

Topic: “{user_input}”

## 🗺️ Future Roadmap
✅ User accounts to save/share courses

✅ Course library with public and private visibility

✅ Notion integration for seamless export

✅ Collaborative learning groups

✅ Mobile-first responsive UI

✅ API access for educators, LMS, and developers

✅ Real-time learning progress tracker

## 💸 Monetization Strategy (Non-Intrusive)
- Affiliate Links
Embed affiliate links for Udemy, Coursera, Skillshare, Amazon, Bookshop, etc.

- Donation Option
“Buy Me a Coffee” or Ko-fi button for voluntary contributions.

- Freemium Extras (Optional)
Future features like user profiles, Notion export, or auto-updating plans may be available as a low-cost premium tier.

- Sponsorships (Optional)
Feature paid creators or courses in modules (clearly marked), while maintaining quality and integrity.

## 🎯 Target Users
- Self-learners and autodidacts

- Students exploring new topics

- Professionals reskilling or upskilling

- Homeschoolers or independent educators

- Hobbyists and creators who want structured learning paths

## 🌱 Brand Ethos
- Access-first: Quality education should be free or affordable.

- Learner-centered: Every course is generated just for you.

- No bloat: No popups, no clutter, no distractions.

- Mission-driven: This project is about building the future of self-education.

## 🤝 Contributing
This is a mission-driven project designed to help people learn better — for free.

If you're a developer, designer, educator, researcher, or curious creator, feel free to:

- Fork the repo

- Suggest features

- Submit pull requests

- Spread the word

Let’s make education truly accessible, one course at a time.

## 📄 License
MIT — Free to use, remix, and build upon for personal or commercial purposes.

## 📬 Contact
Created by Nicolas Rodriguez

📧 nicolasmrodriguez3@gmail.com | @thenicomethod (all socials)