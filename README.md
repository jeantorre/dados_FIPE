# Evolução Preço Médio dos Carros

Com a pandemia de Covid-19, 'iniciada' em 2020 no Brasil, a medida tomada pelo mundo, para evitar a propagação do vírus, foi o isolamento social e com isso houveram grandes problemas econômicos ao redor do mundo.  
O transporte de material ficou restrido (devido a economia globalizada, grande parte dos insumos nacionais são de importação/exportação), com menos pessoas nas ruas os diferentes tipos de comércio sofreram vendo seu faturamento diminuir drasticamente e quem não se reiventou nessa época, simplesmente teve que fechar as portas.  
A inflação chegou em patamares altíssimos e falando especificamente de carros vimos algo que não é natural. Os carros valorizaram com o passar do tempo (invés de depreciarem). 

Este estudo tem como proposta pesquisar os valores médios (de acordo com a tabela [FIPE](https://veiculos.fipe.org.br/)) de 3 modelos dos carros mais vendidos, de diferentes segmentos, em 2018 de acordo com o site [Auto Esporte](https://autoesporte.globo.com/mercado/noticia/2019/01/os-carros-mais-vendidos-de-2018.ghtml). Essa matéria foi publicada em 3 de janeiro de 2019 como retrospectiva do ano anterior.  
Como no site utilizado como referência dos modelos de carros mais vendidos não há especificação na versão mais vendida, foi escolhida uma versão que, pelo meu entendimento, inicou as vendas em 2018, simulando um carro 0 km.

## Web Scraping
Por ser um processo totalmente manual onde:  
* Escolhe o mês de referência
* Escolhe a marca
* Escolhe o modelo
* Escolhe o ano
* Além de copiar resultados e tratá-los

Em um período de 71 meses, para cada modelo de cada categoria. Ou seja, por alto 300 ações (de cada) que podem ser automatizadas.
Para isso foi desenvolvido um programa utilizando as bibliotecas Selenium e BeautifulSoup para dar contar dessa automação. Foi feita uma função para criar, de formar aleatória, um tempo de espera entre uma ação e outra, simulando uma ação humana para, dessa forma, evitar problema de não ter tempo o suficiente para carregar a página ou algo do tipo.

## Base de dados
A base de dados construída é disponibilizada, aqui, para que todos possam fazer um projeto!

## Referências
* Os carros mais vendidos de 2018 por segmento. **Auto Esporte**, 2019. Disponível em: <https://autoesporte.globo.com/mercado/noticia/2019/01/os-carros-mais-vendidos-de-2018.ghtml>. Acesso em 29 de nov. de 2023.
* Preço Médio de Veículos. **FIPE**, 2023. Disponível em: <https://veiculos.fipe.org.br/>. Acesso em 29 de nov. de 2023.
