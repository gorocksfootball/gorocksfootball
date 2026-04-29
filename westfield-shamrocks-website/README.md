# Westfield Shamrocks Football Website

## Files in This Folder
- `index.html` — Homepage
- `coaches.html` — Youth Coaches Hub
- `alumni.html` — Alumni Community / Directory Signup
- `images/` — All photo assets

---

## HOW TO GET THIS LIVE (GitHub Pages)

### Step 1: Create Accounts
1. Go to **gmail.com** → create `westfieldshamrocksfb@gmail.com` (or similar)
2. Go to **github.com** → sign up using that Gmail
3. Go to **namecheap.com** → sign up using that Gmail

### Step 2: Buy Your Domain (Namecheap ~$12/yr)
- Search for `westfieldshamrocksfootball.com` or `westfieldrocksfootball.com`
- Add to cart → checkout

### Step 3: Create GitHub Repository
1. Click the green **New** button on GitHub
2. Name it exactly: `westfieldshamrocksfb.github.io`
3. Set to **Public**
4. Click **Create repository**

### Step 4: Upload Your Files
1. In the new repo, click **uploading an existing file**
2. Drag in ALL files: `index.html`, `coaches.html`, `alumni.html`
3. Also drag the entire `images` folder
4. Click **Commit changes**
5. Your site is now live at: `https://westfieldshamrocksfb.github.io`

### Step 5: Connect Your Custom Domain (Optional but recommended)
In Namecheap DNS settings, add these records:
- Type: `A` | Host: `@` | Value: `185.199.108.153`
- Type: `A` | Host: `@` | Value: `185.199.109.153`
- Type: `A` | Host: `@` | Value: `185.199.110.153`
- Type: `A` | Host: `@` | Value: `185.199.111.153`
- Type: `CNAME` | Host: `www` | Value: `westfieldshamrocksfb.github.io`

Then in GitHub repo → Settings → Pages → Custom domain → enter your domain.

---

## HOW TO UPDATE THE SITE

### Adding a Playbook PDF
1. Go to your GitHub repo
2. Click **Add file** → **Upload files**
3. Upload your PDF (e.g., `offense-playbook.pdf`)
4. Then edit `coaches.html` and replace `href="#"` on that card with `href="offense-playbook.pdf"`

### Linking Your Google Form (Alumni Page)
1. Create your Google Form in Google Drive
2. Click **Send** → link icon → copy the link
3. Edit `alumni.html` and replace `https://forms.google.com` with your real link

### Updating the Email Address
Search for `westfieldshamrocksfb@gmail.com` in all 3 HTML files and replace with your actual email.

---

## COST SUMMARY
| Item | Cost |
|------|------|
| GitHub Pages hosting | FREE |
| Domain (Namecheap) | ~$12/year |
| Gmail | FREE |
| Google Forms | FREE |
| **Total** | **~$12/year** |
