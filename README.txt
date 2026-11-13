AURELION - Cloudflare Workers static website

Project layout:
  public/index.html   Your complete supplied HTML website
  wrangler.jsonc      Tells Wrangler to publish the public folder as static assets

Deploy with Cloudflare Workers Builds (Git integration):
  Root directory: /
  Build command: leave empty
  Deploy command: npx wrangler deploy

Or deploy locally from this project folder:
  npx wrangler deploy

The site uses Tailwind CSS, Google Fonts, and Three.js from external CDNs, so visitors need internet access for those resources.
