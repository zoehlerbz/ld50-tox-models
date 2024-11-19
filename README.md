# Modelos ANN preditivos de LD<sub>50</sub>

Este projeto utiliza Redes Neurais Artificiais (ANNs) para prever a toxicidade aguda (LD<sub>50</sub>) de compostos químicos em diferentes espécies e rotas de administração, com base em dados obtidos do banco de dados [TOXRIC](https://toxric.bioinforai.tech/home).

## Conjunto de dados

Os dados de toxicidade aguda incluem informações estruturais e valores de LD<sub>50</sub>, organizados em quatro conjuntos:

- Toxicidade Aguda em Camundongo por via oral (*n=27.209*)
- Toxicidade Aguda em Camundongo por via intravenosa (*n=20.441*)
- Toxicidade Aguda em Rato por via oral (*n=12.547*)
- Toxicidade Aguda em Rato por via intravenosa (*n=3.242*)

Os arquivos de dados brutos podem ser obtidos no diretório **./dados**.

***
### Avaliação dos modelos

Os resultados de MSE, MAE e R2 dos modelos para cada variação das *features* podem ser encontrados nos arquivos ***_modelos.xlsx** no diretório raíz.

***
### Validação dos modelos

Os resultados de validação dos modelos de melhor desempenho podem ser encontrados no diretório **./validacao**.