# Lumini Hire Test
Se você recebeu o link para este documento, está no caminho certo, o intuito é avaliar nossos candidatos, seguindo critérios que os deixem mais livres para a realização dos desafios, assim, podemos avaliar a capacidade criativa de cada candidato, bem como a originalidade, sem a necessidade que tenham que realizar um teste técnico diretamente dentro de nosso escritório, o que pode atrapalhar o tempo do candidato e a disponibilidade de alguém para aplicar os testes.

Abaixo, seguem os testes para diferentes perfis: Data Scientist, Web Designer e Fullstack Developer.

# Data Scientist
## Objetivo

Testar as habilidades do candidato em técnicas de análise exploratória de dados.

## Critérios de Avaliação

* A análise exploratória deve ser reprodutível
* O relatório deve explicar clara e concisamente os conceitos estatísticos envolvidos nas análises e nos testes de hipótese, se aplicáveis
* Cada gráfico deve conter legendas, eixos com títulos significativos e uma breve descrição do motivo de haver sido construído
* Referências de citações

## Desafio

Neste teste, peço a v. que utilize os dados anexos em um exercício de análise exploratória. Trata-se de uma amostra de inscrições no ENEM de 2016. Utilize as tecnologias, processos e métodos que você preferir para criar um caderno de apresentação do conteúdo descoberto que **contenha o código utilizado e seja reprodutível**.

Além da análise exploratória livre, aborde o seguinte problema:

* Como é possível segmentar os inscritos de forma clara e objetiva com o intuito de justificar investimentos em educação destinados a certas parcelas de alunos?

É obrigatório o uso da sua conta Github para realizar o Fork deste repositório e enviar pull-request ao término do desafio, para sabermos se possui conhecimentos básicos de como funciona a ferramenta git.

* Boas técnicas e conhecimentos em DataViz são um diferencial.

## Requisitos

* Python, R ou ML.NET

## Suprimentos
Os arquivos necessários para a realização do desafio está na pasta "sample_data", chama-se "[Microdados_Enem_2016.zip](https://github.com/lumini-it-solutions/lumini-hire-test/raw/master/sample_data/Microdados_Enem_2016.zip)".

------------------------------------------------------------------------

# Web Designer (Front-End)
## Objetivo
Testar as habilidades dos candidatos em desenvolvimento de UX e UI, além de diagramação (quando necessário).

Desconsiderar os arquivos já existentes neste repositório, crie novos.

É obrigatório o uso da sua conta Github para realizar o Fork deste repositório e enviar pull-request ao término do desafio, para sabermos se possui conhecimentos básicos de como funciona a ferramenta git.

## Critérios de Avaliação
* Aparência
* Criatividade
* Originalidade
* Coerência
* Semântica
* Reusabilidade
* Documentação

## Desafio
Criar uma SPA (Single Page Application) de um site empresarial (fictício), estático, com efeitos visuais coerentes.

Diagramar um Layout Dashboard (cores, gráficos, fontes, disposição de elementos e efeitos visuais como transição ou animação em gráficos).

# Requisitos
* Documentar as técnicas e ferramentas utilizadas.
* Não usar Angular, React ou outro Framework do gênero.
* HTML 5
* CSS 3
* ECMAScript
* Pode usar ferramentas padrões de mercado como: Bootstrap, JQuery, D3, etc.

------------------------------------------------------------------------

# Fullstack Developer
## Objetivo
Testar as habilidades dos candidatos em desenvolvimento C# .NET Core.

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

## Desafios de Desenvolvimento
O candidato é livre a usar as técnicas de desenvolvimento que achar melhor, desde que atenda os requisitos. Para dev Jr e Pleno, desconsiderar os arquivos já existentes neste repositório, crie novos.

Poderá incrementar o desafio com funcionalidades dentro do mesmo escopo, caso faça bem feito, terá destaque com pontuação extra, use a criatividade.

O Layout não é relevante, mas uma boa apresentação tem destaque. Semântica HTML não é levada em consideração.

É obrigatório o uso da sua conta Github para realizar o Fork deste repositório e enviar pull-request ao término do desafio, para sabermos se possui conhecimentos básicos de como funciona a ferramenta git.

### Dev Jr
Criar um blog utilizando Razor Pages ou MVC com banco de dados SQLite, os posts devem poder serem lidos sem precisar se autenticar na aplicação, contudo, para poder publicar um novo artigo, é preciso estar registrado no blog.

### Requisitos
* dotnet core 2.2 ou superior.
* Tem que rodar em qualquer sistema operacional.
* SQLite
* Bootstrap
* Razor Pages ou MVC
* ASP.NET Identity

### Dev Pleno
Criar uma aplicação para controle de estoque, com saída e entrada de notas fiscais e produtos. As telas de gestão deverão estar com acesso restrito para usuários registrados, uma tela pública (sem autenticação) para consulta de estoque deverá existir.

### Requisitos
* dotnet core 2.2 ou superior.
* Tem que rodar em qualquer sistema operacional.
* SQLite
* Bootstrap
* Razor Pages ou MVC
* ASP.NET Identity

### Dev SR
Realizar a ingestão dos dados em "sample_data", "[CollegeScorecard_Raw_Data.zip](https://github.com/lumini-it-solutions/lumini-hire-test/raw/master/sample_data/CollegeScorecard_Raw_Data.zip)", a carga deverá ser realizada para dentro de um Elasticsearch, em um índice nomeado como "scorecard". Criar uma aplicação com Dashboard (acesso privado) para a visualização e uma pesquisa dos dados (acesso público).

### Requisitos
* dotnet core 2.2 ou superior.
* Tem que rodar em qualquer sistema operacional.
* SQLite
* Bootstrap
* Razor Pages ou MVC
* ASP.NET Identity
* Elasticsearch
