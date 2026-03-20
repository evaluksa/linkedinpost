# Unzip
unzip linkedinpost.zip
cd linkedinpost

# Connect to your repo and push
git init
git remote add origin https://github.com/evaluksa/linkedinpost.git
git add .
git commit -m "Initial commit: MyFaceGuard LinkedIn Content Agent"
git branch -M main
git push -u origin main
```

**What's in the zip:**
```
linkedinpost/
├── public/index.html      ← The full agent UI (ready to run)
├── src/agent.js           ← Core logic extracted as a JS module
├── docs/architecture.md   ← Full Miro architecture documented
├── .env.example           ← API key template
├── .gitignore
└── README.md
