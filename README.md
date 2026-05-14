# Sua Marca · Landing One-Page

Landing institucional leve em HTML/CSS/JS puro. Sem build, sem dependências — pronto para publicar no GitHub Pages.

## Estrutura

```
expressiva-landing/
├── index.html      # marcação da página
├── style.css       # tema dark "vibe code" com gradients
├── script.js       # smooth scroll + reveal on scroll
└── README.md
```

## Como publicar no GitHub Pages

1. Crie um repositório novo no GitHub (ex: `expressiva-landing`).
2. Suba os arquivos:
   ```bash
   cd expressiva-landing
   git init
   git add .
   git commit -m "feat: landing inicial"
   git branch -M main
   git remote add origin https://github.com/<seu-usuario>/expressiva-landing.git
   git push -u origin main
   ```
3. No GitHub → **Settings → Pages**:
   - Source: `Deploy from a branch`
   - Branch: `main` / pasta `/ (root)` → **Save**
4. Em ~1 minuto o site fica disponível em:
   `https://<seu-usuario>.github.io/expressiva-landing/`

## Personalização rápida

| O que mudar | Onde |
|---|---|
| Nome da marca | `index.html` — todas ocorrências de "Sua Marca" |
| Headline / textos | `index.html` (hero, sobre, serviços, depoimentos) |
| Número do WhatsApp | `index.html` — `wa.me/5500000000000` (2 ocorrências) |
| E-mail de contato | `index.html` — `contato@suamarca.com.br` |
| Cores do tema | `style.css` — bloco `:root` no topo |

## Dados legais (rodapé)

- **Razão social:** JRLN COMUNICACOES LTDA
- **CNPJ:** 33.770.665/0001-33

Já aplicados no `<footer>` do `index.html`.
