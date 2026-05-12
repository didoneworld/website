# DID One World Website

Production landing page for [DID One World](https://didone.world), a universal decentralized identity platform for humans, AI agents, APIs, skills, things, organizations, verifiable credentials, wallets, and platform infrastructure.

## Website

- Live domain: https://didone.world
- Repository: https://github.com/didoneworld/website
- GitHub organization: https://github.com/didoneworld

## Ecosystem

- Platform: https://github.com/didoneworld/platform
- Agent DID: https://github.com/didoneworld/Agent-DID
- Verifiable Credential: https://github.com/didoneworld/verifiable-credential
- ID Wallet: https://github.com/didoneworld/idwallet

## Local Preview

This is a static HTML site. Open `index.html` directly in a browser or serve it locally:

```bash
python3 -m http.server 8080
```

Then visit:

```text
http://localhost:8080
```

## Platform Quick Start

```bash
git clone https://github.com/didoneworld/platform.git
cd platform
docker-compose up
```

## Local Platform Services

- DID Registry: http://localhost:8000
- VC Issuer: http://localhost:8001
- Wallet: http://localhost:3000

## Structure

```text
index.html   Main website
README.md    Project documentation
robots.txt   Search crawler policy
sitemap.xml  Search engine sitemap
```

## Deployment

The site can be deployed with any static host, including GitHub Pages, Cloudflare Pages, Netlify, or Vercel.
