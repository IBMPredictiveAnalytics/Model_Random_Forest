# Model for Random Forest 
###IBM SPSS Modeler Predictive Extensions

Node for classification and regression based on a forest of trees using random inputs, utilizing conditional inference trees as base learners. Simply install the node, choose the target and predictors and specify additional settings. 

<img align="center" src="https://github.com/IBMPredictiveAnalytics/Modeler_RandomForest/blob/master/Screenshot/Illustration3.png?raw=true" alt="map stream">

![Map](https://github.com/IBMPredictiveAnalytics/Modeler_RandomForest/blob/master/Screenshot/Illustration2.png?raw=true)

---
Requirements
----
- IBM SPSS Modeler v16.0 or later
- IBM SPSS Modeler 'R Essentials'
- R 2.15.x or R 3.1

More information here: [IBM Predictive Extensions][2]


---
Installation intructions
----
1. Download the extension: [Download][3] 
2. Close IBM SPSS Modeler. Save the .cfe file in the CDB directory, located by default on Windows in *"C:\ProgramData\IBM\SPSS\Modeler\16\CDB"* or under your IBM SPSS Modeler installation directory.
3. Restart IBM SPSS Modeler, the node will now appear in the Model palette.

---
R Packages used
----
The R packages will be installed the first time the node is used as long as an Internet connection is available.
- ['party'][4]

---
Documentation and samples
----
- Find a PDF with the documentation of this extension in the [Documentation][5] directory
- There is a sample available in the [example][6] directory

---
License
----

[Apache 2.0][1]


Contributors
----

  - Armand Ruiz ([armand_ruiz](https://twitter.com/armand_ruiz))


[1]: http://www.apache.org/licenses/LICENSE-2.0.html
[2]:https://developer.ibm.com/predictiveanalytics/downloads/#tab2
[3]:https://github.com/IBMPredictiveAnalytics/ModelRandomForest/raw/master/Source%20code/randomforest.cfe
[4]:http://cran.r-project.org/web/packages/party/
[5]:https://github.com/IBMPredictiveAnalytics/ModelRandomForest/blob/master/Documentation/RandomForest-SPSSModelerExtension.pdf
[6]:https://github.com/IBMPredictiveAnalytics/ModelRandomForest/tree/master/Example
