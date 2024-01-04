# Back-end

## Entidades

### Game

id
title
bannerUrl

CDN (Content Delivery Network) - (Amazon S3) => URL

### Ad

id
gameId
name
yearsPlaying
discord
weekDays
hourStart
hourEnd
useVoiceChannel
createAt

#### Arrays

    Ex: arrayDays

    0
    1
    2
    3
    4
    5
    6

    [1,3,6]

#### Dados Númericos

    Trabalhar com Min:

    1:30h -> 90 min
    R$ 179,89 -> 17989

    Datas (fuso horário / formatos diferentes il8n)
    
    Pontos flutuantes

## Casos de uso

- Listagem de games com contagem de anúncios
- Criação de novo anúncio
- Listagem de anúncios por game
- Buscar discord pelo ID do anúncio

### Logica

- Query: ...
- Route: ...
- Body: ...

localhost:3333/ads

(Query:)
localhost:3333/ads?page=2&sort=title

(Route:)
localhost:3333/ads/5
localhost:3333/post/como-criar-uma-api-em-node

(Body:)
localhost:3333/null

HTTP methods / API RESTful / HTTP Codes

GET, POST, PUT, PATCH, DELETE, (HEAD, OPTIONS)
