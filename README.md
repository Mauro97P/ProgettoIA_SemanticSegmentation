# ProgettoIA_SemanticSegmentation

<p align="center">
  <img src="https://github.com/Mauro97P/ProgettoIA_SemanticSegmentation/blob/main/8-50_con_background.png" style="height: 200px;>
</p>


<p align="center">
<img src="https://github.com/Mauro97P/ProgettoIA_SemanticSegmentation/blob/main/8-50_solo_maschere.png" style="height: 200px;">
</p>


La **segmentic segmentation** è un processo applicato alle immagini per la classificazione di ogni pixel in una specifica classe, cioè per ogni singolo pixel bisogna capire a che oggetto appartiene. 
Per entrambi i modelli (grandi capacità e mobile) è stato deciso di utilizzare un’architettura U-Net.

Data Augmentation -> Albumentations (libreria Python)


| Modello        | Loss     |
| ----------- | ----------- |
| U_Net      | IoU       |  128x128  |
| MobileNetV2      | IoU     |  128x128  |


