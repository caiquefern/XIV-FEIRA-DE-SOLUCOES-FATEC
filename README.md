# Alaska Airlines Flight 261 — Análise de Acidente Aeronáutico

## Sobre o projeto

Este repositório reúne um estudo técnico e acadêmico sobre o acidente envolvendo o voo **Alaska Airlines 261**, ocorrido em 31 de janeiro de 2000, com uma aeronave McDonnell Douglas MD-83.

O projeto tem como objetivo analisar o acidente sob a perspectiva da manutenção aeronáutica, engenharia, confiabilidade, regulamentação e segurança operacional, buscando compreender como falhas nos processos de manutenção, inspeção, lubrificação, monitoramento e projeto podem contribuir para a ocorrência de acidentes aeronáuticos.

A investigação do NTSB identificou como causa principal a perda de controle longitudinal da aeronave decorrente da falha das roscas da porca Acme do conjunto do parafuso de acionamento (*jackscrew*) do sistema de compensação do estabilizador horizontal. O desgaste excessivo foi consequência da lubrificação insuficiente do conjunto.

---

## Objetivos

- Compreender a sequência de eventos que levou ao acidente.
- Analisar as falhas relacionadas aos procedimentos de manutenção da aeronave.
- Investigar a importância da lubrificação, inspeção e controle de desgaste de componentes críticos.
- Avaliar os requisitos regulamentares aplicáveis à manutenção aeronáutica.
- Desenvolver análises de falhas utilizando ferramentas de engenharia e confiabilidade.
- Compreender a relação entre manutenção preventiva, gerenciamento de manutenção e segurança operacional.
- Identificar oportunidades de melhoria nos processos de manutenção e nos requisitos de projeto.

---

## Estrutura do projeto

### 1. Publicações Técnicas

Análise das publicações técnicas de manutenção aplicáveis ao contexto do acidente, abordando suas funções, utilização e importância para a execução correta das atividades de manutenção.

- Aircraft Maintenance Manual (AMM)
- Illustrated Parts Catalog (IPC)
- Task Cards Manual (TCM / Work Cards)
- Component Maintenance Manual (CMM)
- Maintenance Review Board Report (MRBR)
- Corrosion Prevention Manual (CPM)
- Wiring Diagram Manual (WDM)
- Non-Destructive Inspection Manual (NDI)
- On-Aircraft Maintenance Planning (OAMP / MGM)
- Service Bulletin (SB)
- Airworthiness Directive (AD)
- Information Letters (SNL)

### 2. Requisitos de Manutenção — RBAC 43 e RBAC 145

Análise dos requisitos regulamentares de manutenção e das falhas identificadas na investigação relacionadas aos procedimentos e práticas adotados pela Alaska Airlines.

- Registros de manutenção
- Retorno da aeronave ao serviço após manutenção
- Peças de reposição
- Ferramentas e equipamentos de apoio no solo
- Requisitos de treinamento de manutenção — FAA AC 120-16G

### 3. Requisitos de Projeto Aplicáveis aos Sistemas de Comandos de Voo

Avaliação dos requisitos de projeto aplicáveis ao sistema de compensação do estabilizador horizontal e desenvolvimento de uma árvore de falhas qualitativa e quantitativa.

- RBAC 25 §25.395 — Control System
- RBAC 25 §25.675 — Stops
- RBAC 25 §25.677 — Trim Systems
- RBAC 25 §25.1309 — Equipment, Systems, and Installations

### 4. Lubrificação

Estudo dos procedimentos de lubrificação do conjunto do jackscrew, considerando equipamentos, métodos, especificações e os efeitos da contaminação e mistura de lubrificantes.

- Equipamentos e métodos de lubrificação
- Tipos de tarefas de lubrificação
- Especificações de graxas e normas MIL-G / MIL-PRF
- Mistura de lubrificantes e contaminação
- Limpeza de componentes

### 5. Metrologia

Análise dos métodos de medição utilizados para avaliar o desgaste das roscas e a folga axial do conjunto, considerando procedimentos realizados na aeronave e em bancada.

- Medição de desgaste das roscas
- Métodos de inspeção não destrutiva (Raio-X e Ultrassom)
- Medição da folga axial (*End Play*)
- Procedimentos On Aircraft e Off Aircraft (Bench)

### 6. Materiais e Corrosão

Estudo dos materiais utilizados no conjunto do sistema de compensação do estabilizador horizontal e dos mecanismos de corrosão que podem afetar sua integridade.

- Dissimilaridade entre eixo e porca trapezoidal
- Aço inoxidável e alumínio-bronze
- Tubo de torque de titânio
- Corrosão galvânica
- Corrosão puntiforme (*Pitting*)
- Controle e prevenção de corrosão
- CPCP — Corrosion Prevention and Control Program
- Proposta de programa de manutenção preventiva com base na FAA AD 99-22-08 e FAA AC 43-4B

### 7. MSG-2

Aplicação da metodologia MSG-2 na análise do sistema de compensação do estabilizador horizontal, considerando a classificação das tarefas de manutenção aplicáveis ao conjunto do eixo.

- Hard Time (HT)
- On-Condition (OC)
- Condition Monitoring (CM)

### 8. MSG-3

Desenvolvimento de análises de sistemas, estruturas e zonas relacionadas ao sistema de compensação do estabilizador horizontal.

- Teste Operacional versus Teste Funcional
- Análise do MSI — Maintenance Significant Item
- Análise do SSI — Structural Significant Item
- Análise zonal da região de instalação
- Acessibilidade e densidade da área de instalação
- Determinação dos intervalos de tarefas
- Análise dos intervalos de manutenção praticados pela Alaska Airlines e sua aprovação pela FAA

### 9. Peças de Reposição

Análise da necessidade de aprovisionamento de peças sobressalentes para o conjunto do jackscrew, considerando dados de confiabilidade, vida limite e tamanho da frota.

- Estimativa de estoque para a Alaska Airlines (48 aeronaves)
- Estimativa de estoque para a Boeing (1.194 aeronaves)
- Estimativa de custos com base no preço de referência de US$ 80.000 por conjunto
- Conceito de aprovisionamento inicial e recorrente
- Alternativas para reposição de componentes
- Estimativa de contrato PBH (*Power by the Hour*)

### 10. Custos de Manutenção

Avaliação dos custos relacionados às tarefas de manutenção do sistema de compensação do estabilizador horizontal.

- Custos associados ao Check C
- Reserva de manutenção
- Custos de manutenção preventiva
- Custos de inspeção, reparo e substituição do conjunto do eixo

### 11. Monitoramento da Frota em Serviço

Análise dos dados de confiabilidade e acompanhamento do desempenho do sistema de compensação do estabilizador horizontal ao longo da operação.

- Dados de confiabilidade do sistema
- Análise das taxas de falha dos componentes do conjunto do eixo
- Extensão dos intervalos de manutenção periódica
- Extensão dos intervalos de lubrificação e Check C pela Alaska Airlines
- Atuação e aprovação da FAA

### 12. Conclusão

Consolidação dos resultados obtidos ao longo do estudo, destacando os principais fatores contribuintes para o acidente, as falhas de manutenção identificadas e as lições aplicáveis à manutenção aeronáutica e à segurança operacional.

---

## Referências principais

- **NTSB — National Transportation Safety Board**  
  Aircraft Accident Report: *Loss of Control and Impact with Pacific Ocean — Alaska Airlines Flight 261*

- **FAA — Federal Aviation Administration**  
  Regulamentos e documentos técnicos aplicáveis à manutenção, certificação e segurança operacional.

- **RBAC — Regulamentos Brasileiros da Aviação Civil**  
  Regulamentos aplicáveis às atividades de manutenção e aos requisitos de certificação de aeronaves.

- **FAA AC 43-4B** — Corrosion Control for Aircraft

- **FAA AC 120-16G** — Air Carrier Maintenance Programs

- **FAA AD 99-22-08** — Diretiva relacionada aos requisitos de manutenção aplicáveis ao contexto analisado.

---

## Equipe AERO MECS

Projeto desenvolvido pela equipe AERO MECS, composta por:

- Alan Douglas
- Caíque Fernandes
- Ryan Ferraz

**Curso:** Manutenção de Aeronaves  
**Projeto:** Análise do acidente Alaska Airlines Flight 261 (2000)

## Disclaimer

Este repositório possui finalidade exclusivamente acadêmica e educacional. As análises, interpretações e propostas apresentadas não substituem manuais oficiais de manutenção, documentação técnica aprovada, diretrizes de aeronavegabilidade ou procedimentos estabelecidos pelos fabricantes e autoridades aeronáuticas.

---

**Projeto acadêmico — Manutenção de Aeronaves**  
Estudo de caso: Alaska Airlines Flight 261 (2000)
