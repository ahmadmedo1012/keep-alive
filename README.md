# keep-alive

Scheduled GitHub Actions pings that keep the free-tier Render services warm
(see `.github/workflows/keep-warm.yml`). Nothing else lives here.

Note: GitHub may disable cron workflows in repos with 60 days of no commits —
if pings stop, any commit (even empty) re-enables them.
