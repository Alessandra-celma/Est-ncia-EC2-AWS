# 🚀 AWS EC2: Gerenciamento de Instâncias

Este repositório contém anotações e explicações práticas sobre o **Gerenciamento de Instâncias EC2 na AWS**, realizadas durante o desafio da [DIO](https://www.dio.me).

---

## 📌 O que é uma Instância EC2?
Uma instância **EC2 (Elastic Compute Cloud)** é uma **máquina virtual** dentro da nuvem da Amazon, onde você pode rodar sistemas operacionais (Linux, Windows) e hospedar aplicações.

Gerenciar essa instância significa cuidar de todo o seu ciclo de vida: criação, configuração, segurança, monitoramento e encerramento.

---

## 🔧 Passos de Gerenciamento

### 1. Provisionamento
- Escolha do tipo de instância (CPU, memória, armazenamento).
- Seleção da AMI (Amazon Machine Image).
- Definição de **VPC**, **sub-rede** e **Security Groups**.

### 2. Configuração
- Instalação de softwares necessários.
- Conexão via **SSH (Linux)** ou **RDP (Windows)**.
- Definição de **roles e permissões** com IAM.

### 3. Monitoramento
- Acompanhamento de desempenho (CPU, memória, rede) via **CloudWatch**.
- Configuração de alarmes e métricas.

### 4. Escalabilidade
- Uso do **Auto Scaling** para ajustar a capacidade automaticamente.
- Balanceamento de tráfego com **Elastic Load Balancer (ELB)**.

### 5. Segurança
- Criação de **Security Groups** e **Network ACLs**.
- Atualizações e patches de segurança.
- Uso de **Key Pairs** para acesso seguro.
  ![Desafio DIO AWS EC2](./images/777CF506-B6C4-4D21-AC4F-2672D896898F.png)
### 6. Backup e Resiliência
- Criação de **snapshots do EBS**.
- Uso de **AMIs personalizadas** para recriação rápida de instâncias.

### 7. Encerramento
- Parar, reiniciar ou terminar a instância quando não for mais necessária.
- Cuidado para evitar **custos extras**.

---

## 📊 Resumo
Gerenciar uma instância EC2 é como ser o **administrador de servidores na nuvem**: você controla desde a criação até o desligamento, garantindo **segurança, desempenho e eficiência de custos**.

---

## 🖼️ Imagem do Desafio
![Desafio DIO AWS EC2](./images/777CF506-B6C4-4D21-AC4F-2672D896898F.png)

---

## 📚 Referências
- [Documentação oficial da AWS EC2](https://docs.aws.amazon.com/ec2/)
- [Digital Innovation One](https://www.dio.me)

---
👩‍💻 AWS EC2**.
