# Shiny Tutorial

This shiny tutorial uses {learnr} package to create an interactive tutorial. The tutorial is designed to help you learn the basics of shiny within a shiny application.

## Getting started

1. Clone this repository and open the `shiny-tutorial.Rproj` file in RStudio.  
2. To install all necessary packages, run the following command in R:

```r
paks <- c("learnr", "rmarkdown", "DT")
install.packages(paks)

``` 

3. Open the `shiny_tutorial.Rmd` 
4. Execute the shiny tutorial using the button `Run the document`
5. Follow the steps and complete the exercises  

## Run the tutorial alongside your shiny project

To be able to develop a shiny application alongside an active shiny tutorial, 2 options are available:
- run the tutorial in the background locally  
- run the tutorial on binder  

### Run the tutorial in the background locally

You need to follow some extra-steps:

1. Stop and close any previous shiny tutorial that is running
2. Create a new shiny project within RStudio
  - `File -> New File -> Shiny Web App -> Multiple File`
3. In the newly created shiny project, go to `Background jobs` tab and click on `Start  background job` to create a new background job
4. Select `run_in_background.R` R script on clicking the `Browse` button
5. Select the `shiny-tutorial` folder as the working directory on clicking the `Browse` button
6. Click on `Start Job` to run the shiny tutorial in the background
7. Copy the returned URL mentioned after `Listening on ` string corresponding to this pattern `http://127.0.0.1:<port_number>`
8. Paste the URL in a new window browser to start the tutorial
9. Follow the steps and complete the exercises 
  - if you had already begun the tutorial, you can continue from where you left off (learnr keeps track of your progress)  
  - you may want to start over the tutorial if so click on `Start Over` button in the sidebar (`caution`: it will reset all your progress in the tutorial)      
10. Continue working within the current shiny project

### Run the tutorial on binder  

Click on the following badge to run the tutorial on binder, it will open a new tab in your browser and you can start the tutorial from there:
  
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jos4uke/shiny_tutorial.git/main) 
  
Be patient, it could take a while to deploy the tutorial code on mybinder.org.  
