
# 🚀 MobilePX — Simulador de Rádio PX Profissional

<div align="center">

[![Acesse o Projeto](https://img.shields.io/badge/ACESSE_O_PROJETO-CLIQUE_AQUI-3B82F6?style=for-the-badge&logo=rocket)](https://byttencourt.github.io/NINO-Mod-Launcher/)

**[https://byttencourt.github.io/NINO-Mod-Launcher/](https://byttencourt.github.io/NINO-Mod-Launcher/)**

---

*Uma ferramenta de comunicação de voz em tempo real (PTT) de baixa latência, focada em entusiastas e comunidades de logística, simulando a experiência física de um rádio PX (CB Radio) com alta fidelidade.*

</div>

## 📖 Sobre o Projeto

O **MobilePX** não é apenas um chat de voz; é um exercício de engenharia de áudio e redes. O projeto foi concebido para entregar uma experiência "Hardware-Like", onde cada botão, ruído de estática e bip de confirmação foi processado via código para emular o comportamento de frequências de rádio reais (RF).

O sistema utiliza arquitetura de malha (Mesh) via WebRTC para garantir que a voz chegue aos outros operadores com o mínimo de atraso possível, essencial para simulações de comboios e logística.

## 🛠️ Stack Tecnológica & Competências

Este projeto demonstra domínio em diversas áreas críticas do desenvolvimento Frontend moderno:

### 🔊 Engenharia de Áudio (Web Audio API)
- **Processamento de Sinal:** Implementação de filtros *Biquad* (High-pass, Low-pass e Peaking) para criar a assinatura sonora característica de rádios antigos.
- **Dinâmica de Som:** Uso de *DynamicsCompressorNode* para normalização de voz e prevenção de clipping em dispositivos móveis.
- **Síntese de Som:** Geração de ruído branco (White Noise) e bipes (Roger Beeps) em tempo real, além de simulação de *Heteródino* (conflito de sinal quando dois usuários falam ao mesmo tempo).

### 📡 Comunicação em Tempo Real (WebRTC & Supabase)
- **P2P Networking:** Implementação de `RTCPeerConnection` para transmissão de áudio direta entre usuários.
- **Realtime Presence:** Uso do **Supabase Realtime** para gerenciamento de presença, sincronização de canais e sinalização WebRTC.
- **Resiliência de Conexão:** Lógica customizada para recuperação automática de conexão em trocas de rede (ex: Wi-Fi para 4G).

### 🎨 UI/UX & Design de Interface
- **Efeito Spotlight Onboarding:** Sistema de tutorial interativo que utiliza coordenadas dinâmicas e máscaras de sombra (box-shadow) para guiar o usuário visualmente.
- **Hardware Simulation:** Interface construída com Tailwind CSS focada em fidelidade visual, utilizando fontes digitais e sombras internas para simular displays LCD.
- **Mobile First:** Totalmente otimizado para dispositivos móveis, com suporte a gestos e prevenção de comportamentos nativos do navegador que interferem na experiência do app.

## ✨ Principais Funcionalidades

- **40 Canais Reais:** Sintonização de frequência com som de "PLL Lock".
- **Sistema de Roger Beep:** 8 tipos de bipes configuráveis (Nasa, Cobra, Colt, etc).
- **Modo Monitor (Talkback):** Permite que o operador ouça a própria voz processada.
- **Segurança & Moderação:** Sistema de banimento via HWID (Hardware ID) e controle de acesso administrativo.
- **Interação PTT:** Lógica de Push-to-Talk com feedback tátil (vibração) e visual.

## 🚀 Como Executar

1. Acesse o site:
   ```bash
   mobilepx.vercel.app
   ```
2. Faça o login ou entre como Acesso rapido:
   ```bash
   npm install
   ```
3. Boa Diversão.


---

<div align="center">

### Desenvolvido com foco em performance e imersão por **Nino** 🚛💨

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=react&logoColor=white)](https://byttencourt.github.io/NINO-Mod-Launcher/)

</div>
