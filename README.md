# Daniel Lourenço Peçanha

**Analista de Sistemas e Dados | Oracle SQL/PLSQL | Python | Tasy | TI Hospitalar**

![Oracle](https://img.shields.io/badge/Database-Oracle-red)
![PL/SQL](https://img.shields.io/badge/Language-PL%2FSQL-blue)
![Python](https://img.shields.io/badge/Language-Python-yellow)
![Healthcare](https://img.shields.io/badge/Domain-TI%20Hospitalar-critical)
![Big Data](https://img.shields.io/badge/Focus-Big%20Data%20%26%20Analytics-green)

---

## 📑 Índice

- [🎯 Perfil profissional](#-perfil-profissional)
- [🧭 Competências principais](#-competências-principais)
- [🏥 Experiência em ambiente hospitalar](#-experiência-em-ambiente-hospitalar)
  - [Sistemas hospitalares e Tasy](#sistemas-hospitalares-e-tasy)
  - [Investigação técnica com Oracle SQL](#investigação-técnica-com-oracle-sql)
- [🧠 Projetos e automações](#-projetos-e-automações)
  - [Automação de agenda do SAME](#1-automação-de-agenda-do-same)
  - [Conciliação entre internações e faturamento SUS](#2-conciliação-entre-internações-e-faturamento-sus)
  - [Projeto Paperless](#3-projeto-paperless)
  - [Análise e otimização de consultas SQL](#4-análise-e-otimização-de-consultas-sql)
  - [Implantação de telefonia IP](#5-implantação-de-telefonia-ip)
- [🧩 Stack técnica](#-stack-técnica)
- [📂 Repositórios](#-repositórios)
- [🎓 Formação](#-formação)
- [📈 Trajetória profissional](#-trajetória-profissional)
- [🔬 Abordagem de trabalho](#-abordagem-de-trabalho)
- [🚀 Próximos passos](#-próximos-passos)
- [📫 Contato](#-contato)

---

## 🎯 Perfil profissional

Profissional com **mais de 9 anos de experiência em ambiente hospitalar**, com atuação em processos administrativos e assistenciais e experiência em **TI hospitalar, sustentação de sistemas, análise de dados e automação de rotinas**.

Trabalho na interface entre sistema, processo e dado: investigo falhas, analiso regras de negócio, valido informações em bases Oracle e busco alternativas para reduzir trabalho manual e melhorar a rastreabilidade das operações.

Minha experiência inclui o ERP hospitalar **Tasy**, consultas com **Oracle SQL/PLSQL**, automações em **Python** e análises relacionadas a fluxos assistenciais, SAME, auditoria e faturamento SUS. Atualmente, curso **Big Data e Inteligência Analítica**, direcionando meu desenvolvimento para análise e engenharia de dados.

**Áreas de interesse:**

- Análise e sustentação de sistemas;
- Investigação de incidentes e análise de causa raiz;
- Oracle SQL, DQL do Tasy e validação de dados;
- Automação de processos com Python;
- Indicadores, modelagem analítica e qualidade de dados;
- Integração entre processos hospitalares e sistemas de informação.

---

## 🧭 Competências principais

| Área | Aplicação prática |
|---|---|
| Sistemas hospitalares | Sustentação funcional do Tasy, análise de chamados, validação de regras e apoio aos usuários |
| Oracle SQL/PLSQL | Consultas analíticas, cruzamento de dados, identificação de inconsistências e investigação de comportamento do sistema |
| Python | Automatização de tarefas, tratamento de dados e geração padronizada de planilhas e relatórios |
| Processos hospitalares | Entendimento dos fluxos de admissão, movimentação, alta, SAME, auditoria e faturamento |
| Análise de dados | Estruturação de informações, conferência de indicadores e preparação para análise dimensional e BI |
| Suporte técnico | Testes, homologação, análise de logs, verificação de integrações e documentação de ocorrências |

---

## 🏥 Experiência em ambiente hospitalar

Minha trajetória na saúde começou em atividades administrativas e evoluiu para experiências que conectam operação hospitalar, sistemas e dados. Esse percurso permite analisar problemas considerando não apenas o comportamento técnico da aplicação, mas também o processo de negócio e os efeitos sobre as áreas envolvidas.

### Sistemas hospitalares e Tasy

Atuação em atividades de sustentação e suporte funcional, incluindo:

- Análise e encaminhamento de chamados relacionados ao ERP Tasy;
- Investigação de falhas sistêmicas e validação de regras de negócio;
- Administração operacional de usuários, perfis e permissões;
- Testes e homologação de correções ou mudanças;
- Análise de dados para apoiar a identificação de divergências;
- Interface com equipes assistenciais, administrativas, fornecedores e áreas de suporte.

O entendimento dos fluxos hospitalares ajuda a avaliar os impactos das ocorrências desde a admissão e movimentação do paciente até a alta, os registros administrativos e o faturamento.

### Investigação técnica com Oracle SQL

Utilizo consultas Oracle para investigar dados e apoiar a análise de ocorrências. Entre as técnicas aplicadas estão:

- CTEs (*Common Table Expressions*);
- Junções, subconsultas e agregações;
- Funções analíticas e *window functions*;
- Comparações entre bases e validações cruzadas;
- Identificação de registros duplicados, ausentes ou inconsistentes;
- Análise de filtros, cardinalidade e custo de execução em consultas selecionadas.

Exemplos de aplicação incluem a conferência entre censo hospitalar e faturamento, a construção de consultas para indicadores e a investigação de divergências entre informações de diferentes etapas do processo.

---

## 🧠 Projetos e automações

Os projetos abaixo representam aplicações práticas de análise de processos, programação e dados no contexto hospitalar. Os impactos informados são estimativas ou resultados observados em rotinas específicas, não garantias de desempenho para qualquer ambiente.

### 1. Automação de agenda do SAME

**Objetivo:** reduzir o trabalho manual necessário para transformar agendas disponibilizadas em PDF em planilhas padronizadas.

**Fluxo da solução:**

1. Leitura e extração das informações do PDF;
2. Tratamento e normalização dos dados;
3. Padronização das colunas e organização dos registros;
4. Exportação para Excel em formato estruturado.

**Tecnologias:** Python, Pandas e XlsxWriter.

**Resultado observado:** redução estimada de aproximadamente **60% no tempo operacional** da rotina.

**Repositório:**

- [Documentação](https://github.com/archfull/Same/blob/main/README.md)
- [Notebook Jupyter](https://github.com/archfull/Same/blob/main/Same_ListaConsulta.ipynb)
- [Código e arquivos do projeto](https://github.com/archfull/Same)

### 2. Conciliação entre internações e faturamento SUS

**Objetivo:** automatizar a conferência entre informações do censo/movimentação hospitalar e registros de faturamento de AIH.

A solução auxilia na identificação de divergências relacionadas a:

- Clínica;
- Caráter da internação;
- Tipo de alta, incluindo óbito;
- Data de alta;
- Diferenças entre os registros assistenciais e de faturamento.

**Tecnologias:** Python, Pandas e geração automatizada de relatórios.

**Resultado observado:** uma conferência que demandava cerca de **duas horas de execução manual** passou a ser processada em segundos, permitindo repetir a validação com maior frequência e manter uma trilha estruturada das divergências encontradas.

**Repositório:**

- [Documentação](https://github.com/archfull/Faturamento/blob/main/README.md)
- [Notebook Jupyter](https://github.com/archfull/Faturamento/blob/main/Bate_faturamento.ipynb)
- [Código e arquivos do projeto](https://github.com/archfull/Faturamento)

### 3. Projeto Paperless

**Contexto:** implantação de fluxo digital de documentos e prontuários, com recursos de assinatura digital e integração entre componentes do ambiente.

**Atividades técnicas realizadas:**

- Investigação de falhas a partir de logs e comportamento da aplicação;
- Análise do código principal e de configurações da API;
- Verificação de dados trafegados na integração;
- Desenvolvimento de script Python para automatizar uma rotina de limpeza de cache da API EVAL;
- Distribuição e padronização da execução do script no ambiente Windows por meio de GPO.

**Resultado:** redução da intervenção manual em uma ocorrência recorrente; a execução automatizada da rotina de limpeza passou a levar menos de **5 segundos**. O trabalho também contribuiu para a estabilidade operacional do fluxo digital.

### 4. Análise e otimização de consultas SQL

Investigação de consultas Oracle utilizadas em relatórios e rotinas hospitalares, com comparação de resultados e do comportamento de execução antes e depois das alterações.

Em consultas específicas, foram observadas reduções de tempo como:

| Tempo anterior | Tempo posterior |
|---:|---:|
| 18 segundos | 3 segundos |
| 8 segundos | 1,7 segundo |
| 45 segundos | 5 segundos |

Os resultados variam conforme a consulta, os filtros, o volume de dados e as condições de execução. A abordagem prioriza preservar o resultado funcional e validar a melhoria por comparação, em vez de alterar a consulta apenas por estilo.

**Repositório:** [Oracle SQL Tuning](https://github.com/archfull/oracle-sql-tuning)

### 5. Implantação de telefonia IP

Participação no processo de transição para telefonia IP, com atividades de configuração de aparelhos e apoio operacional à implantação e à adaptação dos usuários ao novo ambiente.

---

## 🧩 Stack técnica

### Banco de dados

- **Oracle SQL:** consultas, junções, subconsultas, CTEs, agregações e funções analíticas;
- **PL/SQL:** conhecimentos aplicados à leitura e investigação de rotinas no ambiente Oracle;
- **DQL do Tasy:** consultas e extrações voltadas a necessidades operacionais e analíticas;
- Análise de consistência, cruzamento de dados e investigação de divergências.

### Programação e automação

- **Python:** automação de tarefas e transformação de dados;
- **Pandas:** tratamento, validação e consolidação de dados;
- **XlsxWriter:** geração de planilhas Excel formatadas;
- **Jupyter Notebook:** desenvolvimento e documentação de análises.

### Sistemas e ambiente corporativo

- **ERP Tasy:** suporte funcional e investigação de ocorrências;
- **Windows e Active Directory:** rotinas de ambiente, usuários e permissões;
- **GLPI e ManageEngine:** utilização de ferramentas de chamados e suporte;
- **Interact Suite e Google Workspace:** ferramentas do ambiente corporativo;
- **GPO:** distribuição e padronização de execução de scripts em ambiente Windows.

### Dados e BI

- Fundamentos de modelagem relacional e dimensional;
- Estruturação e validação de indicadores;
- Preparação de dados para análise;
- **Power BI:** desenvolvimento em andamento, integrado à formação em análise de dados.

---

## 📂 Repositórios

| Repositório | Descrição |
|---|---|
| [Same](https://github.com/archfull/Same) | Automação de agenda do SAME: extração de PDF e geração de planilha estruturada |
| [Faturamento](https://github.com/archfull/Faturamento) | Conciliação entre censo/movimentação hospitalar e faturamento de AIH |
| [Oracle SQL Tuning](https://github.com/archfull/oracle-sql-tuning) | Estudos e exemplos de análise e otimização de consultas Oracle |

---

## 🎓 Formação

**Tecnólogo em Big Data e Inteligência Analítica — FMU**  
Em andamento · 2025–2028

Formação complementar relevante:

- Fundamentos de Linguagem Python — Data Science Academy (96 horas);
- Python para Análise de Dados — Data Science Academy;
- Introdução à Ciência de Dados — Santander Open Academy;
- Programação Orientada a Objetos — Fundação Bradesco;
- ESG: fundamentos e métricas — FGV;
- Relações Trabalhistas — FGV;
- Cooperativismo — FGV;
- Colaboração e Engajamento em Grupo — FGV.

---

## 📈 Trajetória profissional

| Período | Experiência e desenvolvimento |
|---|---|
| 2017–2018 | Jovem Aprendiz no SAME, com atividades de arquivo, prontuários e documentação hospitalar |
| 2018–2020 | Auxiliar Administrativo, com experiência no SAME e no setor de Diagnóstico por Imagem |
| 2020–atual | Assistente Administrativo na SPDM, com experiências em TI/TIC, SAME, estatística e auditoria hospitalar |
| 2023–atual | Evolução em análise de sistemas, investigação de dados e automação de rotinas hospitalares |
| 2025–2028 | Formação superior em Big Data e Inteligência Analítica, em andamento |

---

## 🔬 Abordagem de trabalho

Na investigação de problemas, procuro relacionar quatro dimensões:

1. **Sintoma:** o que falhou, em qual etapa e com qual impacto;
2. **Evidência:** logs, dados, consultas, parâmetros e comportamento reproduzível;
3. **Regra de negócio:** o resultado esperado pelo processo e pelo sistema;
4. **Validação:** teste da hipótese, conferência do resultado e registro da solução.

Essa abordagem orienta meu trabalho em sustentação de sistemas, análise de dados e automação. Priorizo organização, rastreabilidade, comunicação objetiva e soluções que reduzam retrabalho sem comprometer as regras do processo.

---

## 🚀 Próximos passos

- Construir um projeto demonstrativo de Data Warehouse com dados hospitalares sintéticos;
- Implementar um pipeline ETL documentado, com etapas de extração, transformação e carga;
- Desenvolver análises estatísticas e indicadores a partir de dados públicos ou simulados;
- Aprofundar modelagem dimensional, Power BI e fundamentos de engenharia de dados;
- Ampliar a documentação técnica dos projetos com instruções de execução, exemplos e testes.

---

## 📫 Contato

- **LinkedIn:** [linkedin.com/in/daniel-lourenco-pecanha-692b8b168](https://www.linkedin.com/in/daniel-lourenco-pecanha-692b8b168/)
- **E-mail:** [Daniel_Gabriel.LP@hotmail.com](mailto:Daniel_Gabriel.LP@hotmail.com)

---

> Este portfólio apresenta minha experiência em sistemas hospitalares, investigação com Oracle SQL e automação com Python, além da evolução em andamento para análise e engenharia de dados aplicada à saúde.
