# ECBA Exam Prep Tools

A suite of interactive study tools for the IIBA Entry Certificate in Business Analysis (ECBA) certification. Built as single-file HTML applications — no dependencies, no build step, just open and run.

Co-developed by a human candidate and [Claude (Anthropic)](https://anthropic.com) through conversational iteration.

## Tools

### 📋 Mock Exam (`exam.html`)

A full-length 50-question practice exam modeled on the IIBA ECBA certification format.

- 60-minute countdown timer
- All six BABOK® v3 Knowledge Areas covered
- Navigate freely between questions during the exam
- Detailed answer review with explanations after submission
- Performance breakdown by Knowledge Area
- Full attempt history saved across sessions

### 📖 Study Guide (`study-guide.html`)

An interactive reference covering all six BABOK® v3 Knowledge Areas.

- Sidebar navigation between Knowledge Areas
- Core tasks, key techniques, and exam tips per area
- Tap any technique pill to reveal its definition inline
- Key terms glossary per Knowledge Area

### 🗂 Prep Hub (`index.html`)

Quick-access dashboard — the landing page.

- Live attempt history
- Countdown to exam target date
- Navigation to all tools

### ℹ️ About (`about.html`)

Project background, tool descriptions, co-development credit, and full tech stack.

## Knowledge Areas Covered

1. Business Analysis Planning & Monitoring
1. Elicitation & Collaboration
1. Requirements Life Cycle Management
1. Strategy Analysis
1. Requirements Analysis & Design Definition
1. Solution Evaluation

## Tech Stack

|Tool                                       |Role                                            |
|-------------------------------------------|------------------------------------------------|
|[Claude (Anthropic)](https://anthropic.com)|AI pair programmer — all code, content, and copy|
|[GitHub](https://github.com)               |Version control                                 |
|[Vercel](https://vercel.com)               |Hosting & auto-deploy                           |
|[Notion](https://notion.so)                |Study log & project docs (connected via MCP)    |
|[Cursor](https://cursor.sh)                |AI-powered local code editor                    |
|Pure HTML/CSS/JS                           |No frameworks, no build tools                   |

## Deploy to Vercel

1. Fork or clone this repo
1. Connect to [Vercel](https://vercel.com) — select **“Other”** as the framework preset
1. Leave build command and output directory blank
1. Deploy — `index.html` serves as the landing page automatically

The included `vercel.json` provides clean URLs: `/exam` and `/study-guide`.

## About the ECBA

The ECBA (Entry Certificate in Business Analysis) is the entry-level certification offered by the [International Institute of Business Analysis (IIBA)](https://www.iiba.org), based on the BABOK® Guide v3.

- **Format:** 50 multiple choice questions · 60 minutes
- **Delivery:** Pearson VUE (online or test center)
- **Target score:** 75%+ (community consensus — official passing score not disclosed by IIBA)

-----

*Not affiliated with or endorsed by IIBA. BABOK® is a registered trademark of the International Institute of Business Analysis.*