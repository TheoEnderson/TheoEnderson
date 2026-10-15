<h1 align="center">Théo Enderson</h1>

<p align="center">
  Graduando em <strong>Engenharia de Computação</strong><br>
  Universidade Federal de Sergipe · UFS
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?font=Fira+Code&amp;size=20&amp;duration=3500&amp;pause=2500&amp;color=8957E5&amp;center=true&amp;vCenter=true&amp;width=440&amp;height=40&amp;lines=Aprender%2C+implementar%2C+entender." alt="Aprender, implementar, entender." width="440">
</p>

<p align="center">
  <a href="#sobre-mim">Sobre mim</a> ·
  <a href="#projetos-em-destaque">Projetos</a> ·
  <a href="#tecnologias-na-prática">Tecnologias</a> ·
  <a href="#contato">Contato</a>
</p>

## Sobre mim

Meus projetos conectam os fundamentos da computação à construção de software: da simulação de um processador em C a aplicações desktop, processamento de dados e integração com hardware.

Tenho interesse acadêmico em programação de baixo nível, arquitetura e organização de computadores, desenvolvimento de software, sistemas embarcados e IoT, visão computacional e engenharia de dados. Exploro essas áreas por meio de estudos e projetos, buscando entender as decisões de implementação e seus limites.

## Projetos em destaque

### [InstaFollow Analyzer](https://github.com/TheoEnderson/instafollow-analyzer)

Aplicação desktop para comparar seguidores e seguindo a partir das exportações oficiais do Instagram. Processa localmente ZIPs ou pastas com JSON e oferece dashboard, busca, ordenação e exportação TXT/CSV.

**Tecnologias:** Python · PySide6 · pytest · PyInstaller · GitHub Actions<br>
**Diferencial técnico:** lógica de análise separada da interface, validação de arquivos, testes automatizados e CI com análise estática, testes e builds para Windows e Linux.

> Código-fonte público. Os executáveis oficiais ainda não foram publicados devido a verificações pendentes de licenciamento. A análise reflete a exportação recebida e não identifica automaticamente contas excluídas ou desativadas.

### [Poxim-V — Simulador RISC-V](https://github.com/TheoEnderson/ARQUITETURA)

Simulador em C99 que executa instruções RV32I/M e modela registradores, exceções, interrupções em modo máquina e periféricos mapeados em memória.

**Tecnologias:** C · RISC-V · GNU Make<br>
**Diferencial técnico:** caches L1 separadas para instruções e dados, com substituição LRU e registro de acertos e falhas, aproximando o código dos conceitos de arquitetura de computadores.

### [Engenharia de Dados](https://github.com/TheoEnderson/Engenharia-de-dados)

Projeto acadêmico com portal universitário em Flask e migração de um dump PostgreSQL para MongoDB. Inclui estudos de ETL com Pandas e pipelines Apache Hop para a camada analítica.

**Tecnologias:** Python · SQL · Flask · PostgreSQL · MongoDB · Pandas<br>
**Diferencial técnico:** migração com validação prévia sem gravação, upserts e testes do parser SQL e das regras de integridade da aplicação.

### [Poker Vision Engine](https://github.com/TheoEnderson/poker-vision-engine)

Assistente de análise de Texas Hold'em que combina reconhecimento visual de cartas, leitura de valores por OCR e estimativas de probabilidade por Monte Carlo.

**Tecnologias:** Python · OpenCV · Tesseract OCR · NumPy<br>
**Diferencial técnico:** máquina de estados para acompanhar as etapas da mão, com testes de cálculo de probabilidades e regressões de leitura visual.

## Outros projetos

### [Sistema de Presença Biométrico](https://github.com/TheoEnderson/projeto-sensor)

Protótipo com ESP32 e sensor de impressão digital para cadastrar pessoas e registrar presença. Integra portal web local, armazenamento em LittleFS e envio HTTP ao Google Sheets; inclui exemplos separados com MQTT.

**Tecnologias:** C++ · Arduino · ESP32 · LittleFS · HTTP/MQTT<br>
**Diferencial técnico:** integração entre leitura biométrica por UART, interface de cadastro e armazenamento de registros durante períodos sem Wi-Fi.

### [Estruturas de Dados em C](https://github.com/TheoEnderson/estrutura-de-dados)

Coleção de exercícios com aplicações como dicionário de sinônimos em árvore AVL, indexação de arquivos em árvore B+ e atendimento por fila de prioridade.

**Tecnologias:** C · biblioteca padrão<br>
**Diferencial técnico:** implementação direta de rotações, divisão de nós e operações de heap, com alocação dinâmica e entrada/saída em arquivos.

## Tecnologias na prática

<p align="center">
  <img src="https://img.shields.io/badge/C-282a36?style=flat&amp;logo=c&amp;logoColor=bd93f9" alt="C">
  <img src="https://img.shields.io/badge/C%2B%2B-282a36?style=flat&amp;logo=c%2B%2B&amp;logoColor=bd93f9" alt="C++">
  <img src="https://img.shields.io/badge/Python-282a36?style=flat&amp;logo=python&amp;logoColor=bd93f9" alt="Python">
  <img src="https://img.shields.io/badge/SQL-282a36?style=flat&amp;logo=postgresql&amp;logoColor=bd93f9" alt="SQL">
</p>

As ferramentas abaixo aparecem nos projetos apresentados; representam experiências práticas em contextos específicos, com diferentes níveis de aprofundamento.

- **Aplicações e visão computacional:** PySide6, Flask, OpenCV e Tesseract OCR.
- **Dados:** PostgreSQL, MongoDB, Pandas e Apache Hop.
- **Sistemas e hardware:** RISC-V, ESP32, Arduino, LittleFS e comunicação HTTP/MQTT.
- **Qualidade e entrega:** Git, GNU Make, pytest, unittest, Ruff, PyInstaller e GitHub Actions.

Nos projetos com testes automatizados, exercito a validação de entradas, regras de negócio e casos de regressão. No InstaFollow, também separo domínio e interface e automatizo verificações e empacotamento para dois sistemas operacionais.

## Atividade no GitHub

<details>
  <summary>Ver animação das contribuições</summary>

  <p align="center">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/TheoEnderson/TheoEnderson/output/github-contribution-grid-snake-dracula.svg">
      <img src="https://raw.githubusercontent.com/TheoEnderson/TheoEnderson/output/github-contribution-grid-snake.svg" alt="Animação de uma serpente percorrendo o gráfico de contribuições no GitHub" width="100%">
    </picture>
  </p>

  <p align="center"><a href="https://github.com/TheoEnderson/TheoEnderson/actions/workflows/snake.yml">Workflow de atualização da animação</a></p>
</details>

## Contato

<p align="center">
  <a href="https://www.linkedin.com/in/th%C3%A9o-enderson-a7786431a"><img src="https://img.shields.io/badge/LinkedIn-282a36?style=flat&amp;logoColor=bd93f9" alt="LinkedIn"></a>
  <a href="mailto:endersontheo@gmail.com"><img src="https://img.shields.io/badge/E--mail-282a36?style=flat&amp;logo=gmail&amp;logoColor=bd93f9" alt="E-mail"></a>
  <a href="https://instagram.com/theoenderson"><img src="https://img.shields.io/badge/Instagram-282a36?style=flat&amp;logo=instagram&amp;logoColor=bd93f9" alt="Instagram"></a>
</p>
