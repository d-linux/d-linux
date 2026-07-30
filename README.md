# Denis Koumbou

**`Full-Stack Developer`**

<img width="1280" alt="Denis Koumbou, full-stack developer, London" src="https://raw.githubusercontent.com/d-linux/d-linux/main/banner.png" />

I build apps and take them all the way to real users. One of them is running right now: a basketball app in closed testing on Google Play. I write the frontend, the backend and the database, and I do the deploys.

[![Portfolio](https://img.shields.io/badge/Portfolio-deniswebstudio.com-0A0A0A?style=for-the-badge&logo=vercel&logoColor=white)](https://deniswebstudio.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Denis_Koumbou-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/denis-koumbou)
[![YouTube](https://img.shields.io/badge/YouTube-@denis.webstudio-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@denis.webstudio)
[![TikTok](https://img.shields.io/badge/TikTok-@denis.webstudio-000000?style=for-the-badge&logo=tiktok&logoColor=white)](https://www.tiktok.com/@denis.webstudio)
[![Instagram](https://img.shields.io/badge/Instagram-@denis.webstudio-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/denis.webstudio)
[![Email](https://img.shields.io/badge/Email-deniskoumbou@outlook.com-0078D4?style=for-the-badge&logo=maildotru&logoColor=white)](mailto:deniskoumbou@outlook.com)

---

## About me

I study Computer Science and Mathematics at the University of Derby. Most of what I actually know came from shipping things and watching them break.

I hoop, and I got tired of crossing London to find an empty court. So I built Got Next. That's how my projects usually start. Something annoys me, and I build it properly instead of leaving it as another dead prototype.

I teach the same things I build on YouTube, TikTok and Instagram. If you want to learn how any of this works, everything below is something I've explained or will explain.

**Languages:** French (Native), English (Fluent), Spanish (Elementary)

---

## What I'm building

### 🏀 Got Next

**[gotnext.uk](https://gotnext.uk)**

Pickup basketball, live right now. It started in London and it's opening across the UK. You can see which courts are busy, check in so people know you're on your way, form a crew that holds a court, and run 3x3, 5v5, 1v1 or shootouts. Free, no ads.

Android closed testing is live on Google Play. iOS is built and waiting on the App Store.

<!-- SCREENSHOT SLOT: paste 2 or 3 app screenshots here (drag them into the GitHub editor) -->

Everything in the app hangs off one thing: the check-in. Who, which court, when, and what status. Live counts, who's coming, team rankings and match history are all just different views of that one table. Teams only hold courts off real check-ins, so nobody can claim a court they never turned up to.

Three problems worth talking about:

* **People won't use an app that tracks them.** So the phone works out where you are, the server only confirms you're close enough to the court, and the row it saves holds a court id and nothing else. No coordinates are ever stored.
* **Phones sleep, and live data doesn't wait.** Lock your phone for an hour and you'd come back to a map showing courts that emptied ages ago, because live updates don't replay what you missed. The app notices the gap and refetches instead of trusting what it has.
* **A basketball map is useless if it's empty.** Rather than mapping the country myself, players add a court by standing at it and sending a photo, and every suggestion puts a city on the list for what opens next.

![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Clerk](https://img.shields.io/badge/Clerk-6C47FF?style=flat-square&logo=clerk&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white)

---

## How I build

These are the rules written at the top of my own projects, and I follow them because breaking them has cost me weeks.

**Ship one thing at a time, and keep it working.** I finish a phase before I touch the next one. A working app at every stop beats ten features that are each half done.

**Simple beats clever.** No abstractions I don't need yet, no infrastructure for users I don't have. Over-engineering is the fastest way I've found to kill a project.

**Find the one thing everything else depends on, and model that first.** In Got Next it was the check-in. Get that right and the rest of the app stays simple as it grows. Get it wrong and every feature after it fights you.

---

## Tech I work with

**Frontend**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-0A7EA4?style=for-the-badge&logo=react&logoColor=white)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![tRPC](https://img.shields.io/badge/tRPC-2596BE?style=for-the-badge&logo=trpc&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)

**Data**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Drizzle ORM](https://img.shields.io/badge/Drizzle-C5F74F?style=for-the-badge&logo=drizzle&logoColor=black)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white)

**DevOps and testing**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)

---

## Where I've worked

**Technical Content Creator and Educator**, YouTube / TikTok / Instagram · *Dec 2025 to now*

I teach full-stack development, turning the architecture I use in my own projects into tutorials people can follow.

**Freelance Web Developer**, Denis WebStudio · *Jan 2026 to Jun 2026*

Built and shipped sites for small businesses, from the first conversation through to domains, SEO and hosting.

**Assistant Web Developer**, Techno Skills · *Sept 2023 to Sept 2025*

Built and maintained client web apps. Refactored an e-commerce codebase and got the page loads and the mobile experience into much better shape.

---

## Say hello

**Hiring?** I've taken a product from an empty folder to real users, and I'm comfortable owning a feature from the database through to the deploy. Email me and I'll walk you through the codebase.

**Got something you need built?** I do this for small businesses through [Denis WebStudio](https://deniswebstudio.com).

**Learning this stuff?** Everything on this page gets broken down on [YouTube](https://www.youtube.com/@denis.webstudio) and [TikTok](https://www.tiktok.com/@denis.webstudio). Ask me anything, I answer.

[![Email](https://img.shields.io/badge/deniskoumbou@outlook.com-0078D4?style=for-the-badge&logo=maildotru&logoColor=white)](mailto:deniskoumbou@outlook.com)
[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/denis-koumbou)
