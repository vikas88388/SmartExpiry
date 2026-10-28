# SmartExpiry

**AI-Based Inventory, Expiry and Dead-Stock Loss Prevention System for Retail Businesses**

SmartExpiry is a student project for pharmacies, supermarkets, grocery stores, cosmetic shops and other retailers. It tracks product batches and expiry dates, identifies near-expiry stock, detects potential dead stock, and recommends preventive actions such as discounts, promotions or stock transfer.

## Features
- Dashboard with product, stock and expiry-risk counts
- Product and batch registration
- Expiry monitor with High / Medium / Low risk
- Action recommendations for risky inventory
- FEFO-style sale selection (earliest-expiry stock first)
- Browser localStorage demo — no server required
- MySQL database schema included in `sql/smartexpiry.sql`

## Run locally
Open `index.html` in a browser and click **Load Demo Data**.

## Deploy on GitHub Pages
1. Create a new GitHub repository named `SmartExpiry`.
2. Upload all files and folders from this project.
3. Commit the files to the `main` branch.
4. Open repository **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Select `main` and `/ (root)`, then save.

> The GitHub Pages demo uses localStorage. MySQL cannot run directly on GitHub Pages. The SQL file is included for DBMS implementation and can later be connected through a backend.

## Technologies
HTML, CSS, JavaScript, LocalStorage, MySQL

## Author
VIKAS J — Computer Science and Engineering
