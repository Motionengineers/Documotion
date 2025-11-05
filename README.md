[README.md](https://github.com/user-attachments/files/23357479/README.md)
# Documotion - Starter Scaffold
Minimal scaffold for Documotion (demo-ready without external APIs).

## What is included
- package.json with basic scripts
- simple Next.js placeholder (pages/index.js)
- .env.example
- prisma/schema.prisma
- vercel.json
- .gitignore

## How to use
1. Unzip and `cd documotion_scaffold`
2. `npm install`
3. Set values in `.env` (see `.env.example`)
4. `npm run dev` to run locally (http://localhost:3000)
5. Initialize git and push to your GitHub repo:
   ```
   git init
   git add .
   git commit -m "initial scaffold"
   git remote add origin https://github.com/Motionengineers/documotion.git
   git push -u origin main
   ```
6. Link repo to Vercel and deploy.
