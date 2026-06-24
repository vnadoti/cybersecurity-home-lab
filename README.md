# 🛡️ Cybersecurity Home Lab

Projeto pessoal focado em desenvolvimento prático de competências em Redes, Segurança da Informação, Blue Team, SIEM, EDR e Resposta a Incidentes.

![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-blue)
![Cybersecurity](https://img.shields.io/badge/Cybersecurity-Home%20Lab-green)
![pfSense](https://img.shields.io/badge/pfSense-2.8.1-orange)
![VMware](https://img.shields.io/badge/VMware-Workstation%20Pro-blue)
![Linux](https://img.shields.io/badge/Linux-Ubuntu-yellow)
![Windows](https://img.shields.io/badge/Windows-11-blue)

---

## 🎯 Objetivo

Construir um ambiente virtual semelhante a uma infraestrutura corporativa para praticar:

* Administração de Redes
* Firewall e Segmentação
* Hardening Windows e Linux
* SIEM
* EDR
* Vulnerability Management
* Threat Hunting
* Incident Response
* Monitoramento de Segurança

---

## 🖥️ Infraestrutura

### Host

| Recurso             | Especificação          |
| ------------------- | ---------------------- |
| CPU                 | Intel i9-13900K        |
| RAM                 | 64 GB DDR5             |
| Virtualização       | VMware Workstation Pro |
| Sistema Operacional | Windows 11             |

---

## 🌐 Topologia

```text
                    Internet
                        │
                        ▼
                +---------------+
                |    pfSense    |
                | Firewall/NAT  |
                +-------+-------+
                        │
                        ▼
                 192.168.100.0/24
                        │
      ┌─────────────────┼─────────────────┐
      │                 │                 │
      ▼                 ▼                 ▼
+-------------+  +-------------+  +-------------+
| WIN11-LAB   |  | UBUNTU-SRV  |  | KALI-LAB    |
| Endpoint    |  | Servidor    |  | Pentest     |
+-------------+  +-------------+  +-------------+
                                         │
                                         ▼
                               +----------------+
                               | Metasploitable |
                               | Alvo Vulnerável|
                               +----------------+
```

---

## 🚀 Roadmap do Projeto

### Sprint 01 — Firewall & Rede

* [x] VMware Workstation Pro
* [x] VMnet2 Host-Only
* [x] Instalação do pfSense
* [x] Configuração WAN
* [x] Configuração LAN
* [x] DHCP Server
* [x] DNS
* [x] WebGUI

### Sprint 02 — Windows Endpoint

* [x] Instalação Windows 11 Pro
* [x] Integração com pfSense
* [x] Configuração IP via DHCP
* [x] Testes de conectividade
* [x] DNS Validation
* [x] Windows Update

### Sprint 03 — Linux Server

* [ ] Ubuntu Server
* [ ] OpenSSH
* [ ] Apache
* [ ] Docker
* [ ] Hardening Linux

### Sprint 04 — Pentest

* [ ] Kali Linux
* [ ] Nmap
* [ ] Burp Suite
* [ ] Hydra
* [ ] Wireshark

### Sprint 05 — Vulnerability Lab

* [ ] Metasploitable 2
* [ ] Enumeração
* [ ] Exploração Controlada

### Sprint 06 — SIEM & EDR

* [ ] Wazuh
* [ ] Coleta de Logs
* [ ] Dashboards
* [ ] Alertas

### Sprint 07 — SOC Simulado

* [ ] Port Scan Detection
* [ ] Brute Force Detection
* [ ] Threat Hunting
* [ ] Incident Response

---

## 🧠 Competências Desenvolvidas

### Redes

* TCP/IP
* DNS
* DHCP
* NAT
* VLANs
* VPN
* Firewall

### Sistemas Operacionais

* Windows 11
* Linux
* pfSense

### Segurança

* SIEM
* EDR
* Vulnerability Management
* Threat Hunting
* Incident Response

### Ferramentas

* VMware Workstation
* pfSense
* Kali Linux
* Wazuh
* Nmap
* Wireshark
* Burp Suite
* Metasploit

---

## 📂 Estrutura do Repositório

```text
cybersecurity-home-lab/
├── README.md
├── sprint-01-pfsense
│   ├── notes.md
│   ├── screenshots
│   └── topology
├── sprint-02-windows
├── sprint-03-ubuntu
├── sprint-04-kali
├── sprint-05-metasploitable
├── sprint-06-wazuh
└── sprint-07-soc
```

---

## 📌 Status Atual

```text
Sprint 01 - pfSense Firewall       ✅ Concluído
Sprint 02 - Windows 11 Endpoint    ✅ Concluído
Sprint 03 - Ubuntu Server          ⏳ Em andamento
Sprint 04 - Kali Linux             ⏳ Planejado
Sprint 05 - Metasploitable 2       ⏳ Planejado
Sprint 06 - Wazuh SIEM             ⏳ Planejado
Sprint 07 - SOC Monitoring         ⏳ Planejado
```

---

## 👨‍💻 Sobre

Profissional em transição para Cybersecurity com foco em:

* SOC Analyst
* Blue Team
* Cyber Defense
* Security Operations

Este repositório documenta minha evolução prática através de laboratórios, testes e projetos reais de estudo.
