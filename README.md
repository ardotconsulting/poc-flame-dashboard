# poc-flame-dashboard

Proof of concept for **Self-Hosting Flame Dashboard: Centralize Access to All Your Self-Hosted Tools**.

Live demo: https://flame-dashboard.poc.ardotconsulting.com

Blog post: https://www.ardotconsulting.com/blog/2026/11/16/self-hosting-flame-dashboard-centralize-access-to-all-your-self-hosted-tools/

## What

[Flame](https://github.com/pawelmalak/flame) is a self-hosted start page for your server. It runs as a single container using SQLite — no external database required. Use it to centralize links to all your self-hosted tools in one place.

## Run locally

```bash
docker build -t flame-poc .
docker run -d -p 5005:5005 flame-poc
```

Open http://localhost:5005 to access the dashboard.
