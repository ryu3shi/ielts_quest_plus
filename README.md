# ielts_quest_plus
A helper tool for IELTS learners
IELTS QUEST PLUS

Features:
- Beginner, Intermediate and Advanced question sets.
- Reading, Listening (browser text-to-speech), Vocabulary and Grammar.
- 10-question mixed mock quiz with a 2-minute timer.
- XP, best quiz accuracy, completed-round count and daily streaks saved in local browser storage.
- Writing Task 2 checklist and Speaking Part 1/2/3 prompts with read-aloud and a one-minute timer.

Run locally:
Open index.html in a modern browser. Most features work locally; install/offline caching requires hosting over HTTPS.

Install as Android app:
1. Upload index.html, manifest.json and sw.js to a static HTTPS host (e.g. GitHub Pages or Netlify).
2. Open the hosted URL in Chrome for Android.
3. Use the browser menu -> Install app / Add to Home screen.

Edit questions:
Open index.html and find the JavaScript object named `db`.
All progress is stored locally in the browser. Clearing site data resets it.
Writing feedback is an automated checklist, not an official IELTS band score.
