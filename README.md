# Privacy Policy & Legal Portal for Mercanix (Hira App)

This repository provides the official, production-ready, and **Google Play Store Compliant** Privacy Policy, Terms of Service, and Account/Data Deletion website for **Mercanix (Hira App)** (Package ID: `com.mercanix.app`).

---

## 🚀 How to Host on GitHub Pages in Under 2 Minutes

You have two simple options to host this website on GitHub:

### Option 1: Host via your existing `hira-app` repository (Recommended - Fastest)

Because the files are already placed in `hira-app/docs/`:

1. **Commit and Push the `docs/` folder to GitHub:**
   ```bash
   cd /Users/xujin/Desktop/Projects/hira-app
   git add docs/
   git commit -m "Add Play Store Privacy Policy and Legal Portal"
   git push origin main
   ```

2. **Enable GitHub Pages on GitHub:**
   - Go to your repository on GitHub: `https://github.com/Syed-shan46/hira-app`
   - Click on **Settings** (top right tab)
   - In the left sidebar, click on **Pages** (under "Code and automation")
   - Under **Build and deployment** -> **Branch**:
     - Select branch: `main`
     - Select folder: `/docs`
     - Click **Save**

3. **Your Live Play Store URL will be:**
   ```
   https://syed-shan46.github.io/hira-app/
   ```
   *(GitHub usually takes 30-60 seconds to deploy the page after saving).*

---

### Option 2: Host as a Standalone Repository (`hira-privacy-policy`)

If you prefer having a dedicated, clean repository just for the legal website:

1. **Create a new repository on GitHub:**
   - Go to [GitHub New Repository](https://github.com/new)
   - Repository name: `hira-privacy-policy` (or `privacy-policy`)
   - Keep it **Public** (required for free GitHub Pages)
   - Do NOT initialize with README (already created locally)
   - Click **Create repository**

2. **Push the local folder:**
   ```bash
   cd /Users/xujin/Desktop/Projects/hira-privacy-policy
   git init
   git add .
   git commit -m "Initial commit of Mercanix Privacy Policy website"
   git branch -M main
   git remote add origin https://github.com/Syed-shan46/hira-privacy-policy.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - In GitHub repository Settings -> **Pages**
   - Source: **Deploy from a branch**
   - Branch: `main` / `/(root)`
   - Click **Save**

4. **Your Live Play Store URL will be:**
   ```
   https://syed-shan46.github.io/hira-privacy-policy/
   ```

---

## 📋 URLs for Google Play Console

When submitting or updating your app in the **Google Play Console**:

| Section in Play Console | Value / URL to Provide |
|-------------------------|------------------------|
| **Privacy Policy URL** | `https://syed-shan46.github.io/hira-app/` (or `https://syed-shan46.github.io/hira-privacy-policy/`) |
| **Account Deletion Web Link** | `https://syed-shan46.github.io/hira-app/deletion.html` |
| **Data Safety Section** | Disclosures for Phone Number (Firebase Auth), Order/Shipping Address, and Razorpay Payments are fully covered in Section 2 & 3. |

---

## ✨ Features Included in this Website

- **Google Play Store Policy Compliant**: Explicit disclosures for Firebase Phone OTP, Razorpay payment processing, device permissions, and security practices.
- **Account & Data Deletion Portal**: Google Play mandatory web portal with an interactive request assistant that drafts a pre-filled deletion email or WhatsApp message directly to support.
- **Terms of Service**: Complete B2B wholesale legal terms, Escrow Trade Assurance framework, and return/dispute guidelines.
- **Modern Responsive Design**: Clean typography (Inter font), dark/light mode toggle, table of contents scroll-spy, and real-time policy search bar.
- **Print / PDF Friendly**: Optimized print stylesheet for generating official PDF documentation.
