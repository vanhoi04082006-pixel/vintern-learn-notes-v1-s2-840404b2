# V-Intern Notes integration acceptance

This repository contains an owned synthetic QA fixture. It is not a real student's work or assessment. No personal records or credentials belong here.

The foundation task covers a note model (id/title/content/tags), empty-title rejection, selected-note editing and keyboard access. The independent trusted suite checks browser behavior at a mobile viewport. AI review and instructor approval remain separate decisions.

Run with Node22 and the pinned React/Vite dependencies in package.json using npm install and npm run dev; npm run build creates a production build. The reviewed grading runtime supplies its own preinstalled dependencies and ignores project install scripts.

This foundation fixture keeps notes only in React memory. Reload loses data. Persistence, filtering, deletion and export belong to later tasks and must not be inferred from foundation tests. LocalStorage, when added, is browser-local and is not a secure database or backup.
