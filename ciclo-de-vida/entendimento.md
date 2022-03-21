# Entendimento do Negócio

## Objetivo
* Identificar as variáveis-chave que devem servir como alvo para o modelo e serão utilizadas para criação de métricas 
  que definirão o sucesso do projeto.
* Identificar as fontes de dados relevantes que o cliente possui ou precisará obter

## Como Realizar
### Como definir os objetivos?

1. **Identificar as varíaveis chaves do negócio** que a análise precisa predizer. Nos referimos a essas variáveis como 
  alvo do modelo e posteriormente usaremos métricas associadas a ela para determinar o sucesso do projeto. (Exemplo de 
  alvos são: Forecast de vendas, ou a probabilidade de uma compra ser fraudulenta).
2. **Definir os objetivos do projeto** fazendo e refinando **perguntas que são relevantes, específicas e claras**. 
  Ciência de dados é um processo que usa nomes e números para responder tais questões. 
  Você geralmente usa DS ou ML para responder a 5 tipos de questões:
   - Quanto(s)? (regressão)
   - Que categoria? (classificação)
   - Que grupo? (agrupamento)
   - É estranho? (detecção de anomalia)
   - Que opção deve ser tomada? (recomendação)
3. **Definir uma métrica de sucesso.** Por exemplo, se você pretende realizar uma previsão de churn. Você precisa de 
  uma taxa de acurácia de "x" porcento até o final de 3 meses de projeto. Com esse dado, você pode oferecer ao cliente 
  promoções para redução de churn. Essa métrica deve ser:
   - Específica 
   - Mensurável
   - Alcançável
   - Relevante
   - Limitada pelo tempo
4. **Definir o time do projeto** especificando as funções e responsabilidades dos seus membros. Desenvolver um plano de 
  marcos (de alto nível) enquanto você descobre mais informações.

### Como identificar as fontes de dados?
Para identificar fontes de dados que contém exemplos conhecidos de respostas para a suas perguntas você precisa 
procurar pelos seguintes dados:
  - Dados que são relevantes para o problema. 
  - Dados que possuam relação com alvo ou que permitam calcular o alvo.


## Artefatos 

1. [**Termo de Abertura de Projeto**:](https://github.com/maetthil/TDSPTemplatePtBr/blob/master/Docs/Project/Termo%20de%20Abertura%20de%20Projeto.md) 
  Esse é um documento vivo, o modelo deve ser atualizado enquanto você realiza novas
  descobertas e os requisitos de negócio mudam. O segredo é iterar esse documento, adicionando mais detalhes enquanto
  realiza o processo de entendimento. Mantenha o cliente e outros stakeholders envolvidos nas alterações e comunique 
  claramente as razões das mudanças.
2. **A seção de fontes de dados brutos do Relatório [Definição de dados](https://github.com/maetthil/TDSPTemplatePtBr/blob/master/Docs/Data_Report/Defini%C3%A7%C3%A3o%20de%20Dados.md)**:
  Mais adiante detalhes adicionais serão preenchidos, por exemplo: scripts para mover os dados para o ambiente 
  analítico.
3. **Dicionário de dados**: Esse documento deve ser fornecido pelo cliente, um diagrama de entidade e relacionamento se 
  disponível também pode ser solicitado.