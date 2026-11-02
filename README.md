<div align="center">
  <h1>Théo Enderson</h1>

  <p>
    <img src="https://img.shields.io/badge/Engenharia_de_Computa%C3%A7%C3%A3o-UFS-7c4ec4?style=for-the-badge&amp;labelColor=282a36" alt="Engenharia de Computação · UFS" height="24"><br>
    <sub>Graduando na Universidade Federal de Sergipe</sub>
  </p>

  <p>
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.herokuapp.com/?font=Fira+Code&amp;weight=600&amp;size=25&amp;duration=3000&amp;pause=1800&amp;color=BD93F9&amp;center=true&amp;vCenter=true&amp;width=540&amp;height=44&amp;lines=Da+arquitetura+ao+software.;Construir+para+entender.">
      <img src="https://readme-typing-svg.herokuapp.com/?font=Fira+Code&amp;weight=600&amp;size=25&amp;duration=3000&amp;pause=1800&amp;color=7C4EC4&amp;center=true&amp;vCenter=true&amp;width=540&amp;height=44&amp;lines=Da+arquitetura+ao+software.;Construir+para+entender." alt="Da arquitetura ao software. Construir para entender." width="540">
    </picture>
  </p>

  <p>
    <a href="#sobre-mim"><img src="https://img.shields.io/badge/%E2%96%B8-Sobre-7c4ec4?style=flat-square&amp;labelColor=282a36" alt="Sobre" height="22"></a>
    <a href="#projetos-em-destaque"><img src="https://img.shields.io/badge/%E2%96%B8-Projetos-226e83?style=flat-square&amp;labelColor=282a36" alt="Projetos" height="22"></a>
    <a href="#tecnologias-na-prática"><img src="https://img.shields.io/badge/%E2%96%B8-Tecnologias-257d45?style=flat-square&amp;labelColor=282a36" alt="Tecnologias" height="22"></a>
    <a href="#contato"><img src="https://img.shields.io/badge/%E2%96%B8-Contato-a23b78?style=flat-square&amp;labelColor=282a36" alt="Contato" height="22"></a>
  </p>
</div>

## Sobre mim

Meus projetos vão da simulação de um processador em C a aplicações full-stack, desktop e Android, passando por bancos de dados e integração com hardware. Ao desenvolvê-los, busco entender como as camadas se conectam, as decisões de implementação e seus limites.

<details>
  <summary><strong>Interesses acadêmicos e técnicos</strong></summary>

  <p>Exploro programação de sistemas, arquitetura de computadores, comunicação em tempo real, sistemas embarcados e IoT, visão computacional e engenharia de dados por meio de estudos e projetos.</p>
</details>

## Projetos em destaque

<table>
  <tr>
    <td colspan="2" valign="top">
      <p>
        <img src="https://img.shields.io/badge/01-ANDROID_%2B_WEB-7c4ec4?style=for-the-badge&amp;labelColor=282a36" alt="01 · Android + web" height="18">
      </p>
      <h3><a href="https://github.com/TheoEnderson/poker-table">Poker Table ↗</a></h3>
      <p><strong>Cartas físicas, fichas virtuais e uma mesa conectada.</strong> Aplicação para partidas presenciais de Texas Hold'em, com jogadores, posições, blinds, apostas e potes sincronizados via Socket.IO na rede Wi-Fi ou hotspot, sem internet externa.</p>
      <p><strong>O próprio Android hospeda a partida:</strong> servidor Node.js integrado com Kotlin e C++/JNI, persistência SQLite e interface React com TypeScript. Também pode ser hospedada no computador; os convidados entram pelo navegador.</p>
      <p><a href="https://github.com/TheoEnderson/poker-table/releases/tag/v0.2.0"><strong>APK oficial · v0.2.0 ↗</strong></a> · Android 8.0+ (ARM64).</p>
      <p>
        <img src="https://img.shields.io/badge/React-282a36?style=flat-square&amp;logo=react&amp;logoColor=bd93f9" alt="React">
        <img src="https://img.shields.io/badge/TypeScript-282a36?style=flat-square&amp;logo=typescript&amp;logoColor=bd93f9" alt="TypeScript">
        <img src="https://img.shields.io/badge/Node.js-282a36?style=flat-square&amp;logo=nodedotjs&amp;logoColor=bd93f9" alt="Node.js">
        <img src="https://img.shields.io/badge/Kotlin-282a36?style=flat-square&amp;logo=kotlin&amp;logoColor=bd93f9" alt="Kotlin">
      </p>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="50%" valign="top">
      <p>
        <img src="https://img.shields.io/badge/02-DESKTOP-7c4ec4?style=for-the-badge&amp;labelColor=282a36" alt="02 · Aplicação desktop" height="18">
      </p>
      <h3><a href="https://github.com/TheoEnderson/instafollow-analyzer">InstaFollow Analyzer ↗</a></h3>
      <p><strong>As conexões do Instagram, analisadas localmente.</strong> Compara seguidores e seguindo a partir de ZIPs ou pastas com JSON das exportações oficiais, com busca, ordenação e exportação TXT/CSV.</p>
      <p>Lógica de análise separada da interface, validação de arquivos e testes com pytest. <strong>Disponível pelo código-fonte;</strong> executáveis aguardam revisão de licenciamento.</p>
      <p>
        <img src="https://img.shields.io/badge/Python-282a36?style=flat-square&amp;logo=python&amp;logoColor=bd93f9" alt="Python">
        <img src="https://img.shields.io/badge/PySide6-282a36?style=flat-square&amp;logo=qt&amp;logoColor=bd93f9" alt="PySide6">
      </p>
    </td>
    <td width="50%" valign="top">
      <p>
        <img src="https://img.shields.io/badge/03-SISTEMAS-226e83?style=for-the-badge&amp;labelColor=282a36" alt="03 · Arquitetura de computadores" height="18">
      </p>
      <h3><a href="https://github.com/TheoEnderson/ARQUITETURA">Poxim-V ↗</a></h3>
      <p><strong>Um processador RISC-V modelado em C.</strong> Simulador em C99 que executa instruções RV32I/M e modela registradores, exceções, interrupções em modo máquina e periféricos mapeados em memória.</p>
      <p>Caches L1 separadas para instruções e dados, com substituição LRU e registro de acertos e falhas.</p>
      <p>
        <img src="https://img.shields.io/badge/C99-282a36?style=flat-square&amp;logo=c&amp;logoColor=8be9fd" alt="C99">
        <img src="https://img.shields.io/badge/RISC--V-282a36?style=flat-square&amp;logo=riscv&amp;logoColor=8be9fd" alt="RISC-V">
        <img src="https://img.shields.io/badge/GNU%20Make-282a36?style=flat-square&amp;logo=gnu&amp;logoColor=8be9fd" alt="GNU Make">
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <p>
        <img src="https://img.shields.io/badge/04-DADOS-257d45?style=for-the-badge&amp;labelColor=282a36" alt="04 · Engenharia de dados" height="18">
      </p>
      <h3><a href="https://github.com/TheoEnderson/Engenharia-de-dados">Engenharia de Dados ↗</a></h3>
      <p><strong>Do modelo relacional ao orientado a documentos.</strong> Portal universitário em Flask e migração de um dump PostgreSQL para MongoDB, com validação prévia sem gravação e upserts.</p>
      <p>Testes do parser SQL e das regras de integridade, além de estudos de ETL com Pandas e pipelines Apache Hop para a camada analítica.</p>
      <p>
        <img src="https://img.shields.io/badge/Python-282a36?style=flat-square&amp;logo=python&amp;logoColor=50fa7b" alt="Python">
        <img src="https://img.shields.io/badge/PostgreSQL-282a36?style=flat-square&amp;logo=postgresql&amp;logoColor=50fa7b" alt="PostgreSQL">
        <img src="https://img.shields.io/badge/MongoDB-282a36?style=flat-square&amp;logo=mongodb&amp;logoColor=50fa7b" alt="MongoDB">
      </p>
    </td>
    <td width="50%" valign="top">
      <p>
        <img src="https://img.shields.io/badge/05-VIS%C3%83O-a23b78?style=for-the-badge&amp;labelColor=282a36" alt="05 · Visão computacional" height="18">
      </p>
      <h3><a href="https://github.com/TheoEnderson/poker-vision-engine">Poker Vision Engine ↗</a></h3>
      <p><strong>Da leitura visual à estimativa de probabilidades.</strong> Assistente de análise de Texas Hold'em que combina reconhecimento de cartas, leitura de valores com Tesseract OCR e simulação de Monte Carlo.</p>
      <p>Máquina de estados para acompanhar as etapas da mão, com testes de probabilidades e regressões de leitura visual.</p>
      <p>
        <img src="https://img.shields.io/badge/Python-282a36?style=flat-square&amp;logo=python&amp;logoColor=ff79c6" alt="Python">
        <img src="https://img.shields.io/badge/OpenCV-282a36?style=flat-square&amp;logo=opencv&amp;logoColor=ff79c6" alt="OpenCV">
        <img src="https://img.shields.io/badge/NumPy-282a36?style=flat-square&amp;logo=numpy&amp;logoColor=ff79c6" alt="NumPy">
      </p>
    </td>
  </tr>
</table>

## Outros projetos

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/TheoEnderson/projeto-sensor">Sistema de Presença Biométrico ↗</a></h3>
      <p><strong>C++ · Arduino · ESP32 · LittleFS · HTTP/MQTT</strong></p>
      <p>Protótipo que integra sensor de impressão digital por UART, portal web local para cadastro e armazenamento de registros durante períodos sem Wi-Fi. Envia presenças ao Google Sheets por HTTP e inclui exemplos separados com MQTT.</p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/TheoEnderson/estrutura-de-dados">Estruturas de Dados em C ↗</a></h3>
      <p><strong>C · biblioteca padrão · memória e arquivos</strong></p>
      <p>Exercícios com dicionário de sinônimos em AVL, indexação de arquivos em árvore B+ e atendimento por fila de prioridade. Implementações diretas de rotações, divisão de nós e operações de heap, com alocação dinâmica e entrada/saída em arquivos.</p>
    </td>
  </tr>
</table>

## Tecnologias na prática

As ferramentas aparecem nos projetos conforme o problema e a camada de implementação:

- **Full-stack e Android:** React e TypeScript na interface; Node.js, Express e Socket.IO no servidor; Kotlin e C++/JNI na integração Android do Poker Table.
- **Desktop e visão computacional:** Python e PySide6 no InstaFollow; OpenCV, Tesseract OCR e NumPy no Poker Vision Engine.
- **Bancos de dados e ETL:** SQLite no Poker Table; Flask, SQL, PostgreSQL, MongoDB, Pandas e Apache Hop no projeto de Engenharia de Dados.
- **Sistemas e hardware:** C99, RISC-V e GNU Make no Poxim-V; C++, ESP32, Arduino, LittleFS e comunicação por UART e HTTP no protótipo biométrico, com exemplos de MQTT.

### Qualidade e entrega

No Poker Table, uso Vitest para testes unitários e de integração, Playwright para fluxos no navegador e ESLint para análise estática, com distribuição do APK pelo GitHub Releases. No InstaFollow, o GitHub Actions executa Ruff, pytest e builds com PyInstaller para Windows e Linux. Nos projetos de dados e visão, os testes exercitam validações, regras de integridade e regressões.

## Atividade no GitHub

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/TheoEnderson/TheoEnderson/output/github-contribution-grid-snake-dracula.svg">
    <img src="https://raw.githubusercontent.com/TheoEnderson/TheoEnderson/output/github-contribution-grid-snake.svg" alt="Animação de uma serpente percorrendo o gráfico de contribuições no GitHub" width="100%">
  </picture><br>
  <sub><a href="https://github.com/TheoEnderson/TheoEnderson/actions/workflows/snake.yml">Atualização pelo workflow de contribuições</a></sub>
</p>

## Contato

<p align="center">
  <strong>Vamos conversar sobre software, sistemas e projetos em computação.</strong>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/th%C3%A9o-enderson-a7786431a"><img src="https://img.shields.io/badge/in-LinkedIn-7c4ec4?style=for-the-badge&amp;labelColor=282a36" alt="LinkedIn" height="26"></a>
  <a href="mailto:endersontheo@gmail.com"><img src="https://img.shields.io/badge/E--mail-226e83?style=for-the-badge&amp;logo=gmail&amp;logoColor=8be9fd&amp;labelColor=282a36" alt="E-mail" height="26"></a>
  <a href="https://instagram.com/theoenderson"><img src="https://img.shields.io/badge/Instagram-a23b78?style=for-the-badge&amp;logo=instagram&amp;logoColor=ff79c6&amp;labelColor=282a36" alt="Instagram" height="26"></a>
</p>
