<div align="center">

# 🏠 PropertyPulse — Rental Listings

A full-stack rental property platform where users list, search, bookmark and message about properties.

<a href="https://github.com/miladmo68/property-pulse-nextjs"><img src="https://img.shields.io/badge/Source-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="Source code"></a>
<a href="https://miladweb.com"><img src="https://img.shields.io/badge/Portfolio-miladweb.com-1E3A8A?style=for-the-badge&logo=aboutdotme&logoColor=white" alt="Portfolio"></a>

</div>

## ✨ Features

- Google sign-in with NextAuth
- Add, edit and search property listings
- Bookmarks and in-app messages
- Image uploads to Cloudinary and MongoDB storage

## 🛠️ Tech Stack

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white) ![NextAuth](https://img.shields.io/badge/NextAuth-000000?style=for-the-badge&logo=auth0&logoColor=white) ![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white)

> [!NOTE]
> This project needs its own backend, database or API keys, so it runs locally rather than as a static demo.

## 🚀 Getting Started

**Prerequisites:** [Node.js](https://nodejs.org/) 18 or newer · A MongoDB database (local or MongoDB Atlas)

**Install and run**

```bash
git clone https://github.com/miladmo68/property-pulse-nextjs.git
cd property-pulse-nextjs
npm install
npm run dev
```

### Environment variables

Create a `.env` file (or `.env.local` for Next.js) with:

```env
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
CLOUDINARY_CLOUD_NAME=
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
MONGODB_URI=
NEXT_PUBLIC_DOMAIN=
NEXT_PUBLIC_GOOGLE_GEOCODING_API_KEY=
NEXT_PUBLIC_MAPBOX_TOKEN=
```

## 📁 Project Structure

```
property-pulse-nextjs/
├── _theme_files/
├── app/
├── assets/
├── components/
├── config/
├── context/
├── models/
├── public/
├── utils/
├── jsconfig.json
├── middleware.js
├── next.config.mjs
├── package.json
└── postcss.config.mjs
```

## 👤 Author

**Milad Mohammadi** — Frontend-Focused Full-Stack Developer, Toronto 🇨🇦

[![Website](https://img.shields.io/badge/Website-miladweb.com-FF6A00?style=flat-square&logo=googlechrome&logoColor=white)](https://miladweb.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-miladmo68-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/miladmo68/)
[![GitHub](https://img.shields.io/badge/GitHub-miladmo68-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/miladmo68)

<p align="center"><sub>If you like this project, consider giving it a ⭐</sub></p>
