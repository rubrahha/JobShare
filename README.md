Job Share is a collaborative platform designed to help users share and discover job opportunities. Built with a focus on collaboration rather than competition, this application allows users to post jobs, filter opportunities, and connect with others in a meaningful way.

Features
*Job Posting: Submit job opportunities with details like title, company, location, type, and tags.
*Job Filtering: Filter jobs by type, location, and tags to find the most relevant opportunities.
*Tag Management: Add and remove tags to categorize jobs effectively.
*Responsive Design: A user-friendly interface optimized for both light and dark modes.
*Job Previews: Fetch and display job link previews using external APIs.
*Backend API: A robust API for managing job data, including validation and database integration.

Tech Stack
*Frontend: React with Next.js
*Styling: Tailwind CSS
*Backend: Node.js with Next.js API routes
*Database: MongoDB
*Libraries:
*axios for HTTP requests
*mongoose for database modeling
*sonner for toast notifications
*lucide-react for icons

Clone the repository:
*git clone https://github.com/your-username/jobshare.git
*cd jobshare

Install dependencies:
*npm install

Set up environment variables: Create a .env.local file in the root directory and add the following:
*MONGODB_URI=<your-mongodb-connection-string>
*Start the development server:
*npm run dev
*Access the application at http://localhost:3000.

Example Job Posting
{
  "title": "Frontend Developer",
  "company": "Tech Corp",
  "location": "Remote",
  "link": "https://example.com/job",
  "description": "Looking for a skilled frontend developer.",
  "type": "Full Time",
  "tags": ["React", "JavaScript"]
}
