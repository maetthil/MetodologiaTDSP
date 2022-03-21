# Aquisição e Entendimento dos Dados

## Objetivo
* Produzir um conjunto de dados limpo e de alta qualidade na qual as relações com a variável alvo são conhecidas.
* Desenvolver uma arquitetura para a solução do pipeline de dados que irá receber e processar novos dados regularmente.

## Como Realizar
### Como produzir um conjunto de dados limpo?

1. Definir o processo de **movimentação dos dados** das fontes para a localização de destino onde serão 
  executadas as operações analíticas, como treinamento e previsões.
2. Realizar uma **exploração de dados** para determinar se a qualidade do dado é adequada para responder a questão. 
  É nessa etapa que você:
   1. Desenvolverá um bom entendimento dos dados
   2. Irá sumarizar e visualizar os dados para entender a qualidade e gerar toda informação necessária antes de estar
     pronto para modelagem
   3. Poderá determinar se existe dado suficiente para prosseguir para os próximos passos

### Porque é necessário definir um pipeline de dados?

Um pipeline de dados é definido para processar novos dados ou atualizar os dados regularmente como parte de um processo de 
aprendizado contínuo.
* Nessa fase é definida uma arquitetura da solução do pipeline de dados.
* Essa fase pode ser feita em paralelo com o próximo estágio do projeto de ciência de dados (Modelagem). 

## Artefatos 

* [**Relatório de Dados**](https://github.com/maetthil/TDSPTemplatePtBr/blob/master/Docs/Data_Report/Relat%C3%B3rio%20de%20Dados.md):
  Esse relatório inclui um resumo de qualidade dos dados, relações entre cada atributo e o alvo, ranking de 
  variáveis, etc.
* **Arquitetura da solução**: A arquitetura da solução pode ser representada em forma de diagrama ou descrição do pipeline 
  de dados que será usado para previsão em novos dados após o treinamento do modelo. O documento deve ficar no diretório
  Projeto do TDSP.
* **Decisões checkpoints**: Antes de começar a modelagem e engenharia de variáveis, é possível reavaliar o projeto para 
  determinar se o valor esperado é suficiente para continuar a execução. Você poderá tomar as seguintes decisões:
  - Estar pronto para prosseguir
  - Precisar coletar mais dados
  - Abandonar o projeto já que não existe dado para responder a questão