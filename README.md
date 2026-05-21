# lab-rede-corporativa

Rede corporativa simulada com VLANs, ACLs, VPN Site-to-Site e pfSense.  
Cisco Packet Tracer + Oracle VirtualBox. Documentado passo a passo para portfólio.

---

## Conteúdo do repositório

| Ficheiro | Descrição |
|----------|-----------|
| `lab-rede-corporativa.pkt` | Topologia completa — abre directamente no Cisco Packet Tracer 8.x |
| `Relatorio_Rede_Corporativa_Helder_Sindique.pdf` | Relatório técnico com 20 capturas de ecrã e documentação passo a passo |

## O que o projeto demonstra

- VLANs e trunk 802.1Q — Cisco 3560-24PS e 2960-24TT
- Routing inter-VLAN com sub-interfaces (Router-on-a-Stick) — ISR4331
- ACLs extended para isolamento de segmentos de rede
- Firewall pfSense 2.8.1 — regras por interface
- VPN IPsec Site-to-Site — documentada com comandos e outputs esperados
- Segundo site (Site B) com ligação WAN — 200.0.0.0/30

## Como testar

1. Instala o Cisco Packet Tracer (conta gratuita em [netacad.com](https://netacad.com))  
2. Descarrega e abre `lab-rede-corporativa.pkt`  
3. Modo Realtime — testa os pings conforme documentado no relatório PDF

---

Helder Sindique · Maio 2026
