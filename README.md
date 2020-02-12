O editor de imagens pode redimensionar imagens em formato JPG nos tamanhos 10x15cm, 12x15cm e 13x18cm. Ele também possui a funcionalidade de adicionar filtros paras as imagens como "Blur", "Brightness", "Contrast", "Drop-Shadow", "Grayscale", "Hue-Rotate", "Invert", "Opacity", "Saturate", "Sepia" e "Url" (Total de 11 filtros). 
Você pode selecionar o tamanho que deseja redimensionar a foto sem carregar ela primeiro. Assim como adicionar os devidos filtros. Logo apoś poderá selecionar a quantidade e finalmente carregar a imagem que desesja.
E em Abas, poderá inserir o valor por tamanho e tudo dando o resultado com valores prontos para serem utilizados no Banco de Dados. 

Esse editor simples de imagens está pronto para receber uma requisição Ajax e ser inserida em funcionalidades de linguagens WEB como no PHP, também podendo ser utilizados em frameworks como Symfony e Laravel. 

Todos os dados de filtros podem ser adicionados em uma coluna de filtros de uma unica tabela. A cada movimento do filtro é inserido em um array, contendo todos os filtros que estão sendo utilizados na imagem com suas categorias.

A tabela do banco de dados pode ser organizada assim:


|  Foto  |
----------

idFoto
tamanhoFoto (text)
filtros (text)
dir (text)
preço (double)
quantidate (integer)


Este projeto está pronto para ser finalizado utilizando um framework ou linguagem pura de programação WEb.

