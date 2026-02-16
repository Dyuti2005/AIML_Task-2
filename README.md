Task 2: Exploratory Data Analysis (EDA) - Titanic Dataset
Objective
To analyze the Titanic dataset to discover the "survival signatures"—the characteristics that most accurately predicted whether a passenger survived.

 Key Steps & Findings
Missing Value Audit: Identified that Age has significant missing values (177) and Cabin is mostly empty, requiring strategic handling in Task 1.
Survival Drivers: * Gender: Females had a significantly higher survival rate (>70%) compared to males (<20%), supporting the "women and children first" historical account.
Socio-Economic Status: Passengers in 1st Class (Pclass 1) had much higher survival rates than those in 3rd Class.
Fare Outliers: Discovered extreme outliers in the Fare column (prices up to 512), suggesting that high-paying passengers were prioritized.
Age Trends: Infants (Age <5) had higher survival rates, while the majority of deaths occurred in the 20-40 age bracket.

Visualizations Included
Histograms: To observe the age demographic of the ship.
Heatmaps: To show the correlation between Sex, Pclass, and Survived.
KDE Plots: To visualize the density of survivors vs. non-survivors across different ages.
