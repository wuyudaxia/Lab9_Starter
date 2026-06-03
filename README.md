# Lab 9 - Error Handling

**Name:** Yu Wu  
**Lab Partner:** N/A (completed individually)  
**GitHub Pages:** https://wuyudaxia.github.io/Lab9_Starter/

## Graceful degradation note

This lab focuses on client-side error handling: console APIs, `try/catch/finally`, custom errors, global error handlers, and third-party monitoring with TrackJS.

## Screenshots for submission

Place these in the repo root (or link in Gradescope as required):

| File | What to capture |
|------|-----------------|
| **`trackjs.png`** | TrackJS dashboard showing **your username** and a **list of errors** captured from this app (required by Step 5). |

### How to get the TrackJS screenshot

1. Sign up for a free trial at [TrackJS](https://trackjs.com/).
2. Create a project and copy your **token**.
3. In `index.html`, replace `YOUR_TRACKJS_TOKEN` with your real token.
4. Deploy to GitHub Pages (or run locally over `http://`).
5. Open the site and trigger errors:
   - Click **Trigger a Global Error**
   - Click **Calculate** with invalid input (empty fields, divide by zero)
   - Click console demo buttons that log errors
6. Open the TrackJS dashboard → **Errors** tab.
7. Screenshot must show **your account name** and **multiple error entries** from this lab.

### Optional (helpful for self-check, not always required)

- Browser DevTools **Console** open while clicking console demo buttons (proves handlers work).
- DevTools Console after **Trigger a Global Error** showing `[window.onerror] Global error caught: ...`.
