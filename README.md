# ☁️ AZ-900 – Computação e Rede no Microsoft Azure

![Azure](https://img.shields.io/badge/Microsoft-Azure-0089D6?logo=microsoftazure&logoColor=white)
![Licença](https://img.shields.io/badge/Licen%C3%A7a-MIT-blue)
![Curso](https://img.shields.io/badge/Curso-AZ--900-blueviolet)


---

<p align="center">
  <img src="https://learn.microsoft.com/en-us/media/learn/modules/describe-azure-compute-networking-services/azure-compute-networking.svg" width="450">
</p>

---

## 📑 **Sobre este Repositório**

Este repositório reúne um resumo de temas tratados no **Curso da DIO - Formação Microsoft AZ-900 Certification - Módulo 2 – Arquitetura e Serviços do Azure**, com foco em:

- Serviços de **computação**
- Serviços de **rede**
- **DNS**, **ExpressRoute**, **VPN**
- **Azure Functions**

---

## 🧭 **Sumário**

- [Visão Geral](#visão-geral)
- [Serviços de Computação](#serviços-de-computação)
- [Hospedagem de Aplicações](#hospedagem-de-aplicações)
- [Rede Virtual do Azure](#rede-virtual-do-azure)
- [ExpressRoute](#expressroute)
- [DNS do Azure](#dns-do-azure)
- [Referências](#referências)

---

## 🌐 **Visão Geral**

O Azure oferece serviços de computação e rede altamente escaláveis, seguros e sob demanda.  
Este módulo aborda:

- Tipos de computação (VMs, contêineres, funções)
- Requisitos e opções de máquinas virtuais
- Pontos de extremidade públicos e privados
- Redes virtuais, VPNs e ExpressRoute
- DNS do Azure

---

## ⚙️ **Serviços de Computação**

### 🖥️ Máquinas Virtuais (VMs)
- Emulação completa de computadores físicos  
- Controle total sobre SO, rede e armazenamento  
- Ideal para migrações *lift-and-shift*

### 📈 Conjuntos de Dimensionamento (VMSS)
- Escalabilidade automática horizontal  
- Balanceamento de carga integrado  

### 🛡️ Conjuntos de Disponibilidade
- Redução de indisponibilidade  
- Distribuição entre domínios de falha e atualização  

### 🖥️💨 Área de Trabalho Virtual do Azure (AVD)
- Virtualização de desktops e aplicativos  
- Múltiplas sessões simultâneas  
- Sem necessidade de servidores de gateway  

### 📦 Contêineres e Kubernetes
- **ACI**: execução rápida sem gerenciar infraestrutura  
- **Container Apps**: escalonamento automático  
- **AKS**: orquestração completa de contêineres  

### ⚡ Azure Functions (Serverless)
- Execução baseada em eventos  
- Sem necessidade de servidores  
- Escalabilidade automática  
- Cobrança por execução  

---

## 🌍 **Hospedagem de Aplicações**

### Azure App Service
- Plataforma totalmente gerenciada  
- Suporte a: .NET, Java, Python, Node.js, PHP  
- Escalabilidade, segurança e conformidade corporativa  

---

## 🕸️ **Rede Virtual do Azure**

### 🔌 Pontos de Extremidade
- **Públicos**: acessíveis pela internet  
- **Privados**: acessíveis apenas dentro da VNet  

### 🧩 Sub-redes e Emparelhamento
- Segmentação da rede  
- Conexão privada entre VNets  

### 🔐 VPN Gateway
- Comunicação criptografada entre Azure e ambiente local  
- Usa a internet pública  

---

## ⚡ **ExpressRoute**

<p align="center">
  <img src="https://learn.microsoft.com/en-us/media/learn/modules/describe-azure-compute-networking-services/expressroute.svg" width="450">
</p>

O **ExpressRoute** cria conexões privadas entre o Azure e o ambiente local, sem passar pela internet.

**Benefícios:**
- Menor latência  
- Maior segurança  
- Alta confiabilidade  
- Suporte a BGP  
- Redundância nativa  

---

## 🌐 **DNS do Azure**

### Principais recursos:
- Alta disponibilidade e desempenho  
- Rede Anycast global  
- Suporte a domínios privados  
- Registros de alias que acompanham mudanças de IP  
- Segurança via RBAC e logs  

---

## 📚 **Referências**

- Azure Functions  
  https://learn.microsoft.com/training/modules/describe-azure-compute-networking-services/6-functions  
- Azure DNS  
  https://learn.microsoft.com/training/modules/describe-azure-compute-networking-services/12-domain-name-system  
- ExpressRoute  
  https://learn.microsoft.com/training/modules/describe-azure-compute-networking-services/11-expressroute  

---

## 🧩 **Extras**

### Temas abordados:
- IaaS  
- PaaS  
- Serverless  
- Virtualização  
- Redes privadas virtuais  
- DNS e conectividade híbrida  

---

### 📷 Imagens utilizadas
Todas as imagens são da documentação oficial Microsoft Learn.

---

## 🤝 Contribuições

Pull Requests são bem-vindos!  
Sinta-se à vontade para sugerir melhorias ou adicionar novos conteúdos relacionados ao AZ-900.

---

## 📄 Licença

Distribuído sob a licença **MIT**.
