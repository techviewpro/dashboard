Build a fully functional, frontend-only AI Dashboard web application for TechViewPro.com using React, TypeScript, Tailwind CSS, and shadcn/ui.
The app must start directly with a Login Page (no landing page), and after login, load a modern, glassmorphic, responsive dashboard with a sticky header and a collapsible sidebar containing 10 dynamic sections + Settings — all working client-side with mock data and localStorage (no backend or database).

🎨 THEME & DESIGN STYLE
Theme Name: Futuristic Teal & Orange
Primary Color: #009688 (Teal)
Accent Color: #FF7A00 (Orange)
Background: #0D1117
Text Light: #EAEAEA
Text Muted: #A0AEC0

Fonts:
Headings: Red Hat Display
Body: Inter
Style Features:

Glassmorphism panels with backdrop-blur-md and transparent backgrounds
Soft teal/orange glows on hover
Gradient dividers and smooth transitions (Framer Motion)
Responsive for all devices (desktop, tablet, mobile)

🧠 TECH REQUIREMENTS

React + TypeScript
Tailwind CSS + shadcn/ui
Framer Motion (animations)
Recharts / Chart.js (data visualization)
jsPDF and SheetJS (xlsx) (PDF/Excel downloads)
LocalStorage (auth and data persistence)
React Router DOM (section routing)
🔐 AUTHENTICATION (Mocked, Frontend-Only)

Login Page:
Email + Password input
Google Sign-In button (mocked)
“Forgot password?” link (non-functional UI only)
“Signup” link to create a new local user
On login → redirect to /dashboard

Signup Page:
Name, Email, Password fields
Google signup button (mocked)
After signup → save mock user in LocalStorage → redirect to dashboard
Session Handling:
Auth stored in LocalStorage (user: { name, email, avatar })
Logout clears LocalStorage
Protect routes behind mock auth check

🧭 DASHBOARD LAYOUT

Sticky Header:
Search bar
Notification bell (mocked)
Profile button (avatar → dropdown showing Name, Email, and Logout)

Collapsible Sidebar:
Futuristic icons + glowing labels
On hover / expand transitions
Active section highlighting
Links to 10 sections + Settings

🧩 DASHBOARD SECTIONS (All Fully Functional, Frontend-Only)
1. Document Analysis (AI Studies Summarization)
Upload PDF/DOC/TXT (via FileReader)
Generate mock summary, keywords, and sentiment
Display results in a glass panel
“Download Summary” → exports TXT/PDF via jsPDF

2. Data Input (Business Insights)
Upload CSV → parse via FileReader
Display in responsive data table
Simple transformation options (uppercase headers, filter blanks)
“Export Clean Data” → download CSV/XLSX

3. Live Dashboard (Business Insights)
KPI cards (uptime, requests, risk, users)
Real-time chart updates (mock data with setInterval)
Filter by date range
Progress rings for system status

4. Course Builder (Interactive Learning)
Add/edit course modules & lessons
Auto-generate quiz questions (mock AI text)
“Preview” and “Download Course” as PDF

5. Story Elements (Visual Storytelling)
Generate story structure (characters, setting, conflict)
Editable cards with drag-and-drop reordering
Export story outline as JSON

6. Story Preview
Display formatted story text with highlighted keywords
“Convert to Slides” preview (animated panel view)
Download final story as PDF

7. AI Intelligence Lab
Text input for ad-hoc insights
Generate mock analysis reports (charts + insights)
“Download Insights” → PDF/CSV export

8. Visual & Audio Insights (Media Analyzer)
Upload images → detect mock labels/tags
Upload audio → display mock transcript + waveform
“Download Analysis Report” as PDF

9. Research Copilot (AI Chat Assistant)
Chat interface (mock AI responses)
Dropdown for context mode (Document / Story / Policy / Learning)
“Summarize Chat” & “Export Chat” (TXT/PDF download)

10. Audit Logs & Reports
Display mock user activity log (uploads, downloads, analysis)
Filter by type/date
“Generate Report” → download PDF/CSV

⚙️ Settings

Edit profile (name, email, avatar)
Theme toggle (Light/Dark mode — persists via LocalStorage)
Notification & preference toggles
Reset data (clear LocalStorage)

⚡ FUNCTIONAL BEHAVIOR REQUIREMENTS

All uploads handled client-side using FileReader()
Exports created client-side via jsPDF or SheetJS
Charts and metrics randomly updated every few seconds
Profile dropdown dynamically shows logged-in user info
Smooth transitions when switching sections
Persist auth, preferences, and uploads using LocalStorage
All pages are responsive and have consistent modern UI

✅ FINAL OUTPUT EXPECTATION

Generate a single-page React + TypeScript + Tailwind + shadcn project that:
Starts with a Login Page
Redirects authenticated users to a multi-section dashboard
Implements mock AI functions, charts, uploads, and file downloads
Uses the Futuristic Teal & Orange theme with glassmorphism, soft glows, and highlighted orange keywords
All interactions work client-side only
Includes smooth Framer Motion animations for transitions and hover effects
Layout is fully responsive

