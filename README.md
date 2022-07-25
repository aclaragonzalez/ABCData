# ABCData

O projeto consiste em uma extração de propriedades químicas de compostos a partir de arquivos de saída de dois softwares (Gaussian e Orca) utilizados na Química Computacional. A extração dessas propriedades visa reunir dados em uma base hospedada no MongoDB. Os cálculos realizados por esses softwares, embora forneçam resultados precisos, possuem um alto custo porque cada molécula demanda dias de cálculo. Desse modo, a construção de uma base de dados de propriedades químicas pode ser um ponto de partida para predição dessas propriedades através de modelos de Machine Learning.

## Etapas do projeto
Este projeto será dividido em três etapas:
* Extração dos dados utilizando a biblioteca [cclib](https://cclib.github.io/) diretamente no terminal:
* [Limpeza e organização dos dados obtidos a partir do Gaussian](https://github.com/aclaragonzalez/ABCData/blob/main/json_gaussian.ipynb)
* [Limpeza e organização dos dados obtidos a partir do Orca](https://github.com/aclaragonzalez/ABCData/blob/main/organizando_json_from_orca.ipynb)
