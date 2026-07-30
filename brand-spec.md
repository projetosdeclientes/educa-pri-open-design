# Brand Spec — Educa Pri

> Extraído do código-fonte React + Tailwind original e do prompt de execução.

## Seis tokens principais

| Token | Valor OKLch | Equivalente |
|---|---|---|
| `--bg` | oklch(96.5% 0.012 80) | #FCF9F3 |
| `--surface` | oklch(100% 0 0) | #FFFFFF |
| `--fg` | oklch(32% 0.02 260) | #2C3444 |
| `--muted` | oklch(52% 0.015 260) | #657086 |
| `--border` | oklch(86% 0.015 80) | #E6DFD1 |
| `--accent` | oklch(58% 0.14 148) | #30A667 |

## Paleta completa (HSL → tokens CSS)

- **background:** hsl(40 60% 97%) — creme claro
- **foreground/ink:** hsl(220 22% 22%) — grafite azulado
- **primary:** hsl(148 55% 42%) — verde ação
- **cta:** hsl(32 94% 52%) — laranja compra
- **gold:** hsl(40 90% 55%) — dourado decoração
- **highlight:** hsl(50 100% 72%) — amarelo marca-texto
- **brand-blue:** hsl(218 75% 42%) — azul do logo
- **brand-pink:** hsl(340 82% 72%) — rosa Instagram

## Font stacks

- **Display:** 'Poppins', system-ui, sans-serif (700–800, tracking-tight)
- **Body:** 'Nunito', system-ui, sans-serif (400–700, font-feature-settings: "ss01", "cv11")
- **Hand/manuscrita:** 'Caveat', cursive (600–700, uso em citações)

## Layout posture

- Container max 1200px, padding 20–32px
- Border-radius: 1.25rem (20px) padrão cards, 9999px badges/botões
- Sombras: rgba(51,38,20, ...) com opacidade 0.05–0.14
- Seções: py-16 (mobile) → py-20 (sm) → py-24 (lg)
- Um acento principal (verde/laranja), usado com moderação
- Decoração com bordas tracejadas douradas e faixas gold
- Efeito marca-texto amarelo em destaques inline
