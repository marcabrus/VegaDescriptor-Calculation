# VegaDescriptor-Calculation
Knime wrapper for Calculation of Descriptors of VEGA models

This workflow contains a metanode for the calculation of all available descriptors contained in VEGA.
It takes a SMILES as input.
You need cdk 1.4.9 and Vega libraries (insilicocore.jar).
You can find them on Vega website (https://www.vegahub.eu/portfolio-item/vega-qsar/).
After you have downloaded Vega unzip the folder and you can find the jars you need in the lib folder. You need then to specify the path of the files in the configuration dialog of the wrapped metanode. Other parameters you need to specify is the column of the smiles and the descriptor blocks you want to calculate.

![alt text](https://github.com/marcabrus/VegaDescriptor-Calculation/blob/master/2019-01-28 (1).png)

