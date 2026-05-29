# NeuralNetworks_project_work
Project work of kroucnik and laubeann in the module NeuralNetworks. <br>
The aim of this project is to create a classifier capable of distinguishing between artists based on composition, colours, artstyle/-movement, brushwork and other visual characteristics.
<br>
## Dataset
This project used [this](https://www.kaggle.com/datasets/ikarus777/best-artworks-of-all-time?resource=download) dataset from kaggle containing a total of 8446 images of paintings from 50 different artists. 
<br>
**Important note**: The dataset contains 2 folders of Albrecht Dürer. Which needs to be preprocessed in the following way before running the Jupyter Notebook:<br>
**-->** Delete one folder, they contain the same images<br>
**-->** Rename the other folder to *Albrecht_Durer*. The ü causes issues.<br>
<br>
## Requirements
The following libraries are needed to run this project:
<br>
```bash
tensorflow keras numpy pandas matplotlib scikit-learn pillow
```
<br>
## Link to github repository
The GitHub of this project can be found [here](https://github.com/Kroucil/NeuralNetworks_project_work).
