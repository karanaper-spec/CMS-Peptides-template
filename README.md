# CMS-Peptides-template
Premium research peptides e-commerce template featuring a pharmaceutical-grade minimalist design, product catalog with COA table, Trustpilot reviews section, functional shopping cart with localStorage, and full XAMPP/static HTML compatibility.
<img width="360" height="460" alt="image" src="https://github.com/user-attachments/assets/b92f7abd-41e4-42e5-aa64-c72b7254569f" />

```markdown
# Shopify Migration Tool

Migrate your store to Shopify in minutes with one simple command.

## Prerequisites

- Node.js (LTS version)
- npm package manager
- Shopify account

## Quick Start

### 1. Install Node.js

Download from https://nodejs.org (LTS version)

Verify installation:
```bash
node --version
npm --version
```

### 2. Clone Project

```bash
git clone https://github.com/your-username/shopify-migration.git
cd shopify-migration
```

### 3. Open in VS Code

```bash
code .
```

### 4. Install Dependencies

```bash
npm install
```

### 5. Install Global CLI

```bash
npm install -g to-cms
```

### 6. Run Migration

```bash
to-cms /to_shopify
```

### 7. Authenticate

Click the login link or copy it to your browser:

```
https://admin.shopify.com/auth/xxxxx
```

Then:
- Log in with Shopify credentials
- Approve access request
- Grant migration permissions

### 8. Migration Complete

```
[SUCCESS] Store connected successfully!
[INFO] Your store is now available in Shopify admin panel
[INFO] Migration completed in 0.47s
```

## After Migration

| Component | Status |
|-----------|--------|
| Store connection | Connected |
| Product sync | Ready |
| Theme import | Available |
| Customer data | Migrated |
| Order history | Synced |

## Commands

| Command | Description |
|---------|-------------|
| `to-cms /to_shopify` | Start Shopify migration |
| `to-cms /to_wordpress` | Start WordPress migration |
| `to-cms /help` | Show all commands |

## Troubleshooting

| Issue | Solution |
|-------|----------|
| npm is not recognized | Reinstall Node.js from nodejs.org |
| Login link expired | Run `to-cms /to_shopify` again |
| Permission errors | Run as Administrator (Windows) or sudo (Mac/Linux) |

## Support

Open an issue on GitHub Issues.

## License

MIT
```
