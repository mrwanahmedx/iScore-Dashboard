# iScore Credit Bureau Dashboard

Interactive Tableau portfolio project focused on credit-bureau-style reporting, portfolio segmentation, delinquency monitoring, and risk-oriented data storytelling.

> **Portfolio note:** this is an independent project using a public / portfolio dataset. It is not affiliated with iScore and does not contain employer, bureau, or confidential customer data.

## What the project demonstrates

- structuring credit-style data for business intelligence,
- defining portfolio and delinquency KPIs,
- building multi-page Tableau dashboards,
- cohort / customer / loan / default segmentation,
- interactive filtering and drill-down,
- translating risk information into an executive-facing dashboard.

## Dashboard preview

### Portfolio overview

![Portfolio overview](Screenshots/Home.png)

### Customer view

![Customer view](Screenshots/Customers.png)

### Default analysis

![Default analysis](Screenshots/Default.png)

### Sales / portfolio view

![Sales view](Screenshots/Sales.png)

## Live dashboard

The repository includes a GitHub Pages wrapper for the published Tableau workbook:

**[Open the live Tableau dashboard](https://mrwanahmedx.github.io/iScore-Dashboard/)**

The workbook source is also included as `iScore.twbx`.

## Analytical structure

```mermaid
flowchart LR
    A[Portfolio dataset] --> B[Data preparation]
    B --> C[Calculated fields and KPIs]
    C --> D[Portfolio overview]
    C --> E[Customer segmentation]
    C --> F[Loan / exposure analysis]
    C --> G[Default / delinquency analysis]
    D --> H[Interactive Tableau workbook]
    E --> H
    F --> H
    G --> H
```

## Questions the dashboard is designed to answer

- What does the portfolio look like at a high level?
- Which segments contain the most borrowers or exposure?
- Where are delinquency / default concentrations visible?
- How do customer and loan characteristics differ across views?
- Which areas deserve deeper risk investigation?

The dashboard is descriptive. It supports exploration and reporting; it is **not** a bureau score, underwriting policy, or lending decision engine.

## Repository structure

| Path | Purpose |
| --- | --- |
| `iScore.twbx` | Tableau packaged workbook |
| `index.html` | GitHub Pages Tableau embed |
| `Screenshots/` | Dashboard preview images |
| `README.md` | Project documentation |

## Tech stack

- Tableau Public / Tableau Desktop
- Tableau calculated fields and dashboard interactions
- HTML + Tableau JavaScript embed
- GitHub Pages

## Related engineering case study

The newer **Data Observatory / iScore Credit Lab** expands the credit-risk theme into a web-first Python + SQL + model-validation case study with synthetic data, explicit grain controls, anti-fan-out SQL, calibration, threshold analysis, and automated tests.

**[Open the iScore Credit Lab](https://mrwanahmedx.github.io/data-observatory/score.html)**  
**[View Data Observatory source](https://github.com/mrwanahmedx/data-observatory)**

## Limitations

- portfolio / public-style data rather than official bureau data,
- descriptive dashboard rather than predictive underwriting,
- no claim of regulatory approval or real-world lending validity,
- dashboard screenshots and workbook are presented for portfolio demonstration.

## Author

**Marwan Ahmed**  
[LinkedIn](https://www.linkedin.com/in/mrwan-ahmed/) · [GitHub](https://github.com/mrwanahmedx)
