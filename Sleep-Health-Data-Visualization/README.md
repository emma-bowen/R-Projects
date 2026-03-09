# How Demographic and Lifestyle Variables Affect Sleep Health

### Description
This folder contains the information and final report for my personal data visualization project in R, which focuses on exploring the effects that demographic and lifestyle variables may have on sleep health through data analysis and visualizations. Techniques highlighted throughout this project include data cleaning and manipulation, analysis, and visualization creation. The *Sleep_health_and_lifestyle_dataset.csv* dataset was used; it was created by Tharmalingam (2024) and was downloaded from Kaggle.

### Data Source and Information
- **Title**: *Sleep_health_and_lifestyle_dataset.csv*
- **License**: CC0: Public Domain
- **Creator**: Laksika Tharmalingam (2024)
- This dataset was created by Tharmalingam (2024) and was sourced from Kaggle: https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset/data.
- This dataset is synthetic and includes a variety of demographic, sleep-related, and lifestyle variables for exploratory analysis and data visualization projects.
- **Citation**: \
Tharmalingam, L. (2024). *Sleep Health and Lifestyle Dataset*. [Data set]. Kaggle. <https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyledataset/data>.

### Project Files
- `Sleep_Health_Data_Visualization_files/figure-gfm` - contains the figure data visualizations created in this project.
- `Sleep_Health_Data_Visualization.Rmd` - the Rmarkdown file.
- `Sleep_Health_Data_Visualization.html` - the knitted HTML saved file.
- `Sleep_Health_Data_Visualization.md` - the knitted github document file.

### R Packages
- `tidyverse`
- `ggplot2`

### Methods
- Read-in *Sleep_health_and_lifestyle_dataset.csv*.
- Identified trends within the data through calculated summary statistics.
- Used summary statistics to manipulate the data and draw comparisons between variables.
- Created `ggplot2`data visualizations, including boxplots, scatterplots, and line graphs that represent findings and trends in the dataset.
- Discussion of results.

### Summary
- `Sleep.Duration` medians vary among `Occupation`.
- For both females and males, stress levels decreased with increased amounts of sleep, indicating a negative association between `Stress.Level` and `Sleep.Duration`.
- `Quality.of.Sleep` had a positive association with `Sleep.Duration` for both individuals with sleeping disorders and without. However, for `Insomnia` and `Sleep Apnea`, getting 6 hours of sleep or less greatly lowers `Quality.of.Sleep` compared to individuals without a sleeping disorder.
- Data visualization and exploratory data analysis are key tools to identify and visualize associations and relationships found within data.
