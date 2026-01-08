
# AI-Powered Resume Screening Automation

This project automates resume screening by extracting resume and job description data, matching skills, calculating a match score, and automating shortlisting decisions using 
n8n workflows.

## Features
- Resume PDF upload via webhook
- Job description input
- Skill extraction and matching
- Match score calculation
- Automated shortlisting
- Email notifications
- Google Sheets result storage

## Tech Stack
- n8n (Workflow Automation)
- JavaScript (Function Nodes)
- Google Sheets API
- Gmail API
- Webhooks

## Workflow Overview
1. Resume and JD are submitted via webhook
2. Text is extracted from PDF resumes
3. Skills are parsed from both inputs
4. Match score is calculated
5. Candidates are shortlisted or rejected
6. Results are stored in Google Sheets

## How to Use
1. Import the workflow JSON into n8n
2. Configure Google and Gmail credentials
3. Activate the workflow
4. Submit resume and JD via webhook

## Output
- Match score
- Matched skills
- Shortlisting decision

## Future Enhancements
- ML-based semantic skill matching
- Resume ranking
- Dashboard analytics

