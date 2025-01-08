<div align="center">

# 🚀 **LiveDocs**: A Collaborative Real-Time Editor

![Next.js](https://img.shields.io/badge/-Next_JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=61DAFB)
![TypeScript](https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4)

### 📝 Real-time Collaboration Made Easy!
Developed with **Next.js**, styled with **TailwindCSS**, and powered by **Liveblocks**, LiveDocs is a collaborative text editor inspired by Google Docs.

</div>

---

## 🤖 **Introduction**

**LiveDocs** is a modern real-time collaborative editor featuring a clean UI and robust functionality. It demonstrates advanced developer skills in building scalable, real-time environments, creating a lasting impression.

---

## ⚙️ **Tech Stack**

- **Next.js**
- **TypeScript**
- **Liveblocks**
- **Lexical Editor**
- **ShadCN**
- **Tailwind CSS**

---

## 🔋 **Features**

- 🔑 **Authentication**: Secure user authentication via GitHub using **NextAuth**.
- ✍️ **Collaborative Text Editor**: Real-time updates for multiple users editing the same document.
- 🗂️ **Document Management**:
  - Create, delete, and list documents.
  - Share documents with **view/edit** permissions via email or link.
- 💬 **Comments**: Inline and general comments with discussion threads.
- 👥 **Active Collaborators**: Real-time presence indicators for active collaborators.
- 🔔 **Notifications**: Alerts for document shares, comments, and collaborator activities.
- 📱 **Responsive Design**: Fully responsive across all devices.
- 🎨 **Code Architecture**: Focused on modularity and reusability.

---

## 🤸 **Quick Start**

### **Prerequisites**

Ensure the following tools are installed on your machine:
- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/)

### **Cloning the Repository**
```bash
git clone https://github.com/niladri-1/LiveDocs.git
cd LiveDocs
```

### **Installing Dependencies**
```bash
npm install
```

### **Set Up Environment Variables**

Create a `.env` file in the root directory and add the following:
```env
# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

# Liveblocks
NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=
LIVEBLOCKS_SECRET_KEY=
```

Replace placeholder values with your **Clerk** and **Liveblocks** credentials. Sign up on [Clerk](https://clerk.com/) and [Liveblocks](https://liveblocks.io/) to get your keys.

### **Running the Project**
```bash
npm run dev
```

Open **[`http://localhost:3000`](http://localhost:3000)** in your browser to view the project. 🎉

```