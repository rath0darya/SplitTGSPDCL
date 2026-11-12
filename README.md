# SplitTGSPDCL

A responsive electricity bill-sharing calculator for shared homes in Telangana.

## Calculation modes
- **Equal split:** divides the entered bill equally among the selected number of people.
- **Sub-meter split:** allocates the entered bill in proportion to each person's sub-meter units. Optional common-area units are shared equally.
- **Historical average:** estimates a new resident's contribution using the average of 3–6 previous bills, the number of existing residents, and the new resident's stay duration.

## Publish with GitHub Pages
This repository includes a GitHub Actions workflow that deploys the root site to GitHub Pages. In repository Settings → Pages, select **GitHub Actions** as the build and deployment source if it is not already selected.

## Important calculation notes
This is a bill allocation tool, not an official TGSPDCL bill generator. Enter the final bill amount shown by the utility. Sub-meter mode allocates that amount proportionally; it does not independently reconstruct tariff slabs, fixed charges, taxes, subsidies or FSA/FCA. Historical mode is an estimate based on prior bills, not a guarantee of future consumption or charges.

Official references: [TGSPDCL](https://tgsouthernpower.org/) · [TGERC current-year orders](https://www.tgerc.telangana.gov.in/currentyearorders.php)
