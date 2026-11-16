# Site Preta Brenda

Landing page da Preta Brenda, terapeuta tântrica e massoterapeuta em Natal/RN.
Página estática: um `index.html` com CSS e JS embutidos e a pasta `assets/`. Sem build.

## Rodar localmente

```bash
npx serve .
```

Abra http://localhost:3000.

## Publicar na Vercel

1. Suba este repositório no GitHub.
2. Na Vercel: Add New > Project > importe o repositório.
3. Framework Preset: **Other**. Build Command: vazio. Output Directory: vazio (raiz).
4. Deploy.

Cada `git push` na branch principal publica de novo automaticamente.

## Domínio

Hoje o site usa o endereço gratuito da Vercel (ex.: `preta-brenda.vercel.app`).
Se o nome do projeto na Vercel for outro, troque o endereço em `index.html` nas tags
`og:image`, `canonical` e no JSON-LD.

Para ligar um domínio próprio depois: Vercel > Project > Settings > Domains > Add,
e siga as instruções de DNS que aparecem.

## Onde mudar as coisas

- WhatsApp: constante `FONE` no script do `index.html`.
- Textos: direto no `index.html`.
- Fotos: `assets/img/` (webp). Ao trocar uma foto, mude o nome do arquivo (ex.: `-v3`) para o navegador não mostrar a antiga.
