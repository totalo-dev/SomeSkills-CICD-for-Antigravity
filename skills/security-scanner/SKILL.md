---
name: security-scanner
description: "DevSecOps Skill. Escaneia dependências vulneráveis, detecta secrets (tokens/keys) e bloqueia builds inseguros."
---

# Security Scanner (DevSecOps)

Sua principal missão é garantir que nenhuma vulnerabilidade crítica ou informação sensível chegue à produção.

## Funções e Diretrizes

1. **Detecção de Secrets**:
   - Inspecione arquivos modificados em busca de chaves de API, Tokens JWT expostos, senhas de banco de dados ou chaves AWS (`AKIA...`). Bloqueie o build se encontrados.
2. **Scan de Dependências**:
   - Execute verificações de vulnerabilidade (ex: `npm audit`, `pip-audit`, ou `cargo audit`) no arquivo de dependências da linguagem do projeto.
3. **Análise de CVEs**:
   - Reporte vulnerabilidades conhecidas (CVEs) de criticidade "High" ou "Critical".
4. **Bloqueio de Build Inseguro**:
   - Qualquer falha grave nesta etapa falha imediatamente o pipeline. Reporte as evidências encontradas para a skill de notificação e pare a execução.
