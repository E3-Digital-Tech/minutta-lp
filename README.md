# MINUTTA — Landing Page

Landing page institucional do MINUTTA (CRM para advogados previdenciários).
Site estático, sem build: `index.html` + assets na raiz.

- **Produção:** https://lp.minuttacrm.com
- **App:** https://ember-crm.vercel.app (repo [kapta-crm](https://github.com/gabape4-gif/kapta-crm))

## Origem

Extraída de `landing.html` do repo `kapta-crm`. A cópia antiga continua lá em
`ember-crm.vercel.app/landing.html`; **esta aqui é a versão canônica** (a página
declara `rel="canonical"` apontando para `lp.minuttacrm.com`). Ao editar a LP,
edite aqui — a cópia do outro repo é legado.

## Arquivos

| Arquivo | Uso |
|---|---|
| `index.html` | A landing inteira (CSS e JS inline) |
| `logo-horizontal.webp` | Logo do header |
| `favicon.png` | Favicon / apple-touch-icon |
| `case-checklist/cnis/jef/pericia.webp` | Imagens da seção de casos |
| `final-bg.webp` | Fundo da seção final |

## Rodar local

```bash
npx serve .
```

## Deploy

Push na `main` → deploy automático pela Vercel.
