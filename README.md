# O Papel dos Bancos de Dados SQL e NoSQL na Engenharia de Dados

## O que é um banco de dados?

“Banco de dados” é um sitema capaz de coletar, armazenar e prover informações de consulta de dados.

No mundo digital, por exemplo, só está de pé porque nos bastidores da internet há inúmeros bancos de dados concectados capazes de processar e prover informações a todo momento.

Desde entrar em um site até fazer a compra de um produto em um e-commerce.

## O que é NoSQL?

Vamos começar sobre o NoSQL, o que vem a ser esse conceito ?

Pesquisando pela net, encontramos muitas definições, algumas bem confusas que passam a ideia de um conceito que tenta acabar com o padrão SQL, bem como encontramos também definições mais realistas, que passam a ideia de um padrão de armazenamento de dados alternativo ao SQL, oferecendo uma robustez e escalabilidade melhores.

Para sabermos mais claramente o que é o NoSQL, e qual seu uso, é interessante saber algumas coisas antes.

O termo NoSQL foi primeiramente utilizado em 1998 como o nome de um banco de dados não relacional de código aberto.

Seu autor, Carlo Strozzi, alega que o movimento NoSQL "é completamente distinto do modelo relacional e portanto deveria ser mais apropriadamente chamado "NoREL" ou algo que produzisse o mesmo efeito".

Com a crescente popularização da internet, diversos novos dados foram surgindo e tratá-los foi se tornando gradualmente mais complexo e sua manutenção cada vez mais cara.

Em 2006, o artigo: BigTable: A Distributed Storage System for Structured Data, publicado pelo Google em 2006, traz novamente à tona o conceito NoSQL.

No inicio de 2009, o termo NoSQL é reintroduzido por um funcionário do Rackspace, Eric Evans, quando Johan Oskarson da Last.fm queria organizar um evento para discutir bancos de dados open source distribuídos.

O nome era uma tentativa de descrever o surgimento de um número crescente de bancos de dados não relacionais e fazia uma referência ao esquema de atribuição de nomes dos bancos de dados relacionais mais populares do mercado como MySQL, MS SQL, PostgreSQL, etc.

A partir de então, os bancos de dados não relacionais passaram a ser conhecidos como NoSQL, e com crescente popularização das redes sociais, a geração de conteúdo por dispositivos móveis bem como o número cada vez maior de pessoas e dispositivos conectados, faz com que o trabalho de armazenamento de dados com o objetivo de utilizá-los em ferramentas analíticas, comece a esbarrar nas questões de escalabilidade e custos de manutenção desses dados.

Bancos de dados relacionais escalam, mas quanto maior o tamanho, mais custoso se torna essa escalabilidade, seja pelo custo de novas máquinas, seja pelo aumento de especialistas nos bancos de dados utilizados.

Já os não relacionais, permitem uma escalabilidade mais barata e menos trabalhosa, pois não exigem máquinas extremamente poderosas e sua facilidade de manutenção permite que um número menor de profissionais seja necessário.

Assim, os bancos de dados NoSQL, vão ficando mais populares entre as grandes empresas pois reúnem as características de poder trabalhar com dados semi-estruturados ou crus vindos de diversas origens (arquivos de log, web-sites, arquivos multimídia, etc...).

# Bancos de dados relacionais

Hoje os bancos de dados relacionais são os mais comuns no mercado, como em sistemas ERP e CRM, por exemplo. Tal popularidade é conquistada pela facilidade da armazenagem e pela confiabilidade das informações.

Ele funciona da seguinte maneira: os dados são armazenados em formatos tubulares, ou seja, o dado fica na coluna, enquanto a descrição fica em linhas e atributos. A importância dos bancos de dados relacionais é constituída a partir dos pilares ACID, que é a sigla referente a atomicidade, consistência, isolamento e durabilidade. 

## Qual a importância do SQL para os Bancos de Dados não relacionais?

Por fim, uma outra característica importante é sua linguagem, que é baseada no SQL (Structured Query Language). É justamente por isso que a categoria relacional é considerada fácil, pois a inserção dos dados é fácil e recuperável. Vale ressaltar que a maioria dos tipos de banco de dados usam o SQL. 

## Bancos de dados não-relacionais

Utilizamos o não-relacional toda vez que precisamos trabalhar com dados que não podem ser inseridos em formato tabela, como imagens, vídeos e gráficos. Ele tem uma alta performance e por essa razão é muito valorizado no mercado, todos os registros são feitos em um mesmo lugar.

Em decorrência disso, os bancos de dados não-relacionais dispensam a utilização de um sistema de relacionamento, diferentemente de um banco de dado relacional. Sua linguagem oficial é a NoSQL (do inglês, Not Only SQL — Não Apenas SQL).

Por ser um sistema que absorve alguns conteúdos de maior complexidade, o não-relacional demanda um sistema de aprovação, que permite identificar qual tipo de informação é mais relevante para o negócio. 

Tendo isso em mente, vejamos agora quais os tipos de banco de dados existentes e para quais casos são mais adequados:

 ## Bancos de dados orientados a objetos
 
Nesse tipo de banco, é utilizada a estrutura orientada a objetos. Isso quer dizer que as informações são organizadas em blocos de informações com identificadores. Nesse modelo não há uma lógica preestabelecida, o que o diferencia do banco de dados relacional, em que há uma tabela com linhas e colunas. 

Para exemplificar, vamos supor que desejamos armazenar informações sobre empresas. Então, criamos um identificador chamado “empresa” e para ele passamos atributos com os respectivos valores, como por exemplo, ao criarmos um atributo chamado “nome_fantasia”, poderíamos então passar o valor referente ao nome fantasia da empresa que desejamos armazenar. 

As principais vantagens que um banco de dados oferece são a organização e a agilidade. A implementação de um sistema de armazenamento de dados evita o acúmulo de papéis em setores de arquivamento, que além de requererem espaço físico, dificultam a consulta a informações. 

Nesse quesito, podemos falar da agilidade. Um banco de dados permite a inserção e busca de dados em questão de segundos. Diferentemente dos antigos formulários preenchidos a mão e as extensas consultas em pastas e mais pastas de documentos. 

Outro ponto positivo é a possibilidade de atestar a veracidade de uma informação. Enquanto papéis podem ser perdidos ou danificados, as informações em um banco podem ser checadas, validadas e até rastreadas.

O uso de bancos de dados requer o suporte a um alto volume de consultas complexas e com uma velocidade de resposta instantânea. Dessa forma, vejamos adiante as principais barreiras que as bases de dados enfrentam atualmente:

Absorção de dados: a grande quantidade de informação disparada por sistemas e hardwares pode fazer com que as pessoas encarregadas da administração de bancos de dados fiquem sobrecarregadas, tentando entender qual a melhor forma de lidar com o gerenciamento.

Segurança: nenhum sistema está a salvo de invasões. Portanto, esta é mais uma preocupação que os sistemas de bancos de dados precisam lidar.
Demanda e manutenção: conforme a complexidade de consultas e o volume de dados cresce, as empresas precisam investir recursos para manter a base de dados funcional em relação à demanda exigida.  

Escalabilidade: prever a capacidade de um banco de dados enquanto a empresa cresce ainda é um desafio.

O Big Data é um banco de dados avançado. Nele, chegam uma variedade de dados complexos e em grandes volumes, em que um sistema de armazenamento tradicional não conseguiria gerenciar.

Com Big Data, é possível armazenar dados provenientes de mídias sociais, como vídeos e áudios. Além de haver a possibilidade de aplicar machine learning aos dados coletados, permitindo mineração e gerenciamento e análise autônoma das informações.

Data Analytics, assim como o Big data, é um banco de dados que recebe grande quantidade de informações complexas. Entretanto, no Data Analytics, esses dados são utilizados como objeto de análise em um foco específico. 

Desse modo, no mercado de trabalho, uma pessoa analista de dados pode utilizar o Data Analytics para obter respostas sobre um problema específico, como a relação entre horários de produção e o volume produzido em uma empresa, por exemplo.


Confira quais são os tipos mais comuns, hoje no mercado.

### Oracle
Esse tipo de SGBD é, sem dúvidas, um dos tipos de bancos de dados mais utilizados no mercado. Criado entre os anos 70 e 80, o Oracle tem como sua linguagem principal o PS/SQL. É repleto de funcionalidades, além de ser extremamente flexível, rodando em diferentes plataformas como Windows e Linux.

Umas das características mais marcantes do Oracle é sua alta escalabilidade, ou seja, de acordo com o crescimento da demanda, sua capacidade também aumenta. Por esse motivo, ele é responsável por controlar um grande volume de dados. Para que ele funcione no máximo da sua capacidade, é necessário contar com um bom hardware.

### SQL Server

O SQL Server foi criado pela Microsoft em 1989 e conquistou rápida popularidade no mercado, sendo comumente utilizado em instituições governamentais, lojas online, bancos, indústrias e outros tipos de comércios. A linguagem por ele utilizada é o T-SQL.

Seus dados são criptografados, o que aumenta os níveis de segurança quando comparamos com os demais do mercado, já que os dados podem ser administrados e manipulados por pessoas específicas.

Por ser um produto da Microsoft, ele tem alta compatibilidade com programas da empresa, como Excel.

### MySQL

O MySQL é um SGBD da categoria relacional e também faz parte do grupo da Oracle. Sua principal característica é ser open source, ou seja, ele contém um código aberto para a modificação de programação e desenvolvimento de aplicativos.

Em decorrência do seu foco online, conquistou popularidade e está presente em grandes plataformas como Facebook e Instagram. O sistema de linguagem PHP roda em sistemas como Windows, Linux, MacOS, Solaris etc.

### PostgreSQL

Assim como o modelo anterior, PostgreSQL também é open source e é considerado um dos bancos de dados relacionais mais utilizados no mundo, como Apple e Skype. Lançado em 1986, está em sua 12ª versão e tem como foco plataformas online. 

Uma das maiores vantagens está ligada a não exigir um sistema hardware avançado, além de recursos avançados como consultas complexas, facilidade de acesso, chaves estrangeiras, entre outras. 

### MongoDB

Lançado em 2009, o MongoDB é um dos bancos de dados não-relacionais mais comuns do mercado. Ele tem como linguagem C++ e utiliza o Java Script para facilitar os recursos de pesquisas. 

Ele também é open source e orientado por documentos (document database) em formato JSON. Por ser não relacional, não demanda a utilização de tabelas com colunas e linhas para fazer a armazenagem de dados. O MongoDB funciona em Windows, Linux e OSX. 

### NoSQL

O banco de dados não-relacional de código aberto foi criado em 1998. Graças a popularidade dos dispositivos móveis e as redes sociais, o NoSQL ganhou bastante utilização no mercado. O armazenamento de dados com o objetivo de utilizá-los em ferramentas analíticas passou a acarretar em maiores custos.
