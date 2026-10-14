# Perfil

tagline: Security Managed Services Analyst · XDR | EDR | SIEM | LGPD · Fortaleza, CE
sobre: Atuo em segurança da informação conectando quatro frentes: operação (agentes, cobertura e alertas), investigação técnica (telemetria, XQL e evidências), engenharia (dashboards, scripts e automações) e governança (indicadores que ajudam a priorizar). Busco aprender todos os dias até o menor detalhe, porque é nos detalhes que vemos as diferenças, e nas diferenças, a evolução. Também sou educador desde 2013, o que me ajuda a explicar segurança com clareza.

# Skills

- EDR / XDR | 92 | Cortex XDR e XSIAM, Palo Alto Traps: cobertura, estado dos agentes, instalação, desinstalação e integridade da proteção.
- XQL & Threat Hunting | 90 | Consultas em endpoints, alerts e xdr_data; PowerShell, hashes, BIOC e regras de prevenção.
- Dashboards & Governança | 85 | Transformo telemetria em KPIs de cobertura, versões, vulnerabilidades e tendência de implantação.
- Automação & Desenvolvimento | 82 | Python, Flask, APIs REST, Postman, n8n e PowerShell aplicados a rotinas de segurança.
- Resposta a Incidentes | 85 | Triagem, contenção, erradicação e recuperação seguindo playbooks.
- SIEM & Threat Intel | 80 | Wazuh, OpenCTI, Microsoft Sentinel, OTX e VirusTotal; retenção, indexador e correlação.
- Vulnerabilidades & Riscos | 72 | CVEs, severidade, Nessus, patch manager e remediação.
- Infra, Redes & Identidade | 75 | Active Directory, Oracle Linux, Ubuntu, proxy, certificados e Cloudflare WAF.

# Arsenal

- 🛡️ Endpoint & XDR: Cortex XDR, Cortex XSIAM, Palo Alto Traps, CrowdStrike Falcon (aprendendo), Microsoft Defender for Endpoint
- 📡 SIEM & Threat Intel: Wazuh, OpenCTI, Microsoft Sentinel, OTX, VirusTotal
- 🔎 Vulnerabilidades: Tenable Nessus Expert, CVEs, Patch Manager
- ⚙️ Dev & Automação: Python, Flask, APIs REST, Postman, n8n, PowerShell, Git / GitHub
- 🖧 Infra & Identidade: Active Directory, Oracle Linux, Ubuntu, Windows, systemd, Apache · PHP · MariaDB · PM2
- 🌐 Redes & AppSec: Cloudflare WAF, Proxy, Certificados, FortiGate

# Experiência

- Security Managed Services Analyst | Accenture | Jul 2026 – Atual | Operação de serviços gerenciados de segurança: EDR/XDR, SIEM, resposta a incidentes, threat hunting, automações e relatórios de KPIs/SLAs.
- Segurança da Informação | Alvoar Lácteos | Ago 2023 – Jul 2026 | XDR, EDR, WAF, SIEM, LGPD, Patch Manager e análise de riscos.
- Suporte a Rede N2 e N1 | Connect Internet Sem Limites | 2022 – 2024 | Suporte de rede em dois níveis de atendimento.
- Professor | Studio Games Franchising | Fev 2022 – Atual | Ensino de criação de jogos e design: Roblox Studio, Construct 3, Game Maker, Scratch, AppInventor, Figma e Adobe.
- Coordenador acadêmico e Professor de Computação Gráfica | Gracom Escola de Efeitos Visuais | 2021 – 2023 | Formação de profissionais em jogos e efeitos visuais.
- Coordenador de Ensino e Professor de Informática | Cedaspy Fortaleza | 2017 – 2021 | Supervisão acadêmica de cursos livres de informática e docência.
- Professor de Informática | CDP Online, Microlins e SOS Tecnologia | 2013 – 2017 | Informática profissionalizante, computação gráfica, manutenção de micros e orientação profissional.

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
descrição: Investiga consumo elevado de CPU de componentes do agente de segurança: separa métricas por servidor, analisa média, pico e volume de amostras e correlaciona com o inventário.
impacto: Diferencia pico pontual de problema persistente, com evidência para análise técnica.

## Dashboard de Saúde do Cortex
stack: Flask · XQL · e-mail
tags: Python, XSIAM, Dashboard
descrição: Indicadores de cobertura e proteção, versões antigas de agente, endpoints desprotegidos e separação entre servidores e estações, com envio por e-mail.
impacto: Distingue endpoint conectado, agente instalado e endpoint realmente protegido.

## Dashboard de Implantação de EDR
stack: Cortex XSIAM · XQL
tags: XSIAM, EDR, Dashboard
descrição: Acompanha o rollout de um conjunto-alvo de hosts (online, offline e não instalado), com histórico e detecções por hora categorizadas automaticamente (malware, ransomware, comportamento suspeito, exploração).
impacto: Classificação a partir dos dados disponíveis, sem depender de triagem manual prévia.

## Threat Hunting com XQL
stack: Cortex XSIAM · PowerShell
tags: Threat Hunting, XSIAM
descrição: Consultas para hashes, caminhos, hosts e categorias de alerta; estudo de apagamento de histórico do PowerShell, BIOC e regras de prevenção.
impacto: Separa o que aconteceu, a evidência da hipótese e o controle que previne ou detecta.

## Automação de SOC
stack: XSIAM · XSOAR · n8n
tags: Automação, SIEM
descrição: Execução de consultas por API, coleta de resultados e fluxos de automação, incluindo integração do Wazuh com n8n.
impacto: Menos tarefa repetitiva, verificações padronizadas e mais rastreabilidade.

## SIEM e Inteligência de Ameaças
stack: Wazuh · OpenCTI
tags: SIEM, Threat Hunting
descrição: Administração de Wazuh e OpenCTI: retenção, desempenho do indexador, memória e feeds como OTX, VirusTotal e Kaspersky.
impacto: Plataforma estável e indicadores de comprometimento com contexto.

## Scorecard Executivo de EDR
stack: Flask · API Cortex XSIAM
tags: Python, XSIAM, Dashboard
descrição: Plataforma web que consolida o scorecard executivo de EDR, projetos, memos e criação de atividades para a reunião semanal de segurança.
impacto: Visão única para a gestão e menos preparação manual.

## Sanitização do XDR
stack: HTML · JS · JSON local
tags: XSIAM, Automação, Governança
descrição: Registra e acompanha o projeto de sanitização: remoção de pacotes, desinstalação de agentes e grupos removidos.
impacto: Rastreabilidade de cada etapa do projeto.

## POC e Homologação de Agentes
stack: HTML · JS · JSON local
tags: EDR, Dashboard
descrição: Registro por host de instalação, POC e homologação, com insights prontos para apresentar ao cliente.
impacto: Evidências organizadas e apresentação mais rápida.

## Plataforma de Grupos de Endpoints
stack: Flask · API Cortex XSIAM
tags: Python, XSIAM, Automação
descrição: Filtra grupos por quantidade de membros e expande endpoints, IPs e grupos relacionados via API.
impacto: Análise de grupos em segundos, sem navegar pela console.

## Reorganização por Tags
stack: Governança · Cortex XSIAM
tags: XSIAM, Governança
descrição: Taxonomia de tags (função, infraestrutura, ambiente, criticidade etc.) para aplicar Policies e Profiles em vez de depender de grupos.
impacto: Política mais previsível e fácil de manter.
