# Decisões de design

## Suposições feitas pela IA (confirme ou corrija)
Público jovem adulto (18+), festa noturna em São Paulo, tom animado e direto. Data, local, preços e line-up são fictícios.

## Plano inicial (rejeitado em parte)
Primeiro rascunho: fundo quase preto com um único acento verde-limão, fonte mono para rótulos, seções numeradas 01/02/03.
**Revisão crítica:** esse é o visual "festa/balada" mais previsível e também um padrão comum de páginas geradas por IA. Nada nele vinha do nome "Big Party". Mudei para uma direção que parte da palavra "Big": tipografia enorme, cores chapadas e vibrantes, tom de brincadeira.
**Também cortei:** rótulos em caixa-alta sobre os títulos, numeração (o conteúdo não é uma sequência) e setas nos botões.

## Paleta
| Nome | Hex | Papel |
|---|---|---|
| Rosa Big | #E6007E | Fundo do hero, ingresso em destaque |
| Azul Eletrico | #2A2CF0 | Títulos de seção, line-up |
| Sol | #FFD23F | Botões, "BIG", destaques |
| Lilás Papel | #F3E8FF | Fundo da página |
| Tinta | #1B1464 | Texto, bordas, rodapé (azul-noite, não preto) |

Contraste conferido por estimativa: Tinta sobre Lilás e Sol é alto. Branco sobre Rosa e Azul é adequado para texto grande. **Valide com uma ferramenta de contraste (ex.: WebAIM) antes de entregar.**

## Tipografia
- **Bagel Fat One** (títulos): letra gordinha, lembra balão. É o elemento memorável.
- **Figtree** (corpo): sans limpa e legível, contrasta com a fonte de título.
- Fallbacks locais definidos, caso as fontes do Google não carreguem.

## Layout
Hero com "BIG" amarelo e "Party" branco em escala máxima → faixa de marquee → cards de informação → line-up em lista tipográfica → 3 ingressos (o do meio levemente inclinado) → FAQ → rodapé com CTA repetido.

## Onde gastei a ousadia
Só no título do hero (uma única animação de entrada). O resto é disciplinado: sem animação de scroll, sem efeito em todo card. A marquee é decorativa e some com `prefers-reduced-motion`.

## Qualidade mínima
Responsivo, foco visível, `aria-label` no título animado, FAQ com `<details>` nativo.

## Revisão v2 (baseada em pesquisa real)
Mudanças vieram das referências em `02-pesquisa-e-referencias.md`: sombra dura nos cards, line-up em 3 níveis, programação separada, repetição da identificação do evento e dois caminhos no hero. Versão anterior guardada em `docs/index-v1-antes-das-referencias.html` para comparação. Paleta e tipografia não mudaram.