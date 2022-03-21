# Implantação

## Objetivo
Realizar a implantação dos modelos junto com os pipelines para a produção ou um ambiente semelhante para o ultimo 
estágio do TDSP

## Como Realizar
### Como operacionalizar o Modelo?
Os seguintes pipelines deverão ser operacionalizados para que possam ser executados no ambiente do cliente: 
- Pipeline de Dados
- Pipeline de Scoring
- Pipeline de Treinamento do Modelo

Dependendo dos requisitos do negócio, o dados poderão ser processados em tempo real ou em lotes.\
Para realizar o deploy você expõe os modelos com uma interface de API, para que sejam consumidos por diversas 
aplicações como:
- Websites online
- Planilhas
- Dashboards
- Aplicações line-of-business
- Aplicações back-end


_É uma boa prática registrar logs e monitorar o modelo e o pipeline implantado._

## Artefatos 

[**Relatório de modelagem final**](https://github.com/maetthil/TDSPTemplatePtBr/blob/master/Docs/Model/Relat%C3%B3rio%20Final.md): 
Um relatório de modelagem final com os detalhes do modelo implantado.
**Dashboard de Monitoramento**: Um dashboard de status que mostra as métricas chaves e a saúde do sistema.
**Arquitetura da Solução Final**: Diagramas atualizados demonstrando a arquitetura da solução que foi implantada.