# ✨ Personal Portfolio powered by Notion + Next.js

As a developer, I often needed a clean and customizable static website to showcase my side projects, blogs, and ideas. Over time, I experimented with different approaches — from traditional HTML/CSS, WordPress setups, to static site generators. But none felt as seamless and developer-friendly until I came across **[Travis Fischer](https://github.com/transitive-bullshit)’s open-source [Next.js Notion Starter Kit](https://github.com/transitive-bullshit/nextjs-notion-starter-kit)**.

This starter kit uses **Notion as the content management system (CMS)** and combines it with the power of **Next.js** and modern web features like:

- Dark mode
- SEO support
- Custom routing
- Image preview optimizations (LQIP)
- Easy deployment

It makes managing content and deploying a personal site incredibly efficient.

---

## 🧪 Getting Started

I began by duplicating the default public Notion template provided in the starter kit:

📄 **Template Used**:  
[https://transitive-bs.notion.site/Next-js-Notion-Starter-Kit-Template-7875426197cf461698809def95960ebf](https://transitive-bs.notion.site/Next-js-Notion-Starter-Kit-Template-7875426197cf461698809def95960ebf)

👉 I then duplicated it into my own Notion workspace and used it directly to configure my site.

> ❗ Note: Initially, no custom content was added — I focused on configuration and deployment first.

---

## 🔧 Configuration

The entire configuration is handled in a single file:

📁 `site.config.ts`

This file allows control over:

- 🔗 Your Notion root page ID (`rootNotionPageId`)
- 🌐 Site name, domain, and author info
- 🎨 Default page icons and covers
- 🌍 Language support
- ⚙️ Feature flags (like Redis cache, preview images, search, tweet embeds)
- 📌 Navigation structure and custom route mapping

To use your own Notion page, simply grab your page ID from the Notion URL and update:

```ts
rootNotionPageId: 'your-notion-page-id'

```
## 🚀 Deployment
The site is deployed using Vercel which provides:

🔄 Continuous deployment via GitHub

🔐 Secure management of environment variables

⚡ Fast performance with CDN support

🔗 Live Site: https://nextcmsportfolio.vercel.app/

## 👩‍💻 Author
Kritika Thakkar

## 📌 Credits

- Next.js Notion Starter Kit by @transitive-bullshit
- Notion
- Vercel



