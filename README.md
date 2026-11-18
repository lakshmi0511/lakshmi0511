# Lakshmi Priya

**Senior Programme & Digital Operations Leader · NPTEL, IIT Madras**

13+ years leading national-scale digital education operations at NPTEL. I also build tools
that turn manual scheduling and reporting work into repeatable, checked processes. The main one
is exam planning: taking course lists, registration history and domain mappings and producing
schedules that follow the rules and can be rerun every semester.

[Portfolio](https://lakshmi0511.github.io/) · [LinkedIn](https://www.linkedin.com/in/lakshmi-priya-42583275/) · [Email](mailto:priyamalthy2010@gmail.com)

## Projects

| Project | What it does | Technologies |
| --- | --- | --- |
| [NPTEL Exam Allocation](https://github.com/lakshmi0511/nptel-exam-allocation) | Assigns an exam date to each of 1,000+ courses per semester. Keeps courses within their date windows and after their end dates, minimises domain clashes, spreads big courses and balances registrations per date. Outputs a checked Excel workbook. Packaged as a Claude Code skill. | Python, OR-Tools CP-SAT, pandas, openpyxl |
| [Results Pipeline Dashboard](https://github.com/lakshmi0511/results-pipeline-dashboard) | Live dashboard that tracks 1,000+ courses from scores loaded to results published. A collector gathers data from a web tool and team spreadsheets, a build step reduces it to course-level totals with no personal data, and an access-protected Cloudflare Worker serves it with "Update now" controls. | Node.js, Python, Playwright, Cloudflare Workers |
| [Exam Results Warehouse](https://github.com/lakshmi0511/exam-results-warehouse) | Turns a shared folder of messy exam report exports (several vendors, re-exports, zips) into one SQLite database. Syncs only changed files, keeps the newest snapshot, records where every row came from, and offers a candidate lookup and a browser UI. | Python, SQLite, openpyxl |
| [Live Attendance Feed](https://github.com/lakshmi0511/live-attendance-feed) | Polls an exam-desk API during exam sessions and produces a live per-centre, per-room attendance reading every 10 seconds for a tally dashboard. Includes a mock API to try it. | Node.js |
| [GitHub Ticket Desk](https://github.com/lakshmi0511/github-ticket-desk) | Claude Code skill and tracker for running an operations team's requests as form-based GitHub issues: drafting tickets, assigning, and daily tracking of overdue and unanswered items. | Python, GitHub CLI, Claude Code |

## Tools I use

Deployments of tools built by [Santhoshprabhu S](https://github.com/01234santhoshprabhu):

- [Count Dashboard](https://lakshmi0511.github.io/count/): enrollment, exam registration and membership reports.
- [Scoring Tools](https://lakshmi0511.github.io/Tool/): assignment scoring, attendance analysis and CSV/Excel exports.
- [PDF Watermark](https://github.com/lakshmi0511/NPTEL-Watermark): batch logo watermarking for PDFs.

## Technical focus

- **Optimisation:** constraint programming and multi-objective scheduling with OR-Tools.
- **Data:** Python, pandas, Excel and Google Sheets workflows, data cleaning and matching.
- **Automation & dashboards:** Claude Code skills, browser automation (Playwright), Node.js, Cloudflare Workers, Git and GitHub.
- **Data engineering:** SQLite warehouses, incremental syncs, provenance tracking.

---

Interested in exam scheduling, data operations or automation? [Get in touch](mailto:priyamalthy2010@gmail.com).
