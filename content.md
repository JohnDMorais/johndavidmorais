# Perfil

tagline: Security Managed Services Analyst · XDR | EDR | SIEM | LGPD · Fortaleza, CE

sobre: Atuo em segurança da informação conectando quatro frentes complementares: operação (agentes, cobertura e alertas), investigação técnica (telemetria, XQL e análise de evidências), engenharia (dashboards, scripts e automações) e governança (indicadores que apoiam a priorização e a tomada de decisão). Busco aprender continuamente, explorando os detalhes técnicos e compreendendo as diferenças que permitem aprimorar processos e evoluir profissionalmente. Também sou educador desde 2013, experiência que fortalece minha capacidade de explicar conceitos complexos com clareza e compartilhar conhecimento.

# Skills

- EDR / XDR | 92 | Cortex XDR, Cortex XSIAM e Palo Alto Networks Traps: cobertura, estado dos agentes, instalação, desinstalação, conectividade e integridade da proteção.
- XQL & Threat Hunting | 90 | Consultas nos datasets `endpoints`, `alerts` e `xdr_data`; investigação de PowerShell, hashes, BIOC e regras de prevenção.
- Dashboards & Governança | 85 | Transformação de telemetria em KPIs de cobertura, proteção, versões de agentes, vulnerabilidades e tendências de implantação.
- Automação & Desenvolvimento | 82 | Python, Flask, APIs REST, Postman, n8n e PowerShell aplicados à automação e otimização de rotinas de segurança.
- Resposta a Incidentes | 85 | Triagem, investigação, contenção, erradicação e recuperação orientadas por procedimentos e playbooks de resposta.
- SIEM & Threat Intel | 80 | Wazuh, OpenCTI, Microsoft Sentinel, OTX e VirusTotal; retenção de eventos, desempenho do indexador, correlação e inteligência de ameaças.
- Vulnerabilidades & Riscos | 72 | CVEs, classificação de severidade, Tenable Nessus Expert, Patch Manager e processos de remediação.
- Infra, Redes & Identidade | 75 | Active Directory, Oracle Linux, Ubuntu, Windows, proxies, certificados digitais e Cloudflare WAF.

# Arsenal

- 🛡️ Endpoint & XDR: Cortex XDR, Cortex XSIAM, Palo Alto Networks Traps, CrowdStrike Falcon (em aprendizado), Microsoft Defender for Endpoint
- 📡 SIEM & Threat Intel: Wazuh, OpenCTI, Microsoft Sentinel, OTX, VirusTotal, Kaspersky
- 🔎 Vulnerabilidades: Tenable Nessus Expert, CVEs, Patch Manager, Análise de vulnerabilidades
- ⚙️ Dev & Automação: Python, Flask, APIs REST, Postman, n8n, PowerShell, Git, GitHub
- 🖧 Infra & Identidade: Active Directory, Oracle Linux, Ubuntu, Windows, systemd, Apache, PHP, MariaDB, PM2
- 🌐 Redes & AppSec: Cloudflare WAF, Proxies, Certificados digitais, FortiGate

# Experiência

- Security Managed Services Analyst | Accenture | Jul 2026 – Atual | Operação de serviços gerenciados de segurança, com foco em EDR/XDR, SIEM, investigação de alertas, threat hunting, automações e relatórios de KPIs/SLAs.
- Segurança da Informação | Alvoar Lácteos | Ago 2023 – Jul 2026 | Atuação em XDR, EDR, WAF, SIEM, LGPD, gestão de patches, análise de riscos e acompanhamento de controles de segurança.
- Suporte a Redes N2 e N1 | Connect Internet Sem Limites | 2022 – 2024 | Suporte técnico de redes nos níveis N1 e N2, diagnóstico de conectividade e resolução de problemas técnicos.
- Professor | Studio Games Franchising | Fev 2022 – Atual | Ensino de criação de jogos e design utilizando Roblox Studio, Construct 3, GameMaker, Scratch, App Inventor, Figma e ferramentas Adobe.
- Coordenador Acadêmico e Professor de Computação Gráfica | Gracom Escola de Efeitos Visuais | 2021 – 2023 | Coordenação acadêmica e formação de profissionais nas áreas de jogos, computação gráfica e efeitos visuais.
- Coordenador de Ensino e Professor de Informática | Cedaspy Fortaleza | 2017 – 2021 | Supervisão acadêmica de cursos livres de informática, coordenação de atividades educacionais e docência.
- Professor de Informática | CDP Online, Microlins e SOS Tecnologia | 2013 – 2017 | Ensino de informática profissionalizante, computação gráfica, manutenção de computadores e orientação profissional.

# Formação

- 🎓 Tecnólogo em Segurança da Informação | UniFanor Wyden · 2022 – 2024
- 🎓 Bacharel em Sistemas de Informação | Universidade Estácio de Sá · 2014 – 2018
- 🏅 CompTIA Security+ | Security Goals & Controls - Fundamental Security Concepts
- 🏅 Metodologias Ativas | Certificação
- 🛠️ Técnico em Edificações | Apoena · 2015 – 2017
- 💻 Téc. em Sistemas Computacionais | Colégio Elite · 2012 – 2014
- 💾 Operador de Sistemas | CDP Online · 2010 – 2012
- 🌐 Idiomas | Português (nativo) · Inglês (profissional pleno) · Espanhol e Japonês (limitado)

# Projetos

## AgentX: CPU Root Cause Analysis

stack: XQL · Python · it_metrics

tags: XSIAM, Python, EDR

descrição: Investiga o consumo elevado de CPU por componentes do agente de segurança, separando métricas por servidor, analisando médias, picos e volume de amostras e correlacionando os resultados com informações do inventário.

impacto: Diferencia picos pontuais de problemas persistentes de desempenho, fornecendo evidências para análise técnica e investigação de causa-raiz.

## Dashboard de Saúde do Cortex

stack: Flask · XQL · e-mail

tags: Python, XSIAM, Dashboard

descrição: Consolida indicadores de cobertura e proteção, versões antigas de agentes, endpoints desprotegidos e separação entre servidores e estações de trabalho, com envio de informações por e-mail.

impacto: Centraliza indicadores operacionais e diferencia endpoint conectado, agente instalado e endpoint efetivamente protegido.

## Dashboard de Implantação de EDR

stack: Cortex XSIAM · XQL

tags: XSIAM, EDR, Dashboard

descrição: Acompanha a implantação de EDR para um conjunto-alvo de hosts, classificando os estados em online, offline e não instalado. Inclui histórico de implantação e detecções por hora, categorizadas automaticamente em malware, ransomware, comportamento suspeito e exploração.

impacto: Facilita o acompanhamento do rollout, a identificação de lacunas de implantação e a análise das detecções a partir dos dados disponíveis, sem depender de classificação manual prévia.

## Threat Hunting com XQL

stack: Cortex XSIAM · PowerShell

tags: Threat Hunting, XSIAM

descrição: Desenvolve e ajusta consultas para investigação de hashes, caminhos de arquivos, hosts e categorias de alertas. Inclui estudos sobre apagamento do histórico do PowerShell, indicadores BIOC e regras de prevenção.

impacto: Estrutura a investigação com base em evidências, separando a atividade observada, a hipótese investigativa e os controles capazes de detectar ou prevenir o comportamento analisado.

## Automação de SOC

stack: XSIAM · XSOAR · n8n

tags: Automação, SIEM

descrição: Abrange execução de consultas por API, coleta de resultados e automação de fluxos operacionais, incluindo iniciativas de integração do Wazuh com n8n.

impacto: Busca reduzir tarefas repetitivas, padronizar verificações e aumentar a rastreabilidade das atividades de segurança.

## SIEM e Inteligência de Ameaças

stack: Wazuh · OpenCTI

tags: SIEM, Threat Hunting

descrição: Administração e manutenção do Wazuh e OpenCTI, incluindo retenção de eventos, desempenho do indexador, gerenciamento de memória e avaliação de fontes de inteligência como OTX, VirusTotal e Kaspersky.

impacto: Contribui para a estabilidade das plataformas e para a contextualização de indicadores de comprometimento durante as investigações.

## Scorecard Executivo de EDR

stack: Flask · API Cortex XSIAM

tags: Python, XSIAM, Dashboard

descrição: Plataforma web para consolidar o scorecard executivo de EDR, informações de projetos, memorandos e criação de atividades para as reuniões semanais de segurança.

impacto: Centraliza informações para acompanhamento gerencial e busca reduzir o trabalho manual de preparação das reuniões.

## Sanitização do XDR

stack: HTML · JS · JSON local

tags: XSIAM, Automação, Governança

descrição: Registra e acompanha as etapas do projeto de sanitização do ambiente XDR, incluindo remoção de pacotes, desinstalação de agentes e remoção de grupos.

impacto: Proporciona rastreabilidade das etapas do projeto e facilita o acompanhamento das ações executadas.

## POC e Homologação de Agentes

stack: HTML · JS · JSON local

tags: EDR, Dashboard

descrição: Registra por host as etapas de instalação, prova de conceito (POC) e homologação de agentes, organizando evidências e indicadores para apresentação ao cliente.

impacto: Facilita o acompanhamento das homologações, centraliza evidências e agiliza a preparação de informações para apresentações técnicas.

## Plataforma de Grupos de Endpoints

stack: Flask · API Cortex XSIAM

tags: Python, XSIAM, Automação

descrição: Consulta e analisa grupos de endpoints por meio da API do Cortex XSIAM, permitindo filtrar grupos por quantidade de membros e expandir informações de endpoints, endereços IP e grupos relacionados.

impacto: Agiliza a análise de grupos e relacionamentos, reduzindo a necessidade de navegação manual pela console.

## Reorganização por Tags

stack: Governança · Cortex XSIAM

tags: XSIAM, Governança

descrição: Estrutura uma taxonomia de tags baseada em função, infraestrutura, ambiente, criticidade e outros atributos, com o objetivo de orientar a aplicação de Policies e Profiles em vez de depender exclusivamente de grupos.

impacto: Busca tornar a aplicação de políticas mais previsível, padronizada e simples de manter, fortalecendo a governança dos endpoints.
