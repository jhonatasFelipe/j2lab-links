# J2 Lab — Página de escolha de loja

Página estática de link único (link-in-bio) para a J2 Lab. Mostra a logo da marca e
dois botões que levam o visitante direto para a loja oficial de sua preferência:
Mercado Livre ou Shopee.

Sem build, sem dependências além de fontes do Google Fonts. É só HTML + CSS.

## Estrutura

```
index.html        página principal
css/styles.css     estilos
assets/            logo e favicon
```

## Atualizar os links das lojas

Os links ficam direto no `index.html`, nos dois elementos `<a class="store-card ...">`:

- Mercado Livre: `href` do cartão `store-card--ml`
- Shopee: `href` do cartão `store-card--shopee`

Basta trocar a URL e publicar de novo.

## Rodar localmente

Abra o `index.html` direto no navegador, ou sirva a pasta com qualquer servidor
estático (ex. `npx serve` ou a extensão Live Server do VS Code).

## Publicação (GitHub Pages)

O site é publicado via GitHub Pages a partir da branch `main`, pasta raiz (`/`).
Qualquer push para `main` atualiza o site automaticamente.
