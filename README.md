# Solidificação de Níquel 

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-1.21+-013243?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.5+-11557C)
![Pandas](https://img.shields.io/badge/Pandas-1.4+-150458?logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-1.7+-8CAAE6&logo=scipy&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-success)

Projeto desenvolvido para análise e visualização do processo de solidificação de níquel utilizando processamento de imagens e extração de características microestruturais.

## Objetivo

O objetivo deste projeto é explorar técnicas de:

- processamento de imagens científicas;

![gif](https://github.com/eliza-wollinger/solidification-vision/blob/main/assets/gif1.gif)
![gif](https://github.com/eliza-wollinger/solidification-vision/blob/main/assets/gif2.gif)
  
- detecção de interfaces;
  
  ![detect_contour.png](https://github.com/eliza-wollinger/solidification-vision/blob/main/assets/detect_contour.png)
  
- análise temporal da solidificação;

![temporal_soliditication](https://github.com/eliza-wollinger/solidification-vision/blob/main/assets/temporal_solidification.png)
![temporal_vision](https://github.com/eliza-wollinger/solidification-vision/blob/main/assets/temporal_evolution.png)

- visualização científica de dados.

O estudo utiliza sequências de imagens da base:
```
skimage.data.nickel_solidification()
```

## Tecnologias Utilizadas
- Python
- NumPy
- Matplotlib
- scikit-image
- SciPy
- Pandas

## Parâmetros analisados:
- rugosidade;
- espessura;
- conectividade;
- orientação estrutural;
- densidade microestrutural.
