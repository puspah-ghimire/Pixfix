# PixFix

## Overview

PixFix is an AI-powered image editing platform built to simplify image transformation and enhancement. It provides users with powerful AI-based editing tools through a clean and intuitive interface.

Built with **Next.js** and **TypeScript**, PixFix allows users to effortlessly edit images using advanced AI capabilities such as image restoration, recoloring, object removal, generative filling, and background removal.

The platform uses **Cloudinary AI** for intelligent image processing, **Clerk** for secure authentication, and **Stripe** for seamless payment management. PixFix delivers a fast, secure, and affordable image editing experience designed for modern creators and businesses.

---

## Features

### AI-Powered Image Editing

- **Image Restoration**  
  Enhance old, damaged, or low-quality images using AI-powered restoration.

- **Image Recoloring**  
  Change and enhance image colors with intelligent AI transformations.

- **Object Removal**  
  Remove unwanted objects from images while maintaining realistic backgrounds.

- **Generative Fill**  
  Extend and modify images with AI-generated content.

- **Background Removal**  
  Automatically remove image backgrounds with AI precision.

---

## Authentication

- Secure user authentication using **Clerk**
- User-specific image editing and management
- Protected routes and secure sessions

---

## Payments

- Integrated payment system using **Stripe**
- Credit-based image transformation system
- Secure and smooth checkout experience

---

## AI & Cloud Processing

- Powered by **Cloudinary AI**
- Fast image processing and optimization
- Reliable cloud-based image management

---

## Tech Stack

- **Next.js**
- **TypeScript**
- **React**
- **Tailwind CSS**
- **Cloudinary AI**
- **Clerk Authentication**
- **Stripe Payments**
- **MongoDB**
- **Vercel**

---

## Preview

### Home Page

<img width="1918" height="1078" alt="1" src="https://github.com/user-attachments/assets/0511f6b8-03f6-4b05-a975-15d2b389dddd" />

### AI Image Editor

<img width="1918" height="1078" alt="2" src="https://github.com/user-attachments/assets/4e877f49-b27f-4748-be38-40b11aaa0573" />

### Image Transformations

<img width="1918" height="1078" alt="11" src="https://github.com/user-attachments/assets/072a50d2-e74c-4bec-bc35-3cea06834cd5" />
<img width="1918" height="1078" alt="111" src="https://github.com/user-attachments/assets/ebb31265-bb28-491c-b528-9c380360902a" />
<img width="1917" height="1078" alt="1111" src="https://github.com/user-attachments/assets/ee987e8a-d3d0-43d7-a5ee-55592c107a8f" />

### Login Page

<img width="1918" height="1078" alt="11111" src="https://github.com/user-attachments/assets/49ceb488-d103-49b4-9bf9-d7bd95973f77" />


### Payment Plans

<img width="1918" height="1078" alt="4" src="https://github.com/user-attachments/assets/807f6d8e-e4cc-4661-b64c-f96b4e6efeb9" />


---

## Installation & Setup

Clone the repository:

```bash
git clone https://github.com/puspah-ghimire/Pixfix.git
```

Navigate into the project:

```bash
cd Pixfix
```

Install dependencies:

```bash
npm install
```

Create a `.env` file and add the following environment variables:

```env
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=
NEXT_PUBLIC_SERVER_URL=https://pixfix.vercel.app
MONGODB_URL=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/
```

Run the development server:

```bash
npm run dev
```

Open your browser:

```
http://localhost:3000
```

---
