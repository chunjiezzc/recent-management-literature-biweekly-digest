# Recent Management Literature - Biweekly Digest

## Purpose

This repository publishes a biweekly digest of recent management papers based on article abstracts. The goal is to provide a fast, readable archive of newly available research without requiring readers to scan journal websites one by one.

## Coverage

The repository tracks the latest online articles from the following journals:

- Academy of Management Journal (AMJ)
- Strategic Management Journal (SMJ)
- Organization Science (OS)
- Administrative Science Quarterly (ASQ)
- Academy of Management Review (AMR)
- Entrepreneurship Theory and Practice (ETP)
- Journal of Business Venturing (JBV)
- Strategic Entrepreneurship Journal (SEJ)
- Journal of Management (JoM)
- Journal of Management Studies (JMS)
- Organization Studies (Org Stu)

JBV and Research Policy (RP) are also handled in a separate monthly report.

## Repository Information

- Creator: Zhengchu Zhang
- First release: 2026 Mar 15

## File Guide

This repository contains two output formats for each digest:

- `*.md`: markdown version for reading, editing, and citation
- `*.pdf`: PDF version for easy sharing

### Biweekly digest files

- `weekly_digest_YYYY-MM-DD_en.md`
- `weekly_digest_YYYY-MM-DD_en.pdf`

The date in each weekly digest filename is inclusive. Each weekly digest covers papers that appeared online during the half-month period ending on that date, including papers published on the date shown in the filename.

Examples:

- `weekly_digest_2026-01-15_en`: first half of January 2026, including 2026-01-15
- `weekly_digest_2026-01-31_en`: second half of January 2026, including 2026-01-31
- `weekly_digest_2026-02-14_en`: first half of February 2026, including 2026-02-14
- `weekly_digest_2026-02-28_en`: second half of February 2026, including 2026-02-28
- `weekly_digest_2026-03-14_en`: first half of March 2026, including 2026-03-14

### Monthly JBV and RP files

- `monthly_digest_YYYY-MM-DD_jbv_rp_en.md`
- `monthly_digest_YYYY-MM-DD_jbv_rp_en.pdf`

JBV and RP are summarized separately in a monthly report rather than the regular biweekly digest.

## Current Files

- `weekly_digest_2026-01-15_en.md` and `weekly_digest_2026-01-15_en.pdf`
- `weekly_digest_2026-01-31_en.md` and `weekly_digest_2026-01-31_en.pdf`
- `weekly_digest_2026-02-14_en.md` and `weekly_digest_2026-02-14_en.pdf`
- `weekly_digest_2026-02-28_en.md` and `weekly_digest_2026-02-28_en.pdf`
- `weekly_digest_2026-03-14_en.md` and `weekly_digest_2026-03-14_en.pdf`
- `monthly_digest_2026-03-15_jbv_rp_en.md` and `monthly_digest_2026-03-15_jbv_rp_en.pdf`

## Updating the Repository

If you want to download the latest changes from GitHub:

```bash
git pull origin main
```

If you generate a new digest locally and want to publish it:

```bash
git add .
git commit -m "Add new digest"
git push origin main
```

If you work on another machine for the first time:

```bash
git clone https://github.com/chunjiezzc/recent-management-literature-biweekly-digest.git
cd recent-management-literature-biweekly-digest
git pull origin main
```
