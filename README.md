# Agricultural-Compliance-Dashboard
This project monitors supply-chain performance tracker covering ingredients, cereals and grains, and coffee across several African markets. It monitors delivery against requirements, quality compliance, sustainability targets, EUDR activities, and child-labour remediation, with a master list categorizing the materials tracked.

## Introduction
The CWAR Agric Services Monthly Operating Review (MOR) is a three-page Power BI report that brings the region’s agricultural sourcing performance into one place. It covers supplier quality and compliance, sustainability and EUDR programme delivery, and sourcing volumes against requirements across Cameroon, Côte d’Ivoire, Ghana, Nigeria and Senegal.

Before this report, the information sat in separate trackers, so reviewing status meant stitching files together by hand. The dashboard gives the team one refreshed view they can slice by supplier, material and country.

### Dashboard File
My final Dashboard is in 

### Skills Used
- **📉 Power BI:** multi-page report design, slicers, bookmarks and page navigation, conditional formatting, and custom visual styling.
- **🧮 DAX:** KPI measures, target versus actual logic, percentage achievement, and status classification.
- **❎ Data modelling:** relating supplier, material, country and target tables so slicers filter every page consistently.
- ** Power Query:** cleaning and shaping source trackers into analysis-ready tables.
- ** Dashboard design:** KPI cards, threshold lines, status donuts, and a consistent Nestlé-aligned look across pages.
- ** Figma

### Dataset
The report draws on three groups of data:

- Quality and compliance: supplier test results for rice (aflatoxin, lead, arsenic), maize, green coffee (waste, broken fragments, foreign materials) and palm oil (MCPD, MOAH, MOSH), each with its specification limit.
- Sustainability and EUDR: programme measures with targets and completions, covering tree planting, capacity building, carbon benefit (tCO2e), project pipeline, regenerative agriculture and certification, and the eight EUDR implementation steps.
- Sourcing volumes: 2026 requirement and delivered-to-date tonnage by material and country.

Shared dimensions for supplier, material and country tie these together, and a last-refreshed timestamp on each page shows how current the data is.

## Dashboard Build
- Page 1, Sourcing Volumes. The headline card shows 40,313 t delivered against a 51,429 t requirement (78% achieved). A status donut splits the 14 tracked items into 3 at risk, 6 on track and 5 completed. A dot plot shows percentage of requirement achieved by material and country, and a clustered column chart compares requirement with delivered tonnage. Colour-coded labels (red, amber, green) make the laggards easy to spot.

- Page 2, Sustainability and EUDR. Two KPI cards show achieved YTD (71,290) against target (79,345). Next to them are a status-of-measures donut (3 completed, 4 on track), an EUDR implementation bar chart of target versus completed by step, and a delivered-versus-target view for the tree planting project. A button panel on the left switches between workstreams.

- Page 3, Quality and Compliance. Rice and maize compliance are shown as donuts. Green coffee quality has two bar charts, one against spec and one against the premium limit, with limit markers. Palm oil has four supplier charts (MCPD, MOAH, MOSH, MCPD) with red dashed threshold lines, so any supplier near or over its limit stands out immediately. Supplier and Country slicers sit in the header.

### 🧮 DAX Measures

## Conclusion
The project turns scattered quality, sustainability and sourcing data into a single review tool. In one meeting, the team can see which suppliers sit close to their compliance limits, how EUDR readiness is progressing, and which materials and countries are behind on 2026 volumes (for example, the 3 items flagged at risk). Next steps could include automated alerts when a supplier breaches a threshold, trend views across months, and extending the same model to additional materials and countries.
