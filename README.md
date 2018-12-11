# BETYdb Manuscript Code, Figures, and Data

This repository provides code and data used in:

LeBauer, David, Rob Kooper, Patrick Mulrooney, Scott Rohde, Dan Wang, Stephen P. Long, and Michael C. Dietze. "BETYdb: a yield, trait, and ecosystem service database applied to second‐generation bioenergy feedstock production." GCB Bioenergy 10, no. 1 (2018): 61-71.  http://onlinelibrary.wiley.com/doi/10.1111/gcbb.12420/full

- The file `gcbb_manuscript.Rmd` provides all of the code used to query data, perform statistical analyses, and generate the result figures in the manuscript.
  - this analysis requires access to the underlying postgres database.  
- The file 'fig4a_with_ropensci_traits_package.Rmd' shows how to reproduce the above queries using the rOpenSci traits package.
More information about accessing data can be found in the documentation (go to betydb.org --> docs --> [data access](https://pecan.gitbook.io/betydb-data-access)).


### Installing a copy of BETYdb 

Either of these methods will allow you to use the code from the original analysis (gcbb_manuscript.Rmd).

#### Using PEcAn VM

This is the easiest way ... and is described in 

You can access virtual machine images here: https://opensource.ncsa.illinois.edu/projects/artifacts.php?key=PECAN

This will provide the database, Rstudio, and more. To get the same data used in the manuscript, use PEcAn v 1.4.9.  


#### using docker compose


1. Install Docker https://docs.docker.com/install/
1. clone this repository `git clone https://github.com/ebimodeling/betydb_manuscript`
2. change into this directory `cd betydb_manuscript`
3. run Docker Componse `docker-compose up`
4. additional details to come ...
