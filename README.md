# DeadlineGuard

A responsive student assignment planner built with HTML, CSS, and vanilla JavaScript. No backend or paid hosting required.

## Features
- Add, edit, delete, and complete assignments
- Assign a class, due date, priority, and notes
- Automatically identify overdue and due-soon tasks
- Search, filter, and sort assignments
- Monthly calendar and completion dashboard
- Dark/light mode
- Saves assignments using browser localStorage

## Publish on GitHub Pages
1. Create a new **public** repository named `DeadlineGuard` on GitHub.
2. Upload `index.html`, `style.css`, and `script.js` to the **root** of the repository (not inside an extra folder).
3. Open repository **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select **main** and **/(root)**, then click **Save**.
6. Your site will be available at `https://YOUR-USERNAME.github.io/DeadlineGuard/` after deployment.

## Run locally
Open `index.html` in your browser, or use VS Code Live Server.

## Important limitations
- Data is stored **only in the browser on that device**; it does not sync across devices or accounts.
- Clearing browser site data or using private browsing can remove saved tasks.
- "Due soon" is an on-screen indicator, **not** a push notification. The browser does not send automatic reminders while the site is closed.
- This prototype does not use an AI model or server.

## User testing for the class project
Ask at least three students to: (1) add an assignment, (2) find the next deadline, (3) mark a task completed, and (4) use the calendar. Record whether each task was completed, the time taken, and feedback. Use real findings to plan V2.
