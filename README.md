# AHEP4 Outcomes Editor (GitHub Pages)

This folder contains a static web form (index.html) that:
- Loads modules from `modules_from_module_learning_outcomes.json`
- Lets module supervisors select outcomes
- Submits each record to your Cloudflare Worker, which creates a GitHub Issue in your private submissions repo.

## What you must edit (one time)
Open `index.html` and set:
- `WORKER_URL` (already set to your worker)
- `VIDEO_URL` (optional)

## Deploy
Upload these files to your GitHub Pages repository root and enable Pages (main / root).
