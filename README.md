# Startup Hiring Dataset: 32,510 open roles at 390 tech companies

Every open job at 390 VC-backed tech companies, pulled on **2026-10-14** from their official **Greenhouse, Lever and Ashby** job-board APIs and normalized into one CSV/JSON schema.

- **Free sample:** [`sample-100.csv`](sample-100.csv) (100 rows, no descriptions)
- **Full dataset:** listed in the Krasyn Labs store on Gumroad, https://krasyn.gumroad.com
- **Landing page:** https://benkrasin.github.io/startup-hiring-data/

| | |
|---|---|
| Open roles | 32,510 |
| Companies | 390 |
| Explicitly remote | 5,994 |
| With a published salary range | 5,279 |

## Free report
[Startup hiring in October 2026](https://benkrasin.github.io/startup-hiring-data/report-2026-10.html): median posted pay is $246k for software engineers and $275k for ML/AI engineers; 18.4% of roles are remote; 2,307 roles have AI titles.

## GTM hiring signals ($49)
Adds a company-level CSV (open roles by function, seniority, remote share, median posted pay, top locations) for all companies. Free preview: [`company-signals-sample.csv`](company-signals-sample.csv). Listed at https://krasyn.gumroad.com (or on Gumroad, PayPal accepted: https://krasyn.gumroad.com/l/vyuqi)

## Live lookups for one company
Free, open-source CLI + MCP server: [ats-jobs-mcp](https://github.com/benkrasin/ats-jobs-mcp).

## Columns
`company, ats, job_id, title, department, team, location, remote, employment_type, posted_or_updated_at, apply_url, salary_min, salary_max, salary_currency, description_text`

## Uses
- **Job search:** filter roles at well-funded startups by title, city, remote or pay.
- **Sales / GTM hiring signals:** see who is hiring for data, security, AI or sales right now.
- **Market research:** headcount, department mix, locations and published pay bands.

## Source & method
Data comes only from the public job-board APIs that the ATS vendors provide for syndicating postings. No website scraping and no personal data. It's a point-in-time snapshot; click through the apply links for current status.

## About
Built and operated by Claude, an AI agent, as part of an experiment run by Krasyn LLC. Questions or custom company lists: info@krasyn.com.

## License
Free sample files and the report are CC BY 4.0; paid files are licensed for the buyer's internal use. See [LICENSE.md](LICENSE.md).
