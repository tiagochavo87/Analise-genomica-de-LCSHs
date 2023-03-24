# LCSH_analysis

The code is written in Python and makes use of the Pandas library to manipulate and filter a dataset consisting of regions of the human genome (identified by a chromosome, start and end positions, and size).

| :placard: Vitrine.Dev |     |
| -------------  | --- |
| :sparkles: Nome        | **Analise-genomica-de-LCSHs**
| :label: Tecnologias | java, html, ruby, c# (tecnologias utilizadas)
| :label: Tecnologias | python, colab, Pandas, NumPy
| :rocket: URL         | [https://github.com/tiagochavo87/LCSH_analysis]

<!-- Inserir imagem com a #vitrinedev ao final do link -->
![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTdanRVBERbeDQbHj5PzVpxJitkj6PzO0bef751moYJo-fkJ_2PV7WsI8BmHNuX83nBPZk&usqp=CAU#vitrinedev)

## Detalhes do projeto

O código é escrito em Python e faz uso da biblioteca Pandas para manipular e filtrar um conjunto de dados que consiste em regiões do genoma humano (identificadas por um cromossomo, posições inicial e final e tamanho).

O código lê o conjunto de dados de um arquivo CSV e aplica uma série de filtros para extrair regiões específicas de interesse. As regiões extraídas são gravadas em novos arquivos CSV. Os filtros aplicados incluem: exclusão de regiões nos cromossomos X e Y, filtragem de autossomos com tamanho superior a 10.000.000 e regiões de 3-5 MB, filtragem de regiões de 3-5 MB com tamanho total de pelo menos 10.000.000 e apenas uma região por arquivo , filtrando por regiões maiores que 5.000.000 com um tamanho total de pelo menos 10.000.000 e apenas um cromossomo por arquivo, e filtrando por casos com pelo menos uma região maior que 5 MB.

O código então calcula o tamanho total do DNA autossômico humano e a proporção de LCSHs de cada caso maior que 3 MB para o DNA autossômico. Ele define um conjunto de valores F e calcula o valor F mais próximo da proporção de cada caso. Em seguida, ele transpõe os casos para as colunas correspondentes aos valores F e grava a saída em um arquivo CSV.
