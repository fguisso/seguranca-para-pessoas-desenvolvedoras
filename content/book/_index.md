---
title: Sumário
type: docs
weight: 1
prev: /
next: book/intro
---

#### **1. Introdução**
- A importância da segurança para desenvolvedores
- Conceitos fundamentais (Confidencialidade, Integridade e Disponibilidade)

#### **2. Shift Left Security e a Esteira DevOps**
- Segurança no início do ciclo de desenvolvimento
- Como integrar segurança na cultura DevOps

##### **2.1 Modelagem de Ameaças**
- O que é modelagem de ameaças e por que ela é importante
- Como criar diagramas de ameaças
- Ferramentas e metodologias para modelagem de ameaças (STRIDE, Threat Modeling Express)

##### **2.2 Supply Chain**
- Segurança na cadeia de suprimentos de software
- Dependências vulneráveis e ataques à cadeia de software
- Ferramentas para análise de segurança de dependências (SCA)
- Secret Scanning

##### **2.3 SAST (Static Application Security Testing)**
- Como funciona a análise estática de código
- Ferramentas populares de SAST (Semgrep, CodeQL)
- Reduzindo falsos positivos e priorizando correções

##### **2.4 DAST/Pentest**
- Diferença entre DAST e testes de intrusão
- Ferramentas para testes dinâmicos (Nuclei, ZAP)
- Como validar vulnerabilidades encontradas

#### **3. WebApp Security**
- Princípios de segurança para aplicações web
- A importância do desenvolvimento seguro na web

##### **3.1 Protocolos Seguros**
- HTTPS, TLS e segurança em comunicação
- Configurações seguras de cabeçalhos HTTP
- CORS
- Problemas comuns em configurações de segurança

##### **3.2 Gerenciamento de Secrets**
- Problemas de vazamento de credenciais
- Estratégias seguras para armazenamento de secrets
- Ferramentas de gerenciamento de secrets (Vault, Doppler, AWS Secrets Manager)

##### **3.3 Autenticação**
- Autenticação segura: boas práticas
- Autenticação multifator (MFA) e sua importância
- Protegendo sessões e tokens (JWT, OIDC)

##### **3.4 Autorização**
- Diferença entre autenticação e autorização
- RBAC (Role-Based Access Control) e ABAC (Attribute-Based Access Control)
- Protegendo APIs e endpoints contra acessos indevidos

##### **3.5 Vulnerabilidades Comuns**
- Visão geral do OWASP Top 10
- Detalhamento de vulnerabilidades e explorações práticas:
  - **Injeções**: SQL Injection (SQLi), NoSQL Injection, Command Injection
  - **Execução Remota de Código** (RCE) e ataques de Prototype Pollution
  - **Cross-Site Scripting (XSS)** e suas variações (Reflected, Stored, DOM-Based)
  - **Cross-Site Request Forgery (CSRF)** e formas de mitigação
  - **Server-Side Request Forgery (SSRF)** e ataques relacionados
  - **XML External Entity (XXE)**
  - **Configurações incorretas de CORS** e como evitar exposições indevidas
  - **Path Traversal & File Upload**: Ataques relacionados a manipulação de arquivos
  - **WebSockets Vulnerabilities**: Problemas de segurança em comunicação bidirecional

##### **3.6 Encadeando Problemas**
- Como pequenas falhas podem ser combinadas para grandes ataques
- Exemplos reais de exploração de vulnerabilidades em cadeia
- Exercícios práticos de exploração e mitigação de vulnerabilidades encadeadas

#### **4. Next Steps**
- Como manter a segurança como um processo contínuo
- Cultura de segurança e aprendizado contínuo

##### **4.1 Como Cultivar um Ambiente Seguro**
- **Atividades práticas para incentivar segurança entre devs**
  - Dojo Shield: Criando um dojo de segurança na empresa
  - Talks entre o time sobre segurança
  - CTFs internos e rankings para engajamento
- **Participação na comunidade de segurança**
  - Participação em eventos de segurança e tecnologia
  - Grupos e comunidades para aprendizado contínuo

#### **Agradecimentos**
