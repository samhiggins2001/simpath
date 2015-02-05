simpath
=======



Framework for in silico modeling of functional genomic experiments in a cellular pathway context.



The tar.gz file contains the R package. 
To install, from the R command line run: 

source("http://bioconductor.org/biocLite.R")
biocLite()
install.packages("packageDir_0.1.tar.gz",  
                type = "source", 
                dependencies=TRUE,
                repos=biocinstallRepos()) 

library(packageDir)

allInteractiveMainFunction() #starts the main interactive function

========
note, this assumes packageDir_0.1.tar.gz is in the working directory; if it is not, set the file path accordingly.
