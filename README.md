# Hughes Strategic Group — Website

## File Structure

```
hsg-site/
├── index.html              ← Home page
├── capabilities.html       ← Capability statement page
├── capability-statement.pdf ← Add your PDF here when ready
├── css/
│   └── style.css           ← Shared styles
└── README.md
```

---

## How to Deploy (GitHub + Netlify)

### Step 1 — Create a GitHub Repository

1. Go to [github.com](https://github.com) and sign in (or create a free account)
2. Click the **+** icon → **New repository**
3. Name it `hsg-site` (or anything you like)
4. Set it to **Public** or **Private** — either works with Netlify free tier
5. Click **Create repository**

### Step 2 — Upload Files to GitHub

**Option A — Drag & Drop (easiest):**
1. Open your new repo on GitHub
2. Click **Add file → Upload files**
3. Drag the entire `hsg-site` folder contents in
4. Click **Commit changes**

**Option B — GitHub Desktop (recommended for ongoing updates):**
1. Download [GitHub Desktop](https://desktop.github.com)
2. Clone your repo locally
3. Copy these files into the cloned folder
4. Commit and push

### Step 3 — Connect to Netlify

1. Go to [netlify.com](https://netlify.com) and sign up free
2. Click **Add new site → Import an existing project**
3. Choose **GitHub** and authorize Netlify
4. Select your `hsg-site` repo
5. Leave all settings as default — click **Deploy site**

Your site will be live in about 30 seconds at a URL like `random-name.netlify.app`

### Step 4 — Connect Your Custom Domain (hughesstrategic.net)

1. In Netlify, go to **Site settings → Domain management**
2. Click **Add custom domain** → enter `hughesstrategic.net`
3. Netlify will give you nameserver addresses (e.g. `dns1.p05.nsone.net`)
4. Log in to wherever you registered your domain (GoDaddy, Namecheap, etc.)
5. Find **DNS / Nameservers settings** and replace existing nameservers with Netlify's
6. Wait 10–30 minutes for DNS to propagate — your site will be live at hughesstrategic.net

---

## Contact Form

The contact form uses **Netlify Forms** (free, built-in). It works automatically once deployed to Netlify — no backend code needed. Form submissions appear in your Netlify dashboard under **Forms**.

To add email notifications for new submissions:
1. Netlify dashboard → **Forms → Form notifications**
2. Add your email address

---

## Adding Your Capability Statement PDF

1. Name your PDF file exactly: `capability-statement.pdf`
2. Place it in the root folder (same level as index.html)
3. The download button on capabilities.html will link to it automatically

---

## Making Updates

Once set up with GitHub + Netlify:
1. Edit any HTML/CSS file
2. Upload the changed file to GitHub (or push via GitHub Desktop)
3. Netlify auto-deploys in ~30 seconds — no manual steps needed
