
# 📶 Guia Completo de Diagnóstico Wi-Fi & PowerShell

Um manual prático e interativo para solução de problemas de rede sem fio (WLAN), comandos essenciais do Windows (`netsh`, `ipconfig`, `arp`) e scripts de diagnóstico avançados em **PowerShell**.

Projetado em uma página HTML responsiva com o tema **Dracula**, suporte a modo claro/escuro, cópia rápida de comandos e exportação para PDF.

---

## 🚀 Funcionalidades

- 🛠️ **Solução para o erro `WlanSvc`**: Passo a passo para reativar o serviço de rede sem fio do Windows.
- 📋 **Tabela Prática de Comandos**: Referência rápida para `netsh`, `ipconfig`, `nslookup`, `netstat` e cmdlets do PowerShell.
- 📊 **Gerador e Analisador de WLAN Report**: Instruções para interpretar relatórios avançados de conexões e quedas de rede.
- 📡 **Análise de Frequências (2.4 GHz vs 5 GHz)**: Guia de escolha de canais para redução de interferências.
- 🔄 **Reset Completo da Pilha de Rede**: Execução sequencial para restauração de IPv4, IPv6 e catálogos Winsock.
- ⏱️ **Script de Ping com Timestamp**: Registro contínuo de conectividade e microquedas em arquivo de log.
- 🎨 **Interface Moderna**: Tema Dracula com alternância para modo claro, totalmente responsivo para desktop e dispositivos móveis.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** & **JavaScript (ES6+)**
- **Tailwind CSS** (via CDN)
- **Font Awesome 6** (Ícones)
- **PowerShell / CMD Windows**

---

## 📂 Como Utilizar

### Executar a aplicação localmente
1. Clone este repositório ou baixe os arquivos:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Abra o arquivo `Diagnostico_de_Redes.html` diretamente no seu navegador de preferência (Chrome, Edge, Firefox, Brave, etc.).

---

## 📋 Principais Comandos Cobertos

| Comando | Tipo | Descrição |
| :--- | :---: | :--- |
| `netsh wlan show networks mode=bssid` | CMD/PS | Exibe redes ao alcance com sinal e BSSIDs |
| `Start-Service WlanSvc` | PowerShell | Inicia o serviço de suporte a redes sem fio |
| `netsh wlan show wlanreport` | CMD/PS | Gera relatório HTML detalhado de eventos |
| `netsh winsock reset` | CMD/PS | Restaura os soquetes de rede aos padrões |
| `Test-NetConnection 8.8.8.8 -Port 53` | PowerShell | Teste avançado de latência e porta |

---

## 📄 Licença

Este projeto está sob a licença MIT. Sinta-se à vontade para utilizar, modificar e distribuir.
