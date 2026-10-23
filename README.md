# Portfólio · Ezequiel Costa

Filmmaker e editor de vídeo em Uberlândia, MG.

**Site:** https://portfolio.ezequielcosta.workers.dev/

## Estrutura

| Pasta / arquivo | Conteúdo |
| --- | --- |
| `index.html` | A página do portfólio |
| `img/` | Fotos, bastidores e prints de resultados |
| `capas/` | Capas dos vídeos |
| `video/` | Vídeos em MP4 (computador e Android) |
| `video/hls/` | Os mesmos vídeos em partes (HLS), para tocarem no iPhone e no Safari |
| `_headers` | Tipos de arquivo dos vídeos HLS para o Cloudflare |
| `og-image.jpg` | Imagem de prévia ao compartilhar o link |
| `favicon.svg` | Ícone da aba do navegador |

É um site estático: não precisa de build. Qualquer hospedagem de arquivos estáticos serve a pasta como está.

## Publicação

O repositório está ligado ao Worker **portfolio** no Cloudflare. Todo envio para a branch `main` publica o site automaticamente em https://portfolio.ezequielcosta.workers.dev/.
