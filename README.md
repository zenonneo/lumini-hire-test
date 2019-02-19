# Lumini Hire Test

## Objetivo
Testar as habilidades de novos candidatos a cargos de Desenvolvedor C#.

## Critérios de Avaliação
* Legibilidade de Código
* Originalidade
* Reusabilidade
* Lógica
* Conhecimentos na Linguagem C# e no Framework dotnet core
* Criatividade
* Coerência
* Velocidade
* Documentação

## Requisitos de Sistema
* dotnet core 2.2.104
* sem depêndencia de Sistema Operacional ou ferramentas de plataforma fechada (Excel)

## Desafios de Desenvolvimento
Criar uma aplicação com autenticação por usuário e senha utilizando banco local (SQLite), também poderá ser utilizado, caso tenha conhecimento, Elasticsearch (6.3) para a carga dos dados massivos disponíveis em sample_data, caso considere pouco tempo, poderá criar seu próprio sample de aplicação com CRUD, telas de cadastro (privadas) e de consulta (públicas).

Dashboard com gráficos que agregam as informações no banco e demonstrem de forma concisa.

Os dados em sample_data foram extraídos de uma [fonte pública](https://catalog.data.gov/dataset/college-scorecard) e possui um [catálogo público de referência](https://collegescorecard.ed.gov/). Os dados referem-se à **Scorecard Universitário**.

Para consumir esses dados, também é proposto a criação de um **Console Application** para a carga dos arquivos CSV (apenas) para o banco de dados ou para o elasticsearch.

O candidato é livre a usar as técnicas de desenvolvimento que achar melhor, desde que atenda os requisitos mínimos (primeiro parágrafo) no prazo.

## Prazo
É dado ao candidato o prazo de 5 dias úteis para desenvolver a aplicação após o disparo de e-mail com solicitação de fork deste projeto.

## Requisitos - Dev JR
CRUD com três consultas, cadastros, edições, exclusões com autenticação e três telas de listagem pública.
Usar SQLite para o banco de dados.
Usar bootstrap para a criação das telas.

## Requisitos - Dev PL
Mesmo que Dev JR + Dashboard de gráficos para "gestão" dos dados cadastrados e coletor de dados que leia todos os arquivos CSV do sample data e os carregue em uma base de dados. Usar ajax para carga de dados (ou angular/react).

## Requisitos - Dev SR
Mesmo que Dev PL + Coletor precisa realizar processamento paralelo com otimização de processamento e memória para leitura por stream (sem leitura completa em memória) e carga dos dados em Elasticsearch (6.3), os dados devem ser exibidos no dashboard, o site de catálogo serve como exemplo para idéias de gráficos e análises.
