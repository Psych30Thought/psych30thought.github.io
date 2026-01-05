# Psych30Thought — Basic Psychology Quiz (GitHub Pages)

This is a minimal static site for a basic psychology quiz. It's built with plain HTML/CSS/JavaScript and designed to run on GitHub Pages (no server required).

Features
- Multiple-choice quiz
- Score and simple interpretation
- Attempts saved in browser localStorage
- Download stored attempts as JSON
- Consent checkbox and privacy note (no external data collection)

How to deploy
1. Add the files (index.html, styles.css, script.js, README.md) to the root of the repository `psych30thought.github.io`.
2. Push to the `main` branch (or the repository's default branch). GitHub Pages will serve the site at:
   `https://<your-github-username>.github.io/psych30thought.github.io/`
3. If you prefer a `gh-pages` branch, create it and enable GitHub Pages in repository settings.

Customization
- To change questions, edit `script.js` and modify the `questions` array.
- To add new test pages or multiple quizzes, create additional HTML pages or migrate the app to a framework (React/Vue) for routing and admin UI.

Privacy & ethics notes
- This is an educational, non-clinical quiz. Do not use for diagnosis.
- The app currently stores attempts only in the user's browser. If you add server-side storage, inform users and get explicit consent, and comply with relevant data protection laws.

Next ideas
- Add more quizzes (personality, cognition, developmental).
- Convert to React + Netlify Functions or Firebase to store attempts centrally (requires privacy protections).
- Add a small admin UI to update questions from a JSON file or CMS.

If you want, I can:
- Push these files to a branch in your repository and open a PR.
- Convert this to a React app and add a simple admin editor.
- Add analytics (privacy-friendly) or server storage with an opt-in.

Tell me which option you prefer and whether I should push these files to your repo now.
