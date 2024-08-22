#Dataset de Citações Históricas

##Descrição
Este dataset contém uma coleção de citações históricas extraídas de fontes públicas, incluindo Wikiquote, com foco em uma ampla variedade de figuras históricas, temas e publicações. O objetivo principal deste dataset é fornecer material para fins de pesquisa e desenvolvimento de modelos de inteligência artificial, como sistemas de Recuperação de Informação Aumentada por Geração (RAG).

##Aviso de Conteúdo Sensível
Este dataset pode conter citações de figuras históricas que propagaram ódio, preconceito ou violência. As citações refletem o contexto histórico e cultural da época em que foram proferidas ou atribuídas. Os usuários devem estar cientes de que algumas atribuições podem ser controversas ou incorretas.

###Aviso importante:

####Conteúdo Sensível: Algumas citações podem incluir linguagem ou ideias que são consideradas ofensivas, preconceituosas ou violentas.
Atribuições Erradas: Algumas citações incluídas podem estar incorretamente atribuídas a certas figuras históricas. Esse problema é comum em registros históricos e em fontes secundárias, incluindo a internet.

####Contextualização do Uso
Este dataset foi compilado para fins de pesquisa e desenvolvimento de modelos de IA. Qualquer uso público, educacional ou em produção deve considerar o contexto histórico das citações e, se necessário, incluir notas explicativas para esclarecer a atribuição correta ou para adicionar contexto adicional.

##Formato do Arquivo CSV
O dataset é disponibilizado no formato CSV (Comma-Separated Values), que é um formato de texto simples utilizado para armazenar dados tabulares. No arquivo CSV, cada linha representa uma citação, e as colunas são separadas por ponto e vírgula (;).

###Estrutura do Arquivo CSV:
Coluna 1: Autor_Tema_Publicação
Esta coluna pode conter o nome do autor, um tema específico, ou a referência a uma publicação de onde a citação foi extraída. A mesma coluna é utilizada para armazenar todas essas informações.
Coluna 2: Citação
O texto da citação atribuída ao autor/tema/publicação correspondente.

Exemplo de Dados CSV:
plaintext
Copy code
Autor_Tema_Publicação;Citação
"Albert Einstein";"A imaginação é mais importante que o conhecimento."
"Nelson Mandela";"A educação é a arma mais poderosa que você pode usar para mudar o mundo."
"Mahatma Gandhi";"Seja a mudança que você deseja ver no mundo."
"Ciência";"A ciência é o grande antídoto contra o veneno do entusiasmo e da superstição."
"Livro: O Pequeno Príncipe";"O essencial é invisível aos olhos."
Como Utilizar:
Planilhas: O arquivo CSV pode ser aberto em programas de planilhas como Microsoft Excel, Google Sheets, ou LibreOffice Calc, permitindo que você visualize e manipule os dados de forma fácil.
Linguagens de Programação: Linguagens de programação como Python, R, ou Julia possuem bibliotecas para leitura de arquivos CSV, permitindo que os dados sejam utilizados em scripts ou modelos de machine learning.
Bancos de Dados: O arquivo CSV pode ser importado para bancos de dados como MySQL, PostgreSQL, ou SQLite para consulta e manipulação mais avançada dos dados.
Filtragem por Autor/Tema/Publicação
Se você deseja trabalhar apenas com um subconjunto dos dados, como apenas autores ou apenas temas específicos, pode utilizar ferramentas de planilhas ou scripts personalizados para filtrar as linhas com base no conteúdo da coluna "Autor/Tema/Publicação". Isso permitirá que você extraia apenas os dados mais relevantes para sua aplicação.

##Licenciamento
Este dataset foi gerado utilizando dados públicos da Wikiquote, que estão disponíveis sob os seguintes termos de licenciamento:

Creative Commons - Atribuição - Compartilhamento pela mesma licença 4.0 Internacional (CC BY-SA 4.0)
Licença GNU de Documentação Livre (GFDL), versão original, sem seções invariantes, textos de capa ou contracapa.
Dá-se autorização para copiar, distribuir e/ou modificar este documento segundo os termos das licenças acima mencionadas. Uma cópia da Licença GNU de Documentação Livre, em tradução oficiosa para português, pode ser encontrada na secção intitulada Wikipédia
Free Documentation License.

O conteúdo utilizado para gerar este dataset está sob os termos dos avisos gerais da Wikimedia.

##Exclusão de Responsabilidade
As citações incluídas neste dataset não refletem as opiniões ou visões do compilador do dataset. Este conteúdo é fornecido "como está", e o uso das citações é de total responsabilidade do usuário. O compilador não endossa as opiniões ou visões contidas nas citações.

##Como Contribuir
Se você identificar atribuições erradas ou tiver sugestões de melhorias para este dataset, por favor, entre em contato. O objetivo é melhorar continuamente a precisão e a utilidade deste recurso.