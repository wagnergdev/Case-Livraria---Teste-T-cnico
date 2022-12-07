### 1. Para você, o que significa Business Inteligence ?

        Business Inteligence significa extrair informações de valor agregado, através da coleta de dados diversos de uma ou mais fontes diferentes, armazenando em um repositório central e disponibilizando as informações aos tomadores de decisão de forma rápida, fácil e intuitiva.

### 2. Cite duas ferramentas de ETL

	- SQL
	- Python(Pandas)

### 3. Cite três ferramentas de apresentação de Dados

	- Power BI
	- Tableau
	- Qlik Sense

### 4. O que é uma Tabela Fato e o que é uma tabela Dimensão ?

        Fato: É uma tabela onde contém informações do evento a ser analisado, no geral, cada registro representa um fato e é esperado que tenha ao menos uma coluna com informações de Data, Valor e Identificação Única deste determinado fato.

        Dimensão: São tabelas que armazenam informações de outros atributos que estão relacionadas a tabela fato, costumam informar o quê, quando, quem e onde os fatos foram gerados. No geral, as tabelas dimensões são normalizadas o que significa que não há registros duplicados para uma mesma informação, a fim de criar uma relação de 1 para N com a tabela fato.

### 5. Quais tipos de modelagens são as mais utilizadas em um projeto de BI ?

        Diferente da modelagem OLTP comumente encontrado em ERP's que visam a performance de escrita de dados, em um projeto de BI a modelagem mais comum é a OLAP, que visa a performance de leitura e análise de dados. Nela são extraídos os dados de acordo com modelos conceituais já previamente elaborados, preferêncialmente em Star Schema ou Snow Flake Schema, e armazenados em repositórios chamados de Data Warehouse, Data Mart ou Data Lake a depender da complexididade e quantidade de informações disponíveis e visuais desejados.

### 6. O que significa Surrogate Key ?

        É uma chave substituta a chave derivada originalmente da sua natureza de informação ou mesmo a chave primária de um banco de dados. Ela pode ser criada a partir dos seus atributos a fim de relacionar tabelas que foram modeladas de forma diferente da original, para cumprir determinadas análises em squemas que favorecem esse tipo de aplicação.

### 7. Explique a diferença entre relacionamento 1 para 1 e 1 para N

        Em um relacionamento de 1 para 1 cada uma das duas entidades relacionadas são normalizadas e terão apenas um registro único correspontente a outra e vice versa, sem coexistir nenhuma redundância das informações de chave/valor em ambas tabelas.

        Em um relacionamento de 1 para N, apenas a primeira entidade é caracterizada por um registro único sem redundâncias, enquanto na segunda, é possível ter N registros que referem-se a primeira, relacionando por meio de uma chave estrangeira conferindo atributos adicionais para determinado registro.

### 8. O que significa Drill Down / Drill Up ?

        Significa conseguir percorrer por diferentes filtros de hierarquias de atributos de determinada informação em um determinado visual.
