# BotFanatics Menu

A static HTML page for BotFanatics Service Agreement.

## Deployment to Railway via GitHub

### Step 1: Push to GitHub

1. **Initialize Git** (if not already done):
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   ```

2. **Create a GitHub Repository**:
   - Go to [GitHub](https://github.com/new)
   - Create a new repository (e.g., `botfanatics-menu`)
   - **Don't** initialize with README, .gitignore, or license (we already have these)

3. **Push to GitHub**:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/botfanatics-menu.git
   git branch -M main
   git push -u origin main
   ```
   Replace `YOUR_USERNAME` with your GitHub username.

### Step 2: Deploy to Railway

1. **Sign up/Login to Railway**:
   - Go to [Railway](https://railway.app)
   - Sign up or log in with your GitHub account

2. **Create New Project**:
   - Click "New Project"
   - Select "Deploy from GitHub repo"
   - Choose your `botfanatics-menu` repository

3. **Configure Deployment**:
   - Railway will automatically detect the Node.js project
   - It will install dependencies and run `npm start`
   - The app will be available at a Railway-provided URL

4. **Optional: Custom Domain**:
   - In Railway dashboard, go to Settings
   - Add a custom domain if desired

## Local Development

To run locally:

```bash
npm install
npm start
```

Then visit `http://localhost:3000`

