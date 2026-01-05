## Atividades Executadas

- Criação e edição de dashboards APM no Dynatrace, organizados por fluxos de negócio
  (ex: login, validação de usuário e listagens).

- Configuração e análise de métricas de latência utilizando percentis (P75 e P90),
  com foco em identificar degradações de experiência do usuário.

- Identificação e marcação de Key Requests para endpoints críticos, priorizando
  solicitações com maior impacto no fluxo da aplicação.

- Análise detalhada de serviços monitorados via APM, incluindo drilldown de
  Service → Request para avaliação de tempo de resposta, throughput e dispersão
  entre instâncias.

- Apoio à análise de incidentes e degradações, utilizando janelas temporais
  para identificação de picos e comportamento anômalo antes do escalonamento técnico.


> Observação:
> As imagens utilizadas neste documento foram anonimizadas e têm caráter ilustrativo,
> com o objetivo de demonstrar atividades técnicas realizadas em ambiente corporativo,
> respeitando confidencialidade e boas práticas de segurança da informação.

## Análise Realizada

Durante a análise do fluxo de login, foram observados aumentos de latência
nos percentis P75 e P90, concentrados em requisições específicas marcadas
como Key Requests.

A investigação foi conduzida via Dynatrace APM, permitindo:
- Drilldown por serviço
- Identificação de endpoints ofensores
- Correlação com volume de requisições
- Apoio ao time de desenvolvimento na tomada de decisão
