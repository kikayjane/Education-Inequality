# Education-Inequality Project
This project addresses inequality of educational opportunity in U.S. high schools. Here we will focus on the average student performance on the ACT or SAT exams that students take as part of the college application process. We expect a range of school performance on these exams, but we want to find out if school performance is predicted by socioeconomic factors.

## Data
Two data sets will be utilized: EdGap_data.xlsx and ccd_sch_029_1617_w_1a_11212017.csv. 

The primary data set is the EdGa data set from EdGap.org. This data set from 2016 includes information about average ACT or SAT scores for schools and several socieconomic characteristics of the school district. All socioeconomic are from the Census Bureau's American Community Survey.

The secondary data set is basic information about each school from the National Center for Education Statistics (https://nces.ed.gov/ccd/pubschuniv.asp). Because this data set is too large for Github, it can be accessed from the Google Drive link: https://drive.google.com/file/d/1HvW2w-o2XZzCm4KTvnb1Bb3BvoAa14BP/view?usp=sharing

## Data Preparation
To prepare the data for visualization, the following steps were taken:
  1. Describe the source of the data
  2. Explore the contacts of the data sets
  3. Convert the columns to the necessary types
  4. Select relevant subsets of the data
  5. Rename columns
  6. Join data frames
  7. Check the dataset for out-of-range (impossible/unphysical) values and remove them
  8. Split the dataset into a training and test dataset using an appropriate split ratio
  9. Impute the missing data

The file "ei_data_preparation.ipynb" contains the coding that performs the data preparation, and the results can be found in the "clean_education_inequality_data,csv" file, both linked in the repository.
