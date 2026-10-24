# State of Sustainability Assurance in LQ45: FY2025

Data and calculations behind the report *State of Sustainability Assurance in LQ45: FY2025* by Kelvin Kenzie Muhammad (October 2026). The report looks at how the 45 LQ45 constituents assure their FY2025 sustainability data, and how far those statements are from the form ISSA 5000 and SAKb 5000 will require.

This is a personal portfolio project, not a formal study.

## Files

| File | Contents |
|---|---|
| `Final_Report.pdf` | The full report |
| `LQ45_Assurance_FY2025_Data.xlsx` | The full workbook. Every number in the report traces to a formula here. |
| `csv/data.csv` | One row per issuer: report, assurance statement, provider, standard, level, subject matter, GHG scopes, and readiness scores. |
| `csv/ghg_reconciliation.csv` | Each report with GHG data, checked against itself. Anonymised. |
| `csv/codebook_fields.csv` | Definition and allowed values for every field. |
| `csv/coding_rules.csv` | The 29 coding rules. |

The CSV files are plain copies of the workbook tables, for reading on GitHub. The workbook is the source.

## Workbook tabs

- **About**: scope, method and limitations.
- **Data**: the coded data. Columns after *Assurance page reference* are calculated.
- **GHG reconciliation**: three-lens check of each report. Issuer names, figures and page references are withheld; results are reported in aggregate only.
- **Codebook**: field definitions and coding rules.
- **Exhibit 1** to **Exhibit 7**: one tab per exhibit in the report.
- **Text figures**: numbers quoted in the report text, with the formula behind each.
- **Sources**: public sources used.

## Method

- **Sample:** the LQ45 index for 3 August to 30 October 2026. For each constituent, the FY2025 sustainability or integrated annual report published in 2026 was read, plus one full assurance report published by the issuer (MEDC).
- **Coding:** only what is written in the report or statement is coded, using 29 written rules.
- **AI assistance:** extraction and initial coding were AI-assisted. Claims naming issuers or providers and all headline figures were verified manually.
- **Readiness score:** five ISSA 5000 core criteria and two PSPK criteria, each met or not met. It measures the published statement, not the engagement behind it.

## Limitations

- **Reconciliation:** it tests internal consistency, not the truth of the underlying data, so the counts are a lower bound.
- **Coverage:** one year and 45 large companies, so the results do not describe the wider market.
- **Comparison:** the comparison of assured and non-assured reports is descriptive and rests on small groups.

## Contact

[linkedin.com/in/kelvin-kenzie-muhammad-a50a572a2](https://www.linkedin.com/in/kelvin-kenzie-muhammad-a50a572a2/)
