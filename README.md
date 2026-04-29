# Dr. Mohammad Rashidul Hashan — Personal Academic Website

## 🚀 Deploy to Netlify (3 steps, free)

### Step 1 — Create Formspree form (for the contact form)
1. Go to https://formspree.io and sign up (free)
2. Click "New Form" → name it "Collaboration enquiries"
3. Copy your **Form ID** (looks like `xrgjaklp`)
4. Open `index.html` and find this line:
   ```
   action="https://formspree.io/f/YOUR_FORM_ID"
   ```
   Replace `YOUR_FORM_ID` with your actual Formspree form ID

### Step 2 — Deploy to Netlify (drag & drop — no coding needed)
1. Go to https://app.netlify.com
2. Sign up / log in (free)
3. On the dashboard, drag and drop this entire folder onto the page
4. Netlify will deploy instantly and give you a URL like `random-name.netlify.app`

### Step 3 — Set your custom URL
1. In Netlify, go to **Site settings → Domain management → Site name**
2. Click **Edit site name**
3. Set it to: **`infect-epi-hashan`** → gives you `infect-epi-hashan.netlify.app`
   
   Other great options:
   - `hashan-epi` → hashan-epi.netlify.app
   - `mrhashan-research` → mrhashan-research.netlify.app
   - `epi-evidence-hashan` → epi-evidence-hashan.netlify.app
   - `hashan-infectiousepi` → hashan-infectiousepi.netlify.app

### Update the site
Drag and drop the folder again on Netlify — it redeploys automatically.

## 🔧 Customising the site
- **Add publications**: Find the "pub-list" section in index.html and copy/paste a `<div class="pc">` block
- **Update stats**: Search for `stat-num` and change the numbers
- **Add blog posts**: Copy a `blog-card` block in the blog section
- **Update contact form**: Replace `YOUR_FORM_ID` with your Formspree ID

## 📬 Formspree free plan
- 50 submissions/month free
- Email notifications to you on every submission
- Spam filtering included

