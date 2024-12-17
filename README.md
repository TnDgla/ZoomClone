---

## **Project Name: ZoomClone**

ZoomClone is a full-stack video conferencing application built using **Next.js** and **TypeScript**, with real-time video, audio, and chat features. The app enables secure video meetings with multiple participants, dynamic layouts, and easy scheduling.

---

### **Mission and Objectives for ZoomClone**

---

### **Mission:**
To create a scalable, enterprise-ready video conferencing platform with real-time communication, dynamic video controls, and seamless user management, providing a responsive and interactive meeting experience.

---

### **Objectives:**
1. **User Authentication:**
   - Implement secure authentication with Clerk.
   - Support social sign-ins (Google, GitHub, LinkedIn).

2. **Video Conferencing:**
   - Enable real-time video/audio communication with dynamic layouts.
   - Integrate **Stream** API for enterprise-grade performance.

3. **Meeting Management:**
   - Allow users to schedule, start, and join meetings.
   - Maintain upcoming and past meeting logs.

4. **Responsive Design:**
   - Design a sleek, mobile-first interface using **Tailwind CSS** and **ShadCN UI**.

5. **Real-Time Interactivity:**
   - Include live chat and screen sharing during meetings.

6. **Deployment:**
   - Deploy the application for global accessibility.

---

## **Technology Stack**

### **Frontend**
1. **Next.js**
   - **Why:** Optimized React framework for SSR, dynamic routing, and performance.
   - **Use Case:** Handles frontend rendering and routing.

2. **TypeScript**
   - **Why:** Adds type safety for cleaner, maintainable code.
   - **Use Case:** Ensures structured and error-free development.

3. **Tailwind CSS**
   - **Why:** Utility-first CSS for fast and responsive styling.
   - **Use Case:** Creates responsive layouts and components.

4. **ShadCN UI**
   - **Why:** Provides pre-built and customizable UI components.
   - **Use Case:** Builds buttons, forms, modals, and sheets.

---

### **Backend**
1. **Stream API**
   - **Why:** Enables reliable, real-time video/audio features at scale.
   - **Use Case:** Manages video calling infrastructure.

2. **Next.js API Routes**
   - **Why:** Provides serverless API endpoints.
   - **Use Case:** Handles real-time events and backend operations.

3. **Clerk**
   - **Why:** Secure authentication and profile management.
   - **Use Case:** Supports sign-in, sign-up, and session handling.

---

### **Deployment**
1. **Vercel**
   - **Why:** Optimized for Next.js apps with seamless CI/CD.
   - **Use Case:** Deploys the ZoomClone frontend and API routes.

2. **Stream**
   - **Why:** Manages scalable, real-time video and chat infrastructure.
   - **Use Case:** Ensures smooth video performance.

---

## **System Architecture**

The **ZoomClone** system architecture demonstrates the following:
1. **Next.js Frontend**: Handles user interface, routing, and client-side logic.
2. **Stream API**: Manages real-time video and chat infrastructure.
3. **Clerk Authentication**: Manages user sessions and security.
4. **API Routes**: Handles backend requests for meeting management.
5. **Deployment on Vercel**: Ensures scalability and global availability.

---

## **Week-by-Week Plan**

---

### **Week 1: Project Setup and UI Components**
- **Goal:** Initialize the project and set up the UI structure.

- **Tasks:**
  1. Initialize the Next.js app with TypeScript.
     - **Reading:** [Next.js Docs](https://nextjs.org/docs)  
     - **Video:** [Setting Up Next.js](https://www.youtube.com/watch?v=8HJ1t5VRXqM)
  2. Integrate **Tailwind CSS** for styling.
     - **Reading:** [Tailwind CSS Setup](https://tailwindcss.com/docs)  
     - **Video:** [Tailwind CSS Tutorial](https://www.youtube.com/watch?v=dFgzHOX84xQ)
  3. Install and configure **ShadCN UI** for reusable components.
     - **Reading:** [ShadCN UI Guide](https://ui.shadcn.com/docs)  
     - **Video:** [ShadCN Setup](https://www.youtube.com/watch?v=O4AjymzpIEg)
  4. Build a basic layout with **navbar** and **sidebar**.
     - **Reading:** [Layout in Next.js](https://nextjs.org/docs/app/building-your-application)  
     - **Video:** [Next.js Layouts](https://www.youtube.com/watch?v=Iy5L-Uz2Z9A)

- **Deliverables:**
  - Basic project setup with responsive layouts for navbar and sidebar.

---

### **Week 2: User Authentication**
- **Goal:** Add secure user authentication with **Clerk**.

- **Tasks:**
  1. Set up Clerk for social sign-ins (Google, GitHub).
     - **Reading:** [Clerk Documentation](https://clerk.dev/docs)  
     - **Video:** [Clerk Next.js Integration](https://www.youtube.com/watch?v=RHFmsoiVtKE)
  2. Configure protected routes for authenticated users.
     - **Reading:** [Next.js Middleware](https://nextjs.org/docs/app/building-your-application/routing/middleware)  
     - **Video:** [Protected Routes in Next.js](https://www.youtube.com/watch?v=VJov5QWEKE4)
  3. Customize the login and sign-up pages using Clerk UI.
     - **Reading:** [Clerk Components](https://clerk.dev/docs)  
     - **Video:** [Custom Clerk UI](https://www.youtube.com/watch?v=hrZrbWrhT-s)

- **Deliverables:**
  - Functional authentication system with social sign-ins.

---

### **Week 3: Meeting Rooms and Video Integration**
- **Goal:** Implement real-time video and meeting management.

- **Tasks:**
  1. Integrate **Stream API** for video/audio calls.
     - **Reading:** [Stream API Docs](https://getstream.io/docs/)  
     - **Video:** [Integrating Stream for Video Calls](https://www.youtube.com/watch?v=j2b5gO-p0q0)
  2. Create meeting routes using **Dynamic Routing**.
     - **Reading:** [Dynamic Routes in Next.js](https://nextjs.org/docs/app/building-your-application/routing)  
     - **Video:** [Dynamic Pages Tutorial](https://www.youtube.com/watch?v=0cJ4aB3qYpU)
  3. Implement meeting controls (mute, unmute, exit).
     - **Reading:** [Video Controls in Stream](https://getstream.io/)  
     - **Video:** [Meeting Controls in React](https://www.youtube.com/watch?v=JW6XdATiSkM)

- **Deliverables:**
  - Fully functional video conferencing feature.

---

### **Week 4: Real-Time Chat and Features**
- **Goal:** Add real-time chat and interactive meeting options.

- **Tasks:**
  1. Integrate chat functionality using **Stream Chat**.
     - **Reading:** [Stream Chat Integration](https://getstream.io/chat/docs/)  
     - **Video:** [Building Chat Apps](https://www.youtube.com/watch?v=7dqxzFnu33g)
  2. Add screen sharing and emoji reactions.
     - **Reading:** [Screen Sharing in Stream](https://getstream.io/)  
     - **Video:** [React Screen Sharing](https://www.youtube.com/watch?v=x5xN4_wQZpY)
  3. Display participant list with dynamic management.

- **Deliverables:**
  - Live chat and interactive features within meetings.

---

### **Week 5: Deployment and Testing**
- **Goal:** Deploy the ZoomClone app and ensure optimal performance.

- **Tasks:**
  1. Deploy the app on **Vercel**.
     - **Reading:** [Vercel Deployment Guide](https://vercel.com/docs)  
     - **Video:** [Deploying Next.js on Vercel](https://www.youtube.com/watch?v=6W8opwF7gXg)
  2. Test for performance, bugs, and responsiveness.
     - **Reading:** [Next.js Testing](https://nextjs.org/docs/app/building-your-application/testing)  
     - **Video:** [Testing React Apps](https://www.youtube.com/watch?v=8Xwq35cPwYg)
  3. Optimize video quality and API performance.

- **Deliverables:**
  - Deployed ZoomClone app accessible via public URL.

---

### **Screenshots**
<div align="center">
  <br />
    <a href="https://youtu.be/R8CIO1DZ2b8" target="_blank">
      <img src="https://github.com/adrianhajdin/zoom-clone/assets/67959015/f09a8421-67d3-45ce-b9bc-a791cdc2774b" alt="Project Banner">
    </a>
  
  <br />

---

## **References**
1. [Next.js Documentation](https://nextjs.org/docs)
2. [Stream API Docs](https://getstream.io/docs/)
3. [Clerk Documentation](https://clerk.dev/docs)
4. [Tailwind CSS Docs](https://tailwindcss.com/docs)
5. [ShadCN UI Docs](https://ui.shadcn.com/docs)

---
















  <div>
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="typescript" />
    <img src="https://img.shields.io/badge/-Next_JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000" alt="nextdotjs" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
  </div>

  <h3 align="center">A Zoom Clone</h3>

   <div align="center">
     Build this project step by step with our detailed tutorial on <a href="https://www.youtube.com/@javascriptmastery/videos" target="_blank"><b>JavaScript Mastery</b></a> YouTube. Join the JSM family!
    </div>
</div>

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🕸️ [Assets & Code](#snippets)
6. 🚀 [More](#more)

## 🚨 Tutorial

This repository contains the code corresponding to an in-depth tutorial available on our YouTube channel, <a href="https://www.youtube.com/@javascriptmastery/videos" target="_blank"><b>JavaScript Mastery</b></a>. 

If you prefer visual learning, this is the perfect resource for you. Follow our tutorial to learn how to build projects like these step-by-step in a beginner-friendly manner!

<a href="https://youtu.be/R8CIO1DZ2b8" target="_blank"><img src="https://github.com/sujatagunale/EasyRead/assets/151519281/1736fca5-a031-4854-8c09-bc110e3bc16d" /></a>

## <a name="introduction">🤖 Introduction</a>

Built with the latest Next.js and TypeScript, this project replicates Zoom, a widely used video conferencing tool. It enables users to securely log in, create meetings and access various meeting functionalities such as recording, screen sharing, and managing participants.

If you're getting started and need assistance or face any bugs, join our active Discord community with over 30 thousand members. It's a place where people help each other out.

<a href="https://discord.com/invite/n6EdbFJ" target="_blank"><img src="https://github.com/sujatagunale/EasyRead/assets/151519281/618f4872-1e10-42da-8213-1d69e486d02e" /></a>

## <a name="tech-stack">⚙️ Tech Stack</a>

- Next.js
- TypeScript
- Clerk
- getstream
- shadcn
- Tailwind CSS

## <a name="features">🔋 Features</a>


👉 **Authentication**: Implements authentication and authorization features using Clerk, allowing users to securely log in via social sign-on or traditional email and password methods, while ensuring appropriate access levels and permissions within the platform.

👉 **New Meeting**: Quickly start a new meeting, configuring camera and microphone settings before joining.

👉 **Meeting Controls**: Participants have full control over meeting aspects, including recording, emoji reactions, screen sharing, muting/unmuting, sound adjustments, grid layout, participant list view, and individual participant management (pinning, muting, unmuting, blocking, allowing video share).

👉 **Exit Meeting**: Participants can leave a meeting, or creators can end it for all attendees.

👉 **Schedule Future Meetings**: Input meeting details (date, time) to schedule future meetings, accessible on the 'Upcoming Meetings' page for sharing the link or immediate start.

👉 **Past Meetings List**: Access a list of previously held meetings, including details and metadata.

👉 **View Recorded Meetings**: Access recordings of past meetings for review or reference.

👉 **Personal Room**: Users have a personal room with a unique meeting link for instant meetings, shareable with others.

👉 **Join Meetings via Link**: Easily join meetings created by others by providing a link.

👉 **Secure Real-time Functionality**: All interactions within the platform are secure and occur in real-time, maintaining user privacy and data integrity.

👉 **Responsive Design**: Follows responsive design principles to ensure optimal user experience across devices, adapting seamlessly to different screen sizes and resolutions.

and many more, including code architecture and reusability. 

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/adrianhajdin/zoom-clone.git
cd zoom-clone
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

NEXT_PUBLIC_STREAM_API_KEY=
STREAM_SECRET_KEY=
```

Replace the placeholder values with your actual Clerk & getstream credentials. You can obtain these credentials by signing up on the [Clerk website](https://clerk.com/) and [getstream website](https://getstream.io/)

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

## <a name="snippets">🕸️ Snippets</a>

<details>
<summary><code>app/globals.css</code></summary>

```css
@tailwind base;
@tailwind components;
@tailwind utilities;

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* ======== stream css overrides ======== */
.str-video__call-stats {
  max-width: 500px;
  position: relative;
}

.str-video__speaker-layout__wrapper {
  max-height: 700px;
}

.str-video__participant-details {
  color: white;
}

.str-video__menu-container {
  color: white;
}

.str-video__notification {
  color: white;
}

.str-video__participant-list {
  background-color: #1c1f2e;
  padding: 10px;
  border-radius: 10px;
  color: white;
  height: 100%;
}

.str-video__call-controls__button {
  height: 40px;
}

.glassmorphism {
  background: rgba(255, 255, 255, 0.25);
  backdrop-filter: blur(4px);
  -webkit-backdrop-filter: blur(4px);
}
.glassmorphism2 {
  background: rgba(18, 17, 17, 0.25);
  backdrop-filter: blur(8px);
  -webkit-backdrop-filter: blur(8px);
}

/* ==== clerk class override ===== */

.cl-userButtonPopoverActionButtonIcon {
  color: white;
}

.cl-logoBox {
  height: 40px;
}
.cl-dividerLine {
  background: #252a41;
  height: 2px;
}

.cl-socialButtonsIconButton {
  border: 3px solid #565761;
}

.cl-internal-wkkub3 {
  color: white;
}
.cl-userButtonPopoverActionButton {
  color: white;
}

/* =============================== */

@layer utilities {
  .flex-center {
    @apply flex justify-center items-center;
  }

  .flex-between {
    @apply flex justify-between items-center;
  }
}

/* animation */

.show-block {
  width: 100%;
  max-width: 350px;
  display: block;
  animation: show 0.7s forwards linear;
}

@keyframes show {
  0% {
    animation-timing-function: ease-in;
    width: 0%;
  }

  100% {
    animation-timing-function: ease-in;
    width: 100%;
  }
}
```

</details>

<details>
<summary><code>tailwind.config.ts</code></summary>

```typescript
import type { Config } from 'tailwindcss';

const config = {
  darkMode: ['class'],
  content: [
    './pages/**/*.{ts,tsx}',
    './components/**/*.{ts,tsx}',
    './app/**/*.{ts,tsx}',
    './src/**/*.{ts,tsx}',
  ],
  prefix: '',
  theme: {
    container: {
      center: true,
      padding: '2rem',
      screens: {
        '2xl': '1400px',
      },
    },
    extend: {
      colors: {
        dark: {
          1: '#1C1F2E',
          2: '#161925',
          3: '#252A41',
          4: '#1E2757',
        },
        blue: {
          1: '#0E78F9',
        },
        sky: {
          1: '#C9DDFF',
          2: '#ECF0FF',
          3: '#F5FCFF',
        },
        orange: {
          1: '#FF742E',
        },
        purple: {
          1: '#830EF9',
        },
        yellow: {
          1: '#F9A90E',
        },
      },
      keyframes: {
        'accordion-down': {
          from: { height: '0' },
          to: { height: 'var(--radix-accordion-content-height)' },
        },
        'accordion-up': {
          from: { height: 'var(--radix-accordion-content-height)' },
          to: { height: '0' },
        },
      },
      animation: {
        'accordion-down': 'accordion-down 0.2s ease-out',
        'accordion-up': 'accordion-up 0.2s ease-out',
      },
      backgroundImage: {
        hero: "url('/images/hero-background.png')",
      },
    },
  },
  plugins: [require('tailwindcss-animate')],
} satisfies Config;

export default config;
```

</details>

<details>
<summary><code>components/MeetingCard.tsx</code></summary>

```typescript
"use client";

import Image from "next/image";

import { cn } from "@/lib/utils";
import { Button } from "./ui/button";
import { avatarImages } from "@/constants";
import { useToast } from "./ui/use-toast";

interface MeetingCardProps {
  title: string;
  date: string;
  icon: string;
  isPreviousMeeting?: boolean;
  buttonIcon1?: string;
  buttonText?: string;
  handleClick: () => void;
  link: string;
}

const MeetingCard = ({
  icon,
  title,
  date,
  isPreviousMeeting,
  buttonIcon1,
  handleClick,
  link,
  buttonText,
}: MeetingCardProps) => {
  const { toast } = useToast();

  return (
    <section className="flex min-h-[258px] w-full flex-col justify-between rounded-[14px] bg-dark-1 px-5 py-8 xl:max-w-[568px]">
      <article className="flex flex-col gap-5">
        <Image src={icon} alt="upcoming" width={28} height={28} />
        <div className="flex justify-between">
          <div className="flex flex-col gap-2">
            <h1 className="text-2xl font-bold">{title}</h1>
            <p className="text-base font-normal">{date}</p>
          </div>
        </div>
      </article>
      <article className={cn("flex justify-center relative", {})}>
        <div className="relative flex w-full max-sm:hidden">
          {avatarImages.map((img, index) => (
            <Image
              key={index}
              src={img}
              alt="attendees"
              width={40}
              height={40}
              className={cn("rounded-full", { absolute: index > 0 })}
              style={{ top: 0, left: index * 28 }}
            />
          ))}
          <div className="flex-center absolute left-[136px] size-10 rounded-full border-[5px] border-dark-3 bg-dark-4">
            +5
          </div>
        </div>
        {!isPreviousMeeting && (
          <div className="flex gap-2">
            <Button onClick={handleClick} className="rounded bg-blue-1 px-6">
              {buttonIcon1 && (
                <Image src={buttonIcon1} alt="feature" width={20} height={20} />
              )}
              &nbsp; {buttonText}
            </Button>
            <Button
              onClick={() => {
                navigator.clipboard.writeText(link);
                toast({
                  title: "Link Copied",
                });
              }}
              className="bg-dark-4 px-6"
            >
              <Image
                src="/icons/copy.svg"
                alt="feature"
                width={20}
                height={20}
              />
              &nbsp; Copy Link
            </Button>
          </div>
        )}
      </article>
    </section>
  );
};

export default MeetingCard;
```

</details>

## <a name="links">🔗 Links</a>

Public assets used in the project can be found [here](https://drive.google.com/file/d/1ofTpWii_sCIdJ14uQ431xWVXpYgjtQ8Q/view?usp=sharing)

## <a name="more">🚀 More</a>

**Advance your skills with Next.js Pro Course**

Enjoyed creating this project? Dive deeper into our PRO courses for a richer learning experience. They're packed with detailed explanations, cool features, and exercises to boost your skills. Give it a go!

<a href="https://www.jsmastery.pro/ultimate-next-course" target="_blank">
<img src="https://i.ibb.co/804sPK6/Image-720.png" alt="Project Banner">
</a>
