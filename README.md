# soc-lab-wazuh
My study environment in cybersecurity
SOC Lab com Wazuh – Detecção e Resposta a Incidentes

Objetivo: Criei este laboratório para simular, na prática, o dia a dia de um SOC (Security Operations Center), com foco em monitoramento, análise de eventos e resposta a incidentes.

Desenvolver habilidades e melhorar meu conhecimento em:

Análise de logs
Investigação de alertas
Triagem de incidentes (nível N1)
Tomada de decisão baseada em evidências
Também usei esse projeto como forma de transição da minha experiência em suporte técnico para a área de segurança.

Arquitetura do Ambiente

O ambiente foi montado com máquinas virtuais simples, simulando um cenário real:
Wazuh Server (Ubuntu Server) → responsável por coletar e analisar os eventos
Windows 11 (Endpoint) → máquina monitorada com agente
Kali Linux (Atacante) → usado para simular comportamentos maliciosos

Fluxo:
Kali → gera atividade → Windows → envia logs → Wazuh → gera alertas

Tecnologias Utilizadas:

Wazuh (SIEM)
Ubuntu Server
Windows 11
Kali Linux
VirtualBox / VMware

Durante o laboratório, simulei situações comuns do dia a dia de um analista SOC:

Tentativas de força bruta (Brute Force)
Logins suspeitos
Execução de processos incomuns
Varredura de rede (Port Scan)

Cada cenário foi documentado com:

O que aconteceu ?
Evidências coletadas
Logs analisados
Interpretação do incidente
Ação tomada

Resultados:

