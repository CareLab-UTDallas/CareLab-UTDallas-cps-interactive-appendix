# EPPP Institutional Performance Dashboard

Interactive data visualization dashboard displaying institutional performance across 8 knowledge domains for Clinical Psychology doctoral programs in the USA and Canada.

## Features

- **Interactive Radar Charts**: Compare institutions against PCSAS and APA-only accredited program benchmarks
- **Filterable Rankings**: Horizontal scrolling bar charts with minimum sample size filtering (n≥10)
- **Year Range Filter**: Analyze data from 2015-2024
- **Pearson Correlation Analysis**: Measure similarity between institutional profiles and benchmark groups
- **Longitudinal Trends**: Track performance over time with LOESS smoothing and IQR trend ribbons
- **Downloadable Data**: Export aggregated data in long or wide CSV formats
- **Technical Documentation**: Built-in downloadable documentation
- **PNG Export**: Download charts as high-quality images

## Data Source

This dashboard visualizes EPPP (Examination for Professional Practice in Psychology) performance data aggregated from institutional cohorts across the United States and Canada.

## License

[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-nd/4.0/)

This work is licensed under a [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License](https://creativecommons.org/licenses/by-nc-nd/4.0/).

### License Summary

**You are free to:**
- **Share** — copy and redistribute the material in any medium or format

**Under the following terms:**
- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
- **NonCommercial** — You may not use the material for commercial purposes.
- **NoDerivatives** — If you remix, transform, or build upon the material, you may not distribute the modified material.

**No additional restrictions** — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

### Full License

The full legal text of the CC BY-NC-ND 4.0 license is available at:
https://creativecommons.org/licenses/by-nc-nd/4.0/legalcode

## Technical Stack

- **Frontend**: React 18, TypeScript, Vite
- **UI Components**: Shadcn/ui, Radix UI, Tailwind CSS
- **Data Visualization**: Recharts
- **Backend**: Express.js, Node.js
- **Data Processing**: CSV parsing with server-side aggregation and client-side LOESS smoothing

## Deployment

This is a static website that can be deployed to:
- GitHub Pages
- Vercel
- Netlify
- Any static hosting service

## Questions or Feedback?

For questions about the data or dashboard functionality, please contact the repository owner.

---

**Copyright Notice**: All rights reserved. Use of this dashboard and its data is subject to the terms of the CC BY-NC-ND 4.0 license.
