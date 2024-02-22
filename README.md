# Desafio-Lighthouse-Ciencia-de-Dados

## Descrição do projeto
O presente projeto foi desenvolvido por Lucca Carraro Pinilla Eduardo como parte do processo seletivo do programa de formação em dados chamado Lighthouse da empresa Indicium. O desafio em si consiste em desenvolver um modelo de previsão de preços de aluguéis temporários na cidade de New York a partir do dataset "teste_indicium_precificacao.csv", e avaliar tal modelo utilizando métodos de avaliação que mais fazem sentido para o problema. Inicialmente foi feita o tratamento dos dados, análises estatísticas e geração de gráficos com o intuito de responder dúvidas e extrair insights. Após isso, foi feito um modelo preditivo em uma pipeline usando o método Support Vector Regression (SVR) e avaliação de sua performance. Um segundo modelo foi criado a partir da métrica de otimização de hiperparâmetros conhecida como Randomized Search e sua performance foi comparada com a do modelo anterior. A descrição completa do desafio e o dicionário dos dados se encontra no arquivo "[Lighthouse] Desafio Ciência de Dados 2024-4.docx".

## Como instalar e executar o projeto
1. Crie e ative um ambiente virtual
2. Clone o repositório: https://github.com/Lucca-Pinilla/Desafio-Lighthouse-Ciencia-de-Dados
3. No Prompt de comando, acesse a pasta do projeto
4. Instale os pacotes com suas respectivas versões descritas no arquivo "requisitos.txt"
5. Instale um kernel do jupyter nesse ambiente virtual usando o código: ipython kernel install --user --name=[nome_do_ambiente_virtual]
6. Quando usar o Jupyter Notebook no ambiente virtual, selecione o kernel instalado
7. Uma vez no Jupyter Notebook com o arquivo ipynb aberto execute todas as células indo em Cell > Run All.
