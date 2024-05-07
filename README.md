# Education-Inequality Project
This project addresses inequality of educational opportunity in U.S. high schools. Here we will focus on the average student performance on the ACT or SAT exams that students take as part of the college application process. We expect a range of school performance on these exams, but we want to find out if school performance is predicted by socioeconomic factors.

## Requirements
Colab 

## Data
Three data sets will be utilized: edgap_data.csv and ccd_sch_029_1617_w_1a_11212017.csv, and internet.csv.

The primary data set is the EdGap data set from EdGap.org. This data set from 2016 includes information about average ACT or SAT scores for schools and several socieconomic characteristics of the school district. All socioeconomic are from the Census Bureau's American Community Survey.

The secondary data set is basic information about each school from the National Center for Education Statistics (https://nces.ed.gov/ccd/pubschuniv.asp). Because this data set is too large for Github, it can be accessed from the Google Drive link: https://drive.google.com/file/d/1HvW2w-o2XZzCm4KTvnb1Bb3BvoAa14BP/view?usp=sharing

The third data set is also from the National Center for Education Statistics which provides estimates of school district social characteristics for school-age children enrolled in public school in the U.S.. This is useful for the additional information we want to determine whether ACT scores are also predicted by students' access to a computer or internet at home.

## Preparation
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

The file "final_ei_data_preparation.ipynb" contains the coding that performs the data preparation, and the results can be found in the "final_clean_ei_data,csv" file, both linked in the repository.

## Analysis
To create visualizations for analysis, the following steps were taken:
  1. Load the clean data and internet then review their contents
  2. State specific questions about the data that can be answered with the visualizations
  3. Perform regression analysis and other various forms of analysis utilizing different graphs
  4. Finalize the chosen visualizations to produce conclusions

The file "ei_analysis.ipnyb" contains the coding that performs the visualization analysis, also linked in the repository. 

## Author
Rica Jane Bayani-Dahilig (me)

## License
MIT License

Copyright (c) 2024 Rica Bayani-Dahilig

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
