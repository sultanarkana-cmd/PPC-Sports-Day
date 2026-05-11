# PPC Firebase Live Scoreboard

Upload all files to GitHub root:
- index.html
- admin.html
- initial-data.json

Netlify:
- Build command: empty
- Publish directory: .

Open:
- Public: https://your-site.netlify.app
- Admin: https://your-site.netlify.app/admin.html

In Firebase Realtime Database rules for testing:
{
  "rules": {
    ".read": true,
    ".write": true
  }
}

Use admin.html > Reset Demo Data once, then Save to Firebase after edits.
