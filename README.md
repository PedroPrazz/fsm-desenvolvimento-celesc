# FSM - Desenvolvimento Celesc

Repositório oficial de versionamento dos artefatos do FSM do projeto Celesc.

## 🎯 Objetivo
Centralizar:
- FSM Scripts (Mobile e SmartClient)
- Consultas e ajustes SQL
- Sync Rules (XML)
- Integrações Inbound/Outbound
- Documentação técnica e funcional

## 📁 Estrutura
- /fsm-scripts → Scripts FSM Mobile e SmartClient
- /sql → Consultas e ajustes de banco
- /integracoes → Payloads e contratos de integração
- /xml-sync-rules → Regras de sincronização FSM
- /docs → Regras de negócio, padrões e documentação
- /changelog → Histórico de mudanças por mês

## 👥 Governança
### Devs (Write)
- Lucas Silva  
- Lucas Vieira  
- Leibruder  

### Leitura (Read)
- Janyara  
- Arthur  
- Helen  
- Andre  
- Renato Macedo  
- Guilherme  

## ⚠️ Boas práticas
- Não versionar dados sensíveis (URL produtiva, token, senha)
- Sempre documentar mudanças relevantes no changelog
- Commits com padrão:
  - [FSM-MOBILE] ...
  - [FSM-SMARTCLIENT] ...
  - [SQL] ...
  - [INTEGRACAO] ...
  - [DOC] ...