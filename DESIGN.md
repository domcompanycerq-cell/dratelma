---
name: Dra. Telma Costa
description: Página de links e vendas de Otomodelação, com paleta tirada do retrato da Dra. Telma.
colors:
  cobre-cabelo: "#9A4A2A"
  cobre-cabelo-noite: "#E0936C"
  cobre-veu: "#F1E3DB"
  cobre-veu-noite: "#33231B"
  dourado-blazer: "#A9864F"
  dourado-blazer-texto: "#7F6136"
  dourado-blazer-noite: "#D3B07A"
  porcelana-fria: "#F0F1F1"
  branco-jaleco: "#FFFFFF"
  tinta-cafe: "#1E1916"
  cinza-argila: "#6B625C"
  linha-areia: "#D9D6D3"
  noite-cafe: "#141110"
  superficie-noite: "#1E1A18"
  tinta-noite: "#F2ECE7"
  argila-noite: "#B0A49B"
  linha-noite: "#3A322D"
typography:
  display:
    fontFamily: "Bodoni Moda, Didot, Bodoni 72, Georgia, serif"
    fontSize: "clamp(2.6rem, 5.6vw, 4.9rem)"
    fontWeight: 500
    lineHeight: 1.02
    letterSpacing: "-0.01em"
  headline:
    fontFamily: "Bodoni Moda, Didot, Bodoni 72, Georgia, serif"
    fontSize: "clamp(2rem, 4vw, 3.3rem)"
    fontWeight: 500
    lineHeight: 1.05
    letterSpacing: "-0.01em"
  title:
    fontFamily: "Bodoni Moda, Didot, Bodoni 72, Georgia, serif"
    fontSize: "1.4rem"
    fontWeight: 500
    lineHeight: 1.12
    letterSpacing: "-0.01em"
  body:
    fontFamily: "Instrument Sans, Helvetica Neue, Arial, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.6
  lede:
    fontFamily: "Instrument Sans, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(1.05rem, 1.4vw, 1.2rem)"
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: "Instrument Sans, Helvetica Neue, Arial, sans-serif"
    fontSize: "0.72rem"
    fontWeight: 600
    lineHeight: 1
    letterSpacing: "0.16em"
  numeral:
    fontFamily: "Bodoni Moda, Didot, Bodoni 72, Georgia, serif"
    fontSize: "1.9rem"
    fontWeight: 500
    lineHeight: 1
    fontFeature: "lnum, tnum"
rounded:
  sm: "6px"
  md: "12px"
  lg: "14px"
  xl: "20px"
  arch: "220px"
  pill: "999px"
spacing:
  gutter: "clamp(16px, 4vw, 40px)"
  xs: "8px"
  sm: "12px"
  md: "20px"
  lg: "26px"
  xl: "36px"
  section: "clamp(56px, 8vw, 110px)"
components:
  button-primary:
    backgroundColor: "{colors.cobre-cabelo}"
    textColor: "{colors.branco-jaleco}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: "0 1.6em"
    height: "54px"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.tinta-cafe}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: "0 1.6em"
    height: "54px"
  link-card:
    backgroundColor: "{colors.porcelana-fria}"
    textColor: "{colors.tinta-cafe}"
    rounded: "{rounded.lg}"
    padding: "14px 18px 14px 14px"
  link-card-featured:
    backgroundColor: "{colors.cobre-cabelo}"
    textColor: "{colors.branco-jaleco}"
    rounded: "{rounded.lg}"
    padding: "14px 18px 14px 14px"
  link-card-icon:
    backgroundColor: "{colors.branco-jaleco}"
    textColor: "{colors.cobre-cabelo}"
    rounded: "{rounded.md}"
    size: "48px"
  chip:
    backgroundColor: "{colors.branco-jaleco}"
    textColor: "{colors.tinta-cafe}"
    rounded: "{rounded.pill}"
    padding: "7px 14px"
  floating-tag:
    backgroundColor: "{colors.branco-jaleco}"
    textColor: "{colors.tinta-cafe}"
    rounded: "{rounded.pill}"
    padding: "10px 16px"
  carousel-arrow:
    backgroundColor: "{colors.branco-jaleco}"
    textColor: "{colors.tinta-cafe}"
    rounded: "{rounded.pill}"
    size: "50px"
---

# Design System: Dra. Telma Costa

## Overview

**Creative North Star: "O Retrato de Cobre"**

Todo o sistema sai de uma única fotografia: a Dra. Telma de blazer branco diante de uma parede porcelana, com o cabelo acobreado e os botões dourados do blazer. A parede vira o fundo (porcelana fria), o cabelo vira o acento (cobre), os botões viram o detalhe precioso (dourado) e o blazer vira a superfície (branco). A página é o retrato estendido. Nada nela deveria parecer importado de fora dessa foto.

O tom é editorial de beleza, não clínico. Um Bodoni de alto contraste conduz os títulos, e a segunda linha do título principal cai em itálico cobre, como numa capa de revista. Um sans neutro e calmo (Instrument Sans) carrega a leitura. A densidade é baixa e o ritmo é generoso: cada seção tem um único assunto, cercada de respiro, e as divisões entre seções são feitas por mudança de tom (porcelana, branco, véu de cobre) e por linhas finas de 1px, não por caixas.

Os componentes são refinados e contidos. Pílulas e linhas finas, sombra só como resposta ao toque, e um único elemento cheio de cor por tela: o botão de agendar. A página foi pensada para o polegar de quem chega pelo Instagram. No celular tudo vira uma coluna e um botão de agendar fixo aparece no rodapé.

**Key Characteristics:**
- Paleta derivada do retrato: porcelana, cobre, dourado, branco e tinta café.
- Bodoni Moda nos títulos, com itálico cobre como ênfase. Instrument Sans no texto.
- Fotografia real como protagonista: retrato sangrado com máscara de fade, arco no retrato da bio, comparador antes/depois.
- Plano por padrão: profundidade por tom e linha de 1px, sombra neutra apenas em elementos que flutuam ou respondem ao toque.
- Tema claro e escuro com os mesmos papéis de cor: no escuro, cobre e dourado clareiam e o fundo vira café profundo.

## Colors

Uma paleta quente e quieta tirada do retrato, com um único acento forte (cobre) e um detalhe precioso (dourado) sobre neutros porcelana e café.

### Primary
- **Cobre Cabelo** (`cobre-cabelo`; no escuro `cobre-cabelo-noite`): a cor de ação e de ênfase. Fundo do botão de agendar e do card de WhatsApp em destaque, itálico dos títulos (`em`), ícones dos cards de link, marcadores das listas, rótulos "Etapa", anel de foco e seleção de texto.
- **Véu de Cobre** (`cobre-veu`; no escuro `cobre-veu-noite`): o cobre diluído como fundo de seção. Usado só na seção da biografia, para marcar o momento mais pessoal da página.

### Secondary
- **Dourado Blazer** (`dourado-blazer`; no escuro `dourado-blazer-noite`): o detalhe precioso. Pontos das tags flutuantes do hero e o fio vertical da citação na bio. É decorativo e nunca carrega texto pequeno no tema claro.
- **Dourado Blazer para texto** (`dourado-blazer-texto`): a versão escurecida do dourado para texto pequeno no tema claro (contador "Caso 01 / 03"), com contraste 5:1 sobre porcelana. No escuro usa o próprio dourado claro.

### Neutral
- **Porcelana Fria** (`porcelana-fria`): fundo da página, igual à parede da foto. Também é o fundo dos cards de link dentro da seção branca.
- **Branco Jaleco** (`branco-jaleco`): superfícies elevadas. Faixa de benefícios, seção de links, rodapé, tags flutuantes, chips e botões de seta. Também é o texto sobre cobre.
- **Tinta Café** (`tinta-cafe`): texto principal e títulos. Também é a borda dos elementos em hover e o fundo da legenda sobre o retrato da bio.
- **Cinza Argila** (`cinza-argila`): texto secundário, como lede, descrições, legendas e aviso de resultados.
- **Linha Areia** (`linha-areia`): todas as linhas de 1px, bordas em repouso e trilhos inativos do carrossel.
- **Tema escuro:** `noite-cafe` (fundo), `superficie-noite` (superfícies), `tinta-noite` (texto), `argila-noite` (secundário) e `linha-noite` (linhas) ocupam os mesmos papéis.

### Named Rules
**The One Copper Fill Rule.** Só a ação de agendar ganha fundo cobre cheio: o botão principal do hero, o card de WhatsApp em destaque e o botão fixo no mobile. Todo o resto usa cobre apenas em texto, ícone ou linha.

**The Gold Is Jewelry Rule.** O dourado é joia, não tinta. Aparece em pontos, fios e numerais pequenos, nunca como fundo nem como texto corrido. Em texto pequeno no tema claro, use sempre `dourado-blazer-texto`.

**The Same Roles at Night Rule.** O tema escuro troca valores, nunca papéis. Cada token claro tem um par noturno, e nenhum componente escolhe cor própria para o escuro.

## Typography

**Display Font:** Bodoni Moda (com Didot, Bodoni 72 e Georgia como alternativas)
**Body Font:** Instrument Sans (com Helvetica Neue e Arial como alternativas)

**Character:** Um Didone de moda, de alto contraste, contra um sans contemporâneo e discreto. O Bodoni dá a voz editorial de revista de beleza e o Instrument Sans mantém a leitura clara e próxima. As duas fontes vêm do Google Fonts, com `display=swap`.

### Hierarchy
- **Display** (500, `clamp(2.6rem, 5.6vw, 4.9rem)`, 1.02; 2.45rem abaixo de 480px): só o título do hero. A segunda linha fica em itálico cobre, em bloco próprio.
- **Headline** (500, `clamp(1.9rem, 3.4vw, 2.8rem)` a `clamp(2rem, 4vw, 3.3rem)`, 1.05–1.12): títulos de seção (passos, bio, resultados, links). Podem terminar com um trecho em itálico cobre via `em`.
- **Title** (500, 1.35–1.4rem; casos `clamp(1.6rem, 2.6vw, 2.2rem)`, 1.1): títulos de benefício, etapa e caso.
- **Lede** (400, `clamp(1.05rem, 1.4vw, 1.2rem)`, 1.6, máx. 34ch, cinza argila): o parágrafo de abertura do hero, aberto por uma frase em negrito 600 na cor da tinta.
- **Body** (400, 1rem, 1.6): texto corrido, com medida máxima de 60ch na bio e 40–42ch nos blocos laterais. As descrições secundárias descem para 0.95rem.
- **Label** (600, 0.72rem, 0.16em de tracking, maiúsculas): só para rótulos que carregam informação de sequência ("Etapa 1", "Caso 01 / 03", "Antes/Depois") e para a marca no hero.
- **Numeral** (Bodoni 500, 1.9rem; 1.6rem no mobile; numerais alinhados e tabulares): os fatos de prova do hero (+300, 0, CRF/SP).

### Named Rules
**The Italic Is Copper Rule.** Itálico em título é sempre cobre, e cobre em título é sempre itálico. É a única forma de ênfase dentro de um título: sem negrito, sem sublinhado e sem texto em gradiente.

**The No Kicker Rule.** Nenhum rótulo em maiúsculas fica acima de um título só para anunciá-lo. Maiúsculas espaçadas existem apenas quando dizem algo que o título não diz: posição numa sequência ou estado.

## Layout

O conteúdo vive num contêiner central de no máximo 1180px, com margem lateral fluida `clamp(16px, 4vw, 40px)`. As seções se alternam por tom de fundo (porcelana, branco, véu de cobre e de volta à porcelana) com padding vertical `clamp(56px, 8vw, 110px)`.

- **Hero:** grade dividida 1.05fr / 0.95fr, texto à esquerda e retrato à direita, alinhado pela base, com altura mínima `min(820px, 92vh)`. O retrato sangra com máscara de fade embaixo e nas laterais. Uma marca d'água "Oto" em itálico cobre a 7% fica atrás dele, e duas tags flutuantes se sobrepõem à foto.
- **Faixa de benefícios:** três colunas iguais separadas por linhas verticais de 1px, sem cards.
- **Passos:** três colunas, cada etapa aberta por uma linha de 1px na cor da tinta.
- **Bio:** duas colunas, 0.85fr para o retrato em arco e 1.15fr para o texto.
- **Resultados:** carrossel de slides em largura total. Cada slide é uma grade de duas colunas: comparador (máx. 440px, proporção 600/880) e texto do caso.
- **Links:** coluna central estreita (máx. 620px), centralizada, com a lista de links alinhada à esquerda.
- **Tablet em pé (até 900px, retrato):** o retrato do hero sobe para o topo em largura total (até 68vh), o texto avança 90px sobre o fade da foto e o título cresce para `clamp(2.45rem, 7.4vw, 3.6rem)`. As demais seções mantêm suas colunas (benefícios e passos em três, bio e casos em duas) e o botão fixo de agendar aparece.
- **Celular deitado (altura até 500px):** o hero continua dividido em duas colunas, com o retrato no topo da coluna direita limitado à altura da tela, para não esconder o texto atrás da foto.
- **Celular (abaixo de 700px):** tudo vira coluna única. Benefícios e passos empilham com linhas horizontais e o texto do caso desce para baixo do comparador.
- **Abaixo de 480px:** os botões do hero ocupam 100% da largura.
- **Abaixo de 380px:** os cards de link ficam mais compactos (ícone de 40px, espaços de 12px) para dar largura ao texto.
- **Áreas seguras:** abaixo de 900px a margem lateral respeita `safe-area-inset` para celulares com entalhe deitados.

**The Breathing Room Rule.** Uma ideia por seção, cercada de espaço. Agrupamentos internos ficam apertados (8–14px) e a separação entre grupos fica generosa (26–36px).

## Elevation & Depth

O sistema é plano por padrão. A profundidade vem da alternância de tons de fundo e de linhas de 1px em `linha-areia`. Sombras existem só em duas situações: elementos que flutuam sobre a fotografia (tags, botão do comparador) e elementos de ação respondendo ao toque. Todas as sombras usam o token neutro `--shadow` (café a 38% no claro, preto a 60% no escuro) e sempre têm deslocamento vertical e desfoque.

### Shadow Vocabulary
- **Repouso do CTA** (`box-shadow: 0 10px 24px -14px var(--shadow)`): botão principal de agendar em repouso.
- **Elevação ao toque** (`box-shadow: 0 14px 28px -14px var(--shadow)`): botão principal e card de WhatsApp em destaque no hover, junto com `translateY(-2px)`.
- **Flutuante sobre foto** (`box-shadow: 0 14px 30px -18px var(--shadow)`): tags "Naturalidade" e "Técnica e segurança" sobre o retrato.
- **Botão do comparador** (`box-shadow: 0 8px 20px -6px rgba(0,0,0,.4)`): o círculo branco de arrastar sobre a foto antes/depois.
- **Vidro do CTA fixo** (`backdrop-filter: blur(12px)` sobre a porcelana a 88%): a barra de agendar no rodapé do mobile. É o único uso de desfoque.

### Named Rules
**The Neutral Shadow Rule.** Sombra nunca tem cor de marca. Halo cobre ou dourado é proibido, inclusive no tema escuro.

**The Flat at Rest Rule.** Cards, chips, faixas e setas não têm sombra em repouso. No hover a borda muda para a cor da tinta e o elemento sobe 2px.

## Shapes

A linguagem de forma combina a pílula, o arco e o retângulo de cantos suaves.

- **Pílula** (999px): botões, chips, tags flutuantes, rótulos Antes/Depois, setas e botão do comparador (círculos).
- **Arco** (220px no topo, 14px na base): exclusivo do retrato da bio, como uma janela ou moldura de espelho. É a assinatura formal da página.
- **Cantos suaves** (14px): comparador, cards de link e legenda da bio. A janela do carrossel usa 20px e os ícones dos cards de link usam 12px.
- **Linhas:** sempre de 1px. Separam faixas, etapas e o rodapé e contornam cards e botões fantasma. O fio da citação na bio é uma linha vertical dourada de 1px.
- **Máscaras:** o retrato do hero dissolve nas bordas com `mask-image` em gradiente linear, sem cortes geométricos.

## Components

### Buttons
Contidos e firmes, com a ação de agendar sempre como o elemento mais forte da tela.
- **Shape:** pílula (999px), altura mínima de 54px, padding horizontal 1.6em, ícone de 20px com espaço de 0.6em.
- **Primary:** fundo cobre cabelo e texto branco jaleco em Instrument Sans 600 1rem, com o ícone do WhatsApp sempre à esquerda. Usa a sombra de repouso do CTA.
- **Hover / Active:** sobe 2px e a sombra aumenta, com transições de 0.2s ease. No active volta à posição original. Em telas de toque (`hover: none`) não há elevação: o toque reduz o botão para 98%.
- **Ghost:** transparente, com borda de 1px em linha areia e texto na cor da tinta. No hover a borda muda para a cor da tinta. Usado para a ação secundária "Ver antes e depois".
- **Focus:** contorno cobre de 2px com 3px de afastamento, em todos os elementos interativos.

### Link Cards
A pilha de links é a lista que o visitante do Instagram percorre com o polegar.
- **Corner Style:** cantos suaves (14px).
- **Background:** porcelana fria sobre a seção branca, com borda de 1px em linha areia.
- **Estrutura:** grade de três colunas: ícone de 48px num quadrado branco de 12px com ícone cobre, depois título 600 1rem com descrição de 0.85rem em cinza argila, depois uma seta de 20px.
- **Featured:** o card de WhatsApp é cobre cheio com texto branco. O fundo do ícone é branco a 16% e a descrição e a seta ficam a 85% de opacidade. É sempre o primeiro da lista.
- **Hover:** sobe 2px e a borda muda para a cor da tinta. O card em destaque ganha a sombra de elevação.

### Chips
- **Style:** pílula branca com borda de 1px em linha areia, padding 7px 14px e texto de 0.85rem na cor da tinta. Não são interativos: listam especialidades e o registro CRF/SP na bio.

### Floating Tags
- **Style:** pílula branca sobre o retrato do hero, com ponto dourado de 8px, texto 500 0.85rem e sombra de flutuante sobre foto.
- **Motion:** flutuam 8px num ciclo de 6s em ease-in-out, com a segunda defasada em meio ciclo. Param com movimento reduzido.

### Before/After Comparator
A peça central de prova da página.
- **Estrutura:** a foto "depois" fica embaixo e a foto "antes" por cima, recortada com `clip-path` na posição `--pos`. Uma barra branca de 2px e um botão circular branco de 48px com ícone de setas duplas marcam a divisão.
- **Rótulos:** pílulas "Antes" e "Depois" nos cantos superiores, em fundo café translúcido a 62% e label branco.
- **Interação:** arrastar ou tocar em qualquer ponto da foto move a divisão (eventos de ponteiro, funciona com mouse e toque, inclusive no iOS). Um `input range` invisível fica por baixo só para o teclado, e o foco aparece como contorno cobre na foto inteira. O cursor é `ew-resize` e a rolagem vertical da página continua livre sobre a foto. Ao entrar na tela o comparador faz uma varredura senoidal de 2.2s para ensinar o gesto, e para assim que a pessoa toca.
- **Carrossel:** troca de slide em 0.7s com `cubic-bezier(.65,0,.25,1)` e avanço automático a cada 7s, que para na primeira interação. Os trilhos de navegação têm 4px de altura dentro de uma área de toque de 44px, e o ativo fica na cor da tinta. As setas são círculos brancos de 50px com borda de 1px.
- **Aviso:** a frase "Os resultados variam…" fica sempre logo abaixo, em 0.78rem cinza argila.

### Sticky Booking Bar
- **Style:** só no mobile (abaixo de 900px). Barra fixa no rodapé com fundo porcelana a 88% e desfoque de 12px, borda superior de 1px, respeitando `safe-area-inset-bottom`. Contém um botão principal em largura total.
- **Behavior:** entra deslizando (0.35s) depois que o hero sai da tela e some ao chegar na seção de links.

### Portrait Caption
- **Style:** etiqueta em tinta café com texto porcelana, cantos de 14px, sobreposta ao canto inferior esquerdo do retrato em arco. Traz o número de prova em Bodoni 1.1rem e a descrição em 0.82rem.

## Do's and Don'ts

### Do:
- **Do** tire toda cor nova do retrato: porcelana, cobre, dourado, branco ou café. Se uma cor não está na foto, ela não entra.
- **Do** reserve o fundo cobre cheio para a ação de agendar pelo WhatsApp (The One Copper Fill Rule).
- **Do** use itálico cobre do Bodoni como a única ênfase dentro de títulos.
- **Do** separe seções por mudança de tom e por linhas de 1px em linha areia, não por cards.
- **Do** mostre fotografia real: retrato sangrado com fade e fotos antes/depois de pacientes reais.
- **Do** dê a todo token claro um par noturno e teste os dois temas.
- **Do** mantenha alvos de toque com pelo menos 44px e o contorno de foco cobre de 2px.
- **Do** use `dourado-blazer-texto` (#7F6136) sempre que o dourado virar texto pequeno no tema claro.

### Don't:
- **Don't** coloque rótulos em maiúsculas acima de títulos só para anunciá-los (The No Kicker Rule).
- **Don't** use sombra colorida ou halo de cobre ou dourado. Sombras são neutras e têm deslocamento (The Neutral Shadow Rule).
- **Don't** monte seções com grades de cards iguais de ícone, título e texto. Use colunas abertas separadas por linhas.
- **Don't** use texto em gradiente, negrito dentro de títulos Bodoni ou barras coloridas grossas na lateral de blocos.
- **Don't** substitua as fotos de pacientes por imagens de banco ou geradas por IA, nem recorte o rosto com máscaras geométricas.
- **Don't** introduza uma segunda fonte de exibição nem troque o Bodoni por uma fonte do sistema.
- **Don't** adicione animações decorativas por seção. O movimento é do retrato que sobe, das tags que flutuam e da varredura do comparador, e tudo para com `prefers-reduced-motion`.
