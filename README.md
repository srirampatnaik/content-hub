📚 Knowledge Hub
A lightweight content-focused knowledge hub built with Next.js, where users can:

✍️ Submit new content requests (e.g., “Write a guide on Next.js SEO”)

📰 Browse requested content in a live-updating feed

⚡ Receive real-time updates via Server-Sent Events (SSE)

📖 Explore richly generated guide pages (Markdown/MDX via Contentlayer)

🎨 Enjoy smooth animations and interactive UI

Deployed on Vercel 🚀.

🔗 Live Demo & Repo
Live App: https://knowledge-hub.vercel.app

GitHub Repo: https://github.com/your-username/knowledge-hub

⚙️ Tech Stack
Framework: Next.js (App Router)

Database: SQLite (Prisma ORM)

Data Fetching: TanStack Query + Axios

Forms & Validation: React Hook Form + Zod

State Management: Redux Toolkit

Styling: Tailwind CSS

Animations: Framer Motion

Content: Contentlayer (Markdown/MDX for guides)

🚀 Features
🏠 Home Page – Content Feed
Displays all requested content (GET /api/content)

Animations for new entries (Framer Motion)

Real-time updates via SSE (/api/content/stream)

📝 Submit Content Request
Form with title, description, category

Built using React Hook Form + Zod validation

Posts to API (POST /api/content)

Success state with smooth animation

📖 Guide Pages
Published requests → Markdown/MDX guides

Automatically available at /guides/[slug]

🌐 Global User State
Theme (dark/light)

Reading mode (compact/detailed)

Username (stored via Redux Toolkit)

🛠️ Local Development
1. Clone the repo
git clone https://github.com/your-username/knowledge-hub.git
cd knowledge-hub
2. Install dependencies
npm install
3. Setup environment
Create a .env file in the root:

DATABASE_URL="file:./dev.db"
4. Setup Prisma & SQLite
npx prisma migrate dev --name init
npx prisma generate
5. Run the app
npm run dev
App will be running at: http://localhost:3000 🎉

📦 Deployment
Hosted on Vercel with GitHub integration

Auto-deploys on git push to main

📸 Screenshots (Optional)
(Add images of your app UI once deployed)

👨‍💻 Author
Built by Sriram ✨
