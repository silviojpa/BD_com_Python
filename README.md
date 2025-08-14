Projeto de Conexão Python com Bancos de Dados Diversos
Este repositório é um projeto de estudo e demonstração que explora a conexão e interação da linguagem Python com uma variedade de tecnologias de banco de dados, tanto relacionais (SQL) quanto não-relacionais (NoSQL). Cada pasta numerada representa um módulo de estudo focado em uma tecnologia específica.

O objetivo é servir como um guia prático e um portfólio de exemplos de código para tarefas comuns de manipulação de dados, desde a conexão inicial até operações de CRUD (Create, Read, Update, Delete) e processos de ETL.

⚠️ Aviso Importante sobre Credenciais
As credenciais (logins, senhas, chaves de API, etc.) utilizadas durante o desenvolvimento e os commits deste projeto foram criadas exclusivamente para fins de teste e demonstração. Elas não são mais válidas e foram revogadas.

Nunca exponha suas credenciais reais em repositórios públicos. Sempre utilize métodos seguros como variáveis de ambiente, cofres de segredos (vaults) ou arquivos de configuração locais (incluídos no .gitignore) para gerenciar dados sensíveis em seus projetos.

Tecnologias Abordadas
Abaixo está uma visão geral de cada tecnologia explorada neste projeto e como ela se integra com o ecossistema Python.

01. PostgreSQL com Python
O que é? O PostgreSQL é um poderoso sistema de gerenciamento de banco de dados relacional de código aberto, conhecido por sua robustez, conformidade com os padrões SQL e recursos avançados como suporte a tipos de dados complexos e transações ACID.

Uso com Python: A integração é comumente realizada com a biblioteca psycopg2, o adaptador de banco de dados mais popular e estável para PostgreSQL. Com ele, é possível executar queries SQL, gerenciar transações e manipular dados de forma eficiente e segura diretamente de um script Python.

02. MySQL com Python
O que é? O MySQL é um dos sistemas de gerenciamento de banco de dados relacional mais populares do mundo, amplamente utilizado em aplicações web, desde pequenos blogs até grandes plataformas de e-commerce. É conhecido por sua velocidade e confiabilidade.

Uso com Python: A conexão é feita através de drivers oficiais como o mysql-connector-python. Ele fornece uma API completa para estabelecer conexões, criar cursores, executar comandos SQL e processar os resultados, tornando simples a integração de aplicações Python com bancos de dados MySQL.

03. SQLite com Python
O que é? O SQLite é uma biblioteca em linguagem C que implementa um banco de dados SQL embutido, autocontido, sem a necessidade de um servidor. O banco de dados inteiro é armazenado em um único arquivo no disco, tornando-o extremamente portátil e ideal para aplicações mobile, desktop ou como uma base de dados leve para prototipagem.

Uso com Python: A grande vantagem é que o módulo sqlite3 já faz parte da biblioteca padrão do Python. Não é necessário instalar nada. Isso o torna a escolha perfeita para iniciar estudos com bancos de dados relacionais em Python, permitindo a criação e manipulação de tabelas com comandos SQL padrão de forma direta e descomplicada.

04. ETL com Pandas
O que é? ETL é a sigla para Extract, Transform, Load (Extrair, Transformar, Carregar). É um processo fundamental em engenharia de dados para mover dados de diversas fontes, limpá-los, processá-los e carregá-los em um destino final, como um Data Warehouse.

Uso com Python: A biblioteca Pandas é a principal ferramenta para a etapa de Transformação em processos de ETL com Python. Seus DataFrames fornecem uma estrutura poderosa e flexível para ler dados de várias fontes (CSV, Excel, bancos de dados), realizar limpeza, aplicar regras de negócio, agregar informações e, por fim, exportar os dados tratados para o destino desejado.

05. SQL Server com Python
O que é? O Microsoft SQL Server é um sistema de gerenciamento de banco de dados relacional desenvolvido pela Microsoft. É amplamente utilizado em ambientes corporativos e se integra profundamente com outras tecnologias da Microsoft, como o .NET.

Uso com Python: A conexão é tipicamente realizada utilizando a biblioteca pyodbc, um módulo que permite a conexão com qualquer banco de dados que suporte o padrão ODBC (Open Database Connectivity). Com o driver ODBC correto para SQL Server instalado, o pyodbc permite que aplicações Python executem consultas e gerenciem dados em bancos SQL Server de forma transparente.

06. APIs com Python
O que é? Uma API (Application Programming Interface) é um conjunto de regras e protocolos que permite que diferentes sistemas de software se comuniquem. No contexto de dados, as APIs são frequentemente usadas para buscar ou enviar informações para serviços web.

Uso com Python: Python é uma linguagem excelente tanto para consumir quanto para criar APIs. Para consumir, a biblioteca requests é o padrão de fato, simplificando o envio de requisições HTTP (GET, POST, etc.) para obter dados de serviços externos. Para criar APIs, frameworks como FastAPI e Flask permitem construir serviços web robustos e de alta performance de forma rápida e intuitiva.

07. Google BigQuery com Python
O que é? O Google BigQuery é um Data Warehouse na nuvem, totalmente gerenciado e sem servidor, projetado para analisar petabytes de dados usando SQL em alta velocidade. É um componente central da Google Cloud Platform para análise de Big Data.

Uso com Python: A interação é feita através da biblioteca cliente oficial google-cloud-bigquery. Ela permite que os desenvolvedores executem consultas, gerenciem datasets e tabelas, e carreguem ou exportem grandes volumes de dados programaticamente, integrando o poder de análise do BigQuery diretamente em fluxos de trabalho e aplicações Python.

08. MongoDB com Python
O que é? O MongoDB é o banco de dados NoSQL orientado a documentos mais popular do mercado. Ele armazena dados em documentos flexíveis, do tipo JSON (chamados de BSON), o que permite que os esquemas de dados evoluam facilmente com o tempo. É ideal para aplicações com dados não estruturados ou semiestruturados.

Uso com Python: A conexão é realizada com o driver oficial pymongo. Ele fornece uma interface idiomática e simples para interagir com o MongoDB, permitindo a execução de todas as operações de CRUD, buscas complexas, agregações e o gerenciamento de índices, tudo de forma nativa e eficiente dentro do código Python.
