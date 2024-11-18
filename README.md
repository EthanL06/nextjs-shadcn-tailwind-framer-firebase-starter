# Next.js 15 + ShadCN UI + Tailwind CSS + Framer Motion + Firebase Template  

A modern, opinionated starter template featuring a powerful tech stack to kickstart your Next.js projects.

## 🔥 Features  

- **Next.js 15**: The latest version of Next.js for robust and scalable React applications.  
- **ShadCN UI**: Pre-styled components with seamless integration for a great developer experience.  
- **Tailwind CSS**: Utility-first CSS framework for building stunning designs efficiently.  
- **Framer Motion**: Easy and intuitive animations to bring life to your UI.  
- **Firebase**: Backend integration for authentication, database, and hosting services.  

---

## 📦 Installation  

Clone the repository and install dependencies:  

```bash  
git clone https://github.com/EthanL06/nextjs-shadcn-tailwind-framer-firebase-starter.git  
cd nextjs-shadcn-tailwind-framer-firebase-starter  
pnpm install  
```

---

## 🚀 Getting Started  

1. **Set Up Firebase**:  
   - Create a project in [Firebase Console](https://console.firebase.google.com/).  
   - Add your Firebase configuration to `.env.local`:
     ```env  
     NEXT_PUBLIC_FIREBASE_API_KEY=your-api-key  
     NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your-auth-domain  
     NEXT_PUBLIC_FIREBASE_PROJECT_ID=your-project-id  
     NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your-storage-bucket  
     NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your-messaging-sender-id  
     NEXT_PUBLIC_FIREBASE_APP_ID=your-app-id  
     ```

2. **Run Development Server**:  
   Start the Next.js development server:  

   ```bash  
   pnpm run dev  
   ```

3. **Build and Deploy**:  
   Build the app for production and deploy it to your hosting provider.  

   ```bash  
   pnpm run build  
   pnpm run start  
   ```

---

## 🛠 Tech Stack  

| Technology    | Purpose                              |  
|---------------|--------------------------------------|  
| Next.js 15    | Framework for server-side rendering and API routes. |  
| ShadCN UI     | Component library for consistent UI. |  
| Tailwind CSS  | Utility-first CSS for rapid UI development. |  
| Framer Motion | Animations and motion effects.       |  
| Firebase      | Backend services (auth, database, hosting). |  

---

## 🧩 Folder Structure  

```plaintext  
├── components/   # Reusable UI components  
├── pages/        # Next.js page routes  
├── public/       # Static assets  
├── styles/       # Global and Tailwind CSS files  
├── utils/        # Helper functions and configurations  
├── firebase/     # Firebase setup and initialization  
└── .env.local    # Environment variables  
```

---

## 🎨 Customization  

- Modify Tailwind configuration in `tailwind.config.ts`.  
- Update components or create new ones in `components/`.  
- Integrate additional Firebase services as needed.  

---

## 📖 Resources  

- [Next.js Documentation](https://nextjs.org/docs)  
- [ShadCN UI Documentation](https://shadcn.dev/)  
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)  
- [Framer Motion Documentation](https://www.framer.com/motion/)  
- [Firebase Documentation](https://firebase.google.com/docs)  

---

## 💡 Contributing  

Contributions are welcome! Feel free to fork the repository, create a feature branch, and submit a pull request.  

---

## ⚖️ License  

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.  

