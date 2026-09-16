Home Base — Family Dashboard
A single-page family dashboard: a shared weekly calendar and reminders, meal planning, weather, and per-person checklists (kids' routines + Mom's daily chores).
What's inside
Overview tab — week-at-a-glance events, childcare schedule, upcoming travel, meal plan, and weather for Albion, IL
Kid tabs (G, K, C) — color-coded daily routine checklists with emoji icons
H tab — daily chore reference table, a family focus verse, and a weekly check-in checklist grid
Reminder bubbles — color-coded by family member, shown at the top of every tab
A simple passcode screen (not real security — just a soft privacy speed bump)
Files
`index.html` — the entire site (HTML, CSS, and JavaScript are all self-contained in this one file)
Viewing it locally
Just open `index.html` in any web browser — no build step, no dependencies, no server required.
Hosting on GitHub Pages
Make sure the dashboard file is named `index.html` in the root of this repository (or in a `/docs` folder).
Go to Settings → Pages in this repository.
Under "Build and deployment," set the source to Deploy from a branch, choose the branch (usually `main`), and the folder (`/root` or `/docs`, matching where `index.html` lives).
Save. GitHub will publish the site at a URL like `https://yourusername.github.io/your-repo-name/`.
To update the dashboard later, just replace `index.html` with the new version and push the change — the same URL will automatically show the update within a minute or two.
Updating the dashboard
This file doesn't pull live data from anywhere — everything (events, meals, chores, checklists) is hand-edited directly in the HTML. To make changes, edit `index.html` and re-deploy (push to GitHub, or re-upload if using another host).
A note on privacy
This site has no real backend or authentication — the passcode screen is a basic deterrent, not a security feature, since the code is visible in the page's source. Avoid sharing the live link publicly, and consider adding a `robots.txt` file to discourage search engines from indexing the page if search-engine privacy matters to you.
