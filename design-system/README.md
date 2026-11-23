# Seven Go · Design System

Extraído do site V1 (`src/` — o `index.html` da raiz).

## Arquivos
| Arquivo | Conteúdo |
|---|---|
| `index.html` | Guia visual (abre com duplo clique): cores, tipografia, componentes, raios, sombras, movimento |
| `tokens.css` | Todas as variáveis CSS (cores, tipo, raios, sombras, layout, motion) |
| `components.css` | Base + componentes: container, seções, `.head`, botões, nav, tag, card, campo, lista, acordeão, progresso, CTA strip, reveal |
| `tokens.json` | Mesmos tokens em JSON (Figma Tokens, Tailwind, etc.) |
| `assets/` | Logo branco, símbolo GO, favicon |

## Princípios
- **Fonte única:** Montserrat 300–700. Títulos 500 com tracking negativo; labels 700 caixa-alta 0.18em.
- **Escuro primeiro:** `#07090C` base, seções claras `#EDF0F3` intercaladas; `--bg-850` sempre em degradê para não criar degrau.
- **Um só accent:** azul `#1E9BE0` (linhas ativas, foco, ícones) + gradiente `#0A5E94 → #1893D8` nos CTAs.
- **Big words:** palavra gigante em caixa-alta, cor quase igual ao fundo, como textura de seção.
- **Layout título + aside:** grid `1fr / 340px`; tudo que fica à direita começa no mesmo x.
- **Movimento:** easing `cubic-bezier(0.22,1,0.36,1)`; reveal fade + 24px + blur 6px em 0.8s, stagger 0.08s; linha azul que cresce da esquerda no hover; seta ↗ do botão gira 45°.
- **Acessibilidade:** foco 2px azul com offset 3px; `prefers-reduced-motion` desliga animações.

## Uso
```html
<link rel="stylesheet" href="tokens.css" />
<link rel="stylesheet" href="components.css" />
```
