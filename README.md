# Update README with Date and Day

This repository contains a GitHub Actions workflow that automatically updates the `README.md` file with the current date and day. The update happens daily at midnight (UTC) and can also be triggered manually.

## Last Update
- **Date:** 2024-12-01
- **Day:** Sunday

## Purpose

The goal of this workflow is to ensure that the `README.md` file always reflects the current date and day. This can be useful for projects that need to keep track of when the documentation was last updated or for any project where including the date and day dynamically in the README is a requirement.

## How It Works

1. **Scheduled Updates**: 
   - The workflow runs daily at midnight UTC. It automatically fetches the current date and day in UTC time.
   - The placeholders `2024-12-01` and `Sunday` in the `README.md` file are replaced with the actual date (in `YYYY-MM-DD` format) and the name of the current day (e.g., "Monday").

2. **Manual Trigger**: 
   - The workflow can also be manually triggered via the GitHub Actions interface if you want to update the `README.md` on-demand.

3. **Commit and Push**: 
   - After updating the `README.md` file, the workflow commits the changes and pushes them to the repository, ensuring that the latest date and day are always reflected in the file.

