# Laboratório de redes do Senac
![GitHub License](https://img.shields.io/github/license/gabrielmonn/senac-redes)

Todas (ou quase todas) as minhas experiências nas aulas de redes do Senac. Documentadas e registradas neste repositório do github.

---

## 01. Objetivo

- Montagem e configuração de uma rede de porte doméstico, usando 3 (três) laptops e uma impressora, todos conectados via um modem à Internet

1. Montagem e configuração da rede de maneira virtual/teórica usando o Cisco Packet Tracer, simulando a rede real
2. Implementação da rede no laboratório real

---

## 02. Equipamentos utilizados

- 3 (três) laptops
- 1 (um) modem wireless com 1 (uma) porta WAN e 4 (quatro) portas LAN
- 1 (uma) impressora de rede

---

## 03. Topologia da Rede

Diagrama lógico da rede usada neste laboratório.
```mermaid
graph TD

WAN[Internet/WAN do Provedor]

Router[Roteador Wireless<br>1 Porta WAN<br>4 Portas LAN]

PC1[Notebook 1<br>192.168.0.104]

PC2[Notebook 2<br>192.168.0.102]

PC3[Notebook 3<br>192.168.0.103]

Printer[Impressora de Rede]

WAN--> |Porta WAN| Router

Router--> |Porta LAN| PC1

Router--> |Porta LAN| PC2

Router--> |Porta LAN| PC3

Router--> |Porta LAN| Printer
```

---

Imagem da topologia usada neste laboratório:

![topologia](topologia.png)

---
