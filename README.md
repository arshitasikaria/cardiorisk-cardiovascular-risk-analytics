# CardioRisk — Cardiovascular Risk Analytics Dashboard

An interactive Power BI portfolio project exploring how heart-disease rates vary across clinical risk factors, medical history, demographics, and lifestyle categories.

> **Important:** This is an analytics/portfolio project using a research-calibrated dataset. It is not a medical or diagnostic tool, and the associations shown should not be interpreted as proof of causation or as clinical guidance.

## Dashboard preview
![CardioRisk Executive Overview](screenshots/Screenshot%202026-10-18%20185754.png)

## Video walkthrough

[Watch the CardioRisk dashboard demo](demo/CardioRisk_Dashboard_Demo.mp4) — a 62-second walkthrough of the interactive report pages.

The demo video is compressed for convenient repository sharing. The original Power BI report remains available as `CardioRisk_Dashboard.pbix`.

## Dashboard pages

The Power BI report contains five pages:

1. **Executive Overview** — KPI cards, key findings, filters for Age Group, Region, and Sex, and a comparison of heart-disease rates by hypertension status.
2. **Clinical Risk** — clinical risk-factor analysis.
3. **History & Symptoms** — analysis focused on previous heart-event history and related indicators.
4. **Demographics** — demographic comparisons.
5. **Lifestyle** — lifestyle-category comparisons.

## Key indicators shown

| KPI | Value in the current report |
|---|---:|
| Total patients/records | 100,000 |
| Heart-disease cases | 46,000 (rounded) |
| Heart-disease rate | 46.08% |
| Average cholesterol | 217.67 mg/dL |
| Average resting blood pressure | 142.06 mmHg |
| Average age | 53.50 years |

The overview page currently reports a heart-disease rate of **63.98%** for the hypertension group and **30.22%** for the no-hypertension group. For blood-pressure categories, the report displays **59.23%** for Stage 2 High and **24.43%** for Normal. These are descriptive results from this dataset only.

## Tools and methods

- **Power BI Desktop** for the report and interactive visuals
- **Power Query** for data preparation
- **DAX** for measures and calculated categories
- Slicers and a reset-filters button for report interaction

## Open the project

1. Download `CardioRisk_Dashboard.pbix` from this repository.
2. Open it in Power BI Desktop.
3. Use the report tabs to explore all five pages and interact with the slicers.

The `.pbix` file contains the Power BI report and its model. If you later refresh the data and Power BI prompts for a source path, update the source in **Transform data → Data source settings**.

## Dataset and interpretation

The dataset is research-calibrated for analytical practice rather than a set of real patient records. Metrics summarize the records included in the report. They do not establish that a factor causes heart disease and should not be used to make clinical decisions.

## Suggested future improvements

- Document the precise dataset-generation/source details and any applicable licence.
- Add a project walkthrough and further screenshots for the other report pages.
- Publish a Power BI Service version if a shareable online report is appropriate for the dataset and account settings.
