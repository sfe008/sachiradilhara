# Deployment Guide: sachiradilhara.me

This guide explains how to deploy your personal portfolio website to Namecheap using cPanel.

## Step 1: Prepare the Files
1. Open the project directory (`E:\#University-Doc\Practicle\Antigravity\portfolio-sachiradilhara`).
2. Select all the files and folders inside it (`index.html`, `css` folder, `js` folder, `assets` folder, etc.).
3. Right-click and compress them into a ZIP file (e.g., `portfolio.zip`). On Windows, right-click -> "Compress to ZIP file".

## Step 2: Log into Namecheap cPanel
1. Log in to your Namecheap account.
2. Go to your **Domain List** or **Hosting** dashboard and access **cPanel**.

## Step 3: Upload to File Manager
1. In cPanel, find and click on **File Manager** (usually under the "Files" section).
2. On the left sidebar, click on `public_html`. (If you have a separate folder for `sachiradilhara.me` because of an addon domain, click that folder instead).
3. Make sure the folder is empty (you can safely delete any default `index.php`, `default.html` or Namecheap parking pages inside `public_html`).
4. Click the **Upload** button at the top menu.
5. Select the `portfolio.zip` file you created in Step 1.
6. Once the upload progress bar reaches 100% and turns green, click the link to go back to `public_html`.

## Step 4: Extract and Test
1. Right-click the `portfolio.zip` file in the File Manager and select **Extract**.
2. Make sure it extracts directly into the `public_html` folder.
3. Once extracted, you should see your `index.html` file and folders sitting directly inside `public_html`.
4. You can now delete the `portfolio.zip` file from the server to save space.
5. Open a new browser tab and navigate to `https://sachiradilhara.me`. You should see your new modern portfolio!

## Tips for Future Updates
- To update the site later, you can simply edit the files on your computer and re-upload the specific file that changed (like `index.html` or `css/style.css`) directly through the cPanel File Manager without needing to zip everything again.
- If you don't see your changes immediately after updating, try clearing your browser cache or opening the site in an Incognito/Private window.
