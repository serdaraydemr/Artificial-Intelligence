# Artificial Intelligence

In this repo, you can reach the codes that I will start from the basics and write at a professional level to improve myself in the field of artificial intelligence. In general, I will share my work in the field of artificial intelligence in health in this repo.


1 - fethal_healthy1 : 

Data Summary :

Reduction of child mortality is reflected in several of the United Nations' Sustainable Development Goals and is a key indicator of human progress.
The UN expects that by 2030, countries end preventable deaths of newborns and children under 5 years of age, with all countries aiming to reduce under‑5 mortality to at least as low as 25 per 1,000 live births.

Parallel to notion of child mortality is of course maternal mortality, which accounts for 295 000 deaths during and following pregnancy and childbirth (as of 2017). The vast majority of these deaths (94%) occurred in low-resource settings, and most could have been prevented.

In light of what was mentioned above, Cardiotocograms (CTGs) are a simple and cost accessible option to assess fetal health, allowing healthcare professionals to take action in order to prevent child and maternal mortality. The equipment itself works by sending ultrasound pulses and reading its response, thus shedding light on fetal heart rate (FHR), fetal movements, uterine contractions and more.

The dataset has 2126 rows and 22 columns. There is no missing data in the data set. All values in the dataset are numerical.

Three classes are defined as target variables. These are respectively 1 : 'Normal' , 2 : 'Suspect', 3 : 'Pathological'. There are 1655 results from the Normal class, 295 from the Suspect class, and 176 from the Pathological class.

Applied Model:

An attempt was made to get results by training the XGBoosting algorithm. The F-1 Score table will be used to evaluate the results. The most important variables for the model will be decided by using Random Forest Algorithm.
