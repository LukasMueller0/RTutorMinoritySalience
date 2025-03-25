This package constitutes an interactive R problem set based on the RTutor package (https://github.com/skranz/RTutor). 

The problem set "Minority Salience and Political Extremism – An Interactive Analysis with R" is based on the article  "Minority Salience and Political Extremism" from Tommaso Colussi, Ingo E. Isphording and
Nico Pestel. The paper examines the impact of increased minority salience during Ramadan on voting outcomes in the state of North Rhine-Westphalia. The article, appendix, and data are available at:

https://www.aeaweb.org/articles?id=10.1257/app.20190703

## 1. Installation

RTutor and this package is hosted on Github. To install everything, run the following code in your R console.
```s
install.packages("RTutor",repos = c("https://skranz-repo.github.io/drat/",getOption("repos")))

if (!require(devtools))
  install.packages("devtools")

devtools::install_github("LukasMueller0/RTutorMinoritySalience")
```

## 2. Show and work on the problem set
To start the problem set first create a working directory in which files like the data sets and your solution will be stored. Then adapt and run the following code.
```s
library(RTutorMinoritySalience)

# Adapt your working directory to an existing folder
setwd("C:/problemsets/RTutorMinoritySalience")
# Adapt your user name
run.ps(user.name="Jon Doe", package="RTutorMinoritySalience",
       auto.save.code=TRUE, clear.user=FALSE)
```
If everything works fine, a browser window should open, in which you can start exploring the problem set.
