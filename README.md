# ShinyR-DAM

### Authors 
Karol Cichewicz, Jay Hirsh, University of Virginia, Charlottesville, VA

### Short description
ShinyR-DAM is an application for analyzing Drosophila locomotor activity, sleep, and circadian periodicity recorded by the Drosophila Activity Monitor (DAM) system, developed and manufactured by TriKinetics (Waltham, MA). Our program operates in the cloud and can be accessed via this link: https://karolcichewicz.shinyapps.io/shinyr-dam/ , or deployed locally using RStudio. For optimization and grant writing purposes, we track the usage of our app using google analytics java script included in this repository. We do not collect any information about the data processed by our program. 

The source code is divided into the app.R file with the main program structure, and multiple *_ui.R and *_server.R files comprising pairs of the user interface and the algorithms used in the specific tabs of the program. *_ui.R and *_server.R files are sourced in  app.R.

### Testing
For testing, we provide 5 monitor files in this repository. Each monitor file contains data of 32 flies, each representing a unique condition (genotype). There are 5 LD days: 23-06-2017 - 27-06-2017; and 5 DD days: 28-06-2017 - 02-07-2017 in this dataset. Light onset time was set at 6 AM, and acquisition frequency was set to 1 min. 

### Abstract
We developed a web application ShinyR-DAM for analyzing Drosophila locomotor activity, sleep, and circadian rhythms recorded by the Drosophila Activity Monitor (DAM) system (TriKinetics, Waltham, MA). The DAM system measures locomotor activity as infrared beam break counts of flies walking in glass tubes. It allows long-term recording of behavior, making it particularly suitable for circadian biology studies. Comparing with the existing programs for DAM data analysis, ShinyR-DAM substantially decreases the complexity and time required to analyze the data, producing aesthetically pleasing plots, summary tables, and data files for further statistical analysis. Our program has an intuitive graphical user interface that enables novice users to quickly learn the analyses. It runs in a web browser and requires no installation on a local computer, nor programming skills. 

### License
ShinyR-DAM source code is provided under the GPLv3 free software license.

### Current ShinyR-DAM version: 3.1

### R session info:
R version 4.0.2 (2020-06-22)
Platform: x86_64-w64-mingw32/x64 (64-bit)
Running under: Windows 10 x64 (build 18363)

Matrix products: default

locale:
[1] LC_COLLATE=English_United States.1252 
[2] LC_CTYPE=English_United States.1252   
[3] LC_MONETARY=English_United States.1252
[4] LC_NUMERIC=C                          
[5] LC_TIME=English_United States.1252    

attached base packages:
[1] grid      stats     graphics  grDevices utils     datasets  methods  
[8] base     

other attached packages:
 [1] colourpicker_1.1.0 lubridate_1.7.9    data.table_1.12.8 
 [4] gridExtra_2.3      scales_1.1.1       gtools_3.8.2      
 [7] zoo_1.8-8          dplyr_1.0.0        ggplot2_3.3.2     
[10] plyr_1.8.6         shiny_1.5.0       

loaded via a namespace (and not attached):
 [1] Rcpp_1.0.6        pillar_1.4.7      compiler_4.0.2    later_1.1.0.1    
 [5] tools_4.0.2       digest_0.6.25     jsonlite_1.7.2    lifecycle_0.2.0  
 [9] tibble_3.0.1      gtable_0.3.0      lattice_0.20-41   pkgconfig_2.0.3  
[13] rlang_0.4.9       rstudioapi_0.13   curl_4.3          fastmap_1.0.1    
[17] withr_2.3.0       askpass_1.1       htmlwidgets_1.5.3 generics_0.1.0   
[21] vctrs_0.3.0       tidyselect_1.1.0  glue_1.4.1        R6_2.5.0         
[25] purrr_0.3.4       magrittr_2.0.1    promises_1.1.1    ellipsis_0.3.1   
[29] htmltools_0.5.0   rsconnect_0.8.16  mime_0.10         xtable_1.8-4     
[33] colorspace_1.4-1  httpuv_1.5.4      miniUI_0.1.1.1    openssl_1.4.3    
[37] munsell_0.5.0     crayon_1.3.4      Cairo_1.5-12.2


