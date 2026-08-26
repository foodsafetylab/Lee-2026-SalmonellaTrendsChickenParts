# Lee-2026-SalmonellaTrendsChickenParts

## Overview
The United States Department of Agriculture’s Food Safety and Inspection Service (FSIS) collects *Salmonella* data from poultry products and assigns establishment categories based on *Salmonella* prevalence over 52-week moving windows, with Category 1 representing lower, Category 2 intermediate, and Category 3 higher prevalence. In this study, we analyzed FSIS Raw Poultry Laboratory Sampling Data for chicken parts from January 1, 2023 to September 30, 2025 to provide further insight on *Salmonella* prevalence, high-level contamination (≥ 10 CFU/mL rinsate), and establishment categorization across establishment sizes, product types, months, years, and serotypes. *Salmonella* prevalence varied significantly by establishment size, product type, and their interaction. Small and very small establishments had significantly higher odds of *Salmonella* positive than large establishments for leg and wing products (adjusted odds ratios [aORs] = 1.7–2.1), while differences by establishment size were smaller for breast products. In contrast, high-level *Salmonella* occurrence differed significantly by product type, sampling month, and sampling year. Positive samples without serotype data had lower odds of high-level *Salmonella* than positive samples with a higher risk serotype (aORs = 0.37–0.40). At the establishment level, sample numbers per moving window and category distributions varied by establishment size. Large establishments generally had more samples per moving window than small and very small establishments, but a lower proportion of moving windows classified as Category 1 or 3. We observed a significant increasing monotonic trend in Category 1 (Kendall’s τ = 0.77, p-value < 0.001) and decreasing trends in Categories 2 and 3. These insights could help inform government regulatory and industry management processes for better *Salmonella* control in poultry products.
## Usage
## Setup
- Raw chicken parts laboratory sampling data was obtained from the USDA-FSIS Laboratory Sampling Data webpage here: https://www.fsis.usda.gov/news-events/publications/raw-poultry-sampling
- The Meat, Poultry and Egg Product Inspection Directory file was obtained from USDA-FSIS Meat, Poultry and Egg Product Inspection Directory webpage here: https://www.fsis.usda.gov/inspection/establishments/meat-poultry-and-egg-product-inspection-directory

### Running
Data processing, prevalence-based categorization, statistical testing, and data visualization can be conducted using the code in "Data filtering & prevalence-based performance standards.Rmd" file. Refer to the annotations for guidance on each step.

## Authors
You can view the list of authors in the [AUTHORS](/AUTHORS) file.

## Contact
Corresponding author: Matthew J. Stasiewicz<br>
103 Agricultural Bioprocess Lab<br>
1302 W. Pennsylvania<br>
Urbana, IL, 1361801<br>
USA<br>
+1-217-265-0963<br>
[mstasie@illinois.edu](mailto:mstasie@illinois.edu)

## Citation
Include citation here.

## License
This project's code is licensed under the GNU General Public License v3.0 and dataset is licensed the Creative Commons Attribution Share Alike 4.0 International license. Please see the [LICENSE.code](/LICENSE.code) and [LICENSE.dataset](/LICENSE.dataset) files for details.

## Acknowledgements
Stasiewicz has received unrelated research funding from the US Poultry and Egg Association and Perdue Foods LLC.

## Funding
This study was supported by the Doctoral Merit Fellowship to Jungeun Lee, administered though the Department of Food Science and Human Nutrition at the University of Illinois Urbana-Champaign. 
