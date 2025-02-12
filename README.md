# Projeto de Previsão de Preços de Aluguéis em Nova York
Este projeto tem como objetivo prever o preço de aluguéis temporários na cidade de Nova York com base em um conjunto de dados fornecido. O modelo foi desenvolvido utilizando técnicas para identificar os principais fatores que influenciam os preços. O trabalho inclui:

1. Análise exploratória de dados (EDA) mais detalhada possível.
2. Implementação de um modelo final para previsão de preços.
3. Relatórios e documentação em Jupyter Notebook.

A respeito dos arquivos, o "teste_indicium_precificacao_dados.csv" contém os dados utilizados para o desenvolvimento do modelo. Ele inclui informações sobre localização, tipo de quarto, disponibilidade, número de reviews, entre outras variáveis que foram fornecidas para a realização do desafio. O modelo preditivo treinado, salvo no formato .pkl, está disponível neste repositório como "model_previsao_precos.pkl".
O modelo escolhido foi o Random Forest, ajustado para capturar as relações não lineares entre as variáveis e fornecer as previsões.
Todo o processo de desenvolvimento está documentado no arquivo Jupyter Notebook EDADesafio.ipynb. Ele contém:

Análise exploratória dos dados (EDA), incluindo gráficos e estatísticas descritivas.

Pré-processamento dos dados, exclusão de dados e codificação de variáveis categóricas.

Visualizações para interpretação dos resultados.

Treinamento do modelo preditivo, incluindo divisão de dados em treino e teste e avaliação do desempenho.

Exemplo de uso do modelo para prever o preço de um apartamento com características específicas do dataset.

Tutorial: Como Rodar o Projeto

1. Pré-requisitos:
Certifique-se de ter o Python instalado.
Instale o anaconda navigator e posteriormente o ambiente Jupyter Notebook, pois grande parte das bibliotecas já serão instaladas.
2. Executar o Notebook:
Abra o Jupyter Notebook para acessar o arquivo EDADesafio.ipynb na pasta que deixou o repositório baixado.
3. Instalação de bibliotecas:
Ao abrir o arquivo no ambiente, tente rodar as importações, caso ocorra um erro de falta de intalações, digite pip install nome_da_biblioteca-que_necessita
4. Teste o código:
Rode o código usando a opção "run" no canto superior esquerdo e escolha se prefere dar "run" em uma célula de cada vez(para compreender melhor) ou aperte "run all cells" para ter acesso ao resultado de todos os códigos em sequência.

Link de vídeo explicativo no driver: https://drive.google.com/file/d/1DIsGLNMAP8NuFQfO6hW3YxXmS7DV7dCU/view?usp=sharing
