# reNEWS Story Generator

A web application that converts press releases into professional news stories following reNEWS editorial standards.

## 🚀 Quick Deploy to Vercel (FREE - Recommended)

### Prerequisites
- A GitHub account
- An Anthropic API key (get one at https://console.anthropic.com/settings/keys)

### Step-by-Step Deployment Instructions

#### 1. Upload to GitHub
1. Go to https://github.com/new
2. Create a new repository named `renews-story-generator`
3. Make it **Public** (required for free Vercel hosting)
4. Click "Create repository"
5. Upload all the files from this folder to your new repository:
   - Click "uploading an existing file"
   - Drag and drop: `package.json`, `server.js`, and the entire `public` folder
   - Commit the files

#### 2. Deploy to Vercel
1. Go to https://vercel.com/signup
2. Sign up with your GitHub account (it's free)
3. Click "Add New Project"
4. Import your `renews-story-generator` repository
5. Vercel will auto-detect it as a Node.js project
6. Click "Deploy"
7. Wait 1-2 minutes for deployment to complete
8. You'll get a URL like: `https://renews-story-generator.vercel.app`

#### 3. Share with Your Team
1. Share the Vercel URL with your team
2. Each team member needs their own Anthropic API key
3. They paste their API key, click "Save", and start generating stories!

---

## 💻 Alternative: Deploy to Render (Also FREE)

### Step-by-Step for Render

1. Go to https://render.com/
2. Sign up with GitHub
3. Click "New +" → "Web Service"
4. Connect your GitHub repository
5. Configure:
   - **Name**: renews-story-generator
   - **Environment**: Node
   - **Build Command**: `npm install`
   - **Start Command**: `npm start`
6. Click "Create Web Service"
7. Wait for deployment
8. You'll get a URL like: `https://renews-story-generator.onrender.com`

**Note**: Render's free tier spins down after inactivity, so first load might be slow (30 seconds). Vercel is faster.

---

## 🏃 Run Locally (For Testing)

If you want to test it on your computer first:

```bash
# Install dependencies
npm install

# Start the server
npm start

# Open browser to:
http://localhost:3000
```

---

## 📁 File Structure

```
renews-story-generator/
├── package.json          # Node.js dependencies
├── server.js             # Backend API server
├── public/
│   └── index.html        # Frontend web interface
└── README.md             # This file
```

---

## 🔧 How It Works

1. **Frontend** (index.html): Beautiful web interface where users input press releases
2. **Backend** (server.js): Node.js server that proxies requests to Anthropic API
3. **API**: Uses Claude Sonnet 4 to transform press releases using reNEWS editorial guidelines

---

## 💰 Costs

- **Hosting**: $0 (Free tier on Vercel or Render)
- **API Usage**: ~$0.05-0.10 per story (Claude Sonnet 4 pricing)
- **Estimated**: $5-10/month for 100 stories

---

## 🔒 Security

- API keys are stored in browser localStorage (never sent to the server or stored server-side)
- Each user uses their own API key
- All communication uses HTTPS

---

## 🆘 Troubleshooting

**"Error generating story"**
- Check your API key is correct (starts with sk-ant-)
- Verify you have API credits in your Anthropic account
- Make sure you clicked "Save" after entering your API key

**Deployment failed on Vercel**
- Make sure your repository is Public
- Check all files were uploaded correctly
- Try re-deploying

**Need help?**
- Check Vercel logs: Dashboard → Your Project → Deployments → Click latest deployment → View logs
- Contact your IT team for assistance with deployment

---

## 📝 License

MIT License - Feel free to use and modify for your organization.
