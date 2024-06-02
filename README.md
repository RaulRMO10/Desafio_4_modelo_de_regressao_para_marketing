# Desafio de Machine Learning: Predição de Vendas

Desenvolvi um modelo de Regressão Linear para prever o coeficiente de determinação (r²) e calcular o retorno de vendas a partir de investimentos em três plataformas de publicidade: YouTube, Facebook e jornais.

## Etapas do Projeto

### 1. Análise Descritiva

- Verificação de dados nulos e duplicados
- Verificação dos formatos dos dados
- Exibição de informações gerais e estatísticas

### 2. Análise Exploratória

**Insights:**

- YouTube recebeu mais investimentos, seguido por jornais e Facebook.
- Investimentos maiores no YouTube e Facebook aumentam a probabilidade de aumento nas vendas.
- Investimentos em jornais têm menos correlação com o retorno de vendas.
- Média de vendas: aproximadamente R$16,000.

### 3. Desenvolvimento do Modelo

- Divisão dos Dados: 80% treino, 20% teste
- Método: `train_test_split` do scikit-learn

### 4. Resultados

- Coeficiente de Determinação (r²): 87,29% de confiabilidade

Este projeto envolveu uma análise detalhada dos dados, criação e avaliação de um modelo de Regressão Linear, resultando em uma predição altamente confiável.
