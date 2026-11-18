# Studio Vitoria Carvalho · Lash Designer

Site de uma página (HTML estático) para o studio de extensão de cílios da Vitoria Carvalho, em Campo Grande – MS.

## Estrutura
- `index.html` — a página inteira (estilos e script inclusos)
- `assets/` — fotos, capas e vídeos

## Editar
- **WhatsApp:** no fim do `index.html`, troque `55[NUMERO]` pelo número com 55 + DDD (ex.: `5567999999999`). Todos os botões de agendar usam esse número.
- **Fotos/vídeos:** coloque o arquivo em `assets/` e troque o nome no `index.html`.

## Publicar no Cloudflare Pages
Workers & Pages → Create → Pages → Connect to Git → escolha este repositório.
Build command: *(vazio)* · Output directory: `/`
Cada push na branch principal publica automaticamente.
