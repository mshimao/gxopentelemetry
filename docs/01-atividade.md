# Atividade 1

Vamos entender um pouco o conceito de observabilidade e elementos de sofware que fazem parte da implementação da observabilidade no Genexus.

### Observabilidade

Observabilidade em uma aplicação é a capacidade de entender o estado interno de um sistema apenas observando suas saídas. Isso é especialmente importante em ambientes de produção, onde você não tem acesso direto ao sistema. A observabilidade é alcançada através de três pilares principais: logs, métricas e rastreamento distribuído.

Logs são registros de eventos que ocorreram no sistema. 
Métricas são medidas quantitativas do comportamento do sistema ao longo do tempo. 
Rastreamento distribuído é a capacidade de acompanhar uma solicitação à medida que ela passa por vários serviços.

Esses três pilares permitem que os desenvolvedores e operadores entendam o que está acontecendo dentro de um sistema, identifiquem problemas e otimizem o desempenho.

### Observabilidade no Genexus

O Genexus implementou recursos de observabilidade a partir da versão 18 upgrade 5:
- [Observabilidade no Genexus](https://wiki.genexus.com/commwiki/wiki?53773,Observability+in+GeneXus+Apps)

Configurando o Genexus adequadamente uma aplicação gerada pelo Genexus pode exportar logs, métricas e traces para que sejam apresentados em aplicações de monitoramento como Grafana, Azure Application Insigths, entre outros.

### Grafana

Grafana é uma plataforma de análise e visualização de dados de código aberto. É comumente usada para visualizar séries temporais de dados de infraestrutura e aplicativos e criar painéis com gráficos ricos. Com Grafana, você pode criar alertas, notificações e ad-hoc explorar seus dados além de apenas visualizá-los. É muito usada em conjunto com outras ferramentas de observabilidade para monitorar o desempenho e a saúde de aplicações e sistemas.



