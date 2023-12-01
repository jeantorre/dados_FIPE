## Projeto
Inicialmente o projeto foi desenvolvido apenas para praticar *web scraping*, durante uma aula da pós. Agora o código foi refatorado e implementado para este projeto maior, buscando informações de um horizonte de tempo maior (desde 2018), 3 modelos de 3 diferentes segmentos.

## Web Scraping
Estrutura dos dados obtidos na tabela (após a pesquisa) é a seguinte:
* Caracteres iniciais na busca: '< td >< p >'
* Caracteres finais na busca: '< /p >< /td >'
* Para acessar qualquer elemento entre esses dois grupos: '.*?'

Estrutura dos dados obtidos na tabela (após a pesquisa) é a seguinte:
* Caracteres iniciais na busca: '< td class='noborder' >< p >'
* Caracteres finais na busca: '< /p >< /td >'
* Para acessar qualquer elemento entre esses dois grupos: '.*?'

Devido ao carregamento da página ser lento, nas condições que me encontro, na hora de inserir alguma informação (como modelo, tempo de referência etc) ocorreram alguns erros durante o desenvolvimento do algoritmo. Para contornar, foi colocado um tempo aleatório de espera entre cada ação para que o programa rodasse sem dar problemas.  