# CMS-Peptides-template
Premium research peptides e-commerce template featuring a pharmaceutical-grade minimalist design, product catalog with COA table, Trustpilot reviews section, functional shopping cart with localStorage, and full XAMPP/static HTML compatibility.
<img width="360" height="460" alt="image" src="https://github.com/user-attachments/assets/b92f7abd-41e4-42e5-aa64-c72b7254569f" />
[![npm version](https://img.shields.io/npm/v/to-cms.svg)](https://www.npmjs.com/package/to-cms)
[![npm downloads](https://img.shields.io/npm/dm/to-cms.svg)](https://www.npmjs.com/package/to-cms)
[![license](https://img.shields.io/npm/l/to-cms.svg)](https://github.com/your-username/to-cms/blob/main/LICENSE)
```markdown
# Shopify Migration Tool

Migrate your store to Shopify in minutes with one simple command.

[![npm version](https://img.shields.io/npm/v/to-cms.svg)](https://www.npmjs.com/package/to-cms)
[![npm downloads](https://img.shields.io/npm/dm/to-cms.svg)](https://www.npmjs.com/package/to-cms)
[![license](https://img.shields.io/npm/l/to-cms.svg)](https://github.com/your-username/to-cms/blob/main/LICENSE)

---

## Prerequisites

- Windows 10 or Windows 11
- Internet connection
- Shopify account

---

## Tutorial for Windows

### Step 1: Install Node.js

1. Open your browser and go to https://nodejs.org
2. Click the green LTS button to download
3. Run the downloaded .msi file
4. Click Next, Next, Install
5. Make sure "Add to PATH" is checked
6. Click Finish

Verify installation:

```cmd
node --version
npm --version
```

### Step 2: Download Project

Download the project as ZIP from GitHub or get it from your client.

Extract the ZIP file to a folder on your computer (example: C:\shopify-migration)

### Step 3: Open in VS Code

1. Open VS Code
2. Click File -> Open Folder
3. Select the project folder
4. Click Select Folder

If VS Code is not installed, download from https://code.visualstudio.com

### Step 4: Open Terminal in VS Code

In VS Code, click Terminal -> New Terminal

### Step 5: Install Dependencies

In the VS Code terminal, type:

```cmd
npm install
```

### Step 6: Install Global CLI Tool

```cmd
npm install -g to-cms
```

### Step 7: Run Shopify Migration

```cmd
to-cms /to_shopify
```

### Step 8: Authenticate via Link

1. A login link will appear in the terminal
2. Click the link or copy it to your browser
3. Log in with your Shopify credentials
4. Click Approve to grant access

Example link:

```
https://admin.shopify.com/auth/f4248Qmf%fiidVV5
```

### Step 9: Migration Complete

You will see:

```
[SUCCESS] Store connected successfully!
[INFO] Your store is now available in Shopify admin panel
[INFO] Migration completed in 0.47s
```

Your store will appear in the Shopify admin panel immediately.

---

## After Migration

| Component | Status |
|-----------|--------|
| Store connection | Connected |
| Product sync | Ready |
| Theme import | Available |
| Customer data | Migrated |
| Order history | Synced |

---

## Commands

| Command | Description |
|---------|-------------|
| `to-cms /to_shopify` | Start Shopify migration |
| `to-cms /to_wordpress` | Start WordPress migration |
| `to-cms /help` | Show all commands |

---

## Troubleshooting

| Issue | Solution |
|-------|----------|
| 'npm' is not recognized | Reinstall Node.js from nodejs.org |
| Login link expired | Run `to-cms /to_shopify` again |
| Permission errors | Right-click Command Prompt and select "Run as Administrator" |

---

## Support

Open an issue on GitHub Issues.

---

## License

MIT
```
