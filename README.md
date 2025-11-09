<br />
<a href="https://youtu.be/lie0cr3wESQ" target="_blank">
  <img src="public/readme/hero.png" alt="Storage Management Solution - Project Banner" width="100%" />
</a>
<br />
<br />

<div>
  <img src="https://img.shields.io/badge/Next.js-15-black?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js 15" />
  <img src="https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React 19" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Appwrite-FD366E?style=for-the-badge&logo=appwrite&logoColor=white" alt="Appwrite" />
</div>

<h1>Storage Management Solution</h1>
<p>A modern, full-stack file storage and sharing platform built with cutting-edge technologies</p>

<br />

## 📸 Preview
<img width="2087" height="1216" alt="image" src="https://github.com/user-attachments/assets/d3bcab7d-102b-4f69-966b-35af9a6206f3" />

## 📋 Table of Contents

- [🤖 Introduction](#introduction)
- [⚙️ Tech Stack](#tech-stack)
- [🔋 Features](#features)
- [🚀 Quick Start](#quick-start)
- [🔗 Assets](#assets)
- [🎯 More Resources](#more-resources)

## <a name="introduction"></a>🤖 Introduction

A comprehensive cloud storage solution that enables users to upload, manage, and share files seamlessly. Built with the latest web technologies including React 19, Next.js 15, and Appwrite backend services.

## <a name="tech-stack"></a>⚙️ Tech Stack

- **Frontend**: React 19, Next.js 15, TypeScript
- **Styling**: TailwindCSS, ShadCN/UI
- **Backend**: Appwrite (Authentication, Database, Storage)
- **State Management**: React Hooks & Context
- **Development**: ESLint, Prettier, TypeScript

## <a name="features"></a>🔋 Features

### 🔐 Authentication & Security
- Secure user authentication with Appwrite
- Session management and protected routes

### 📁 File Management
- **Multi-format Support**: Upload documents, images, videos, and audio files
- **File Operations**: Rename, delete, and organize files efficiently
- **Storage Analytics**: Dashboard with storage usage insights and file type breakdown
- **Smart Sorting**: Sort files by date, name, or size

### 🔄 Sharing & Collaboration
- **Easy File Sharing**: Generate shareable links for collaboration
- **Download Management**: Secure file downloads with proper access control

### 🔍 Advanced Search & UX
- **Global Search**: Find files and shared content across the platform
- **Responsive Design**: Optimized for all devices with modern UI/UX
- **Recent Activity**: Quick access to recently uploaded files

## <a name="quick-start"></a>🚀 Quick Start

### Prerequisites

Ensure you have the following installed:
- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en) (v18 or higher)
- [npm](https://www.npmjs.com/)

### Installation

1. **Clone the repository**
   ```
   git clone https://github.com/JavaScript-Mastery-Pro/storage_management_solution.git
   ```
   ```
   cd storage_management_solution
   ```
   
2. **Install dependencies**
   ```
   npm install
   ```
   
3. **Environment Setup**
   ```
   NEXT_PUBLIC_APPWRITE_ENDPOINT="https://cloud.appwrite.io/v1"
   ```
   ```
   NEXT_PUBLIC_APPWRITE_PROJECT="your_project_id"
   ```
   ```
   NEXT_PUBLIC_APPWRITE_DATABASE="your_database_id"
   ```
   ```
   NEXT_PUBLIC_APPWRITE_USERS_COLLECTION="your_users_collection_id"
   ```
   ```
   NEXT_PUBLIC_APPWRITE_FILES_COLLECTION="your_files_collection_id"
   ```
   ```
   NEXT_PUBLIC_APPWRITE_BUCKET="your_bucket_id"
   ```
   ```
   NEXT_APPWRITE_KEY="your_appwrite_key"
   ```
4. **Run the development server**
    ```
    npm run dev
    ```
5. **Open your browser**
- Navigate to http://localhost:3000
