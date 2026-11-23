# Seven ID Visual

Identidade visual da **Seven Go**: logos, fontes e design system em um só lugar.

## Conteúdo

| Caminho | O que é |
|---|---|
| `Logo 02.png`, `Logo 04.png` | Logos da marca |
| `Montserrat-VariableFont_wght.ttf`, `Montserrat-Italic-VariableFont_wght.ttf` | Fonte Montserrat (variável) |
| `static/` | Montserrat estática, do Thin ao Black, com itálicos |
| `OFL.txt`, `README.txt` | Licença OFL e instruções da fonte |
| `design-system/` | Design system do site Seven Go (V1) |

### `design-system/`

| Arquivo | Conteúdo |
|---|---|
| `index.html` | Guia visual: cores, tipografia, componentes, raios, sombras, movimento |
| `tokens.css` | Variáveis CSS (cor, tipo, raios, sombras, layout, motion) |
| `tokens.json` | Mesmos tokens em JSON (Figma Tokens, Tailwind etc.) |
| `components.css` | Base e componentes: botões, nav, card, campo, acordeão etc. |
| `assets/` | Logo branco, símbolo GO e favicon |

## Princípios da marca

- **Fonte única:** Montserrat 300–700.
- **Escuro primeiro:** base `#07090C`, com seções claras `#EDF0F3` intercaladas.
- **Um só accent:** azul `#1E9BE0`, com gradiente `#0A5E94 → #1893D8` nos CTAs.

## Uso

Link direto de um arquivo:

```
https://raw.githubusercontent.com/sevengomarketing/Seven-ID-Visual/main/design-system/tokens.css
```

No HTML:

```html
<link rel="stylesheet" href="design-system/tokens.css" />
<link rel="stylesheet" href="design-system/components.css" />
```

Repositório inteiro em zip:
`https://github.com/sevengomarketing/Seven-ID-Visual/archive/refs/heads/main.zip`

## Licenças

Montserrat está sob a SIL Open Font License (`OFL.txt`). Logos e design system são da Seven Go.