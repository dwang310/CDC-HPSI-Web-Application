# CDC HPSI Web Application Mini-tutorial
*Tested & working on R version 3.3.0*

The following tutorial assumes that you have installed R and R-studio.
## How do I setup HPSI?
**Installation -** Before we begin running HPSI, we need to make sure that all of the dependencies are installed on R. 
I have made this easier by creating two installation scripts located within the `init` folder. Within the `init` folder 
you will find two scripts called `init_libraries.R` and `install_script.R`. The `init_libraries.R` script simply just
loads all installed dependencies that the application will need in order to run. The `install_script.R` script will install
all the necessary dependencies that are needed within `init_libraries.R`. You will first want to source the `install_script.R`
and then the `init_libraries.R` file. To do this simply run the following commands:
``` 
source("install_script.R")
source("init_libraries.R") 
```



## Application Layout


