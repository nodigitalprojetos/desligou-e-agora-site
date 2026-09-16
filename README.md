# Desligou. E Agora?

Landing page do Kit Visual para Transição do Tempo de Tela.

Página estática em `index.html`, sem dependências ou etapa de build. A configuração existente do GitHub Pages foi preservada.

## Checkout

Preencha somente `const CHECKOUT_URL = '';` no JavaScript do `index.html` com o endereço definitivo da Celetus. Os três botões usam essa constante. Enquanto estiver vazia, o clique informa que as compras ainda não estão disponíveis.

## Imagens pendentes

- Substituir `assets/capa.jpg`: o arquivo atual renderiza quase inteiramente cinza, com apenas uma faixa superior visível. Foi preservado, mas precisa de uma exportação íntegra da capa real.
- Adicionar `assets/avisos.jpg`.
- Adicionar `assets/primeiro-depois.jpg`.
- Adicionar `assets/atividades.jpg`.
- Adicionar `assets/conquista.jpg`.

Depois de adicionar as quatro prévias reais, altere `data-ready="false"` para `data-ready="true"` na galeria do `index.html`. Até lá, nenhum arquivo ausente é solicitado ou substituído por uma imagem genérica. As prévias ocupam a largura disponível no celular e duas colunas no desktop, preservando a proporção com `object-fit: contain`.

Não adicionar o PDF pago a este repositório público.

## Verificação

Layout verificado em navegador nas larguras de 375, 390, 430 e 1440 pixels: três seções, sem rolagem horizontal, capa a partir de aproximadamente 229–241 pixels no celular e botões com pelo menos 56 pixels de altura. FAQ e os três CTAs foram exercitados com checkout vazio e com endereço simulado. Nenhum erro de JavaScript ou requisição de arquivo ausente na configuração atual.
