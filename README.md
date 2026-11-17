# ☁️ Resumo do Laboratório DIO: Governança e Infraestrutura Azure

Este repositório documenta os conceitos fundamentais explorados no laboratório da **DIO (Digital Innovation One)** sobre o Microsoft Azure, abrangendo desde a organização de recursos até a escalabilidade de serviços.

---

## 📋 Índice
- [1. Introdução aos Grupos de Recursos](#1-introdução-aos-grupos-chaves-de-recursos)
- [2. Governança e Segurança (Tags e Locks)](#2-governança-e-segurança-tags-e-locks)
- [3. Monitoramento e Logs](#3-monitoramento-e-logs)

---

## 1. Introdução aos Grupos de Recursos

Um **Grupo de Recursos (Resource Group)** é o contêiner fundamental que gerencia o ciclo de vida de recursos relacionados em uma solução no Azure. Ele permite agregar, gerenciar e monitorar serviços como Virtual Machines, VNets e SQL Databases.

Abaixo, visualizamos a estrutura lógica de um Resource Group no Portal do Azure:

> 📸 **Ilustração: Visão Geral de um Resource Group**

> ![](https://learn.microsoft.com/pt-br/azure/azure-resource-manager/management/media/overview/consistent-management-layer.png)
> <br>
> <sub>Imagem reproduzida de: <a href="https://learn.microsoft.com/pt-br/azure/azure-resource-manager/management/overview">Microsoft Learn - Visão Geral do Azure Resource Manager</a></sub>

*O print/diagrama acima ilustra como o Azure Resource Manager (ARM) agrupa logicamente os serviços, facilitando operações como exclusão ou implantação em massa.*


