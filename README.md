# ⚡ SecOps Automation Suite & Cloud SIEM Lab

Projeto focado na implementação de um SIEM em nuvem (Microsoft Sentinel) e no desenvolvimento de uma suíte de automação customizada. O ecossistema simula ingestão de logs, threat hunting e resposta a incidentes (IR) em infraestruturas críticas.

## 🏗️ 1. Arquitetura do Laboratório (Híbrido)

O ambiente centraliza a telemetria de fontes On-Premise e Cloud no Log Analytics, com monitoramento contínuo via Sentinel.

<p align="center">
  <img src="Untitled diagram _ Mermaid Chart-2025-09-28-231653 - Copia.png" width="850">
</p>

## 🛡️ 2. Plataforma SIEM: Microsoft Sentinel

### Visualização e Dashboards (Workbooks)
Ativação de Workbooks interativos para monitoramento do **Microsoft Entra ID** e **Azure Activity**.
<p align="center">
  <img src="imagem (2) (1).png" width="850">
</p>

### Threat Hunting com KQL
Uso de Kusto Query Language para identificação de anomalias e estabelecimento de baselines de atividade.
<p align="center">
  <img src="imagem (1) (1).png" width="850">
</p>

### Detecção em Tempo Real
Validação de regras de análise com incidentes reais gerados automaticamente.
<p align="center">
  <img src="imagem (6).png" width="850">
</p>

## ⚡ 3. Suíte de Automação Customizada (DevSecOps)

### Security Ops Dashboard (GUI PowerShell / WPF)
Interface gráfica desenvolvida para centralizar a triagem de sistemas, auditoria de Active Directory e coleta de logs, otimizando o MTTR.
<p align="center">
  <img src="imagem (3) (1).png" width="850">
</p>

## 🔄 4. Fluxo de Resposta a Incidentes (IR)

Integração tática entre detecção em nuvem e resposta no host através de scripts automatizados.
<p align="center">
  <img src="Untitled diagram _ Mermaid Chart-2025-09-28-231826.png" width="850">
</p>

---
**Certificações Relacionadas:** SC-300, SC-200, AZ-500.
