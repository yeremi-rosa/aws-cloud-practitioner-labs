# AWS Cloud Practitioner Labs

This log documents how the repository was created and why each step was done.

## Goal
Create a public GitHub repository that turns AWS learning into visible, organized, professional artifacts.

## Repository
```text
yeremi-rosa/aws-cloud-practitioner-labs
```

## Step 1 — Create repository

### Command
```bash
cd /home/yeremi/job-search/github
gh repo create aws-cloud-practitioner-labs --public --clone --description "AWS cloud fundamentals notes, labs, and hands-on learning artifacts"
```

### Why
A dedicated AWS repo gives the GitHub profile an immediate cloud-focused project that matches the current study path.

## Step 2 — Create structure

### Files created
```text
README.md
notes/cloud-architecture.md
notes/shared-responsibility-model.md
notes/aws-global-infrastructure.md
labs/s3-static-website.md
labs/ec2-basics.md
labs/iam-users-groups-policies.md
resources/links.md
```

### Why
The repo separates concept notes, hands-on labs, diagrams/resources, and study workflow. This keeps it recruiter-readable and easy to grow.

## Step 3 — Push first version

Planned commands:
```bash
git add .
git commit -m "Create AWS cloud learning repo skeleton"
git branch -M main
git push -u origin main
```
