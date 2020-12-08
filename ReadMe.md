Project Purpose: This project is designed to compare the relationship between sea star and mussels abundance data before
and after the occurrence of Sea Star Wasting Syndrome (SSWS)

Packages Required

- dplyr
-ggplot2
-knitr
-tidyr
-gridExtra

Project Directory:

  - Data: consists of the original data sets downloaded off figshare
      
      - change in pisaster and mussels PISCO sites.csv : a dataset that contains changes in abundance of mussels and Pisaster
      at various sites along the California coast
      
      - Copy of mussel_bed_limits.csv : a dataset that contains data on the size and limits of mussel beds
      
      - Copy of MusselSizeAll.csv : a dataset containing data on mussel body sizes
      
      - Copy of Spp_composition_all_years_stacked.csv : a data set containing the species composition of the sites along the 
      California coast
      

- Scripts: contains scripts mostly practice scripts done during 
  
      - reading_data.R : a script used for in-class practice before starting the project
    

      
- Output: Any output files such as HTML files 

  
      - mussels_markdown.html : the final product of the mussels markdown file
      
      - mussels_presentation.html : the final product (slide show) of the mussels presentation file
      
      
  
  - Markdown files: contain .Rmd files including the presentation file for this project
  
      - mussels_markdown.Rmd :  a Markdown file for the project includes code that manipulates the change in pisaster
      and mussels PISCO sites.csv dataset and creates a histogram comparing pre and post mean mussel cover
      
      - mussels_presentation.Rmd : a Markdown file for the presentation of this project, is essentially a newer, working form
      of mussels_markdown.Rmd, contains prose and code
      

 -  Images: contains any pictures used for this project

  
      - Pisaster Predate mussels.jpg : picture of sea stars feeding on bed of mussels
      
      - Seastar_white_lesions.jpg : picture of sea star with SSWS
  
  
  - .gitignore
  
  
  - .Rhistory
  
  
  - ReadMe : contains information about directory and project in general
  
  
  
  Plans for this Project:
  
  1) Create a better looking presentation with simplified code (put into pipes) and easy to read tables
  
  2) Create a graph that effectively and concisely compares mussel cover and sea star density before and after SSWS
  
  3) Look at how change in mussel percent cover varies between regions of West Coast