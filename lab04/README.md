# Modelo para Apresentação do Lab04 - Serviços

## Tarefa 1
![tarefa1](/lab04/images/tarefa1.png)

## Tarefa 2
![tarefa2](/lab04/images/tarefa2.png)

## Tarefa 3
![tarefa3](/lab04/images/tarefa3.png)

## Tarefa 4

### Serviço `1`

* **Título do serviço**: `News API`
* **Breve descrição**:
  > Serviço usado para obter notícias de graça. No caso estou buscando por 5 notícias de esporte no Brasil. Para maiores informações, clique [aqui](https://newsapi.org/).
* **URL completa da requisição**: `https://newsapi.org/v2/top-headlines?country=br&category=sports&pageSize=5&apiKey=my_api_key`
* **Cabeçalho HTTP da chamada**:
```http
Accept	text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,*/*;q=0.8
Accept-Encoding	gzip, deflate, br
Accept-Language	en-US,en;q=0.5
Connection	keep-alive
DNT	1
Host	newsapi.org
Upgrade-Insecure-Requests	1
User-Agent	Mozilla/5.0 (Macintosh; Intel Mac OS X 10.15; rv:79.0) Gecko/20100101 Firefox/79.0
```
* **Cabeçalho HTTP da resposta**:
```http
X-Firefox-Spdy	h2
cache-control	no-cache
cf-cache-status	DYNAMIC
cf-ray	5c9a7c6c5952eeb2-GRU
cf-request-id	04d46c17b50000eeb2ebb94200000001
content-encoding	br
content-type	application/json; charset=utf-8
date	Fri, 28 Aug 2020 02:08:43 GMT
expect-ct	max-age=604800, report-uri="https://report-uri.cloudflare.com/cdn-cgi/beacon/expect-ct"
expires	-1
pragma	no-cache
server	cloudflare
x-cached-result	false
```
* **Conteúdo da resposta**:
```json
{
    "status": "ok",
    "totalResults": 70,
    "articles": [
        {
            "source": {
                "id": null,
                "name": "Omunicipio.com.br"
            },
            "author": "Redação",
            "title": "Brusque vence Brasil de Pelotas e está na quarta fase da Copa do Brasil - O Munícipio",
            "description": "",
            "url": "https://omunicipio.com.br/brusque-vence-brasil-de-pelotas-e-esta-na-quarta-fase-da-copa-do-brasil/",
            "urlToImage": "https://omunicipio.com.br/wp-content/uploads/2020/08/dsc8658.jpg",
            "publishedAt": "2020-08-27T23:50:00Z",
            "content": "O Brusque se classificou à quarta fase da Copa do Brasil após vencer o Brasil de Pelotas por 1 a 0, mesmo resultado do jogo de ida. Marco Antônio marcou o gol da partida aos 38 do primeiro tempo. O p… [+3268 chars]"
        },
        {
            "source": {
                "id": null,
                "name": "Superesportes.com.br"
            },
            "author": null,
            "title": "Fred se diz à disposição para formular proposta razoável ao Cruzeiro em ação de R$ 78 milhões - Superesportes",
            "description": null,
            "url": "https://www.mg.superesportes.com.br/app/noticias/futebol/cruzeiro/2020/08/27/noticia_cruzeiro,3860382/fred-se-diz-a-disposicao-para-formular-proposta-razoavel-ao-cruzeiro.shtml",
            "urlToImage": null,
            "publishedAt": "2020-08-27T23:49:00Z",
            "content": null
        },
        {
            "source": {
                "id": "globo",
                "name": "Globo"
            },
            "author": null,
            "title": "Ponte devolve Safira ao Londrina, mas atacante tem outro clube da Série B como provável destino - globoesporte.com",
            "description": "Com interesse do CRB, jogador rescinde contrato de empréstimo que tinha com a Macaca",
            "url": "https://globoesporte.globo.com/sp/campinas-e-regiao/futebol/noticia/ponte-devolve-safira-ao-londrina-mas-atacante-tem-outro-clube-da-serie-b-como-provavel-destino.ghtml",
            "urlToImage": "https://s2.glbimg.com/pYaNSKJzP3xZGWgbgH5aro3nWfY=/1200x/smart/filters:cover():strip_icc()/i.s3.glbimg.com/v1/AUTH_bc8228b6673f488aa253bbcb03c80ec5/internal_photos/bs/2020/2/Z/QZXpTVQ5GQb2VZwUYiAQ/50157502017-c957754bfb-c.jpg",
            "publishedAt": "2020-08-27T23:27:00Z",
            "content": "Fora dos planos da Ponte Preta, o atacante Safira foi devolvido para o Londrina, donos dos direitos econômicos do jogador. O clube campineiro confirmou nesta quinta-feira a rescisão do contrato de em… [+743 chars]"
        },
        {
            "source": {
                "id": "globo",
                "name": "Globo"
            },
            "author": null,
            "title": "Grêmio faz proposta de R$ 15 milhões para contratar Cléber, centroavante do Ceará - globoesporte.com",
            "description": "Conforme apurado pelo ge, oferta seria por 60% dos direitos econômicos do xodó do Vozão",
            "url": "https://globoesporte.globo.com/rs/futebol/noticia/gremio-faz-proposta-de-r-15-milhoes-para-contratar-cleber-centroavante-do-ceara.ghtml",
            "urlToImage": "https://s2.glbimg.com/VGkpKbudXcm5O4H6MQYMljcFCuA=/1200x/smart/filters:cover():strip_icc()/i.s3.glbimg.com/v1/AUTH_bc8228b6673f488aa253bbcb03c80ec5/internal_photos/bs/2020/K/h/4nEQ9mRCuK5TECHuLZhg/whatsapp-image-2020-08-12-at-21.42.14.jpeg",
            "publishedAt": "2020-08-27T23:27:00Z",
            "content": "O novo centroavante do Grêmio pode ser Cléber, xodó do Ceará em 2020. Conforme apurou o ge, o Tricolor fez uma proposta de R$ 15 milhões por 60% dos direitos econômicos do atacante. O clube gaúcho ad… [+1422 chars]"
        },
        {
            "source": {
                "id": "globo",
                "name": "Globo"
            },
            "author": null,
            "title": "Torcedores do Newell's Old Boys fazem carreata e pedem que Messi vá para o time de coração - globoesporte.com",
            "description": "Centenas de pessoas vão às ruas de Rosário e manifestam, com gritos e cânticos, a ilusão de ver o argentino no clube para o qual torce e onde começou no futebol",
            "url": "https://globoesporte.globo.com/futebol/futebol-internacional/noticia/torcedores-do-newells-old-boys-fazem-carreata-e-pedem-que-messi-va-para-o-time-de-coracao.ghtml",
            "urlToImage": "https://s2.glbimg.com/hffLd2BieBz9x5aOTwpNvrMEakw=/1200x/smart/filters:cover():strip_icc()/i.s3.glbimg.com/v1/AUTH_bc8228b6673f488aa253bbcb03c80ec5/internal_photos/bs/2020/A/s/tqU0GiSWSbBbRqrnzjiA/000-1wt2ez.jpg",
            "publishedAt": "2020-08-27T23:04:00Z",
            "content": "A palavra ilusión acompanha muito os torcedores sul-americanos em sua paixão pelos clubes, nos seus cânticos e gritos nas arquibancadas. E ela moveu centenas de pessoas a saírem em carreata pelas rua… [+2065 chars]"
        }
    ]
}
```

### Serviço `2`

* **Título do serviço**: `The Open Movie Database`
* **Breve descrição**:
  > Serviço usado para obter informações sobre filmes e séries. No caso estou buscando pela palavra 'Fast' e estou limitando o resultado para somente a categoria 'movies'. Para maiores informações, clique [aqui](http://www.omdbapi.com/).
* **URL completa da requisição**: `http://www.omdbapi.com/?s=Fast&type=movie&apikey=my_api_key`
* **Cabeçalho HTTP da chamada**:
```http
Accept	text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,*/*;q=0.8
Accept-Encoding	gzip, deflate
Accept-Language	en-US,en;q=0.5
Connection	keep-alive
DNT	1
Host	www.omdbapi.com
Upgrade-Insecure-Requests	1
User-Agent	Mozilla/5.0 (Macintosh; Intel Mac OS X 10.15; rv:79.0) Gecko/20100101 Firefox/79.0
```
* **Cabeçalho HTTP da resposta**:
```http
Access-Control-Allow-Origin	*
Age	1813
CF-Cache-Status	HIT
CF-RAY	5c9a8c9e1a70eed6-GRU
Cache-Control	public, max-age=86400
Connection	keep-alive
Content-Encoding	gzip
Content-Type	application/json; charset=utf-8
Date	Fri, 28 Aug 2020 02:19:46 GMT
Expires	Fri, 28 Aug 2020 02:49:33 GMT
Last-Modified	Fri, 28 Aug 2020 01:49:33 GMT
Server	cloudflare
Transfer-Encoding	chunked
Vary	*, Accept-Encoding
X-AspNet-Version	4.0.30319
X-Powered-By	ASP.NET
cf-request-id	04d47636cb0000eed6b63b9200000001
```
* **Conteúdo da resposta**:
```json
{
    "Search": [
        {
            "Title": "Fast & Furious 6",
            "Year": "2013",
            "imdbID": "tt1905041",
            "Type": "movie",
            "Poster": "https://m.media-amazon.com/images/M/MV5BMTM3NTg2NDQzOF5BMl5BanBnXkFtZTcwNjc2NzQzOQ@@._V1_SX300.jpg"
        },
        {
            "Title": "Fast Five",
            "Year": "2011",
            "imdbID": "tt1596343",
            "Type": "movie",
            "Poster": "https://m.media-amazon.com/images/M/MV5BMTUxNTk5MTE0OF5BMl5BanBnXkFtZTcwMjA2NzY3NA@@._V1_SX300.jpg"
        },
        {
            "Title": "The Fast and the Furious",
            "Year": "2001",
            "imdbID": "tt0232500",
            "Type": "movie",
            "Poster": "https://m.media-amazon.com/images/M/MV5BNzlkNzVjMDMtOTdhZC00MGE1LTkxODctMzFmMjkwZmMxZjFhXkEyXkFqcGdeQXVyNjU0OTQ0OTY@._V1_SX300.jpg"
        },
        {
            "Title": "Fast & Furious",
            "Year": "2009",
            "imdbID": "tt1013752",
            "Type": "movie",
            "Poster": "https://m.media-amazon.com/images/M/MV5BYjQ1ZTMxNzgtZDcxOC00NWY5LTk3ZjAtYzRhMDhlNDZlOWEzXkEyXkFqcGdeQXVyNzkwMjQ5NzM@._V1_SX300.jpg"
        },
        {
            "Title": "2 Fast 2 Furious",
            "Year": "2003",
            "imdbID": "tt0322259",
            "Type": "movie",
            "Poster": "https://m.media-amazon.com/images/M/MV5BMzExYjcyYWMtY2JkOC00NDUwLTg2OTgtMDI3MGY2OWQzMDE2XkEyXkFqcGdeQXVyMTQxNzMzNDI@._V1_SX300.jpg"
        },
        {
            "Title": "The Fast and the Furious: Tokyo Drift",
            "Year": "2006",
            "imdbID": "tt0463985",
            "Type": "movie",
            "Poster": "https://m.media-amazon.com/images/M/MV5BMTQ2NTMxODEyNV5BMl5BanBnXkFtZTcwMDgxMjA0MQ@@._V1_SX300.jpg"
        },
        {
            "Title": "Fast & Furious Presents: Hobbs & Shaw",
            "Year": "2019",
            "imdbID": "tt6806448",
            "Type": "movie",
            "Poster": "https://m.media-amazon.com/images/M/MV5BOTIzYmUyMmEtMWQzNC00YzExLTk3MzYtZTUzYjMyMmRiYzIwXkEyXkFqcGdeQXVyMDM2NDM2MQ@@._V1_SX300.jpg"
        },
        {
            "Title": "Fast Times at Ridgemont High",
            "Year": "1982",
            "imdbID": "tt0083929",
            "Type": "movie",
            "Poster": "https://m.media-amazon.com/images/M/MV5BYzBlZjE1MDctYjZmZC00ZTJmLWFkOWEtYjdmZDZkODBkZmI2XkEyXkFqcGdeQXVyNjQ2MjQ5NzM@._V1_SX300.jpg"
        },
        {
            "Title": "Fast Food Nation",
            "Year": "2006",
            "imdbID": "tt0460792",
            "Type": "movie",
            "Poster": "https://m.media-amazon.com/images/M/MV5BYzM0ODQ5OGItZDZhMy00NDk0LWJmNTgtZGRiMTBjMDI1YTAwXkEyXkFqcGdeQXVyMTQxNzMzNDI@._V1_SX300.jpg"
        },
        {
            "Title": "Atanarjuat: The Fast Runner",
            "Year": "2001",
            "imdbID": "tt0285441",
            "Type": "movie",
            "Poster": "https://m.media-amazon.com/images/M/MV5BNmIwMjRiMzgtYjM5NC00MTdlLWI2ZWMtNDQxOTAzZTJmNzMxXkEyXkFqcGdeQXVyNTM0NTU5Mg@@._V1_SX300.jpg"
        }
    ],
    "totalResults": "581",
    "Response": "True"
}
```