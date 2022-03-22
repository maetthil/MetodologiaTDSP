# Modelagem

## Objetivo
* Determinar as melhores variáveis para o modelo de machine learning
* Definir um modelo Baseline
* Criar um modelo de machine learning e compará-lo com um Baseline:
  * É informativo e prediz o alvo de forma acurada?
  * É adequado para produção?
* Avaliar se o modelo se comporta de forma injusta (Fairness) 

## Como Realizar
### Como pré-processar os dados para o modelo?
Podemos realizar engenharia de variáveis para criar variáveis a partir dos dados brutos e facilitar o 
treinamento do modelo, isso envolve todo tipo de transformação, inclusão e agregação de variáveis brutas para criar 
variáveis utilizadas posteriormente. É nessa tarefa que usaremos todo conhecimento gerado nas fases anteriores 
(Entendimento do Negócio e Aquisição e Entendimento dos Dados). Isso é importante pois:
  * Ajuda a entender como as variáveis se relacionam entre si e como os algoritmos irão utilizar essas variáveis
  * Encontramos um balanceamento entre descobrir variáveis informativas e ao mesmo tempo evitar muitas variáveis não 
    relacionadas

### Como criar um modelo Baseline?
[comment]: <> (Abordar futuramente em detalhes essa questão)

### Como treinar o modelo?

Nessa tarefa será escolhido uma classe de algoritmos para trabalhar, o algoritmo escolhido irá depender dos dados.
O processo de treinamento inclui:
- **Escolha de uma estratégia de validação**: Como os dados irão ser separados entre conjunto de dados de treino, 
  validação e teste 
- **Construição do modelo**: Construir o modelo utilizando os dados de treino
- **Avaliação do modelo**: Avaliar o modelo no conjunto de dados de validação enquanto otimiza os hiperparâmetros e
  posteriormente nos dados de teste.
- **Determinar a "melhor" solução**: Realizar uma comparação da métrica de sucesso entre modelos alternativos 

### O que é Fairness em IA?

Iremos utilizar a biblioteca Fairlean para esse tipo de avaliação. Um sistema de IA pode comportar-se de forma injusta 
por uma variedade de razões. No Fairlean, um sistema de IA é dito injusto se ele se comporta de forma injusta em termos
do seu impacto nas pessoas - ou seja, em termos de danos. Dois tipos de dados são observados:

* **Danos de alocação**: Estes danos podem ocorrer quando o sistema de IA favorece ou desfavorece oportunidades, recursos, 
ou informações. Algumas das principais aplicações são em contratações, admissão escolar e empréstimos.
* **Danos de qualidade de serviço**. A qualidade do serviço refere-se a se um sistema funciona tão bem para uma pessoa 
como para outra, mesmo que nenhuma oportunidade, recursos, ou informação sejam favorecidos, ou desfavorecidos.


### O que é Data Leakage?
[comment]: <> (Abordar futuramente em detalhes essa questão)

## Artefatos 

* [**Relatório Baseline**](https://github.com/maetthil/TDSPTemplatePtBr/blob/master/Docs/Model/Baseline/Relat%C3%B3rio%20Baseline.md):
  Relatório descrevendo detalhes sobre o método utilizado como Baseline
* [**Relatório Modelo**](https://github.com/maetthil/TDSPTemplatePtBr/blob/master/Docs/Model/Model%201/Relat%C3%B3rio%20Modelo.md):
  Relatório descrevendo detalhes sobre o modelo treinado
* **Avaliação de fairness**: O que podemos concluir sobre o modelo em relação a injustiça?
* **Decisões checkpoints**: Avaliar se o modelo está suficientemente bom para implantação
  * O modelo responde a questão com confiança suficiente utilizando os dados de teste?
  * Devemos coletar dados adicionais, realizar mais engenharia de dados ou experimentos com outros algoritmos?
  * Devemos testar outras métricas?
  
[comment]: <> (Interpretação do modelo: - Gerar um relatório que explica o comportamento do modelo nos dados locais e em nuvem - Providenciar técnicas de interpretabilidade para as variáveis criadas)
