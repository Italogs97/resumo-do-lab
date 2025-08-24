# ☁️ Resumo – Tipos de Serviços em Nuvem (IaaS, PaaS, SaaS)

Este documento é um resumo do que eu entendi sobre os **modelos de serviços em nuvem** mais comuns: **Infraestrutura como Serviço (IaaS)**, **Plataforma como Serviço (PaaS)** e **Software como Serviço (SaaS)**.  

---

## 🔹 Introdução
A computação em nuvem oferece diferentes níveis de serviços, permitindo que empresas escolham **o quanto querem gerenciar** e **o quanto querem delegar ao provedor de nuvem**.  
Cada modelo traz vantagens específicas de **flexibilidade, custo e agilidade**.

---

## 🖥️ IaaS (Infrastructure as a Service)
- Fornece **infraestrutura de TI sob demanda**, como servidores, redes, armazenamento e virtualização.  
- Usuário é responsável por gerenciar **sistema operacional, aplicativos, dados e configuração de rede**.  
- **Exemplo:** Azure Virtual Machines, Amazon EC2.  

📌 **Quando usar:**  
- Migração de cargas de trabalho locais para a nuvem.  
- Hospedagem de aplicações que exigem controle total do ambiente.  
- Ambientes de teste e desenvolvimento escaláveis.  

---

## ⚙️ PaaS (Platform as a Service)
- Fornece uma **plataforma pronta para desenvolvimento e implantação de aplicações**.  
- O provedor gerencia a **infraestrutura, SO, banco de dados e middleware**, enquanto o usuário foca apenas no **código e lógica de negócio**.  
- **Exemplo:** Azure App Service, Google App Engine.  

📌 **Quando usar:**  
- Desenvolvimento rápido de aplicações.  
- Ambientes de CI/CD.  
- Projetos que precisam escalar sem se preocupar com infraestrutura.  

---

## 📦 SaaS (Software as a Service)
- Entrega **aplicativos prontos para uso**, executados e gerenciados totalmente pelo provedor.  
- Usuário só precisa acessar via navegador ou app, sem preocupação com manutenção.  
- **Exemplo:** Microsoft 365, Gmail, Salesforce.  

📌 **Quando usar:**  
- Ferramentas de produtividade.  
- Softwares de colaboração e comunicação.  
- Qualquer serviço que precise ser usado de forma prática e rápida.  

---

## 📊 Comparação Geral
| Modelo | Gerenciado pelo Provedor | Gerenciado pelo Usuário | Exemplos |
|--------|--------------------------|--------------------------|----------|
| **IaaS** | Hardware, rede, armazenamento | SO, apps, dados, config | Azure VM, AWS EC2 |
| **PaaS** | Infraestrutura + SO + DB | Código e dados do app | Azure
