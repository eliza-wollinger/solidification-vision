# Solidificação de Níquel 

Projeto desenvolvido para análise e visualização do processo de solidificação de níquel utilizando processamento de imagens e extração de características microestruturais.

## Objetivo

O objetivo deste projeto é explorar técnicas de:

- processamento de imagens científicas;
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
