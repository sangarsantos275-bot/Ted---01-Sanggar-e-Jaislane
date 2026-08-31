# Ted-01 Jaislane e Sanggar

Processamento e Análise de Dados com Coleções Avançadas em Python

Jaislane Santos da silva - 26.1.20568
Sanggar santos guimarães - 26.120576

Explicação das Estruturas Utilizadas e Justificativa

Tuplas (tuple): Usadas no carregamento inicial dos CSVs por garantirem a imutabilidade dos registros lidos da base de dados original.

Dicionários (dict):Um índice mapa_livros mapeia o id_livro aos detalhes dele, permitindo buscas otimizadas $O(1)$ ao cruzar dados.
Dicionários aninhados dentro de uma lista foram estruturados para consolidar a coleção final de empréstimos tratados.

Conjuntos (set):Remoção de Duplicidades: Eliminam de forma nativa as linhas redundantes (E031-E034) repetidas propositalmente no arquivo original de empréstimos.

Operações de Conjunto: Executam operações de .intersection() e .difference() sobre os perfis de leitores de Romance e Ficção sem usar condicionais repetitivos.

List e Dict Comprehensions: Filtram e agrupam informações agilmente de forma expressiva.
