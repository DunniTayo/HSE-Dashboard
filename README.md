# HSE Dashboard — Power BI

A 5-page Power BI report that tracks Health, Safety, and Environmental (HSE) performance across facilities: recordable and lost-time incidents, process safety events, environmental permit compliance, and training/compliance scores.

## What this dashboard answers

- Is TRIR (Total Recordable Incident Rate) trending up or down against the CIAC industry benchmark, year over year?
- Which facilities carry the highest incident rate and the most days lost?
- How many Tier 1 and Tier 2 process safety events occurred, and how does that trend look year over year?
- Are environmental discharge readings (e.g., chlorate) staying inside permit limits, and by how much?
- What is training completion by course, and how are safety culture "pillars" scoring?

## Pages

**1. Executive HS&E Overview**
Single-page rollup for leadership: TRIR, recordable incidents, days lost, training completion, and a culture score as KPI cards, plus a TRIR/LTIR trend line against the CIAC benchmark, recordable incidents by month (2023 baseline vs. 2024), TRIR by facility, and training completion by course.

**2. Incidents & TRIR**
Drills into recordables and lost-time incidents: TRIR/LTIR trend by year, days lost by facility, Tier 1 vs. Tier 2 events by year, and a facility-level detail table (facility, province/state, TRIR, LTIR, recordable incidents, days lost).

**3. Environmental Performance**
Tracks discharge/exposure readings against permit limits: observed vs. permit-limit trend by month, observed vs. limit by agent, and supporting detail tables (metric, value, unit, period-over-period change; agent, limit, limit type, status).

**4. Training & Compliance**
Completion rate by training course and a safety-culture score by "pillar," with supporting detail tables.

**5. Process Safety & Exposure**
Tier 1/Tier 2 process safety event counts, recordable incidents by facility, and exposure readings by agent against limits, with a status detail table.

## Key metrics modeled

| Metric | What it measures |
|---|---|
| TRIR | Total Recordable Incident Rate |
| LTIR | Lost Time Incident Rate |
| Tier 1 / Tier 2 | Process safety event severity tiers |
| Days Lost | Lost-time days from recordable incidents |
| Completion Rate | Training course completion by employee population |
| Observed vs. Limit | Environmental reading vs. permit/exposure limit, by agent |
| Score | Safety culture score by pillar |

## Data model

Facility, Year/Month, Training, Pillar, and Agent are used as the primary slicing dimensions across pages, with facility and province/state supporting geographic roll-ups and year/month supporting trend analysis.

## Tools

Power BI Desktop — data modeling, DAX measures, report design across 5 report pages with cross-page slicers.

## Notes on the data

Built on illustrative/sample HSE data for portfolio purposes; figures do not represent any real company's actual safety or environmental performance.

<img width="1517" height="855" alt="Process Safety   Exposure" src="https://github.com/user-attachments/assets/d3f852bd-5209-4655-ab52-ce079766bb07" />
<img width="1577" height="846" alt="Incidents   TRIR" src="https://github.com/user-attachments/assets/2c9dbcad-5fb5-41ba-9b8d-a782b346b865" />
<img width="1652" height="862" alt="Executive HS E Overview" src="https://github.com/user-attachments/assets/c072cb00-a67d-4bdb-918d-10c073de66de" />
<img width="1575" height="843" alt="Environmental Performance" src="https://github.com/user-attachments/assets/20109d6d-a11e-4790-bee8-fbf8b5e09347" />
<img width="1532" height="828" alt="Training   Compliance" src="https://github.com/user-attachments/assets/33bab0b3-a480-46d2-a43c-0c57346c1790" />


