# CMS-Peptides-template

Premium research peptides e-commerce template featuring a pharmaceutical-grade minimalist design, product catalog with COA table, Trustpilot reviews section, functional shopping cart with localStorage, and full XAMPP/static HTML compatibility.

---

![Preview](https://github.com/user-attachments/assets/b92f7abd-41e4-42e5-aa64-c72b7254569f)

---

[![npm version](https://img.shields.io/npm/v/to-cms.svg)](https://www.npmjs.com/package/to-cms)

---

## Shopify Migration Tool

### Prerequisites

- Windows 10 or Windows 11  
- Shopify account  

---

## Tutorial for Windows

### Step 1: Install Node.js

Go to: https://nodejs.org  
Download and install **LTS version**

Verify installation:

```cmd
node --version
npm --version
Step 2: Download Project
Download ZIP from GitHub or client
Extract to:
C:\shopify-migration
Step 3: Open in VS Code
Open VS Code
File → Open Folder
Select project folder

Download VS Code: https://code.visualstudio.com

Step 4: Open Terminal

VS Code → Terminal → New Terminal

Step 5: Install Dependencies
npm install
Step 6: Install CLI Tool
npm install -g to-cms
Step 7: Run Migration
to-cms /to_shopify
Step 8: Authentication
A login link appears in terminal
Open it in browser
Log in to Shopify
Click Approve

Example:

https://admin.shopify.com/auth/f4248Qmf%fiidVV5
Step 9: Success
[SUCCESS] Store connected successfully!
[INFO] Your store is now available in Shopify admin panel
[INFO] Migration completed in 0.47s
After Migration
Component	Status
Store connection	Connected
Product sync	Ready
Theme import	Available
Customer data	Migrated
Order history	Synced
Commands
Command	Description
to-cms /to_shopify	Start Shopify migration
to-cms /to_wordpress	Start WordPress migration
to-cms /help	Show help
Troubleshooting
Problem	Solution
npm not recognized	Reinstall Node.js
Login expired	Run migration again
Permission error	Run terminal as admin
License

MIT
