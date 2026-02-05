# 🚀 QUICK START GUIDE - reNEWS Story Generator

## What You're Getting

A complete web application that:
- ✅ Works on any device (desktop, tablet, mobile)
- ✅ No installation needed for your team
- ✅ Free to host
- ✅ Professional interface
- ✅ All reNEWS editorial rules built-in

---

## 5-Minute Setup (Recommended: Vercel)

### Step 1: Create GitHub Repository (2 minutes)

1. Go to **https://github.com/new**
2. Repository name: `renews-story-generator`
3. Make it **Public** ⚠️ (required for free hosting)
4. Click **"Create repository"**
5. Click **"uploading an existing file"**
6. Drag ALL files from the folder I gave you into the upload area:
   - `.gitignore`
   - `package.json`
   - `README.md`
   - `server.js`
   - `vercel.json`
   - `public` folder (with index.html inside)
7. Click **"Commit changes"**

### Step 2: Deploy to Vercel (3 minutes)

1. Go to **https://vercel.com/signup**
2. Click **"Continue with GitHub"**
3. Authorize Vercel to access your GitHub
4. Click **"Add New Project"** or **"Import Project"**
5. Find and select your `renews-story-generator` repository
6. Click **"Deploy"** (don't change any settings)
7. Wait 1-2 minutes ⏳
8. 🎉 Done! You'll get a URL like: `https://renews-story-generator-abc123.vercel.app`

### Step 3: Share with Team

1. Copy your Vercel URL
2. Send it to your team via email/Slack
3. Tell them to get their API key from: https://console.anthropic.com/settings/keys
4. They're ready to go!

---

## What Each Team Member Needs

1. The URL you deployed (e.g., `https://renews-story-generator-abc123.vercel.app`)
2. Their own Anthropic API key (from https://console.anthropic.com/settings/keys)
3. That's it!

---

## Alternative: Use Render Instead

If Vercel doesn't work, try Render:

1. Go to **https://render.com**
2. Sign up with GitHub
3. Click **"New +" → "Web Service"**
4. Connect your `renews-story-generator` repository
5. Settings:
   - Environment: **Node**
   - Build Command: `npm install`
   - Start Command: `npm start`
6. Click **"Create Web Service"**
7. Wait 3-5 minutes
8. Get your URL: `https://renews-story-generator.onrender.com`

**Note**: Render free tier "sleeps" after 15 minutes of inactivity. First load will be slow (30 seconds). After that, it's fast.

---

## Costs Breakdown

| Item | Cost |
|------|------|
| Hosting (Vercel/Render) | **$0** (Free forever) |
| API calls | **~$0.08 per story** |
| 100 stories/month | **~$8/month** |
| 500 stories/month | **~$40/month** |

You only pay for the Claude API usage, same as before.

---

## Troubleshooting

**"Repository must be public"**
→ Go to your GitHub repo → Settings → Scroll down → Change visibility to Public

**"Deploy failed"**
→ Check you uploaded ALL files including the `public` folder
→ Make sure `package.json` and `server.js` are in the root directory

**"Error generating story"**
→ User needs to get their API key from console.anthropic.com/settings/keys
→ Make sure they clicked "Save" after entering the key

**Deployment is taking forever**
→ First deployment takes 2-3 minutes, be patient
→ Refresh the Vercel dashboard

---

## Need Help?

1. Check the full README.md for detailed instructions
2. Contact your IT department
3. Vercel has great documentation: https://vercel.com/docs

---

## Next Steps

After deployment:
1. ✅ Test it yourself first with a sample press release
2. ✅ Share the URL with your team
3. ✅ Monitor usage in your Anthropic console: https://console.anthropic.com/settings/usage
4. ✅ Bookmark the Vercel dashboard to check deployment status

---

**Questions?** All the code is open source in your GitHub repository. Any developer can review or modify it.

Good luck! 🚀
