# Results:

Our analysis revealed:

## Trends and Patterns in Mortality
1. **Youth, Child, and Infant Mortality by Continent**:
   - Africa has the highest youth, child, and infant mortality rates, significantly higher than other continents.
   - Asia follows as the second highest, though considerably lower than Africa.
   - Europe has the lowest mortality rates across all age groups.
   - North America, Oceania, and South America have moderate mortality rates, positioned between Europe and Asia.

2. **Youth, Child, and Infant Mortality by African Countries**:
   - Substantial disparities in mortality rates across different African nations.
   - Some countries like Algeria, Libya, and Mauritius have relatively low rates, while others such as Chad, Central African Republic, and South Sudan have staggeringly high rates.
   - The burden of mortality is not evenly distributed, and certain regions face much greater challenges.

3. **Trends in Nigeria**:
   - Youth mortality rate in Nigeria has steadily declined from 1979 to 2022.
   - Child mortality rate in Nigeria has experienced a significant decline, particularly after the early 2000s.
   - Infant mortality rate in Nigeria showed an upward trend from 1979 to the mid-1990s, followed by a noticeable decline in recent years.

## Healthcare and Vaccination Coverage
1. **Relationship between Healthcare Access and Child Mortality**:
   - A strong negative correlation between the percentage of births attended by skilled health staff and the under-five mortality rate.
   - Linear regression analysis shows that a 1% increase in skilled health staff attendance is associated with a 0.15 decrease in the under-five mortality rate.

2. **Trends in Vaccination Coverage in Africa**:
   - Significant progress in vaccination coverage over the decades, with consistent increases in most vaccines.
   - Plateauing trends in recent years, indicating challenges in maintaining universal immunization.
   - Vaccines like HepB3 and RCV1 show slower adoption compared to others.
   - Declines in vaccination coverage for some vaccines, such as BCG and DTP3, in the late 2010s.

3. **Correlation between Vaccination Coverage and Mortality Rates in Africa**:
   - Most vaccines, particularly MCV1, Pol3, and DTP3, show a strong negative correlation with under-five mortality rates.
   - HepB3 and RCV1 have relatively weak correlations with both infant and under-five mortality rates.
   - High inter-vaccine correlations, suggesting comprehensive vaccination programs being implemented.

## Socioeconomic and Environmental Factors
1. **Relationship between Maternal Mortality and Infant/Child Mortality**:
   - Asia and Africa exhibit a strong positive correlation between maternal and infant/child mortality.
   - Europe and North America show relatively lower maternal and infant/child mortality rates.

2. **Geographical Disparities in Mortality within Africa**:
   - Significant variations in under-five and infant mortality rates across the African continent.
   - Hot spots with the highest mortality rates are concentrated in parts of West and Central Africa, including Chad, Central African Republic, and parts of Nigeria.

3. **Relationship between Health Insurance Coverage and Mortality Rates**:
   - A strong negative correlation between health insurance coverage and under-five mortality rates.
   - Countries with lower health insurance coverage tend to have higher under-five mortality rates.

## Predictive Insights
1. **Predictive Model to Identify High-Risk Regions/Populations**:
   - The Random Forest Classifier model achieved an accuracy of 87% and a high ROC AUC score of 0.983 in distinguishing between high-risk and low-risk regions.

2. **Key Factors Influencing Mortality**:
   - The most significant factors in reducing mortality are:
     1. Births attended by skilled health staff
     2. Share of population covered by health insurance
     3. Estimated maternal deaths
   - Vaccination coverage, while important, has a relatively lower impact compared to healthcare staffing and health insurance.
