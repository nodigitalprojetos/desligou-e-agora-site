# Desligou. E Agora?

Landing page do Kit Visual para Transição do Tempo de Tela.

Página estática em `index.html`, sem dependências ou etapa de build. A configuração existente do GitHub Pages foi preservada.

## Checkout

Preencha somente `const CHECKOUT_URL = '';` no JavaScript do `index.html` com o endereço definitivo da Celetus. Os três botões usam essa constante. Enquanto estiver vazia, o clique informa que as compras ainda não estão disponíveis.

## Imagens

- `assets/capa.webp`: apresentação enviada como `capa site.png`, substituindo na página a antiga capa incompleta.
- `assets/conteudo-kit.webp`: apresentação enviada como `ChatGPT Image 15 de set. de 2026, 22_18_05.png`.

As duas artes foram convertidas para WebP, sem cortes ou redimensionamento (1225 × 1284 pixels). Total aproximado de 478 KB, contra 3,58 MB dos PNGs originais. Ambas podem ser abertas em tamanho original pelo toque; a imagem de conteúdo tem carregamento adiado. São artes de apresentação fornecidas pelo usuário, não exportações individuais das páginas do PDF.

A arte `ChatGPT Image 15 de set. de 2026, 22_15_51.png` não foi incluída: contém afirmações sobre evitar birras e reduzir conflitos, incompatíveis com a orientação inicial de evitar essas promessas. As etapas continuam descritas em texto acessível na página.

As páginas individuais ainda não foram fornecidas. A galeria adicional está preparada para:

- `assets/avisos.jpg`
- `assets/primeiro-depois.jpg`
- `assets/atividades.jpg`
- `assets/conquista.jpg`

Se essas quatro prévias forem adicionadas, altere `data-ready="false"` para `data-ready="true"` na galeria do `index.html`. Nenhum arquivo ausente é solicitado enquanto ela estiver desativada. As imagens preservam a proporção com `object-fit: contain`.

Não adicionar o PDF pago a este repositório público.

## Verificação

Layout revisado nas larguras de 375, 390, 430 e 1440 pixels: três seções, sem rolagem horizontal e botões com pelo menos 56 pixels de altura. Verificados carregamento e proporções das artes, links para ampliação, FAQ e CTAs com checkout vazio e endereço simulado.
