# Previsão de Estoque Inteligente na AWS com SageMaker Canvas

## Introdução
Este projeto faz parte do desafio de projeto "Previsão de Estoque Inteligente na AWS com SageMaker Canvas" da DIO. Nele, aplicamos conceitos práticos de Machine Learning (ML) utilizando o SageMaker Canvas para criar previsões de estoque.

## Objetivo
Desenvolver um modelo de previsão de estoque utilizando o SageMaker Canvas e documentar o processo.

## Passo a Passo

### 1. Criação da Conta AWS
Para iniciar, criei uma conta na AWS. Se você ainda não tem uma conta, consulte o [AWS Cloud Quickstart](https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque) para obter ajuda na criação da sua conta.

### 2. Fork do Repositório
Fiz um fork do repositório base fornecido pela DIO:
- Repositório base: [digitalinnovationone/lab-aws-sagemaker-canvas-estoque](https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque)

### 3. Seleção do Dataset
Naveguei até a pasta `datasets` do repositório e escolhi um dataset para treinar o modelo de previsão de estoque. Você pode usar o dataset fornecido ou gerar/enriquecer seus próprios datasets.

### 4. Upload do Dataset no SageMaker Canvas
No SageMaker Canvas:
- Fiz o upload do dataset selecionado.
- Verifiquei e limpei os dados conforme necessário.

### 5. Construção e Treinamento do Modelo
- Importe o dataset para o SageMaker Canvas.
- Configurei as variáveis de entrada (features) e saída (target).
- Iniciei o treinamento do modelo, que pode levar algum tempo dependendo do tamanho do dataset.

### 6. Análise do Modelo
- Após o treinamento, examinei as métricas de performance do modelo.
- Verifiquei as principais características que influenciam as previsões.
- Fiz ajustes no modelo e re-treinei até obter um desempenho satisfatório.

### 7. Previsão
- Usei o modelo treinado para fazer previsões de estoque.
- Exporte os resultados e analisei as previsões geradas.

### 8. Análise dos Resultados
- Analisei os gráficos e as previsões para entender melhor o comportamento do estoque.
- Documentei minhas conclusões e quaisquer insights obtidos a partir das previsões.

## Conclusão
Este projeto demonstrou como utilizar o SageMaker Canvas para criar um modelo de previsão de estoque sem a necessidade de codificação. Foi uma excelente oportunidade para aplicar conceitos de Machine Learning no-code e documentar o processo.

## Recursos Adicionais
- [Documentação Oficial do SageMaker Canvas](https://docs.aws.amazon.com/sagemaker/latest/dg/canvas.html)
- [Guia de Introdução ao SageMaker](https://aws.amazon.com/sagemaker/getting-started/)
- [Tutoriais e Exemplos Práticos](https://aws.amazon.com/sagemaker/resources/)
- [Curso Criação de Modelos de Linguagem na AWS](https://www.digitalinnovation.one)

## Repositório
Você pode encontrar o código e os detalhes do projeto no meu repositório do GitHub:
- [Meu repositório](https://github.com/SEU_USUARIO/lab-aws-sagemaker-canvas-estoque)
