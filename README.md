# Alura Challenge: Data Science 1ª Edição <!-- omit from toc -->
![Badge em Desenvolvimento](https://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge) ![License MIT](https://img.shields.io/github/license/vinszrt/alura-voz?style=for-the-badge&color=GREEN)

Este repositório tem o propósito de armazenar os arquivos e registrar o progresso no desenvolvimento do Challenge de Data Science 1ª Edição da Alura. 

O desafio pode ser conferido [aqui](https://www.alura.com.br/challenges/data-science/). Há no arquivo [README-Alura-Team.md](./README-Alura-Team.md) mais informações do desafio e sobre o time que desenvolveu o desafio. O repositório original do desafio está disponível em: 

[![Badge em Desenvolvimento](https://img.shields.io/badge/github-sthemonica%2Falura--voz-blue?style=plastic&logo=github)](https://github.com/sthemonica/alura-voz/)

# Índice <!-- omit from toc -->
- [1. Introdução](#1-introdução)
- [2. Etapas](#2-etapas)
- [3. Contribuições](#3-contribuições)
- [4. Autor](#4-autor)
- [5. Licença](#5-licença)

# 1. Introdução

O desafio proposto é atuar como cientista de dados na empresa fictícia de telecomunicações, "Alura Voz". O objetivo é diminuir o Churn Rate da empresa. Para isso, será utilizada uma base de dados obtida a partir de uma API, analisada e tratada para treinamento de um modelo de Machine Learning para classificação dos clientes afim de obter melhores resultados na tomada de decisão da empresa.

# 2. Etapas

O desafio se divide em 3 etapas:
1. [Limpeza dos dados trazidos de uma API](01.%20Limpeza%20dos%20dados/)
2. [Exploração dos dados](02.%20Exploração%20dos%20dados/)
3. [Criação de modelo de Machine Learning](03.%20Modelo%20de%20Machine%20Learning/)

A partir de uma [base de dados](Dados/Telco-Customer-Churn.json) em formato JSON extraída de uma API, a primeira etapa será a limpeza desses dados. Para isso, será preciso entender as informações do conjunto de dados (para auxiliar, foi fornecido um [Dicionário de Dados](Dados/dicionario.md)), analisar os tipos de dados, verificar as inconsistências e corrigi-las.

Na etapa seguinte, o objetivo será explorar os dados, identificar e analisar a variável Target (Churn), visualizando sua distribuição e analisando a correlação entre as variáveis.

Por último, será desenvolvido um modelo de Machine Learning para classificar os clientes, identificando-os como sendo ou não potenciais candidatos a deixarem a empresa. Esse modelo deverá ser avaliado e otimizado para melhorar os resultados.

# 3. Contribuições
Contribuições são sempre bem-vindas. Se você deseja contribuir, por favor, abra uma issue ou envie uma pull request.

# 4. Autor
| <img src="https://github.com/vinszrt.png" width="150px"> |
| -------------------------------------------------------- |
| [Vinicius N. Zorzetti](https://github.com/vinszrt)       |

# 5. Licença 
Este projeto está licenciado sob a [licença MIT](LICENSE).