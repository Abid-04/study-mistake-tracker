# Study Mistake Tracker

A browser-based study tool for recording mistakes across subjects and deciding what to revise next.

## Features
- Add and edit mistakes with a subject, topic and correct explanation.
- Mark entries as Needs practice or Understood.
- Filter by subject and progress.
- See topics ranked by unresolved mistakes.
- Quiz yourself with explanations hidden until you reveal them.
- Review up to five unresolved mistakes daily, prioritizing older reviews.

## Run
Open index.html in a modern browser, or use VS Code Live Server. No installation, backend, API key or build step is required.

## Storage
Entries are saved in localStorage for the current browser and website address. They do not sync across devices or move automatically between the ChatGPT Sites version, localhost and Netlify. Clearing browser data removes saved entries. The app currently has no export or backup feature.

## Publish
Upload index.html to the root of your GitHub repository. To deploy manually on Netlify, upload a folder containing index.html. No build command is required.

## Technology
HTML, CSS and JavaScript. Quiz results are self-assessed; this app does not use an AI model to grade answers.

## Verification
JavaScript syntax and daily queue logic were checked. Full browser interaction testing remains to be done.
