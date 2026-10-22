# StudyHub — Style 1

A responsive, light-theme educational quiz dashboard.

## Included
- Student dashboard with subject cards, summary stats, and recent activity
- Sample Anatomy & Physiology, Microbiology, and Biochemistry quizzes
- MCQ flow with previous/next navigation and automatic score calculation
- Progress and local test history
- Demo admin panel to create/delete quizzes and import/export JSON
- Responsive layout for mobile, tablet, and desktop

## Run locally
Open `index.html` in a modern browser.

## Deploy on Vercel
1. Create a GitHub repository and upload `index.html` and `vercel.json`.
2. In Vercel, select **Add New → Project**, import the repository, and deploy.
3. No build command is required for this static starter.

## Important limitation
This version stores quizzes and progress in the current browser using `localStorage`. It does **not** synchronize progress between users or devices. The admin panel is a demo, not secure authentication. For a real public student platform, connect a database and authenticated backend (for example Supabase) and enforce admin permissions server-side.
