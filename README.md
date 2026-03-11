# Laboratório de Monitoramento: Zabbix + Docker

Projeto focado em infraestrutura como código (IaC) e monitoramento de ambientes críticos utilizando containers.

## 🚀 Tecnologias Utilizadas
* **Docker & Docker Compose**: Orquestração de microserviços.
* **Zabbix 6.0**: Servidor de monitoramento e coleta de métricas.
* **PostgreSQL 15**: Banco de dados para persistência do Zabbix.
* **Alpine Linux**: Imagens otimizadas para performance e segurança.

## 🛠️ O que foi implementado
* Stack completa (Server, Web, Database e Agent) isolada em rede interna Docker.
* Configuração de **Zabbix Agent** para monitoramento do host.
* Dashboards de monitoramento de performance (CPU/Memória).
* Configuração de **Triggers** e alertas de criticidade.

## 📦 Como rodar o projeto
1. Tenha o Docker e Docker Compose instalados.
2. Clone o repositório: `git clone https://github.com/Claudiosan86/zabbix-docker-lab.git`
3. Na pasta do projeto, suba o ambiente: `docker-compose up -d`
4. Acesse no navegador: `http://localhost` (User: Admin / Pass: zabbix)

---
*Este projeto faz parte do meu portfólio de transição para DevOps.*
