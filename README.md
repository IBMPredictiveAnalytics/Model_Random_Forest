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
Installation instructions
----
1. Download the extension: [Download][3] 
2. Close IBM SPSS Modeler. Save the .cfe file in the CDB directory, located by default on Windows in *"C:\ProgramData\IBM\SPSS\Modeler\16\CDB"* or under your IBM SPSS Modeler installation directory.
The ProgramData folder is a hidden system folder by default, either you need to turn off "Hidden System Folders" in Folder Options or put the direct path in the toolbar in order to navigate to that folder. 
Another alternative is to place a CFE in the "C:\Program Files\IBM\SPSS\Modeler\17\ext\lib" folder. Modeler will recognize the extension if it is placed here as well. However, you need to have Admin rights to copy a file to that location.
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
- [Video-tutorial][20]

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
[20]:https://www.youtube.com/watch?v=5xXtlusawHo
