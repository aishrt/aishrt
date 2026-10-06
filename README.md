I've updated your GitHub profile and the changes are live at **github.com/aishrt** (commit `570d6af` on `aishrt/aishrt`). I compared the before and after automatically: all text, all 114 links and all 23 alt texts are unchanged. The only changes are image sources and the section dividers.

**What changed**
- **Header:** replaced the capsule-render banner with an animated SVG of your own. It keeps the same gradient, text and size, adds soft glows that drift slowly and one light sweep when the page loads, and fades the name and tagline in one after the other. On phones the text is now larger; before, the tagline was about 7px tall.
- **Section dividers:** the seven `---` lines are now a 1px blue-to-purple line with a slow travelling highlight, and it stays 1px at every screen width.
- **"Open to opportunities" badge:** same flat style, with a pulsing green "available" dot added.
- **Footer:** same treatment as the header, with the gradient reversed.
- All motion uses transform and opacity only, and switches off for visitors who have reduced motion turned on.

**Checks**
- I rendered the README through GitHub's own Markdown API and looked at it on desktop, on a 375px phone width, in light and dark themes, and with reduced motion on.
- On your live profile, all four new SVGs load correctly as images.

**Limits and side effects**
- **Hover effects and scroll-triggered entrance animations aren't possible on GitHub.** READMEs strip all CSS and JavaScript, so the hover and scroll parts of your brief can't be done there; animated SVG images that play when the page loads are the only option.
- **The stats cards still have animations turned off,** as you set them earlier today. Those cards don't respect reduced motion.
- **The typing SVG is unchanged** and doesn't respect reduced motion either.
- **Your profile-views counter is up by about 7** because my preview renders loaded it.

## Full code

### `README.md`
```html
<!-- ===================== HEADER ===================== -->
<p align="center">
  <img src="./assets/header.svg" width="100%" alt="Aishwarya Raj Tyagi" />
</p>

<p align="center">
  <a href="https://aishwaryarajtyagi.netlify.app/">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=900&color=70A5FD&center=true&vCenter=true&width=640&lines=SDE+3+%40+Websmiths;Full-Stack+Engineer+%E2%80%A2+React+%E2%80%A2+Next.js+%E2%80%A2+Node.js;Building+AI+voice+agents+%26+LLM+workflows;15%2B+products+shipped+across+SaaS%2C+Fintech+%26+Logistics" alt="Typing intro" />
  </a>
</p>

<p align="center">
  <a href="https://aishwaryarajtyagi.netlify.app/"><img height="30" src="https://img.shields.io/badge/Portfolio-Visit-70A5FD?style=flat&logo=googlechrome&logoColor=white&labelColor=1a1b27" alt="Portfolio" /></a>
  <a href="https://aishwaryarajtyagi.netlify.app/AISHWARYA_RAJ_TYAGI_RESUME.pdf"><img height="30" src="https://img.shields.io/badge/Resume-Download-BF91F3?style=flat&logo=adobeacrobatreader&logoColor=white&labelColor=1a1b27" alt="Resume" /></a>
  <a href="https://www.linkedin.com/in/aishwarya-raj-tyagi/"><img height="30" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white&labelColor=1a1b27" alt="LinkedIn" /></a>
  <a href="mailto:aishraj05@gmail.com"><img height="30" src="https://img.shields.io/badge/Email-aishraj05%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white&labelColor=1a1b27" alt="Email" /></a>
</p>

<p align="center">
  <img src="./assets/status-open.svg" alt="Open to opportunities" />
  <img src="https://img.shields.io/badge/Location-Mohali%2C_India-FF9933?style=flat" alt="Location" />
  <img src="https://komarev.com/ghpvc/?username=aishrt&label=Profile%20views&color=3d59a1&style=flat" alt="Profile views" />
</p>

<p align="center"><img src="./assets/divider.svg" width="100%" height="8" alt="" /></p>

## 👨‍💻 About Me

I'm a **Full-Stack Software Engineer (SDE 3)** at **Websmiths** with **5 years** of experience building scalable web apps, SaaS platforms, enterprise systems, AI-powered products and browser extensions, from pixel-perfect React frontends to solid Node.js APIs.

🏢 &nbsp;**Currently** &nbsp; `SDE 3 @ Websmiths`  
⏳ &nbsp;**Experience** &nbsp; `5 years` `15+ client products shipped`  
📍 &nbsp;**Based in** &nbsp; `Mohali, India`  
🌍 &nbsp;**Domains** &nbsp; `SaaS` `Fintech` `Logistics` `E-commerce` `AI` `Security`  
⚡ &nbsp;**Daily drivers** &nbsp; `React` `Next.js` `TypeScript` `Node.js` `MongoDB`  
🤖 &nbsp;**Building now** &nbsp; `AI voice agents` `LLM workflows` `Real-time systems`  
💬 &nbsp;**Ask me about** &nbsp; `Auth & payments` `Chrome extensions` `Monorepos` `Performance`  

**What I bring**
- 🧩 I own features **end-to-end**: requirements → architecture → APIs → deployment → production support
- 🔐 Deep experience with **authentication, payments, subscriptions, webhooks & third-party integrations**
- 🤝 I work directly with clients to turn business requirements into production-ready software
- ⚡ I care about **performance, reliability & reusable architecture**

<p align="center"><img src="./assets/divider.svg" width="100%" height="8" alt="" /></p>

## 💼 Experience

**🟣 SDE 3 · Full-Stack Software Engineer** · Websmiths Pvt. Ltd. &nbsp; `Apr 2026 – Present`  
Own SaaS features end-to-end in a monorepo: auth, payments, subscriptions, webhooks & real-time features across AI, logistics & e-commerce products.

**🔵 Software Engineer** · [Softuvo Solutions](https://www.softuvo.com/) &nbsp; `May 2024 – Apr 2026`  
Delivered 5+ client projects · Stripe subscriptions with Angular + Node.js · Built a PowerPoint add-in · Led team tasks & client communication.

**🟢 MERN Stack Developer** · [Esferasoft Solutions](https://www.esferasoft.com/) &nbsp; `Feb 2023 – May 2024`  
Contributed to 9+ full-stack apps · Integrated Redis, Firebase Auth, SMTP, Google Maps, Stripe, Vector DB & Escrow.

**🟠 Frontend Developer** · Zenid Infotech &nbsp; `Jan 2022 – Oct 2022`  
Responsive UIs with React, TypeScript & Zustand · Webhooks & social login (Google, GitHub, Twitter).

<p align="center"><img src="./assets/divider.svg" width="100%" height="8" alt="" /></p>

## 🧠 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=react,nextjs,ts,js,angular,tailwind,vite,redux,threejs,html,css&perline=11" alt="Frontend" />
  <br/>
  <img src="https://skillicons.dev/icons?i=nodejs,express,fastapi,mongodb,postgres,redis,supabase,firebase&perline=11" alt="Backend & Data" />
  <br/>
  <img src="https://skillicons.dev/icons?i=aws,docker,githubactions,netlify,git,github,postman,vscode,jest,vitest&perline=11" alt="DevOps & Tools" />
  <br/>
  <img src="https://go-skill-icons.vercel.app/api/icons?i=zustand,tanstack,reactquery,framer,hono,socketio,drizzle&perline=7" alt="Modern tooling" />
  <br/>
  <img src="https://go-skill-icons.vercel.app/api/icons?i=stripe,shopify,claude,turborepo,railway,playwright,cursor&perline=7" alt="Integrations & tooling" />
</p>

<details>
<summary><b>🧰 Full toolbox (click to expand)</b></summary>
<br/>

**🎨 Frontend**  
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat&logo=redux&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-433E38?style=flat&logo=react&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat&logo=reactquery&logoColor=white)
![TanStack Router](https://img.shields.io/badge/TanStack_Router-FF4154?style=flat)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=flat&logo=reactrouter&logoColor=white)
![React Hook Form](https://img.shields.io/badge/React_Hook_Form-EC5990?style=flat&logo=reacthookform&logoColor=white)
![Radix UI](https://img.shields.io/badge/Radix_UI-161618?style=flat&logo=radixui&logoColor=white)
![Mantine](https://img.shields.io/badge/Mantine-339AF0?style=flat&logo=mantine&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat&logo=framer&logoColor=white)
![React Flow](https://img.shields.io/badge/React_Flow-FF0072?style=flat)
![Recharts](https://img.shields.io/badge/Recharts-22B5BF?style=flat)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat&logo=threedotjs&logoColor=white)
![dnd kit](https://img.shields.io/badge/dnd_kit-1E293B?style=flat)

**⚙️ Backend & APIs**  
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=flat&logo=express&logoColor=white)
![Hono](https://img.shields.io/badge/Hono-E36002?style=flat&logo=hono&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![oRPC](https://img.shields.io/badge/oRPC-0F172A?style=flat)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat&logo=socketdotio&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat&logo=zod&logoColor=white)
![OpenAPI](https://img.shields.io/badge/OpenAPI_/_Swagger-85EA2D?style=flat&logo=swagger&logoColor=black)
![REST APIs](https://img.shields.io/badge/REST_APIs-02569B?style=flat)
![Better Auth](https://img.shields.io/badge/Better_Auth-0F172A?style=flat)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat&logo=jsonwebtokens&logoColor=white)

**🗄️ Database & Storage**  
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)
![Drizzle ORM](https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat&logo=drizzle&logoColor=black)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black)
![Vector DB](https://img.shields.io/badge/Vector_DB-4A90E2?style=flat)
![Serverless DB](https://img.shields.io/badge/Serverless_DB-0F172A?style=flat)
![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=flat&logo=amazons3&logoColor=white)

**🤖 AI & Voice**  
![Claude AI](https://img.shields.io/badge/Claude_AI-D97757?style=flat&logo=anthropic&logoColor=white)
![Vercel AI SDK](https://img.shields.io/badge/Vercel_AI_SDK-000000?style=flat&logo=vercel&logoColor=white)
![ElevenLabs](https://img.shields.io/badge/ElevenLabs-111111?style=flat&logo=elevenlabs&logoColor=white)
![Vapi](https://img.shields.io/badge/Vapi-111827?style=flat)
![Retell AI](https://img.shields.io/badge/Retell_AI-111827?style=flat)
![LLM Workflows](https://img.shields.io/badge/LLM_Workflows-8B5CF6?style=flat)
![Chatbots](https://img.shields.io/badge/Chatbots-8B5CF6?style=flat)

**💳 Payments, Auth & Integrations**  
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat&logo=stripe&logoColor=white)
![PayPal](https://img.shields.io/badge/PayPal-003087?style=flat&logo=paypal&logoColor=white)
![Escrow](https://img.shields.io/badge/Escrow-1F2937?style=flat)
![Shopify](https://img.shields.io/badge/Shopify_API-7AB55C?style=flat&logo=shopify&logoColor=white)
![Firebase Auth](https://img.shields.io/badge/Firebase_Auth-FFCA28?style=flat&logo=firebase&logoColor=black)
![Azure AD](https://img.shields.io/badge/Azure_AD-0078D4?style=flat)
![Google Maps API](https://img.shields.io/badge/Google_Maps_API-4285F4?style=flat&logo=googlemaps&logoColor=white)
![Google Drive API](https://img.shields.io/badge/Google_Drive_API-4285F4?style=flat&logo=googledrive&logoColor=white)
![Resend](https://img.shields.io/badge/Resend-000000?style=flat&logo=resend&logoColor=white)
![React Email](https://img.shields.io/badge/React_Email-000000?style=flat)
![AWS SES](https://img.shields.io/badge/AWS_SES-FF9900?style=flat)
![AWS Textract](https://img.shields.io/badge/AWS_Textract-FF9900?style=flat)
![SMTP](https://img.shields.io/badge/SMTP-6B7280?style=flat)
![Chrome Extensions](https://img.shields.io/badge/Chrome_Extensions_(MV3)-4285F4?style=flat&logo=googlechrome&logoColor=white)
![Office Add-ins](https://img.shields.io/badge/Office_Add--ins-D83B01?style=flat)

**☁️ DevOps & Cloud**  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=flat&logo=turborepo&logoColor=white)
![AWS Amplify](https://img.shields.io/badge/AWS_Amplify-FF9900?style=flat&logo=awsamplify&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=flat&logo=awslambda&logoColor=white)
![AWS ECS](https://img.shields.io/badge/AWS_ECS-FF9900?style=flat&logo=amazonecs&logoColor=white)
![AWS CloudFront](https://img.shields.io/badge/AWS_CloudFront-FF9900?style=flat)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat&logo=netlify&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat&logo=railway&logoColor=white)
![Hostinger](https://img.shields.io/badge/Hostinger-673DE6?style=flat&logo=hostinger&logoColor=white)
![cPanel](https://img.shields.io/badge/cPanel-FF6C2C?style=flat&logo=cpanel&logoColor=white)

**🧪 Testing & Tools**  
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat&logo=vitest&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat&logo=jest&logoColor=white)
![Testing Library](https://img.shields.io/badge/Testing_Library-E33332?style=flat&logo=testinglibrary&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat&logo=sentry&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat)
![Cursor](https://img.shields.io/badge/Cursor-000000?style=flat&logo=cursor&logoColor=white)

</details>

<p align="center"><img src="./assets/divider.svg" width="100%" height="8" alt="" /></p>

## 🚀 Featured Projects

**🤖 [Auto Connex](https://auto-connex.ai/)**: AI automotive platform, a multi-service monorepo with voice agents, conversational AI & intelligent workflows  
`Hono` `FastAPI` `Node.js` `React` `Better Auth` `ElevenLabs`

**🚗 [Rento Vroom](https://www.rentovroom.com/)**: New Zealand peer-to-peer car-sharing marketplace with ID & licence verification, NZD payments and photo check-ins  
`React` `Vite` `AWS S3` `CloudFront`

**🚚 [Trux360](https://master.d3k9fkzq1x1pde.amplifyapp.com/)**: Enterprise transport management for bulk fuel & port-to-depot cargo with real-time shipment tracking  
`React` `Node.js` `Express` `MongoDB`

**🛰️ [Bridge18](https://prod.bridge18.com/dashboard)**: Enterprise fleet management with real-time tracking, vehicle management, route optimization & analytics  
`React` `Node.js` `Express` `MongoDB`

**🗂️ [TaskNest](https://chromewebstore.google.com/detail/tasknest-%E2%80%94-to-do-list-tas/coiljcbmhgkhepaajapkabojjledmdoa)**: Chrome extension task manager with list, board & calendar views in a side panel, plus natural-language task capture  
`TypeScript` `React` `Manifest V3`

**🍱 [Zerocaters](https://zerocater.com/)**: B2B corporate catering platform for bulk order booking & management  
`React` `Node.js` `MongoDB` `Stripe` `Redis`

**🕵️ [Demisty5](https://demysti5.com/)**: Digital privacy & security platform with unlimited threat checks & real-time alerts  
`Angular` `Node.js` `MongoDB` `Vector DB` `Redis`

**🔐 [YourDMARC](https://www.yourdmarc.com/)**: Email authentication (SPF · DKIM · DMARC) compliance with advanced reporting & domain monitoring  
`React` `Node.js` `MongoDB` `Redis`

**🛡️ [Track Your Security](https://www.trackyoursecurity.com/)**: AI-driven security platform with real-time status monitoring, threat levels & interactive dashboards  
`React` `Tailwind CSS` `Framer Motion`

**🛍️ [Alinkriti](https://alinkriti.com)**: Custom Shopify storefront for a lifestyle brand with a curated catalog & secure checkout  
`Shopify` `Liquid`

<details>
<summary><b>✨ More projects</b></summary>
<br/>

- 🎨 **[Paint & Memories](https://create.paintandmemories.com/)**: AI platform that turns personal photos into traditional paintings &nbsp;`React` `Node.js` `Stripe`
- 📸 **[SnapShot Pro](https://chromewebstore.google.com/detail/lajmpjkepgpiaondpghbajapdgkdaiop)**: Chrome extension for HD full-page, scrolling & visible-area screenshots &nbsp;`Manifest V3`
- 🎓 **[Student Chrome Extension](https://student-chrome-extension.web.app/)**: discounts, loan offers & personal finance with real-time data &nbsp;`Firebase`
- 📊 **PowerPoint Add-in**: dynamic UI tabs & contextual switching inside PowerPoint &nbsp;`Office Add-in API`
- 🎁 **[Generic Ideas](http://genericideas.com/)**: e-commerce gift store with secure checkout & same-day delivery &nbsp;`MERN` `Stripe`
- 🥭 **[Golden Harvest Mango](https://goldenharvestmango.com/)**: e-commerce store for premium farm-fresh mangoes &nbsp;`React`
- 🌍 **[Gulf Connect Consultancy](https://www.gulfconnectconsultancy.com/)**: bilingual (EN/AR) site for a Dubai capital-markets consultancy &nbsp;`Next.js`
- 🏢 **[SOFISAM](https://sofisam-seven.vercel.app/)**: corporate advisory platform for a Dubai-based firm &nbsp;`React`
- 🧸 **[Country Kids Learning Center](https://www.countrykids.au/)**: website for a not-for-profit early learning centre in Victoria, Australia &nbsp;`React`
- 🤝 **[Bestow India](https://www.bestowindia.com/)**: end-to-end people & business development partner &nbsp;`React`

👉 See them all with screenshots on my **[portfolio](https://aishwaryarajtyagi.netlify.app/projects)**.

</details>

<p align="center"><img src="./assets/divider.svg" width="100%" height="8" alt="" /></p>

## 🎓 Education & Certifications

**🎓 MCA**: Chandigarh University &nbsp; `2023`  
**🎓 BCA**: JMIT, Kurukshetra University &nbsp; `2021`  
**📜 Node.js Training**: Apptunix  
**📜 Web Development**: Tech Mahindra  
**📜 O-Level**: Aptech (NIELIT)

## 🏆 Achievements

- 🥇 **Excellence Certificate in Quiz**: Aptron Solutions Pvt. Ltd.
- 🎤 **Finalist**: Power Grid Corporation Haryana Debate &nbsp;`2018`
- 🧑‍🤝‍🧑 **Organizer**: Make It Happen Club
- 🧠 **Quiz Participant**: APJ Abdul Kalam Technical University

<p align="center"><img src="./assets/divider.svg" width="100%" height="8" alt="" /></p>

## 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-stats-extended.vercel.app/api?username=aishrt&show_icons=true&theme=tokyonight&hide_border=true&border_radius=16&disable_animations=true" alt="GitHub stats" />
  <img height="170" src="https://github-stats-extended.vercel.app/api/top-langs?username=aishrt&layout=donut&theme=tokyonight&hide_border=true&border_radius=16&disable_animations=true&hide=html,css,scss,handlebars,dockerfile,php,c,c%2B%2B&langs_count=4" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=aishrt&theme=tokyonight&hide_border=true&border_radius=16" alt="GitHub streak" />
</p>

<p align="center">
  <img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=aishrt&theme=tokyonight" alt="Contribution graph" />
</p>

<p align="center"><img src="./assets/divider.svg" width="100%" height="8" alt="" /></p>

## 🤝 Let's Connect

<p align="center">
  <a href="https://aishwaryarajtyagi.netlify.app/"><img height="30" src="https://img.shields.io/badge/Portfolio-70A5FD?style=flat&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/aishwarya-raj-tyagi/"><img height="30" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://github.com/aishrt"><img height="30" src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="mailto:aishraj05@gmail.com"><img height="30" src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<p align="center">
  <i>Open to full-stack & AI product opportunities. Feel free to reach out! 🚀</i>
</p>

<!-- ===================== FOOTER ===================== -->
<p align="center">
  <img src="./assets/footer.svg" width="100%" alt="Thanks for visiting!" />
</p>
```

### `assets/header.svg`
```svg
<svg xmlns="http://www.w3.org/2000/svg" width="900" height="200" viewBox="0 0 900 200" role="img" aria-labelledby="hdr-title hdr-desc">
  <title id="hdr-title">Aishwarya Raj Tyagi</title>
  <desc id="hdr-desc">SDE 3 • Full-Stack Software Engineer • MERN • AI</desc>
  <style>
    .orb, .name, .rule, .tagline { transform-box: fill-box; transform-origin: center; }
    .orb-a { animation: drift-a 18s cubic-bezier(.45, 0, .55, 1) infinite alternate; }
    .orb-b { animation: drift-b 23s cubic-bezier(.45, 0, .55, 1) infinite alternate; }
    .orb-c { animation: drift-c 29s cubic-bezier(.45, 0, .55, 1) infinite alternate; }
    .name { animation: rise 1s cubic-bezier(.22, 1, .36, 1) .15s both; }
    .tagline { animation: rise 1s cubic-bezier(.22, 1, .36, 1) .32s both; }
    .rule { animation: grow .9s cubic-bezier(.22, 1, .36, 1) .5s both; }
    .sheen { animation: sweep 2.4s cubic-bezier(.4, 0, .2, 1) .6s both; }
    @keyframes drift-a { to { transform: translate(-64px, 18px) scale(1.12); } }
    @keyframes drift-b { to { transform: translate(72px, -16px) scale(.94); } }
    @keyframes drift-c { from { opacity: .6; } to { transform: translate(-36px, 22px); opacity: 1; } }
    @keyframes rise { from { opacity: 0; transform: translateY(10px); } }
    @keyframes grow { from { opacity: 0; transform: scaleX(0); } }
    @keyframes sweep { from { transform: translateX(0); } to { transform: translateX(1500px); } }
    /* Inside an SVG image, width queries match the rendered image size: keep text legible on phones. */
    @media (max-width: 520px) {
      .name { font-size: 56px; transform: translateY(-4px); }
      .tagline { font-size: 26px; transform: translateY(6px); }
    }
    @media (prefers-reduced-motion: reduce) {
      .orb, .name, .rule, .tagline, .sheen { animation: none; }
    }
  </style>
  <defs>
    <linearGradient id="hdr-bg" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#1a1b27"/>
      <stop offset=".5" stop-color="#3d59a1"/>
      <stop offset="1" stop-color="#bf91f3"/>
    </linearGradient>
    <radialGradient id="hdr-orb-a">
      <stop offset="0" stop-color="#e3c8ff" stop-opacity=".55"/>
      <stop offset="1" stop-color="#bf91f3" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="hdr-orb-b">
      <stop offset="0" stop-color="#70a5fd" stop-opacity=".38"/>
      <stop offset="1" stop-color="#70a5fd" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="hdr-orb-c">
      <stop offset="0" stop-color="#a9c1ff" stop-opacity=".22"/>
      <stop offset="1" stop-color="#a9c1ff" stop-opacity="0"/>
    </radialGradient>
    <linearGradient id="hdr-gloss" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0" stop-color="#fff" stop-opacity=".08"/>
      <stop offset=".45" stop-color="#fff" stop-opacity="0"/>
    </linearGradient>
    <linearGradient id="hdr-sheen" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#fff" stop-opacity="0"/>
      <stop offset=".5" stop-color="#fff" stop-opacity=".14"/>
      <stop offset="1" stop-color="#fff" stop-opacity="0"/>
    </linearGradient>
    <linearGradient id="hdr-rule" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#9ec1ff"/>
      <stop offset="1" stop-color="#e2c9ff"/>
    </linearGradient>
    <pattern id="hdr-dots" width="24" height="24" patternUnits="userSpaceOnUse">
      <circle cx="2" cy="2" r="1" fill="#fff" fill-opacity=".09"/>
    </pattern>
    <radialGradient id="hdr-fade" cx=".5" cy=".5" r=".6">
      <stop offset="0" stop-color="#fff"/>
      <stop offset="1" stop-color="#000"/>
    </radialGradient>
    <mask id="hdr-dots-mask">
      <rect width="900" height="200" fill="url(#hdr-fade)"/>
    </mask>
    <clipPath id="hdr-clip">
      <rect width="900" height="200" rx="16"/>
    </clipPath>
    <filter id="hdr-shadow" x="-10%" y="-30%" width="120%" height="160%">
      <feDropShadow dx="0" dy="2" stdDeviation="6" flood-color="#0b0d1a" flood-opacity=".35"/>
    </filter>
  </defs>

  <g clip-path="url(#hdr-clip)">
    <rect width="900" height="200" fill="url(#hdr-bg)"/>
    <circle class="orb orb-b" cx="150" cy="190" r="220" fill="url(#hdr-orb-b)"/>
    <circle class="orb orb-c" cx="470" cy="-20" r="190" fill="url(#hdr-orb-c)"/>
    <circle class="orb orb-a" cx="770" cy="40" r="240" fill="url(#hdr-orb-a)"/>
    <rect width="900" height="200" fill="url(#hdr-dots)" mask="url(#hdr-dots-mask)"/>
    <rect width="900" height="200" fill="url(#hdr-gloss)"/>
    <g class="sheen">
      <rect x="-420" y="-40" width="240" height="280" fill="url(#hdr-sheen)" transform="skewX(-18)"/>
    </g>
  </g>
  <rect x=".5" y=".5" width="899" height="199" rx="15.5" fill="none" stroke="#fff" stroke-opacity=".1"/>

  <g font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', 'Noto Sans', Helvetica, Arial, sans-serif" text-anchor="middle" fill="#fff">
    <text class="name" x="450" y="92" font-size="46" font-weight="700" letter-spacing="-.5" filter="url(#hdr-shadow)">Aishwarya Raj Tyagi</text>
    <rect class="rule" x="422" y="111" width="56" height="2" rx="1" fill="url(#hdr-rule)" opacity=".9"/>
    <text class="tagline" x="450" y="144" font-size="18" font-weight="500" letter-spacing=".3" fill-opacity=".86">SDE 3 • Full-Stack Software Engineer • MERN • AI</text>
  </g>
</svg>
```

### `assets/divider.svg`
```svg
<!-- Outer svg has no viewBox/fixed size on purpose: GitHub forces `height:auto` on README images,
     so an intrinsic aspect ratio would shrink the line on narrow screens. Without one, the image
     falls back to its `max-height` (8px) and the inner svg stretches the artwork to full width. -->
<svg xmlns="http://www.w3.org/2000/svg" width="100%" height="100%" aria-hidden="true">
  <style>
    .glint { animation: travel 8s cubic-bezier(.65, 0, .35, 1) 1s infinite; }
    @keyframes travel {
      0% { transform: translateX(0); opacity: 0; }
      4% { opacity: 1; }
      34% { opacity: 1; }
      38% { transform: translateX(1120px); opacity: 0; }
      100% { transform: translateX(1120px); opacity: 0; }
    }
    @media (prefers-reduced-motion: reduce) {
      .glint { animation: none; opacity: 0; }
    }
  </style>
  <svg width="100%" height="8" viewBox="0 0 900 8" preserveAspectRatio="none">
    <defs>
      <linearGradient id="div-line" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0" stop-color="#70a5fd" stop-opacity="0"/>
        <stop offset=".3" stop-color="#70a5fd" stop-opacity=".7"/>
        <stop offset=".7" stop-color="#bf91f3" stop-opacity=".7"/>
        <stop offset="1" stop-color="#bf91f3" stop-opacity="0"/>
      </linearGradient>
      <linearGradient id="div-glint" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0" stop-color="#9ab8ff" stop-opacity="0"/>
        <stop offset=".5" stop-color="#c9a8ff"/>
        <stop offset="1" stop-color="#bf91f3" stop-opacity="0"/>
      </linearGradient>
      <linearGradient id="div-fade" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0" stop-color="#000"/>
        <stop offset=".2" stop-color="#fff"/>
        <stop offset=".8" stop-color="#fff"/>
        <stop offset="1" stop-color="#000"/>
      </linearGradient>
      <mask id="div-mask" maskUnits="userSpaceOnUse" x="0" y="0" width="900" height="8">
        <rect width="900" height="8" fill="url(#div-fade)"/>
      </mask>
    </defs>
    <rect y="3.5" width="900" height="1" fill="url(#div-line)"/>
    <g mask="url(#div-mask)">
      <rect class="glint" x="-220" y="3" width="220" height="2" rx="1" fill="url(#div-glint)"/>
    </g>
  </svg>
</svg>
```

### `assets/status-open.svg`
```svg
<svg xmlns="http://www.w3.org/2000/svg" width="147" height="20" role="img" aria-label="Open to: opportunities">
  <title>Open to: opportunities</title>
  <style>
    .ping { transform-box: fill-box; transform-origin: center; animation: ping 2.4s cubic-bezier(0, 0, .2, 1) infinite; }
    @keyframes ping {
      0% { transform: scale(1); opacity: .7; }
      70%, 100% { transform: scale(2.6); opacity: 0; }
    }
    @media (prefers-reduced-motion: reduce) {
      .ping { animation: none; opacity: 0; }
    }
  </style>
  <filter id="blur"><feGaussianBlur stdDeviation="16"/></filter>
  <linearGradient id="s" x2="0" y2="100%"><stop offset="0" stop-color="#bbb" stop-opacity=".1"/><stop offset="1" stop-opacity=".1"/></linearGradient>
  <clipPath id="r"><rect width="147" height="20" rx="3"/></clipPath>
  <g clip-path="url(#r)">
    <rect width="64" height="20" fill="#555"/>
    <rect x="64" width="83" height="20" fill="#2ea44f"/>
    <rect width="147" height="20" fill="url(#s)"/>
  </g>
  <circle class="ping" cx="9.5" cy="10" r="3" fill="#3fb950"/>
  <circle cx="9.5" cy="10" r="3" fill="#3fb950"/>
  <g fill="#fff" text-anchor="middle" font-family="Verdana,Geneva,DejaVu Sans,sans-serif" text-rendering="geometricPrecision" font-size="110">
    <g transform="scale(.1)"><g aria-hidden="true" fill="#010101"><text x="375" y="150" fill-opacity=".8" filter="url(#blur)" textLength="430">Open to</text><text x="375" y="150" fill-opacity=".3" textLength="430">Open to</text></g><text x="375" y="140" textLength="430">Open to</text></g>
    <g transform="scale(.1)"><g aria-hidden="true" fill="#010101"><text x="1045" y="150" fill-opacity=".8" filter="url(#blur)" textLength="730">opportunities</text><text x="1045" y="150" fill-opacity=".3" textLength="730">opportunities</text></g><text x="1045" y="140" textLength="730">opportunities</text></g>
  </g>
</svg>
```

### `assets/footer.svg`
```svg
<svg xmlns="http://www.w3.org/2000/svg" width="900" height="110" viewBox="0 0 900 110" role="img" aria-labelledby="ftr-title">
  <title id="ftr-title">Thanks for visiting!</title>
  <style>
    .orb, .farewell { transform-box: fill-box; transform-origin: center; }
    .orb-a { animation: drift-a 20s cubic-bezier(.45, 0, .55, 1) infinite alternate; }
    .orb-b { animation: drift-b 25s cubic-bezier(.45, 0, .55, 1) infinite alternate; }
    .farewell { animation: rise 1s cubic-bezier(.22, 1, .36, 1) .2s both; }
    @keyframes drift-a { to { transform: translate(60px, 12px) scale(1.1); } }
    @keyframes drift-b { to { transform: translate(-70px, -10px) scale(.94); } }
    @keyframes rise { from { opacity: 0; transform: translateY(8px); } }
    /* Inside an SVG image, width queries match the rendered image size: keep text legible on phones. */
    @media (max-width: 520px) {
      .farewell { font-size: 40px; transform: translateY(3px); }
    }
    @media (prefers-reduced-motion: reduce) {
      .orb, .farewell { animation: none; }
    }
  </style>
  <defs>
    <linearGradient id="ftr-bg" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#bf91f3"/>
      <stop offset=".5" stop-color="#3d59a1"/>
      <stop offset="1" stop-color="#1a1b27"/>
    </linearGradient>
    <radialGradient id="ftr-orb-a">
      <stop offset="0" stop-color="#e3c8ff" stop-opacity=".5"/>
      <stop offset="1" stop-color="#bf91f3" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="ftr-orb-b">
      <stop offset="0" stop-color="#70a5fd" stop-opacity=".34"/>
      <stop offset="1" stop-color="#70a5fd" stop-opacity="0"/>
    </radialGradient>
    <linearGradient id="ftr-gloss" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0" stop-color="#fff" stop-opacity=".08"/>
      <stop offset=".5" stop-color="#fff" stop-opacity="0"/>
    </linearGradient>
    <pattern id="ftr-dots" width="24" height="24" patternUnits="userSpaceOnUse">
      <circle cx="2" cy="2" r="1" fill="#fff" fill-opacity=".09"/>
    </pattern>
    <radialGradient id="ftr-fade" cx=".5" cy=".5" r=".6">
      <stop offset="0" stop-color="#fff"/>
      <stop offset="1" stop-color="#000"/>
    </radialGradient>
    <mask id="ftr-dots-mask">
      <rect width="900" height="110" fill="url(#ftr-fade)"/>
    </mask>
    <clipPath id="ftr-clip">
      <rect width="900" height="110" rx="16"/>
    </clipPath>
    <filter id="ftr-shadow" x="-10%" y="-40%" width="120%" height="180%">
      <feDropShadow dx="0" dy="2" stdDeviation="5" flood-color="#0b0d1a" flood-opacity=".3"/>
    </filter>
  </defs>

  <g clip-path="url(#ftr-clip)">
    <rect width="900" height="110" fill="url(#ftr-bg)"/>
    <circle class="orb orb-a" cx="130" cy="20" r="200" fill="url(#ftr-orb-a)"/>
    <circle class="orb orb-b" cx="760" cy="110" r="190" fill="url(#ftr-orb-b)"/>
    <rect width="900" height="110" fill="url(#ftr-dots)" mask="url(#ftr-dots-mask)"/>
    <rect width="900" height="110" fill="url(#ftr-gloss)"/>
  </g>
  <rect x=".5" y=".5" width="899" height="109" rx="15.5" fill="none" stroke="#fff" stroke-opacity=".1"/>

  <text class="farewell" x="450" y="66" text-anchor="middle" fill="#fff" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', 'Noto Sans', Helvetica, Arial, sans-serif" font-size="30" font-weight="700" letter-spacing="-.3" filter="url(#ftr-shadow)">Thanks for visiting!</text>
</svg>
```

To undo all of this, run `git revert 570d6af` in the `aishrt/aishrt` repo.
