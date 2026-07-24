# Landing page — Rodrigo Damasceno

Projeto estático para uma landing page premium, responsiva e acessível de **Rodrigo Damasceno**, com foco em apresentação artística, agenda, imprensa, redes sociais e contato para contratação.

> O conteúdo foi estruturado com placeholders para evitar a publicação de informações não confirmadas ou atribuíveis a homônimos.

## Estrutura de arquivos

```text
.
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── icons/
│   ├── images/
│   └── js/
│       └── main.js
├── index.html
├── manifest.json
├── robots.txt
├── sitemap.xml
└── README.md
```

## Como editar conteúdo

1. Abra `index.html` e substitua apenas os textos marcados como **Placeholder** depois de confirmar os dados em fontes públicas oficiais ou material aprovado pelo artista/assessoria.
2. Atualize URLs de redes e plataformas nos botões e links preparados para Instagram, YouTube, Spotify, WhatsApp e contratação.
3. Inclua fotos autorizadas em `assets/images/` e ajuste os atributos `data-full`, `data-caption` e textos alternativos da galeria.
4. Adicione ícones PWA em `assets/icons/` e substitua os caminhos `icon-192-placeholder.png` e `icon-512-placeholder.png` no `manifest.json`.
5. Troque `https://www.example.com/` pela URL oficial em `index.html`, `robots.txt` e `sitemap.xml`.
6. Não publique datas, repertório, prêmios, lançamentos, participações ou contatos sem confirmação.

## Placeholders que precisam de dados públicos confirmados

- URL canônica oficial do site.
- Imagem Open Graph e foto oficial do artista.
- Usuário oficial do Instagram.
- Canal oficial do YouTube.
- Perfil oficial do Spotify.
- Número oficial de WhatsApp para contratação.
- E-mail oficial de contato ou assessoria.
- Biografia curta aprovada.
- Linha do tempo com anos e eventos verificados.
- Repertório ou releases musicais confirmados.
- Vídeos oficiais incorporados.
- Fotos autorizadas, créditos e legendas.
- Agenda com data, local, cidade e links de ingresso confirmados.
- Release de imprensa aprovado.

## Validações realizadas

- Estrutura HTML semântica com `header`, `nav`, `main`, `section` e `footer`.
- CSS responsivo com paleta vinho profundo `#16070D`, dourado `#F2B84B`, creme claro e acentos cobre para contraste em textos, botões e links.
- Tipografia configurada para Playfair Display em títulos e Inter em textos.
- Estados de foco visíveis, contraste adequado e suporte a `prefers-reduced-motion`.
- JavaScript com menu mobile, rolagem suave, animações discretas, lazy loading complementar e lightbox acessível.
- SEO básico, Open Graph, Twitter Cards, JSON-LD, `robots.txt`, `sitemap.xml` e `manifest.json`.
- Ausência de menções às músicas proibidas e de informações biográficas não confirmadas.
