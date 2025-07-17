# ☁️ Azure: Computação e Serviços de Rede

## 📘 Introdução

O **Microsoft Azure** é a plataforma de nuvem da Microsoft que oferece uma variedade de serviços para computação, rede, armazenamento e mais. Este resumo detalha os principais serviços de **computação**, **rede** e os **modelos de computação em nuvem** disponíveis no Azure.

---

## 🖥️ Modelos de Computação no Azure

O Azure suporta os três principais modelos de computação em nuvem:

### 🔹 IaaS — Infrastructure as a Service
- Modelo mais próximo do hardware tradicional.
- Você gerencia o **sistema operacional, middleware e aplicativos**.
- Exemplo: **Azure Virtual Machines (VMs)**.

### 🔹 PaaS — Platform as a Service
- Modelo gerenciado onde você foca no **desenvolvimento do aplicativo**, sem se preocupar com a infraestrutura.
- O Azure gerencia o SO, rede, servidores e armazenamento.
- Exemplo: **Azure App Service**, **Azure Functions**, **Azure SQL Database**.

### 🔹 SaaS — Software as a Service
- Aplicações completas entregues pela internet.
- Você apenas consome o serviço, sem gerenciar infraestrutura ou plataforma.
- Exemplo: **Microsoft 365**, **Dynamics 365**, **Power BI**.

---

## 🧮 Serviços de Computação do Azure

Os serviços de computação fornecem os recursos para **executar aplicativos e processar dados**.

### ✅ Principais serviços:

- **Azure Virtual Machines (VMs)**
  - Máquinas virtuais personalizáveis.
  - Suporta Windows, Linux, e imagens personalizadas.

- **Azure App Service**
  - Plataforma para **hospedagem de aplicativos web e APIs**.
  - Suporte a várias linguagens: .NET, Node.js, Java, PHP, Python.

- **Azure Functions**
  - Executa **código sob demanda** (modelo serverless).
  - Ideal para tarefas pequenas e eventos.

- **Azure Kubernetes Service (AKS)**
  - Orquestrador de contêineres baseado no Kubernetes.
  - Escala e gerencia clusters automaticamente.

- **Azure Container Instances (ACI)**
  - Executa contêineres rapidamente, sem necessidade de orquestrador.
  - Bom para cargas de trabalho isoladas e temporárias.

---

## 🌐 Serviços de Rede no Azure

Os serviços de rede conectam, isolam e protegem recursos no Azure, permitindo **alta disponibilidade e segurança**.

### ✅ Principais serviços:

- **Azure Virtual Network (VNet)**
  - Cria redes privadas no Azure.
  - Define sub-redes, IPs, DNS e gateways.

- **Network Security Groups (NSGs)**
  - Controlam o tráfego de entrada/saída.
  - Usados para aplicar **regras de firewall** em sub-redes ou VMs.

- **Azure Load Balancer**
  - Balanceia tráfego **entre VMs ou serviços**.
  - Funciona na camada 4 (TCP/UDP).

- **Azure Application Gateway**
  - Balanceador de carga com **WAF (Web Application Firewall)**.
  - Funciona na camada 7 (HTTP/HTTPS).

- **Azure VPN Gateway**
  - Cria uma conexão segura **entre rede local e Azure**.
  - Suporta VPN site-to-site e ponto-a-site.

- **Azure ExpressRoute**
  - Conexão **privada e dedicada**, sem passar pela internet pública.
  - Usada para **alta segurança e desempenho**.

- **Azure DNS**
  - Hospedagem e gerenciamento de **registros DNS públicos e privados**.

---

## ⚙️ Casos de Uso Comuns

- Hospedagem de sites e APIs
- Criação de ambientes de desenvolvimento e testes
- Execução de cargas de trabalho distribuídas
- Migração de data centers locais para a nuvem
- Alta disponibilidade e recuperação de desastres
- Gerenciamento de redes híbridas

---

## ✅ Conclusão

O Azure oferece um ecossistema completo para computação e rede, adequado para qualquer tipo de aplicação — de um site pessoal a um sistema corporativo global. Com os modelos **IaaS, PaaS e SaaS**, é possível escolher o nível de controle e abstração que melhor atende às necessidades do seu projeto.

Você pode começar com máquinas virtuais (IaaS), subir para um serviço de aplicativo (PaaS) e até consumir soluções completas (SaaS) — tudo dentro da mesma plataforma integrada.

---
