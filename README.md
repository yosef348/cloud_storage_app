# StoreIt

StoreIt - The only storage solution you need for your business.

## 🚀 Overview

StoreIt is a modern cloud storage application built with Next.js that allows users to securely upload, manage, and organize their files. It provides a user-friendly interface for handling various file types including documents, images, media, and more, with features like drag-and-drop uploads, advanced search, and file conversion capabilities.

## ⚙️ Tech Stack

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

## 🔋 Features

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

## 📸 Screenshots

![Dashboard](./public/readme/dashboard.png)
![File Upload](./public/readme/upload.png)
![File Management](./public/readme/files.png)

## 🛠️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd storeit
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**

   Create a `.env.local` file in the root directory and add your Appwrite configuration:
   ```env
   NEXT_PUBLIC_APPWRITE_PROJECT_ID=your_project_id
   NEXT_PUBLIC_APPWRITE_URL=your_appwrite_url
   NEXT_PUBLIC_APPWRITE_DATABASE_ID=your_database_id
   NEXT_PUBLIC_APPWRITE_STORAGE_ID=your_storage_id
   NEXT_PUBLIC_APPWRITE_BUCKET_ID=your_bucket_id
   NEXT_PUBLIC_APPWRITE_USERS_COLLECTION_ID=your_users_collection_id
   NEXT_PUBLIC_APPWRITE_FILES_COLLECTION_ID=your_files_collection_id
   ```

4. **Set up Appwrite**

   - Create an Appwrite project
   - Configure database collections for users and files
   - Set up storage bucket for file uploads
   - Update the environment variables with your Appwrite credentials

5. **Run the development server**
   ```bash
   npm run dev
   ```

6. **Open your browser**

   Navigate to [http://localhost:3000](http://localhost:3000) to see the application.

## 📁 Project Structure

```
storeit/
├── app/                    # Next.js app directory
│   ├── (auth)/            # Authentication routes
│   ├── (root)/            # Protected routes
│   └── globals.css        # Global styles
├── components/            # Reusable UI components
│   ├── ui/               # Radix UI components
│   └── ...               # Custom components
├── constants/            # App constants and config
├── hooks/                # Custom React hooks
├── lib/                  # Utility functions and integrations
│   ├── actions/          # Server actions
│   └── appwrite/         # Appwrite configuration
├── public/               # Static assets
└── types/                # TypeScript type definitions
```

## 🚀 Deployment

### Build for production
```bash
npm run build
```

### Start production server
```bash
npm start
```

### Deploy to Vercel
The easiest way to deploy is using Vercel:

1. Push your code to GitHub
2. Connect your repository to Vercel
3. Add environment variables in Vercel dashboard
4. Deploy

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Support

For support, email support@storeit.com or join our Discord community.

---

Built with ❤️ using Next.js and Appwrite
