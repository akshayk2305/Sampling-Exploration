# Sampling Definition

--> Sampling in 6 key points:

1. Extracting the essence: Sampling is the art of selecting a representative subset (sample) from a larger group (population) to understand the whole. Imagine tasting a spoonful of soup to gauge the entire pot's flavor.
2. Efficiency matters: Studying the entire population is often impractical or expensive. Sampling allows for quicker, cheaper insights with good planning and execution.
3. Accuracy through representation: A good sample reflects the population's key characteristics. Imagine surveying diverse age groups to understand a community's opinion, not just teenagers.
4. Different flavors, one recipe: Various sampling methods exist, each with its strengths. Random selection gives everyone a fair chance, while stratified sampling ensures specific groups are represented.
5. Size matters, but not always: A larger sample generally brings more accurate results, but diminishing returns occur. A well-chosen smaller sample can be just as informative.
6. Error is inevitable: No sample is perfect, and estimates based on samples will always have some sampling error. Understanding and managing this error is crucial for drawing accurate conclusions.

# Sampling Exploration

Sampling emerges as a crucial method for extracting insights from a community by examining data from a representative subset, eliminating the need to scrutinize every individual data point. To address the initial dataset imbalance, an oversampling technique was employed, given the presence of 763 non-fraudulent cases and a mere 9 fraudulent cases. This involved generating additional instances of the minority class (fraudulent cases) to align with the majority class (non-fraudulent cases), resulting in a unified dataset integrated into a cohesive data frame.

# Dataset and Outcomes

Data Set: Creditcard_data.csv

Outcome: comparison.csv

# Sampling Techniques Used

Random Sampling: Involves the random selection of samples from the population.
Systematic Sampling: Entails selecting samples at regular intervals after a random start.
Cluster Sampling: Involves randomly selecting clusters from the population.
Stratified Sampling: Divides the population into subgroups based on specific criteria.
Bootstrap Sampling: Utilizes resampling with replacement to create multiple samples from the original dataset.

Following the creation of five distinct samples using these techniques, each sample underwent evaluation with five distinct models. The resulting accuracies of each model for a given sample are concisely presented in the table below:

![image](https://github.com/akshayk2305/Sampling-Exploration/assets/97044134/bc74ab79-3e56-444d-99d0-c9010f6e2803)


The table showcases each sampling technique in a row, while columns represent the accuracy achieved by models applied to the respective samples generated using that specific technique.
