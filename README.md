# Activity-Tracking
Activity Tracking

## Monthly Sync
This repository now includes a GitHub Actions workflow at `.github/workflows/monthly-sync.yml`.
It runs on the 1st of every month, updates a sync marker, pushes a `monthly-sync` branch, and opens or updates a pull request.
