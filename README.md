<div align="center">

# Sou Lucas, Especialista Contábil e Desenvolvedor

### Engenharia de Software aplicada à Contabilidade · Automação Fiscal · IA

Uno a vivência prática da rotina contábil e fiscal do varejo ao desenvolvimento de sistemas web, integrações com banco de dados e automações que eliminam o trabalho manual.

[Conheça meus projetos](#em-producao-arquitetura-corporativa) · [Explore os repositórios](https://github.com/FassoloLucas?tab=repositories)

</div>

---

## Em produção (Arquitetura Corporativa)

### [Plataforma Web de Gestão Contábil, Fiscal e Controladoria](https://github.com/FassoloLucas/gestao-contratos-locacao-ia)

**Ecossistema corporativo integrado ao ERP Consinco (Oracle) para operação de varejo em escala (19 lojas).**

Projetei e desenvolvi do zero a plataforma interna que centraliza a análise contábil, a auditoria fiscal, a gestão de contratos e o acompanhamento orçamentário do grupo. O sistema substitui dezenas de planilhas manuais e aplica regras contábeis e tributárias padronizadas direto na fonte de dados.

- **Escala e Arquitetura:** Mais de 55 telas e 201 rotas de API divididas em 6 módulos (Contabilidade, Fiscal, Orçamento, Financeiro, Comercial e Contratos), com mais de 1.400 testes automatizados no servidor e na interface.
- **Contabilidade e Controladoria:** DRE contábil e gerencial por loja, Livro Razão de alta velocidade em PDF, controle de Arrendamento Mercantil (CPC 06), cálculo e conciliação estrita de Depreciação do imobilizado e gestão de Budget anual por setor.
- **Auditoria Fiscal em Volume:** Conferência automática item a item entre XML de entrada e lançamentos do ERP, integração com portal NDD, apurações de F100, FECP e DIFAL, além de leitor de SPED Fiscal (EFD ICMS/IPI) e extrator de XML processados direto no navegador.
- **Contratos e IA Contextual:** Controle de aluguéis com reajuste por índices oficiais (IGP-M, IPCA, INPC, IGP-DI), leitura automática de contratos em PDF e assistente virtual integrada às telas para análise de indicadores.

`Python` `FastAPI` `Oracle SQL` `MongoDB` `JavaScript` `Chart.js` `Firebase` `pandas` `ReportLab` `WeasyPrint` `LLMs (Gemini / Groq)` `pytest`

[Ver estudo de caso e arquitetura](https://github.com/FassoloLucas/gestao-contratos-locacao-ia)

---

## Ferramentas Contábeis e Fiscais (Open Source)

### [Gerador de Livro Razão (ECD)](https://github.com/FassoloLucas/gerador-razao-ecd)

**Da escrituração contábil ao Livro Razão, com conferência dos saldos.**

Indexa o TXT da ECD em SQLite, gera PDFs por grupo de contas e confere os movimentos impressos contra os saldos da escrituração. Inclui interface com progresso, cancelamento e retomada, cálculos com Decimal e testes com dados fictícios.

`Python` `SQLite` `Tkinter` `ReportLab` `pytest` `GitHub Actions`

[Ver código e documentação](https://github.com/FassoloLucas/gerador-razao-ecd)

### [Extrator de XML Fiscal para Excel](https://github.com/FassoloLucas/extrator-xml-fiscal)

**Documentos fiscais transformados em uma planilha organizada.**

Aplicativo desktop que lê XMLs fiscais de uma pasta e exporta os dados para Excel formatado. O processamento é local, com interface para selecionar arquivos e acompanhar a extração.

`Python` `CustomTkinter` `pandas` `XlsxWriter` `XML`

[Explorar o extrator](https://github.com/FassoloLucas/extrator-xml-fiscal)

### [Relatório Gerencial (CGO × Filial)](https://github.com/FassoloLucas/relatorio-gerencial-cgo)

**Cruzamento de produtos e filiais para apoiar a conferência gerencial.**

Cruza relatórios CSV por código de produto e gera um Excel com movimentos por filial. Produtos vinculados a múltiplos CGOs ficam em uma aba de auditoria para revisão.

`Python` `Tkinter` `pandas` `openpyxl`

[Conhecer o relatório](https://github.com/FassoloLucas/relatorio-gerencial-cgo)

### [Conversor de planilhas](https://github.com/FassoloLucas/Conversor2)

**Conversão de vários arquivos XLS para XLSX pelo navegador.**

Recebe planilhas, processa suas abas com pandas e entrega os arquivos convertidos em um ZIP para download.

`Python` `Flask` `pandas` `HTML` `JavaScript`

[Ver a implementação](https://github.com/FassoloLucas/Conversor2)

---

## IA, Aplicações Web e Automação

### [Mundo das IAs (Vila Nova)](https://github.com/FassoloLucas/mundo-das-ias)

**Uma cidade simulada para explorar decisões de agentes de IA.**

Simulação experimental com moradores, economia e eleições. Um motor Python valida as ações dos agentes; FastAPI e WebSocket atualizam o mapa e os indicadores no navegador. Inclui um modo offline com decisões heurísticas.

`Python` `FastAPI` `WebSocket` `JavaScript` `Agentes de IA`

[Conhecer a simulação](https://github.com/FassoloLucas/mundo-das-ias)

### [J.A.R.V.I.S. (Assistente de voz)](https://github.com/FassoloLucas/jarvis-assistente)

**Um protótipo que conecta voz, IA e automação do PC.**

Reúne interface desktop no Windows, reconhecimento e síntese de voz e ferramentas acionadas por um modelo de linguagem. Inclui backend FastAPI e cliente Flutter com chat e voz.

`Python` `FastAPI` `Flutter` `Dart` `MongoDB` `LLMs`

[Explorar o assistente](https://github.com/FassoloLucas/jarvis-assistente)

### [10 e Faixa (Gestão de vendas)](https://github.com/FassoloLucas/10efaixa2)

**Organização de produtos, estoque e vendas em uma aplicação web.**

Projeto com backend Flask e frontend em HTML, CSS e JavaScript. A interface reúne visão geral, compras, produtos, estoque, registro de vendas e clientes.

`Python` `Flask` `HTML` `CSS` `JavaScript` `PostgreSQL`

[Explorar o projeto](https://github.com/FassoloLucas/10efaixa2)

### [TV no PC](https://github.com/FassoloLucas/tv-no-pc)

**O celular vira controle remoto; o PC vira uma experiência de TV box.**

Integra um servidor Node.js no Windows ao LDPlayer por ADB. O controle funciona pelo navegador ou por um app Android próprio, com descoberta do PC na rede local, touchpad, digitação e comandos de reprodução.

`JavaScript` `Node.js` `PowerShell` `Java` `Android` `ADB`

[Ver código e instruções](https://github.com/FassoloLucas/tv-no-pc#como-funciona)

### [Bot de música para Discord](https://github.com/FassoloLucas/discord-music-bot)

**Música com comandos de barra, botões e playlists persistentes.**

Bot Python com fila por servidor, controles de reprodução e playlists salvas. Integra discord.py, yt-dlp e FFmpeg, com testes de lógica local e scripts de implantação para Ubuntu/systemd.

`Python` `discord.py` `yt-dlp` `FFmpeg`

[Ver código e documentação](https://github.com/FassoloLucas/discord-music-bot)

---

## O que você encontra por aqui

- **Sistemas Contábeis e Fiscais:** automação de fechamento, auditoria de SPED/XML, conciliações complexas e integração direta com banco de dados de ERP (Oracle).
- **Aplicações Web e APIs:** backends em FastAPI e Flask, geração de relatórios de alta performance (Excel e PDF) e processamento de dados com pandas.
- **IA Aplicada:** assistentes contextuais, leitura de documentos e simulação de agentes.
- **Integração entre dispositivos:** comunicação em rede local, apps mobile e automação no Windows.
