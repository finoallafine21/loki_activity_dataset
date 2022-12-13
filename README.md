# loki_activity_dataset
This repository contains a data set for human activity recognition

# Information about the dataset
This dataset was created in the course of a research project to make human activity recongition (HAR) suitable for heart rate variability (HRV) measurements. Detailed info provided in the follwoing publication (Link, link will provided after successful publication ;) )

Data was measured between June 2021 and September 2021. Subjects wore a Suunto Movesense HR belt around the chest and perfomed the activities walking, running, sitting, standing, lying and pc work. Data was sampled at 52 Hz for around three minutes. Measurements were conducted in various conditions: indoor, outdor, with and without supervision. (Information about those conditions will be added to the dataset) Detailed information about sex, age, etc. are provided in the table.

# Description of dataset (pkl)
Filename: Loki_dataset.pkl (pandas pickle file format)

columns:
'x': accelerometer x-values
'y': accelerometer y-values
'z': accelerometer z-values
'user': user number (not all labeled) 
'activity': corresponding activity for each data point (string) 'class': same as activity but transfomed into label (scipy)
Note: classes are slightly unbalanced, due to the fact that only a few subjects participated for the activity 'pc'. 

# Contact
If there are any questions regarding the content feel free to write me an email:

lorenz.kiss@hotmail.com

# Referencing/Licensing
Data may be used for educational or scientific purpose

Commerical use of any kind is prohibited

Lorenz Kiss, 2022
