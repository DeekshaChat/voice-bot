# Voice bot

## 1. Edit two things
- `api/chat.js`: change `MY_NAME`, and add any real details (company names, a project, a short story) into the "ABOUT ME" section.
- `index.html`: nothing required.

## 2. Get a free Groq key
https://console.groq.com -> API Keys -> Create. Copy it.

## 3. Push to GitHub
Create a new repo and upload these files, keeping this layout:
```
index.html
api/chat.js
```

## 4. Deploy on Vercel
1. vercel.com -> Add New -> Project -> import the repo.
2. Framework preset: **Other**. Leave all build settings empty.
3. Before clicking Deploy, open **Environment Variables**, add:
   `GROQ_API_KEY` = your key.
4. Click Deploy. Your public URL is ready.

If you added the variable after deploying: Settings -> Environment Variables, then Deployments -> Redeploy.

## 5. Test
Open the URL on desktop Chrome and on your phone. Try all five sample questions, a follow-up question, and the typing box.
