# Malaria Incidences in India from 2016-2019

## 1) Overview :

This project is my course project on Data Visualizations Lab. The project aims to visualize Malaria Incidences state-wise and region-wise over years 2016 to 2019. This project is done using **R Markdown** and all the plots uses the **ggplot2** library. The dataset used is taken from the official site for goverment data in India. Refer this [source](https://visualize.data.gov.in/?inst=ac16d8cb-286e-4b6f-b29d-898688904fa0&vid=101827) for the dataset.


## 2) Technical Details :

### Libraries Used :

* plyr
* dplyr
* tibble
* tidyr
* scales
* ggplot2
* devtools
* ggradar
* sp
* rgdal
* units
* sf

The code is written in a way that the libraries will be installed if they are not already present. In particular there is only one library that needs an explicit command on the R Markdown terminal if it throws an error while installation. The **rgdal** library may throw an **error** while installing. To tackle this, extra dependencies needs to be installed through the R terminal. In the **R terminal** type the command **sudo apt-get install gdal-bin proj-bin libgdal-dev libproj-dev**.

### Dataset :

The dataset contains 5 columns with the first column as the name of the States and UTs and the other 4 columns contains 4 years Malaria Count data of the respective States or UTs from 2016 - 2019. The name of the file is **ac16d8cb-286e-4b6f-b29d-898688904fa0.csv** which can be found inside the **Code folder**.

### Report :

The final report can be found in the folder **Report** by the name **204161008-report.pdf**

### Code Execution :

The code file is an R Markdown document by the name **204161008.Rmd** in the folder **Code**. One simply has to **knit** the full notebook to get the output as **204161008.pdf** in the **Code** folder.
This output pdf or the Report will show all the visualizations done for the topic.

### Miscellaneous :

1. One folder named **india_administrative_state_boundary** in the folder **Code** is kept as it contains the indian map file to perform the geographical visualization.
2. **IITG_logo.png** is also kept in the folder **Code** as this image is knitted in the output according to my task.

## 3) Future Developments :

As these visualizations helps in realising the red areas for malria, the same kind of analysis can be done for more mosquito-borne diseases. This can help in administering the geogrophical activities of different types of mosquitoes.
