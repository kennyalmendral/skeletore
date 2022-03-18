# Skeletore

A Shopify 2.0 starter theme that uses Alpine.js and Tailwind CSS.

## Setup

**1. Install Shopify CLI**
https://shopify.dev/apps/tools/cli/installation

**2. Initialize theme**
```sh
shopify theme init <THEME_NAME> --clone-url https://github.com/kennyalmendral/skeletore
```

**3. Connect theme to Shopify store**
```sh
shopify login --store=<STORE_NAME>.myshopify.com
shopify theme serve
```

**4. Run the following command to install node modules and compile CSS/JS assets**
```sh
npm i
npm run start
```

---

Just in case you encountered the *Unauthorized access error*, check out https://github.com/Shopify/shopify-cli/issues/2059#issuecomment-1049237586
