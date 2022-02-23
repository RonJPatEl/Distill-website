# Distill-website
My personal website created through R's distill package 

If you are interested in how I created this website feel free to browse the code.

## Automatically generated list of publications

In publications.Rmd I have made use of the Zotero API to generate a list of my publications. I need to build the website whenever I want to update my publications list, but this process allowed me to make use of R's functionality to manipulate data. For example, I use regex to repair variations of my name, and to make my name boldface. In addition journal articles are automatically seperated by year of publication.

It is not the most elegant code. I know I could have made one API call and then split the dataframe based on publication-type. But because I also wanted to split my journal publications based on year I ran into the trouble of three layer nested for loops. I have issues with concentration and small details so I cheated a bit by making API calls per publication type.
