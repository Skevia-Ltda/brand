# SKEVIA — reconstrução vetorial final

## Direção congelada
- Direção A — Convergência
- V: derivado do estudo V5
- Símbolo: derivado do S4
- Final escolhido: B, sem ponto no símbolo
- Único ponto circular: ponto teal do I
- Sem gradientes, filtros, sombras ou raster

## Cores
- Graphite: #0F1720
- Teal: #0F766E
- Off-white: #F7F6F3
- Mineral: #6B727B

O contraste teal × graphite calculado é aproximadamente 3.30:1, portanto o teal oficial foi preservado no fundo escuro.

## Construção
O símbolo usa exatamente dois shapes vetoriais recoloráveis (LeftShape / RightShape), com poucos nós Bézier. O V do wordmark é construído com duas formas separadas que compartilham a mesma lógica de convergência do símbolo. O restante do wordmark parte de uma base geométrica sans, convertido em outlines, com ajuste manual de largura e espaçamento; o V e o I são construções próprias. Nenhum SVG depende de fonte externa.

## Clear space inicial
Unidade x = espessura visual principal da haste. Área recomendada inicial: 1.5x em todos os lados.

## Tamanho mínimo validado nesta reconstrução
- Símbolo: 16 px
- Wordmark: 96 px de largura recomendada
- Lockup horizontal: 128 px de largura recomendada

Os tamanhos mínimos são recomendações desta reconstrução e devem ser confirmados no ambiente real de uso (browser, favicon, impressão e UI).

## Master
`skevia-logo-master.svg` contém grupos nomeados: `01_CONSTRUCTION`, `02_PRIMARY`, `03_DARK`, `04_MONOCHROME`, `05_SCALE_TEST`, `06_EXPORT`.

## Observação
A prancha de revisão contém textos auxiliares; os SVGs de logo de produção contêm apenas paths, rects e circles vetoriais e não dependem de fontes.
