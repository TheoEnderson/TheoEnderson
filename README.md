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

Meus projetos vão da simulação de um processador em C a aplicações desktop, dados e integração com hardware. Ao desenvolvê-los, busco entender as decisões de implementação e seus limites.

<details>
  <summary><strong>Interesses acadêmicos e técnicos</strong></summary>

  <p>Exploro programação de baixo nível, arquitetura e organização de computadores, desenvolvimento de software, sistemas embarcados e IoT, visão computacional e engenharia de dados por meio de estudos e projetos.</p>
</details>

## Projetos em destaque

<table>
  <tr>
    <td colspan="2" valign="top">
      <p>
        <img src="https://img.shields.io/badge/01-APLICA%C3%87%C3%83O_DESKTOP-7c4ec4?style=for-the-badge&amp;labelColor=282a36" alt="01 · Aplicação desktop" height="22">
      </p>
      <h3><a href="https://github.com/TheoEnderson/instafollow-analyzer">InstaFollow Analyzer ↗</a></h3>
      <p>
        <strong>As conexões do Instagram, analisadas localmente.</strong> Aplicação desktop que compara seguidores e seguindo a partir de ZIPs ou pastas com JSON das exportações oficiais, com dashboard, busca, ordenação e exportação TXT/CSV.
      </p>
      <p>
        <img src="https://img.shields.io/badge/Python-282a36?style=flat-square&amp;logo=python&amp;logoColor=bd93f9" alt="Python">
        <img src="https://img.shields.io/badge/PySide6-282a36?style=flat-square&amp;logo=qt&amp;logoColor=bd93f9" alt="PySide6">
        <img src="https://img.shields.io/badge/GitHub_Actions-282a36?style=flat-square&amp;logo=githubactions&amp;logoColor=bd93f9" alt="GitHub Actions">
      </p>
      <p align="center">
        <a href="https://github.com/TheoEnderson/instafollow-analyzer#interface">
          <picture>
            <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/TheoEnderson/instafollow-analyzer/main/assets/results-dark.png">
            <img src="https://raw.githubusercontent.com/TheoEnderson/instafollow-analyzer/main/assets/results-light.png" alt="Dashboard real do InstaFollow Analyzer: resumo das relações, busca e tabela de resultados com dados fictícios" width="600">
          </picture>
        </a><br>
        <sub>Interface real do projeto · dados fictícios · clique para explorar</sub>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      Lógica de análise separada da interface, validação de arquivos e testes com <strong>pytest</strong>. O CI executa análise estática com <strong>Ruff</strong>, testes e builds com <strong>PyInstaller</strong> para Windows e Linux.
    </td>
    <td width="50%" valign="top">
      <strong>Código-fonte disponível; executáveis ainda não publicados.</strong> A distribuição depende de verificações de licenciamento. A análise reflete a exportação recebida e não identifica automaticamente contas excluídas ou desativadas.
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="50%" valign="top">
      <p>
        <img src="https://img.shields.io/badge/02-ARQUITETURA-226e83?style=for-the-badge&amp;labelColor=282a36" alt="02 · Arquitetura de computadores" height="18">
      </p>
      <h3><a href="https://github.com/TheoEnderson/ARQUITETURA">Poxim-V ↗</a></h3>
      <p>
        <strong>Um processador RISC-V modelado em C.</strong> Simulador em C99 que executa instruções RV32I/M e modela registradores, exceções, interrupções em modo máquina e periféricos mapeados em memória.
      </p>
      <p>
        <img src="https://img.shields.io/badge/C99-282a36?style=flat-square&amp;logo=c&amp;logoColor=8be9fd" alt="C99">
        <img src="https://img.shields.io/badge/RISC--V-282a36?style=flat-square&amp;logo=riscv&amp;logoColor=8be9fd" alt="RISC-V">
        <img src="https://img.shields.io/badge/GNU_Make-282a36?style=flat-square&amp;logo=gnu&amp;logoColor=8be9fd" alt="GNU Make">
      </p>
    </td>
    <td width="50%" valign="top">
      <p>
        <img src="https://img.shields.io/badge/03-ENGENHARIA_DE_DADOS-257d45?style=for-the-badge&amp;labelColor=282a36" alt="03 · Engenharia de dados" height="18">
      </p>
      <h3><a href="https://github.com/TheoEnderson/Engenharia-de-dados">Engenharia de Dados ↗</a></h3>
      <p>
        <strong>Do modelo relacional ao orientado a documentos.</strong> Projeto acadêmico com portal universitário em Flask e migração de um dump PostgreSQL para MongoDB. Inclui estudos de ETL com Pandas e pipelines Apache Hop para a camada analítica.
      </p>
      <p>
        <img src="https://img.shields.io/badge/Python-282a36?style=flat-square&amp;logo=python&amp;logoColor=50fa7b" alt="Python">
        <img src="https://img.shields.io/badge/PostgreSQL-282a36?style=flat-square&amp;logo=postgresql&amp;logoColor=50fa7b" alt="PostgreSQL">
        <img src="https://img.shields.io/badge/MongoDB-282a36?style=flat-square&amp;logo=mongodb&amp;logoColor=50fa7b" alt="MongoDB">
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <strong>Caches L1 de instruções e dados</strong>, com substituição LRU e registro de acertos e falhas, aproximam a implementação dos conceitos de arquitetura de computadores.
    </td>
    <td width="50%" valign="top">
      <strong>Migração com validação prévia sem gravação e upserts.</strong> Os testes cobrem o parser SQL e as regras de integridade da aplicação.
    </td>
  </tr>
</table>

<table>
  <tr>
    <td colspan="2" valign="top">
      <p>
        <img src="https://img.shields.io/badge/04-VIS%C3%83O_COMPUTACIONAL-a23b78?style=for-the-badge&amp;labelColor=282a36" alt="04 · Visão computacional" height="22">
      </p>
      <h3><a href="https://github.com/TheoEnderson/poker-vision-engine">Poker Vision Engine ↗</a></h3>
      <p>
        <img src="https://img.shields.io/badge/Python-282a36?style=flat-square&amp;logo=python&amp;logoColor=ff79c6" alt="Python">
        <img src="https://img.shields.io/badge/OpenCV-282a36?style=flat-square&amp;logo=opencv&amp;logoColor=ff79c6" alt="OpenCV">
        <img src="https://img.shields.io/badge/NumPy-282a36?style=flat-square&amp;logo=numpy&amp;logoColor=ff79c6" alt="NumPy">
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <strong>Da leitura visual à estimativa de probabilidades.</strong> Assistente de análise de Texas Hold'em que combina reconhecimento de cartas, leitura de valores por OCR e simulação de Monte Carlo.
    </td>
    <td width="50%" valign="top">
      <strong>Máquina de estados</strong> para acompanhar as etapas da mão, OCR com <strong>Tesseract</strong> e testes de cálculo de probabilidades e regressões de leitura visual.
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

Uso essas ferramentas em contextos específicos dos projetos, com diferentes níveis de aprofundamento.

<table>
  <tr>
    <td width="50%" valign="top">
      <p><strong>Software e visão:</strong> Python, PySide6, Flask, OpenCV, Tesseract OCR e NumPy.</p>
      <p>
        <img src="https://img.shields.io/badge/Python-282a36?style=flat-square&amp;logo=python&amp;logoColor=bd93f9" alt="Python">
        <img src="https://img.shields.io/badge/PySide6-282a36?style=flat-square&amp;logo=qt&amp;logoColor=bd93f9" alt="PySide6">
        <img src="https://img.shields.io/badge/Flask-282a36?style=flat-square&amp;logo=flask&amp;logoColor=bd93f9" alt="Flask">
        <img src="https://img.shields.io/badge/OpenCV-282a36?style=flat-square&amp;logo=opencv&amp;logoColor=ff79c6" alt="OpenCV">
        <img src="https://img.shields.io/badge/NumPy-282a36?style=flat-square&amp;logo=numpy&amp;logoColor=ff79c6" alt="NumPy">
      </p>
    </td>
    <td width="50%" valign="top">
      <p><strong>Dados:</strong> SQL, PostgreSQL, MongoDB, Pandas e Apache Hop.</p>
      <p>
        <img src="https://img.shields.io/badge/PostgreSQL-282a36?style=flat-square&amp;logo=postgresql&amp;logoColor=50fa7b" alt="PostgreSQL">
        <img src="https://img.shields.io/badge/MongoDB-282a36?style=flat-square&amp;logo=mongodb&amp;logoColor=50fa7b" alt="MongoDB">
        <img src="https://img.shields.io/badge/Pandas-282a36?style=flat-square&amp;logo=pandas&amp;logoColor=50fa7b" alt="Pandas">
        <img src="https://img.shields.io/badge/Apache_Hop-282a36?style=flat-square&amp;logo=apache&amp;logoColor=50fa7b" alt="Apache Hop">
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <p><strong>Arquitetura e hardware:</strong> C, C++, RISC-V, ESP32, Arduino, LittleFS e HTTP/MQTT.</p>
      <p>
        <img src="https://img.shields.io/badge/C-282a36?style=flat-square&amp;logo=c&amp;logoColor=8be9fd" alt="C">
        <img src="https://img.shields.io/badge/C%2B%2B-282a36?style=flat-square&amp;logo=cplusplus&amp;logoColor=8be9fd" alt="C++">
        <img src="https://img.shields.io/badge/RISC--V-282a36?style=flat-square&amp;logo=riscv&amp;logoColor=8be9fd" alt="RISC-V">
        <img src="https://img.shields.io/badge/ESP32-282a36?style=flat-square&amp;logo=espressif&amp;logoColor=8be9fd" alt="ESP32">
        <img src="https://img.shields.io/badge/Arduino-282a36?style=flat-square&amp;logo=arduino&amp;logoColor=8be9fd" alt="Arduino">
      </p>
    </td>
    <td width="50%" valign="top">
      <p><strong>Qualidade e entrega:</strong> Git, GNU Make, pytest, unittest, Ruff, PyInstaller e GitHub Actions.</p>
      <p>
        <img src="https://img.shields.io/badge/Git-282a36?style=flat-square&amp;logo=git&amp;logoColor=ffb86c" alt="Git">
        <img src="https://img.shields.io/badge/GNU_Make-282a36?style=flat-square&amp;logo=gnu&amp;logoColor=ffb86c" alt="GNU Make">
        <img src="https://img.shields.io/badge/pytest-282a36?style=flat-square&amp;logo=pytest&amp;logoColor=ffb86c" alt="pytest">
        <img src="https://img.shields.io/badge/Ruff-282a36?style=flat-square&amp;logo=ruff&amp;logoColor=ffb86c" alt="Ruff">
        <img src="https://img.shields.io/badge/GitHub_Actions-282a36?style=flat-square&amp;logo=githubactions&amp;logoColor=ffb86c" alt="GitHub Actions">
      </p>
    </td>
  </tr>
</table>

> **Qualidade faz parte da construção.** Nos projetos com testes automatizados, exercito a validação de entradas, regras de negócio e casos de regressão. No InstaFollow, também separo domínio e interface e automatizo verificações e empacotamento para dois sistemas operacionais.

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
  <strong>Vamos conversar sobre projetos e computação.</strong>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/th%C3%A9o-enderson-a7786431a"><img src="https://img.shields.io/badge/in-LinkedIn-7c4ec4?style=for-the-badge&amp;labelColor=282a36" alt="LinkedIn" height="26"></a>
  <a href="mailto:endersontheo@gmail.com"><img src="https://img.shields.io/badge/E--mail-226e83?style=for-the-badge&amp;logo=gmail&amp;logoColor=8be9fd&amp;labelColor=282a36" alt="E-mail" height="26"></a>
  <a href="https://instagram.com/theoenderson"><img src="https://img.shields.io/badge/Instagram-a23b78?style=for-the-badge&amp;logo=instagram&amp;logoColor=ff79c6&amp;labelColor=282a36" alt="Instagram" height="26"></a>
</p>
