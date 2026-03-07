# DeployWise — Remix Template

A production-ready Remix (React Router) starter, pre-configured for one-click deployment to your VPS with [DeployWise](https://deploywise.dev).

## What's Included

- React Router 7 with server-side rendering
- TypeScript and Tailwind CSS
- Docker support included
- Optimized for PM2 + Nginx deployment

## Quick Start

```bash
npm install
npm run dev
```

Open [http://localhost:5173](http://localhost:5173).

## Deploy with DeployWise

1. Push this repo to GitHub
2. Open [deploywise.dev/dashboard](https://deploywise.dev/dashboard)
3. Add your VPS → Create a project → Select this repo
4. Click **Deploy**

DeployWise automatically runs `react-router build`, starts with PM2, configures Nginx, and issues a free SSL certificate. Docker deployment is also supported — just keep the Dockerfile and DeployWise will auto-detect it.

## Project Structure

```
├── app/
│   ├── routes/       # Route components
│   ├── root.tsx      # Root layout
│   └── app.css       # Global styles
├── Dockerfile        # Docker support
└── package.json
```

## Learn More

- [DeployWise Docs](https://deploywise.dev/docs)
- [React Router Documentation](https://reactrouter.com)

---

Deployed with [DeployWise](https://deploywise.dev) — free, open source.
