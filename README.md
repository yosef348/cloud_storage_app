<img width="6912" height="2304" alt="storeit" src="https://github.com/user-attachments/assets/b5c57952-7b47-4101-8541-6ba713120387" />


# StoreIt

StoreIt - The only storage solution you need for your business.

## Overview

StoreIt is a modern cloud storage application built with Next.js that allows users to securely upload, manage, and organize their files. It provides a user-friendly interface for handling various file types including documents, images, media, and more, with features like drag-and-drop uploads, advanced search, and file conversion capabilities.

## Tech Stack

### Frontend
- **Next.js 16** - React framework with App Router
- **React 19** - UI library
- **TypeScript** - Type-safe JavaScript

### Styling
- **Tailwind CSS** - Utility-first CSS framework
- **Radix UI** - Accessible UI components
- **Lucide React** - Icon library

### Backend & Storage
- **Appwrite** - Backend-as-a-Service for authentication, database, and file storage

### Form Handling & Validation
- **React Hook Form** - Performant forms
- **Zod** - Schema validation

### Additional Libraries
- **Recharts** - Data visualization
- **React Dropzone** - File upload handling
- **use-debounce** - Debounced search

## Features

- **User Authentication** - Secure sign-in and sign-up with Appwrite
- **Dashboard** - Overview of recent files and storage usage
- **File Upload** - Drag-and-drop interface with progress tracking (max 50MB)
- **File Management** - View, rename, share, download, and delete files
- **File Organization** - Categorize files by type (documents, images, media, others)
- **Advanced Search** - Real-time file search with debouncing
- **Sorting Options** - Sort by date, name, or file size
- **File Conversion** - Convert files to PDF, JPG, PNG, TXT, DOCX, XLSX formats
- **Responsive Design** - Mobile-friendly interface
- **Data Visualization** - Charts showing file type distribution
- **Toast Notifications** - User feedback for actions
