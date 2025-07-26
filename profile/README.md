<div align="center">


  <a href="https://safire-five.vercel.app/" target="_blank">
    <img src="https://raw.githubusercontent.com/rajveeerr/Safire/main/client/src/assets/Safire.svg" alt="Safire Logo" width="250"/>
  </a>

  <h1 align="center">Safire - The Harassment Saver</h1>
  <p align="center">
    A real-time, AI-powered browser extension to detect, hide, and document online harassment, 
    <br />
    creating a safer digital space for everyone.
  </p>

  <p align="center">
    <a href="https://github.com/rajveeerr/Safire/stargazers"><img src="https://img.shields.io/github/stars/rajveeerr/Safire?style=for-the-badge&logo=github&color=ce93d8" alt="Stars"></a>
    <a href="https://github.com/rajveeerr/Safire/network/members"><img src="https://img.shields.io/github/forks/rajveeerr/Safire?style=for-the-badge&logo=github&color=81d4fa" alt="Forks"></a>
    <a href="https://github.com/rajveeerr/Safire/blob/main/LICENSE"><img src="https://img.shields.io/github/license/rajveeerr/Safire?style=for-the-badge&color=a5d6a7" alt="License"></a>
    <img src="https://img.shields.io/badge/Hackathon-WINNER-gold?style=for-the-badge&logo=trophy" alt="Hackathon Winner">
  </p>

  <p align="center">
    <a href="https://safire-five.vercel.app/"><strong>View the Website</strong></a>
    ·
    <a href="#-demo-video">Watch Demo</a>
    ·
    <a href="https://github.com/rajveeerr/Safire/issues/new?assignees=&labels=bug&template=bug_report.md&title=">Report a Bug</a>
    ·
    <a href="https://github.com/rajveeerr/Safire/issues/new?assignees=&labels=enhancement&template=feature_request.md&title=">Request a Feature</a>
  </p>

</div>

---

## Hackathon Achievements

Safire has been recognized for its innovative approach and social impact at multiple hackathons. We are proud to have won:

- **1st Winner at CodeKshetra2.0**
- **First Prize at HackWie**
- **Best Impact Project at SheBuilds**

---

## Demo Video

[![Watch the demo](https://github.com/rajveeerr/Safire/blob/main/extension/assets/screenshots/client-updated-ui.png)](https://vimeo.com/1059493429?share=copy)
*(Click the image above to watch the full demo on Vimeo)*

---

## The Problem

Online harassment is a critical social issue, disproportionately affecting women and marginalized communities. Existing anti-harassment tools are often inadequate:
- **Reactive, not Proactive**: Users experience trauma *before* any action can betaken.
- **Ineffective Blocking**: Traditional blocking can escalate the situation, as harassers simply create new accounts.
- **Lack of Evidence**: Manually collecting evidence for legal action is difficult, stressful, and often incomplete.
- **Slow Manual Reporting**: Platform reporting systems are slow and often ineffective, leaving victims unprotected.

<div align="center">
  <a href="https://drive.google.com/file/d/1XuOpAc2S8qeLWhWpD5HGfEtjNZ-d_To4/view?usp=share_link" target="_blank">  
     <img width="1014" height="568" alt="Problem" src="https://github.com/user-attachments/assets/4fa39729-7c76-432f-9ed9-d555fb082abd" />

  </a>
  <br>
  <em>Click the image above to view the full presentation</em>
</div>

---

## Our Solution: Safire

Safire is a browser extension that acts as your personal guardian against online harassment. It uses advanced AI to analyze messages in real-time, proactively hiding harmful content before you see it. Safire silently collects evidence, empowers you to take legal action, and helps create a safer online community.

<div align="center">
  <a href="https://drive.google.com/file/d/1XuOpAc2S8qeLWhWpD5HGfEtjNZ-d_To4/view?usp=share_link" target="_blank">
     <img width="1014" height="568" alt="Our Solution" src="https://github.com/user-attachments/assets/8620915c-9f64-448e-95f2-cccd05bd130f" />
  </a>
  <br>
  <em>Click the image above to view the full presentation</em>
</div>

---

## Key Features

Safire is packed with features designed to provide comprehensive protection and peace of mind.

| Feature                  | Description                                                                                                                              |
| ------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------- |
| 🛡️ **AI-Powered Detection**    | Utilizes Natural Language Processing (NLP) to detect both obvious and subtle forms of harassment in real-time.                         |
| 👻 **Invisible Shield**         | Automatically hides harassing messages without alerting the sender, preventing retaliation and further trauma.                       |
| 📂 **Automated Evidence**      | Captures tamper-proof screenshots with metadata (timestamps, sender details) and stores them securely for 30 days.                     |
| 📄 **One-Click Legal Reports** | Generates detailed, evidence-backed PDF reports formatted for submission to authorities or platform moderators.                        |
|  community-driven **Harasser Tagging**    | A visible "Harasser" tag is added beside a user's name if they have been hidden by 5+ users, creating community awareness. |
| 📊 **User Dashboard**          | A central hub to view harassment analytics, manage hidden users, customize keywords, and access generated reports.                     |
| 🌐 **Cross-Platform**          | Initially for LinkedIn, with plans to expand to Twitter, Instagram, WhatsApp, and more.                                                |

---

## Tech Stack

This project is a monorepo combining a web app, browser extension, and multiple backend services.

| Component                  | Technologies                                                                                                   |
| -------------------------- | -------------------------------------------------------------------------------------------------------------- |
| 🌐 **Landing Page**        | [React](https://reactjs.org/), [Vite](https://vitejs.dev/), [Tailwind CSS](https://tailwindcss.com/), [Framer Motion](https://www.framer.com/motion/) |
| 📊 **User Dashboard**      | [Next.js](https://nextjs.org/), [TypeScript](https://www.typescriptlang.org/), [Tailwind CSS](https://tailwindcss.com/), [shadcn/ui](https://ui.shadcn.com/) |
| 🧩 **Browser Extension**   | [Plasmo](https://www.plasmo.com/), [React](https://reactjs.org/), [TypeScript](https://www.typescriptlang.org/), [Upstash](https://upstash.com/) (for caching) |
| ⚙️ **Main Backend Server** | [Node.js](https://nodejs.org/), [Express](https://expressjs.com/), [MongoDB](https://www.mongodb.com/), [JWT](https://jwt.io/), [Puppeteer](https://pptr.dev/) |
| 🤖 **AI Moderation Server**| [Node.js](https://nodejs.org/), [Express](https://expressjs.com/), [Google Gemini AI](https://ai.google.dev/)          |

---

## Wireframes & Screenshots

We went from initial low-fidelity wireframes to a polished final product in a short amount of time.

<details>
<summary><strong>Click to view Wireframes and Screenshots</strong></summary>
<br>

**Initial Wireframes:**
<div align="center">
  <a href="https://app.eraser.io/workspace/JUmzwgvpm12ATQiWXZUU?origin=share" target="_blank">
     <img width="1168" height="447" alt="Screenshot 2025-07-22 at 1 46 04 AM" src="https://github.com/user-attachments/assets/33d7c365-0d59-4db5-899f-984145510b9e" />
  </a>
  <br>
  <em>Click the image above to view the full wireframe</em>
</div>

**Extension in Action:**
<div align="center">
     <img src="https://github.com/rajveeerr/Safire/blob/main/extension/assets/screenshots/real_time_detection.png" alt="Extension UI" width="800"/>
     <img src="https://github.com/rajveeerr/Safire/blob/main/extension/assets/screenshots/harasser_tag.png" alt="Harraser Tag" width="800"/>
     <img src="https://github.com/rajveeerr/Safire/blob/main/extension/assets/screenshots/login_to_save.png" alt="Login Msg UI" width="800"/>
  <br>
  <em>Harassing messages are being blocked by the extension even before the users sees them.</em>
</div>


**Dashboard UI:**
<div align="center">
  <a href="https://safe-dm-dashboard.vercel.app/" target="_blank">
    <img width="1280" height="800" alt="Dashboard UI" src="https://github.com/user-attachments/assets/3bd0384d-37f5-49f2-86cb-d72d356e8a2e" />
 <img width="1280" height="800" alt="Dashboard UI 2" src="https://github.com/user-attachments/assets/72e7a13a-a026-429f-b665-ebf03a6e386f" /> 
  </a>
  <br>
  <em>Click the image above to create your account and view dashboard.</em>
</div>

**Generated Legal Report:**
<div align="center">
  <a href="https://drive.google.com/file/d/100yg2kfhHHoeIC910DvbznlqmIDm0tjL/view?usp=sharing" target="_blank">
     <img width="452" height="619" alt="Screenshot 2025-07-22 at 1 14 41 AM" src="https://github.com/user-attachments/assets/69b6c162-4c0b-4ccc-9918-09d0f608bf1a" />
  </a>
  <br>
  <em>Click the image above to view the full report</em>
</div>


</details>

---


## Contributors

This project was brought to life by the team "Smooth Operators".

| Name               | GitHub Profile                               |
| ------------------ | -------------------------------------------- |
| **Rajveer Singh**  | [@rajveeerr](https://github.com/rajveeerr)     |
| **Anamika Aggarwal** | [@Anamika1608](https://github.com/Anamika1608) |
| **Divyansh Sharma**| [@divyansharma001](https://github.com/divyansharma001)|
| **Anushree**       | [@ashree2118](https://github.com/ashree2118)       |

---

## 🌱 A Note on Our Development Journey

As a project born from the fast-paced and dynamic environment of hackathons, our codebase was migrated between private repositories several times during its initial development. This was necessary to meet deadlines and adapt to evolving requirements.

Consequently, the commit history visible here doesn't fully capture the extensive, iterative process—and the hundreds of commits—that went into building Safire from the ground up. The current history reflects the final, polished state of the project as we prepared it for the public.

We share this note to provide context on our journey and to give a nod to the immense effort, late nights, and passion our team poured into bringing this idea to life.

<img width="4128" height="1380" alt="banner" src="https://github.com/user-attachments/assets/668c4fc3-bf7a-402b-aff1-2aa691210c4a" />   
