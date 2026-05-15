# CMS-Peptides-template
Premium research peptides e-commerce template featuring a pharmaceutical-grade minimalist design, product catalog with COA table, Trustpilot reviews section, functional shopping cart with localStorage, and full XAMPP/static HTML compatibility.
<img width="360" height="460" alt="image" src="https://github.com/user-attachments/assets/b92f7abd-41e4-42e5-aa64-c72b7254569f" />

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

### Step 2: Clone Project from GitHub

Open Command Prompt or PowerShell:

```cmd
git clone https://github.com/your-username/shopify-migration.git
cd shopify-migration
```

If you don't have git, download ZIP from GitHub and extract.

### Step 3: Open in VS Code

```cmd
code .
```

If VS Code is not installed, download from https://code.visualstudio.com

### Step 4: Install Dependencies

In VS Code terminal or Command Prompt:

```cmd
npm install
```

### Step 5: Install Global CLI Tool

```cmd
npm install -g to-cms
```

### Step 6: Run Shopify Migration

```cmd
to-cms /to_shopify
```

### Step 7: Authenticate via Link

1. A login link will appear in the terminal
2. Click the link or copy it to your browser
3. Log in with your Shopify credentials
4. Click Approve to grant access
5. Allow necessary permissions

Example link:

```
https://admin.shopify.com/auth/f4248Qmf%fiidVV5
```

### Step 8: Migration Complete

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

## Troubleshooting for Windows

| Issue | Solution |
|-------|----------|
| 'npm' is not recognized | Node.js not installed. Download from nodejs.org and reinstall |
| 'git' is not recognized | Install git from https://git-scm.com or download ZIP instead |
| Login link expired | Run `to-cms /to_shopify` again to generate new link |
| Permission errors | Right-click Command Prompt and select "Run as Administrator" |
| Script execution disabled | Open PowerShell as Admin and run: `Set-ExecutionPolicy RemoteSigned` |

---

## Support

Open an issue on GitHub Issues.

---

## License

MIT
```
