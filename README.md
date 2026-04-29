# 🎯 Claude Job Application Skill

A Claude skill that helps you apply for jobs smarter — ATS score, tailored resume, and cover letter in one shot.

## What It Does

Drop in your resume + a job description (or URL), and the skill automatically:

- 📊 **ATS Score** — rates your resume match (0–100) with strengths, gaps, and what will be fixed
- 📄 **Tailored Resume** (.docx) — rewrites only your Professional Summary and reorders skills to match the JD. Everything else (companies, dates, links, bullet points) is preserved exactly
- ✉️ **Cover Letter** (.docx) — professional, formal, one page, grounded in your actual experience

## Key Principles

- **Honest** — never adds skills you don't have or inflates your experience
- **Safe** — skills you're exploring appear only in the cover letter, framed as "actively learning", never in the resume
- **Minimal changes** — only touches what matters for ATS; your resume stays yours

## Installation

1. Download [`job-application-skill.skill`](https://github.com/kenduraghav/claude-job-application-skill/raw/main/job-application-skill.skill)
2. In Claude, go to **Settings → Skills → Add Skill**
3. Upload the `.skill` file — done

## How to Use

In any Claude conversation, just say:

> *"Help me apply for this job"* + attach your resume (PDF or DOCX) + paste or link the job description

Claude will handle the rest.

## Triggers

The skill activates automatically when you:
- Upload a resume alongside a job description or URL
- Ask for an ATS score
- Ask to tailor your resume or write a cover letter

## Built With

- [Claude](https://claude.ai) by Anthropic
- Skill created using the Claude Skill Creator

## Author

**Raghavendran S**  
[LinkedIn](https://www.linkedin.com/in/raghavendran-karthik/) · [GitHub](https://github.com/kenduraghav)
