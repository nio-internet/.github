# 🌐 GitHub | V.tal
[![Powered by Platform Engineering](https://img.shields.io/badge/Powered%20by-Platform%20Engineering-%230083FF)]() [![Crafted by Engineering Squads](https://img.shields.io/badge/Crafted%20by-Engineering%20Squads-blueviolet)]() [![InnerSource Collaboration](https://img.shields.io/badge/InnerSource-Collaboration-brightgreen)]() [![CI/CD](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-blue)]() [![GitOps Enabled](https://img.shields.io/badge/GitOps-enabled-brightgreen)]() [![Security](https://img.shields.io/badge/Security-by--design-red)]() [![Developer Experience](https://img.shields.io/badge/Developer%20Experience-Golden%20Path-yellow)]() [![FinOps Culture](https://img.shields.io/badge/FinOps-Culture-lightgrey)]()

Bem-vindo ao espaço oficial da engenharia da [NIO](https://github.com/nio-internet) no GitHub.

Este ambiente concentra os repositórios de tecnologia da **V.tal** — produtos digitais, serviços de plataforma e ativos compartilhados de engenharia.

> Escopo desta organização: **somente NIO**.  
> Repositórios da holding e de outras empresas do grupo (como **V.Tal, NIO e Tecto**) serão estruturados em organizações dedicadas.

---

## 🚀 Propósito

Consolidar um ambiente único para desenvolvimento, versionamento e operação dos ativos digitais da NIO, com foco em:

- Escala de entrega com qualidade
- Padronização com autonomia dos times
- Governança técnica e segurança desde o design
- Colaboração entre squads com InnerSource

---

## 🧱 O que você encontra aqui

- Repositórios de **produtos e serviços digitais** da NIO
- **Templates e aceleradores** para criação de novos projetos
- Pipelines e componentes de **plataforma de engenharia**
- Padrões reutilizáveis de **CI/CD, observabilidade e segurança**
- Boas práticas para ciclo de vida completo: build, test, release e operação

---

## 🧱 Golden Path

A NIO adota o conceito de *Golden Path* como base para aceleração do desenvolvimento. Repositórios com `template-` no nome contêm scaffolds prontos para:

- APIs em Java Spring Boot com OTEL, CI/CD e Docker seguro
- Workers em Go e Python
- Serviços com mensageria (Kafka, Pub/Sub, RabbitMQ)
- Jobs de dados e ML com Airflow e Vertex AI

---

## 🔁 GitOps e Infraestrutura

A entrega de infraestrutura segue o padrão **GitOps**, com repositórios versionados e reconciliados por ArgoCD ou Crossplane. Todos os componentes seguem práticas de:

- Infraestrutura como código (IaC) com Terraform e YAML
- Pipelines de CI/CD reutilizáveis com GitHub Actions
- Observabilidade nativa com OTEL e Datadog

---

## 📌 Convenções

- **Commits:** Padrão [Conventional Commits](https://www.conventionalcommits.org/)
- **Branches:** GitHub Flow (`main` como branch principal)
- **Pipelines:** armazenadas em `.github/workflows/`
- **Segurança:** código analisado com GHAS e SonarQube
