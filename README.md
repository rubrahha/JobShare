# 💼 Job Share

**Job Share** is a collaborative platform designed to help users share and discover job opportunities. Built with a focus on *collaboration* rather than *competition*, this application allows users to post jobs, filter opportunities, and connect with others in meaningful ways.

---

## ✨ Features

- **Job Posting**: Submit job opportunities with details like title, company, location, type, and tags.
- **Job Filtering**: Filter jobs by type, location, and tags to find the most relevant opportunities.
- **Tag Management**: Add and remove tags to categorize jobs effectively.
- **Responsive Design**: User-friendly interface optimized for both light and dark modes.
- **Job Previews**: Fetch and display job link previews using external APIs.
- **Backend API**: A robust API for managing job data, with validation and database integration.

---

## 🛠️ Tech Stack

- **Frontend**: React with Next.js
- **Styling**: Tailwind CSS
- **Backend**: Node.js using Next.js API routes
- **Database**: MongoDB

### 📚 Libraries & Tools

- [`axios`](https://github.com/axios/axios) – For HTTP requests  
- [`mongoose`](https://mongoosejs.com/) – For MongoDB data modeling  
- [`sonner`](https://sonner.emilkowal.ski/) – For toast notifications  
- [`lucide-react`](https://lucide.dev/) – For icons  

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/jobshare.git
cd jobshare

### 2. Install Dependecies
npm install

### 3.Set up environment variables
create a .env.local file in the root directory and add the following:
MONGODB_URI=<your-mongodb-connection-string>

### 4.Start the development server
npm run dev
visit the app at: http://localhost:3000


Example job Posting JSON
{
  "title": "Frontend Developer",
  "company": "Tech Corp",
  "location": "Remote",
  "link": "https://example.com/job",
  "description": "Looking for a skilled frontend developer.",
  "type": "Full Time",
  "tags": ["React", "JavaScript"]
}
