
## GeoMongo
<br>

The **GeoMongo** package utilizes methods of the [*PyMongo*](https://github.com/mongodb/mongo-python-driver) Python library to initialize, insert and query GeoJson data. Furthermore, it allows the user to validate GeoJson objects and to use the console for [*MongoDB*](https://www.mongodb.com/) (bulk) commands. The [*reticulate*](https://github.com/rstudio/reticulate) package provides the R interface to Python modules, classes and functions. More details on the functionality of GeoMongo can be found in the [blog post](http://mlampros.github.io/2017/08/07/the_GeoMongo_package/) and in the package Vignette.


<br>

### **System Requirements**

<br>

* [MongoDB (>= 3.4.0)](https://docs.mongodb.com/manual/installation/)

* Python (>= 2.7) [ preferably python 3 because Python 2.7 will reach the end of its life on January 1st, 2020 ]

* [PyMongo](https://github.com/mongodb/mongo-python-driver#installation) (to install use : **python3 -m pip install --upgrade pymongo**)

* [jsonschema](https://pypi.org/project/jsonschema/) (to install use : **pip3 install jsonschema --ignore-installed six**)


<br>

### **Installation of the GeoMongo package**

<br>

To install the package from CRAN use, 

```R

install.packages('GeoMongo')

```
<br>

and to download the latest version from Github use the *install_github* function of the devtools package,
<br><br>

```R

devtools::install_github(repo = 'mlampros/GeoMongo')

```
<br>
Use the following link to report bugs/issues,
<br><br>

[https://github.com/mlampros/GeoMongo/issues](https://github.com/mlampros/GeoMongo/issues)

<br>
