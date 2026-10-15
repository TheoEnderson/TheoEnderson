<h1 align="center">Théo Enderson</h1>

<p align="center">
  <strong>Engenharia de Computação · UFS</strong><br>
  Graduando na Universidade Federal de Sergipe
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?font=Fira+Code&amp;size=26&amp;duration=3000&amp;pause=1800&amp;color=BD93F9&amp;background=282A36&amp;center=true&amp;vCenter=true&amp;width=460&amp;height=72&amp;lines=Da+arquitetura+ao+software.;Construir+para+entender." alt="Da arquitetura ao software. Construir para entender." width="600">
</p>

<p align="center">
  <a href="#sobre-mim">Sobre</a> &nbsp;·&nbsp;
  <a href="#projetos-em-destaque">Projetos</a> &nbsp;·&nbsp;
  <a href="#tecnologias-na-prática">Tecnologias</a> &nbsp;·&nbsp;
  <a href="#contato">Contato</a>
</p>

## Sobre mim

Meus projetos vão da simulação de um processador em C a aplicações desktop, dados e integração com hardware. Ao desenvolvê-los, busco entender as decisões de implementação e seus limites.

<details>
  <summary><strong>Interesses acadêmicos e técnicos</strong></summary>

  <p>Exploro programação de baixo nível, arquitetura e organização de computadores, desenvolvimento de software, sistemas embarcados e IoT, visão computacional e engenharia de dados por meio de estudos e projetos.</p>
</details>

## Projetos em destaque

<p>
  <img src="https://img.shields.io/badge/01-APLICA%C3%87%C3%83O_DESKTOP-7c4ec4?style=for-the-badge&amp;labelColor=282a36" alt="01 · Aplicação desktop">
</p>

### [InstaFollow Analyzer ↗](https://github.com/TheoEnderson/instafollow-analyzer)

**As conexões do Instagram, analisadas localmente.** Aplicação desktop que compara seguidores e seguindo a partir de ZIPs ou pastas com JSON das exportações oficiais, com dashboard, busca, ordenação e exportação TXT/CSV.

<p>
  <img src="https://img.shields.io/badge/Python-282a36?style=flat-square&amp;logo=python&amp;logoColor=bd93f9" alt="Python">
  <img src="https://img.shields.io/badge/PySide6-282a36?style=flat-square&amp;logo=qt&amp;logoColor=bd93f9" alt="PySide6">
  <img src="https://img.shields.io/badge/GitHub_Actions-282a36?style=flat-square&amp;logo=githubactions&amp;logoColor=bd93f9" alt="GitHub Actions">
</p>

Lógica de análise separada da interface, validação de arquivos e testes com **pytest**. O CI executa análise estática com **Ruff**, testes e builds com **PyInstaller** para Windows e Linux.

<p align="center">
  <a href="https://github.com/TheoEnderson/instafollow-analyzer#interface">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/TheoEnderson/instafollow-analyzer/main/assets/results-dark.png">
      <img src="https://raw.githubusercontent.com/TheoEnderson/instafollow-analyzer/main/assets/results-light.png" alt="Dashboard real do InstaFollow Analyzer: resumo das relações, busca e tabela de resultados com dados fictícios" width="500">
    </picture>
  </a><br>
  <sub>Interface real do projeto · dados fictícios · clique para explorar</sub>
</p>

> **Código-fonte disponível; executáveis ainda não publicados.** A distribuição depende de verificações de licenciamento. A análise reflete a exportação recebida e não identifica automaticamente contas excluídas ou desativadas.

---

<p>
  <img src="https://img.shields.io/badge/02-ARQUITETURA-226e83?style=for-the-badge&amp;labelColor=282a36" alt="02 · Arquitetura de computadores">
</p>

### [Poxim-V ↗](https://github.com/TheoEnderson/ARQUITETURA)

**Um processador RISC-V modelado em C.** Simulador em C99 que executa instruções RV32I/M e modela registradores, exceções, interrupções em modo máquina e periféricos mapeados em memória.

<p>
  <img src="https://img.shields.io/badge/C99-282a36?style=flat-square&amp;logo=c&amp;logoColor=8be9fd" alt="C99">
  <img src="https://img.shields.io/badge/RISC--V-282a36?style=flat-square&amp;logo=riscv&amp;logoColor=8be9fd" alt="RISC-V">
  <img src="https://img.shields.io/badge/GNU_Make-282a36?style=flat-square&amp;logo=gnu&amp;logoColor=8be9fd" alt="GNU Make">
</p>

**Caches L1 de instruções e dados**, com substituição LRU e registro de acertos e falhas, aproximam a implementação dos conceitos de arquitetura de computadores.

---

<p>
  <img src="https://img.shields.io/badge/03-ENGENHARIA_DE_DADOS-257d45?style=for-the-badge&amp;labelColor=282a36" alt="03 · Engenharia de dados">
</p>

### [Engenharia de Dados ↗](https://github.com/TheoEnderson/Engenharia-de-dados)

**Do modelo relacional ao orientado a documentos.** Projeto acadêmico com portal universitário em Flask e migração de um dump PostgreSQL para MongoDB. Inclui estudos de ETL com Pandas e pipelines Apache Hop para a camada analítica.

<p>
  <img src="https://img.shields.io/badge/Python-282a36?style=flat-square&amp;logo=python&amp;logoColor=50fa7b" alt="Python">
  <img src="https://img.shields.io/badge/PostgreSQL-282a36?style=flat-square&amp;logo=postgresql&amp;logoColor=50fa7b" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/MongoDB-282a36?style=flat-square&amp;logo=mongodb&amp;logoColor=50fa7b" alt="MongoDB">
</p>

**Migração com validação prévia sem gravação e upserts.** Os testes cobrem o parser SQL e as regras de integridade da aplicação.

---

<p>
  <img src="https://img.shields.io/badge/04-VIS%C3%83O_COMPUTACIONAL-a23b78?style=for-the-badge&amp;labelColor=282a36" alt="04 · Visão computacional">
</p>

### [Poker Vision Engine ↗](https://github.com/TheoEnderson/poker-vision-engine)

**Da leitura visual à estimativa de probabilidades.** Assistente de análise de Texas Hold'em que combina reconhecimento de cartas, leitura de valores por OCR e simulação de Monte Carlo.

<p>
  <img src="https://img.shields.io/badge/Python-282a36?style=flat-square&amp;logo=python&amp;logoColor=ff79c6" alt="Python">
  <img src="https://img.shields.io/badge/OpenCV-282a36?style=flat-square&amp;logo=opencv&amp;logoColor=ff79c6" alt="OpenCV">
  <img src="https://img.shields.io/badge/NumPy-282a36?style=flat-square&amp;logo=numpy&amp;logoColor=ff79c6" alt="NumPy">
</p>

**Máquina de estados** para acompanhar as etapas da mão, OCR com **Tesseract** e testes de cálculo de probabilidades e regressões de leitura visual.

## Outros projetos

### [Sistema de Presença Biométrico ↗](https://github.com/TheoEnderson/projeto-sensor)

**C++ · Arduino · ESP32 · LittleFS · HTTP/MQTT**

Protótipo que integra sensor de impressão digital por UART, portal web local para cadastro e armazenamento de registros durante períodos sem Wi-Fi. Envia presenças ao Google Sheets por HTTP e inclui exemplos separados com MQTT.

### [Estruturas de Dados em C ↗](https://github.com/TheoEnderson/estrutura-de-dados)

**C · biblioteca padrão · memória e arquivos**

Exercícios com dicionário de sinônimos em AVL, indexação de arquivos em árvore B+ e atendimento por fila de prioridade. Implementações diretas de rotações, divisão de nós e operações de heap, com alocação dinâmica e entrada/saída em arquivos.

## Tecnologias na prática

Uso essas ferramentas em contextos específicos dos projetos, com diferentes níveis de aprofundamento.

- **Software e visão:** Python, PySide6, Flask, OpenCV, Tesseract OCR e NumPy.
- **Dados:** SQL, PostgreSQL, MongoDB, Pandas e Apache Hop.
- **Arquitetura e hardware:** C, C++, RISC-V, ESP32, Arduino, LittleFS e HTTP/MQTT.
- **Qualidade e entrega:** Git, GNU Make, pytest, unittest, Ruff, PyInstaller e GitHub Actions.

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
  <a href="https://www.linkedin.com/in/th%C3%A9o-enderson-a7786431a"><img src="https://img.shields.io/badge/LinkedIn-7c4ec4?style=for-the-badge" alt="LinkedIn"></a>
  <a href="mailto:endersontheo@gmail.com"><img src="https://img.shields.io/badge/E--mail-7c4ec4?style=for-the-badge&amp;logo=gmail&amp;logoColor=white" alt="E-mail"></a>
  <a href="https://instagram.com/theoenderson"><img src="https://img.shields.io/badge/Instagram-7c4ec4?style=for-the-badge&amp;logo=instagram&amp;logoColor=white" alt="Instagram"></a>
</p>
