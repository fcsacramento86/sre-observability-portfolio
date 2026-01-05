# Zabbix – Monitoramento e Observabilidade

Este diretório apresenta evidências e descrições de atividades realizadas com **Zabbix** em ambientes corporativos, com foco em monitoramento de disponibilidade, serviços web e operação contínua de infraestrutura crítica.

As imagens têm caráter **ilustrativo e anonimizado**, respeitando práticas de segurança da informação.

---

## Atividades Executadas

- Configuração e manutenção de **Web Scenarios** para monitoramento sintético de aplicações web, simulando acessos reais a endpoints críticos (ex: páginas de login).

- Definição de **steps HTTP** com validação de status code (HTTP 200), garantindo a verificação objetiva de disponibilidade e resposta correta da aplicação.

- Configuração de **timeouts controlados**, prevenindo falsos positivos e ajustando o monitoramento ao comportamento esperado do serviço.

- Associação de Web Scenarios a **hosts produtivos**, permitindo correlação direta entre indisponibilidade de serviço e infraestrutura monitorada.

- Gestão operacional de **hosts no Zabbix**, incluindo:
  - Criação e edição de hosts
  - Organização por grupos (Produção, Banco de Dados, Servidores)
  - Configuração de interfaces de monitoramento (Agent, Proxy)
  - Remoção controlada de hosts obsoletos ou desativados

- Atuação em ambientes com grande volume de monitoramento, envolvendo:
  - Centenas de itens
  - Dezenas de triggers
  - Múltiplos gráficos e regras de descoberta

---

## Análise Realizada

A partir da configuração dos Web Scenarios, foi possível:

- Validar a **disponibilidade contínua** de serviços web críticos
- Detectar falhas de acesso antes do impacto percebido pelo usuário final
- Apoiar a operação NOC/SRE na **identificação rápida de indisponibilidades**
- Garantir maior confiabilidade no monitoramento de aplicações expostas via HTTP

O uso de validação por status code e controle de timeout contribuiu para alertas mais precisos e acionáveis.

---

## Benefícios para o Negócio

- Redução do tempo de detecção de falhas em aplicações web
- Maior confiabilidade na operação de serviços críticos
- Apoio à continuidade do negócio através de monitoramento proativo
- Melhoria na eficiência do time operacional (NOC/SRE)
- Base sólida para tomada de decisão durante incidentes

---

> **Observação:**  
> As imagens utilizadas neste documento foram anonimizadas e não representam ambientes reais em produção.  
> O objetivo é demonstrar práticas técnicas aplicadas em contexto corporativo, sem exposição de dados sensíveis.

