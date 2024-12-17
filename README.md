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

### **Workflow Overview**
This section illustrates the interaction between the frontend, CSS-based styling, and deployment workflow.

## **System Architecture**

The **ZoomClone** system architecture demonstrates the following:
1. **Next.js Frontend**: Handles user interface, routing, and client-side logic.
2. **Stream API**: Manages real-time video and chat infrastructure.
3. **Clerk Authentication**: Manages user sessions and security.
4. **API Routes**: Handles backend requests for meeting management.
5. **Deployment on Vercel**: Ensures scalability and global availability.

![image](https://github.com/user-attachments/assets/f177ffbd-dc98-42e3-8da1-a93487073af0) 

---

### **Project Structure for Feature Implementation**
This project is structured to ensure a systematic and incremental development process. Each week builds upon the previous deliverables, enabling a smooth transition from basic to advanced functionalities.

**NOTE:** Participants are encouraged to customize the design and functionality to make the application unique.

---

## **Week-by-Week Plan**

---

### **Week 1: Project Setup and UI Components**
- **Goal:** Initialize the project and set up the UI structure.

- **Tasks:**
  1. Initialize the Next.js app with TypeScript.
     - **Reading:** [Next.js Docs](https://nextjs.org/docs)  
     - **Video:** [Setting Up Next.js](https://www.youtube.com/watch?v=ZVnjOPwW4ZA&t=63s)
  2. Integrate **Tailwind CSS** for styling.
     - **Reading:** [Tailwind CSS Setup](https://tailwindcss.com/docs)  
     - **Video:** [Tailwind CSS Tutorial](https://www.youtube.com/watch?v=dFgzHOX84xQ)
  3. Install and configure **ShadCN UI** for reusable components.
     - **Reading:** [ShadCN UI Guide](https://ui.shadcn.com/docs)  
     - **Video:** [ShadCN Setup](https://www.youtube.com/watch?v=O4AjymzpIEg)
  4. Build a basic layout with **navbar** and **sidebar**.
     - **Reading:** [Layout in Next.js](https://nextjs.org/docs/app/building-your-application)  
     - **Video:** [Next.js Layouts](https://www.youtube.com/watch?v=ZVnjOPwW4ZA&t=83s)

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
     - **Video:** [Custom Clerk UI](https://www.youtube.com/watch?v=MGwbCxnGDUM)

- **Deliverables:**
  - Functional authentication system with social sign-ins.

---

### **Week 3: Meeting Rooms and Video Integration**
- **Goal:** Implement real-time video and meeting management.

- **Tasks:**
  1. Integrate **Stream API** for video/audio calls.
     - **Reading:** [Stream API Docs](https://getstream.io/docs/)  
     - **Video:** [Integrating Stream for Video Calls](https://www.youtube.com/watch?v=64LJJhT6Ybo)
  2. Create meeting routes using **Dynamic Routing**.
     - **Reading:** [Dynamic Routes in Next.js](https://nextjs.org/docs/app/building-your-application/routing)  
     - **Video:** [Dynamic Pages Tutorial](https://www.youtube.com/watch?v=D7YuI6vOzdY)
  3. Implement meeting controls (mute, unmute, exit).
     - **Reading:** [Video Controls in Stream](https://getstream.io/)  
     - **Video:** [Meeting Controls](https://www.youtube.com/watch?v=8guP6F56TPk)

- **Deliverables:**
  - Fully functional video conferencing feature.

---

### **Week 4: Real-Time Chat and Features**
- **Goal:** Add real-time chat and interactive meeting options.

- **Tasks:**
  1. Integrate chat functionality using **Stream Chat**.
     - **Reading:** [Stream Chat Integration](https://getstream.io/chat/docs/)  
     - **Video:** [Building Chat Apps](https://www.youtube.com/watch?v=xO9QDQaVHxU)
  2. Add screen sharing and emoji reactions.
     - **Reading:** [Screen Sharing in Stream](https://getstream.io/)  
     - **Video:** [Screen Sharing](https://www.youtube.com/watch?v=X8QHHB7DA90)
  3. Display participant list with dynamic management.

- **Deliverables:**
  - Live chat and interactive features within meetings.

---

### **Week 5: Deployment and Testing**
- **Goal:** Deploy the ZoomClone app and ensure optimal performance.

- **Tasks:**
  1. Deploy the app on **Vercel**.
     - **Reading:** [Vercel Deployment Guide](https://vercel.com/docs)  
     - **Video:** [Deploying Next.js on Vercel](https://www.youtube.com/watch?v=2HBIzEx6IZA)
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
  </div>

![Screenshot (294)](https://github.com/user-attachments/assets/88eb0189-b011-42a1-a585-703c8f3d9e89)
![Screenshot (295)](https://github.com/user-attachments/assets/feba7f8e-6563-46da-bb0f-39153416a377)
![Screenshot (296)](https://github.com/user-attachments/assets/1f831080-03e5-4cef-a0d0-d91f74ab06b8)
![Screenshot (297)](https://github.com/user-attachments/assets/00d46018-1ce8-4e9e-8664-d286aaffef95)
![Screenshot (298)](https://github.com/user-attachments/assets/5f7c659c-d124-4991-a5c8-3f0e564175dd)
![Screenshot (299)](https://github.com/user-attachments/assets/5a93cf3a-5aa0-43c9-8d08-e2a18affd433)
![Screenshot (300)](https://github.com/user-attachments/assets/6c2353fe-c73a-400a-a192-2cf2da4ccd0b)
![Screenshot (301)](https://github.com/user-attachments/assets/c528c196-5d2c-4fe2-9843-398eb2a9c4cd)
![Screenshot (302)](https://github.com/user-attachments/assets/e7883db4-37ad-4b4a-8824-4fbd7445f1e7)
![Screenshot (303)](https://github.com/user-attachments/assets/964d9e29-c36c-4416-b1bd-4dbe65d4dadd)
![Screenshot (304)](https://github.com/user-attachments/assets/959f9143-f706-435c-bf12-9fa3a0749164)
![Screenshot (305)](https://github.com/user-attachments/assets/e5cd4c38-4eeb-46b3-8b6b-32309deaefab)
![Screenshot (281)](https://github.com/user-attachments/assets/abbbd962-451c-47c2-8175-f87180c9b571)
![Screenshot (290)](https://github.com/user-attachments/assets/85e643e6-87fd-4294-b050-eb0457ad8f85)
![Screenshot (291)](https://github.com/user-attachments/assets/e62e3e76-709f-4950-b431-2ed81f9140db)
![Screenshot (292)](https://github.com/user-attachments/assets/25d9259c-8b73-463d-8aa6-2b80cbd17ca0)
![Screenshot (293)](https://github.com/user-attachments/assets/c2feb872-67bb-46a5-a4f3-3cd5fd16ed3a)

---

## **References**
1. [Next.js Documentation](https://nextjs.org/docs)
2. [Stream API Docs](https://getstream.io/docs/)
3. [Clerk Documentation](https://clerk.dev/docs)
4. [Tailwind CSS Docs](https://tailwindcss.com/docs)
5. [ShadCN UI Docs](https://ui.shadcn.com/docs)
6. https://www.youtube.com/watch?v=R8CIO1DZ2b8&t=102s
7. https://github.com/adrianhajdin/zoom-clone

---
