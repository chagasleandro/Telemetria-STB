# 📡 Console Linear Denki - Operação Pro

![Status](https://img.shields.io/badge/Status-Desenvolvimento-blue)
![Tech](https://img.shields.io/badge/Tecnologias-HTML5%20%7C%20CSS3%20%7C%20JS-orange)

Interface técnica de monitoramento para transmissores digitais de TV (padrão ISDB-T). O projeto simula um console de engenharia real, permitindo visualizar o fluxo de sinal de RF, telemetria de potência e configurações de módulos individuais.

## 🚀 Funcionalidades

- **Acesso Restrito:** Tela de login customizada com validação de credenciais.
- **Diagrama de Blocos Interativo:** Representação visual do caminho do sinal (Power Supply → Modulator → HPA → Filter).
- **Telemetria em Tempo Real:** Monitoramento dinâmico de potência direta (FWD) e refletida (REF).
- **Detalhamento de Módulos:** Clique em cada bloco para abrir um painel com especificações técnicas (MER, Temperatura, Corrente, etc.).
- **Design Responsivo:** Interface otimizada para operação em monitores de estações de controle.

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estruturação semântica e elementos SVG para as linhas de fluxo.
- **CSS3:** Estilização moderna com variáveis (Custom Properties), gradientes e animações de fluxo de sinal.
- **JavaScript (Vanilla):** Lógica de login, transição de telas, relógio em tempo real e manipulação de modais.

## 📸 Demonstração da Interface

1. **Login:** Tema azul profissional com autenticação.
2. **Dashboard:** Fundo em tom *Dark Slate* (`#1a202c`) para reduzir o cansaço visual do operador.
3. **Animação:** Linhas de sinal pulsantes indicando que o transmissor está em "RF ON".

## ⚙️ Como executar o projeto

1. Faça o download ou clone este repositório:
   ```bash
   git clone [https://github.com/seu-usuario/console-linear-denki.git](https://github.com/seu-usuario/console-linear-denki.git)
