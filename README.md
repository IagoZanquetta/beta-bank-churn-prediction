# beta-bank-churn-prediction
Projeto de machine learning para prever a evasão de clientes do Beta Bank e apoiar estratégias de retenção.

## Visão Geral

Este projeto tem como objetivo desenvolver um modelo de machine learning capaz de prever a evasão de clientes do **Beta Bank**. A proposta é identificar, com base em características demográficas, financeiras e comportamentais, quais clientes apresentam maior probabilidade de encerrar seu relacionamento com o banco.

A análise busca apoiar decisões de negócio voltadas para retenção de clientes, redução de churn e melhoria na eficiência de campanhas de relacionamento.

## Problema de Negócio

Manter clientes ativos é essencial para a sustentabilidade e crescimento de uma instituição financeira. O **Beta Bank** deseja antecipar quais clientes têm maior risco de evasão para agir preventivamente com estratégias de retenção mais direcionadas.

Para isso, este projeto utiliza técnicas de machine learning para construir e avaliar modelos preditivos capazes de classificar clientes entre aqueles com maior ou menor probabilidade de churn.

## Conjunto de Dados

O conjunto de dados contém informações sobre clientes do banco, incluindo variáveis relacionadas a perfil, histórico e comportamento financeiro, como por exemplo:

- pontuação de crédito
- país
- gênero
- idade
- tempo de relacionamento com o banco
- saldo em conta
- número de produtos contratados
- posse de cartão de crédito
- status de cliente ativo
- salário estimado
- indicador de evasão do cliente

O arquivo utilizado no projeto está organizado na pasta `datasets/`:

- `churn.csv`

## Objetivo do Projeto

Desenvolver um modelo de machine learning capaz de prever a evasão de clientes do Beta Bank, com foco em identificar padrões úteis para antecipação de churn e direcionamento de estratégias de retenção.

## Objetivos da Análise

Este projeto busca responder perguntas como:

- Quais características estão mais associadas à evasão de clientes?
- É possível prever churn com desempenho satisfatório usando machine learning?
- Qual modelo apresenta melhor equilíbrio entre precisão e capacidade de identificar clientes em risco?
- Como os resultados podem ser utilizados para apoiar estratégias de retenção?

## Etapas do Projeto

O projeto foi desenvolvido nas seguintes etapas:

1. carregamento e inspeção inicial dos dados
2. preparação e pré-processamento
3. divisão entre treino, validação e teste
4. treinamento de modelos de classificação
5. ajuste e comparação de desempenho
6. avaliação com métricas apropriadas
7. seleção do modelo final
8. conclusões de negócio

## Ferramentas e Bibliotecas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Estrutura do Repositório

```text
beta-bank-churn-prediction/
├── .gitignore
├── README.md
├── requirements.txt
├── beta_bank_churn_prediction.ipynb
└── datasets/
    └── churn.csv
````

## Como executar

1. Clone este repositório:

   ```bash
   git clone https://github.com/IagoZanquetta/beta-bank-churn-prediction.git
   ```

2. Acesse a pasta do projeto:

   ```bash
   cd beta-bank-churn-prediction
   ```

3. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

4. Abra o arquivo `beta_bank_churn_prediction.ipynb` no Jupyter Notebook, JupyterLab ou VS Code.

5. Execute as células em ordem.

## Principais Pontos Analisados

Entre os principais focos do projeto, estão:

* preparação dos dados para modelagem
* tratamento de variáveis categóricas e numéricas
* comparação entre modelos de classificação
* avaliação de métricas de desempenho
* identificação do modelo mais adequado para o problema
* implicações estratégicas para retenção de clientes

## Resultados

Preparação dos dados, comparação de diferentes modelos de classificação e seleção de uma abordagem adequada para o problema de churn. Demonstração da possibilidade de transformar dados históricos de perfil e comportamento financeiro em suporte prático para decisões de retenção, com destaque para variáveis relevantes na identificação de clientes em maior risco de saída.

O notebook inclui:

* exploração inicial dos dados
* preparação para machine learning
* treinamento e avaliação de modelos
* comparação de desempenho
* seleção do modelo final
* conclusões com foco em negócio

## Conclusão

Este projeto demonstra como técnicas de machine learning podem ser aplicadas para prever a evasão de clientes em um contexto bancário. A construção e avaliação de modelos preditivos permitem transformar dados históricos em suporte prático para decisões estratégicas, ajudando a identificar clientes em risco e a orientar ações de retenção mais eficientes.

## O que foi aprendido

Desenvolvimento e consolidação de habilidades em:
- preparação de dados para machine learning
- tratamento de variáveis categóricas e numéricas
- comparação de modelos de classificação
- avaliação com métricas apropriadas para churn
- interpretação de resultados preditivos em contexto bancário

## Melhorias Futuras

Possibilidades de evolução do projeto:
- testar técnicas adicionais para balanceamento de classes
- ampliar a busca de hiperparâmetros
- incluir análise de importância de variáveis mais aprofundada
- comparar modelos mais avançados de boosting

## Autor

**Iago Zanquetta**
