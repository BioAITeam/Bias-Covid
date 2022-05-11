# Bias-Covid
Dataset and experiments from "Biases associated with database structure for
COVID-19 detection in x-ray images" \cite
## Cohen Datasets
On this folder are the Images from Cohen dataset with the respective dataset from [ieee8023/covid-chestxray-dataset](https://github.com/ieee8023/covid-chestxray-dataset) also on Divided Sets is found the metadata of each of the set of the experiment used on notebook Cohen experiment.ipynb, but also those datasets are separated and saved on NPY files on the NPY files folder.
## Notebooks 
### Cohen experiment.ipynb 
this notebook contains the development of a classification model using the Cohen dataset and a VGG19 the result of this notebook is save in df_pred1.csv for its use on the Ethical tool Aequitas on Aequitas Notebook.ipynb
### Aequitas Notebook.ipynb
this notebook containes the test of the Cohen experiment on the Ethical Tool Aequitas using its python library \cite but this can also be develop using its web app \cite for doing this we use the dataset named midterm.csv, the reason to change this file is because there are some metrics of the tool that result in NaN values and on python library a previous change on metric is develop before plotting but on web tool this is not posible so the data change, still the results are extremelly simillar and can be found on - Aequitas - The Bias Report - aequitas.dssg.io (1).pdf
