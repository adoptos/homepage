# Adoptos: paleta de cores

A paleta segue a estratégia definida na `brandkit`:

- **Personalidade:** confiável e precisa.
- **Tom visual:** claro e limpo.
- **Evitar:** anúncio invasivo, fintech genérica, corporativo frio e visual infantil.

A regra central é **um único acento, com significado**. As demais cores existem para dar suporte a ele.

| Papel | Nome | HEX | RGB | HSL |
|---|---|---|---|---|
| Base | **Ivory** | `#F4EFE6` | 244, 239, 230 | 39°, 39%, 93% |
| Estrutura | **Ink** | `#17150F` | 23, 21, 15 | 45°, 21%, 7% |
| Acento | **Signal** | `#DB391C` | 219, 57, 28 | 9°, 77%, 48% |
| Neutro claro | Stone | `#DDD6C9` | 221, 214, 201 | 39°, 23%, 83% |
| Neutro médio | Warm gray | `#8C857A` | 140, 133, 122 | 37°, 7%, 51% |

---

## Signal `#DB391C` (o acento)

**Por que existe:** em todos os conceitos de logo, o Signal marca **sempre a mesma coisa: o lugar**, seja o espaço físico ou o público que está nele. É o ponto no Conceito 1, o segmento escolhido na 1A, a travessa no Conceito 2 e o encontro no Conceito 3. A cor não decora, ela aponta.

**Por que esse tom:**
- **Sinalização e localização.** É o vermelho-alaranjado das placas, dos pinos de mapa e dos marcadores de "você está aqui". A Adoptos vende presença em lugares físicos, e essa é a cor que o mundo já usa para dizer "aqui".
- **Calor sem agressividade.** O matiz de 9° fica entre o vermelho e o laranja. O vermelho puro (0°) carrega alarme, erro e liquidação, que é o "anúncio invasivo" que a marca quer evitar. Puxar levemente para o laranja mantém a energia e tira a urgência.
- **Foge da fintech genérica.** O território roxo-azulado de tecnologia e finanças está saturado. Um acento quente diferencia a marca de imediato.
- **Distância da Target.** O vermelho da Target, `#CC0000` (0°, 100% de saturação), é mais puro e mais frio. O Signal é deliberadamente mais alaranjado. Isso não elimina sozinho o risco de semelhança no Conceito 1, que depende mais da forma de alvo do que da cor.

**Por que exatamente `#DB391C`:** o tom original era `#E4472B`. Ele tinha só 4,01:1 de contraste com o branco e reprovava como texto e com texto branco por cima. O `#DB391C` mantém o mesmo matiz (9°) e a mesma saturação (77%) e só reduz a luminosidade, de 53% para 48%. Isso basta para chegar a **4,55:1 com o branco**, nível AA. Visualmente, a diferença é quase imperceptível. As alternativas mais escuras que foram avaliadas estão em `signal-opcoes.html`.

> **Atenção:** 4,55:1 fica no limite do mínimo de 4,5:1. Não escureça o fundo nem clareie o Signal em aplicações, e evite usá-lo como texto sobre fundos que não sejam branco puro. Telas e impressões que deslocam a cor podem fazer o contraste reprovar.

**Regra de uso:** o Signal é escasso, ocupando cerca de 5% de qualquer composição, e sempre marca algo que importa: o lugar, o público, a ação principal. Se tudo for Signal, nada é.

---

## Ink `#17150F` (a estrutura)

**Por que existe:** carrega o símbolo, o wordmark e todo o texto. É a cor da **precisão e da confiança**, a voz séria da marca.

**Por que esse tom:**
- **Quase preto, não preto.** O preto puro (`#000000`) é duro e digital, e sobre o marfim parece recortado. O Ink tem um subtom quente (matiz de 45°, o mesmo da família do Ivory), então as duas cores parecem feitas do mesmo material.
- **Referência à tinta de impressão.** Mídia out-of-home é mídia impressa e física: cartazes, adesivos, displays. O Ink remete à tinta sobre papel, não à tela.
- **Contraste máximo.** Com 15,9:1 sobre o Ivory, passa com folga no nível AAA de acessibilidade em qualquer tamanho de texto.

---

## Ivory `#F4EFE6` (a base)

**Por que existe:** é o fundo padrão da marca e responde à escolha de um visual **claro e limpo**.

**Por que esse tom:**
- **Branco quente, não branco puro.** O branco `#FFFFFF` é o fundo de todo SaaS e leva ao "corporativo frio" que você pediu para evitar. O Ivory é acolhedor sem deixar de ser limpo.
- **Papel e mundo físico.** Ele remete a papel, cartaz e materiais reais. Reforça que a Adoptos vive nos espaços físicos, e não só na tela.
- **Conforto visual.** Cansa menos a vista do que o branco puro em telas e mantém o Ink e o Signal nítidos.

---

## Neutros de apoio

- **Stone `#DDD6C9`**: superfícies secundárias, divisórias e cartões sobre o Ivory. É da mesma família quente (39°). Não serve para texto.
- **Warm gray `#8C857A`**: elementos gráficos discretos, como linhas, ícones inativos e grades de construção.

---

## Contraste e acessibilidade (WCAG 2.x)

| Combinação | Contraste | Texto normal (≥ 4,5) | Texto grande e gráficos (≥ 3) |
|---|---|---|---|
| Ink sobre Ivory | **15,94:1** | ✅ AAA | ✅ |
| Ink sobre Stone | 12,63:1 | ✅ AAA | ✅ |
| Signal sobre branco | 4,55:1 | ✅ AA (no limite) | ✅ |
| Branco sobre Signal | 4,55:1 | ✅ AA (no limite) | ✅ |
| Signal sobre Ink | 4,01:1 | ❌ | ✅ |
| Signal sobre Ivory | 3,97:1 | ❌ | ✅ |
| Ivory sobre Signal | 3,97:1 | ❌ | ✅ |
| Signal sobre Stone | 3,15:1 | ❌ | ✅ |
| Warm gray sobre Ink | 5,00:1 | ✅ AA | ✅ |
| Warm gray sobre Ivory | 3,19:1 | ❌ | ✅ |
| Stone sobre Ivory | 1,26:1 | ❌ | ❌ |

**O que isso significa na prática:**
- **Como texto, o Signal só vale sobre branco puro** (4,55:1). Sobre o Ivory, o Stone e o Ink, use-o apenas em formas, ícones, no logo e em textos grandes (24px ou mais, ou 19px em negrito).
- **Em botões, o texto deve ser branco puro** (4,55:1). Texto em Ivory (3,97:1) ou em Ink (4,01:1) sobre o Signal reprova para texto normal.
- **No logo**, o Signal passa como elemento gráfico (≥ 3:1) sobre o branco, o Ivory e o Ink.
- **Problema encontrado:** o Warm gray sobre o Ivory não passa para texto comum, e eu usei essa combinação nos rótulos pequenos das páginas de preview. Para texto secundário sobre fundos claros, a recomendação é um tom mais escuro da mesma família:

| Proposta | HEX | Sobre Ivory | Sobre Stone |
|---|---|---|---|
| **Graphite** (texto secundário) | `#605B52` | 5,89:1 ✅ | 4,67:1 ✅ |

O Graphite ainda **não foi aplicado** aos arquivos. Ele entra quando você aprovar.

---

## Uso sobre branco `#FFFFFF`

### Como a paleta se comporta sobre o branco

| Cor | Contraste com branco | Texto normal (≥ 4,5) | Gráficos e texto grande (≥ 3) |
|---|---|---|---|
| Ink `#17150F` | 18,25:1 | ✅ AAA | ✅ |
| Signal `#DB391C` | 4,55:1 | ✅ AA (no limite) | ✅ |
| Warm gray `#8C857A` | 3,65:1 | ❌ | ✅ |
| Stone `#DDD6C9` | 1,44:1 | ❌ | ❌ |
| Ivory `#F4EFE6` | 1,15:1 | não se aplica | não se aplica |

**Resolvido:** o Signal foi ajustado e agora contrasta com o branco, tanto como texto quanto com texto branco por cima.

### Adaptações ainda propostas

> Status: **proposta**, ainda não aplicada aos arquivos.

| Nova cor | HEX | Sobre branco | Sobre Ivory | Para que serve | Resolve |
|---|---|---|---|---|---|
| **Graphite** | `#605B52` | 6,74:1 ✅ AA | 5,89:1 ✅ AA | Texto secundário, legendas e rótulos | O Warm gray reprova como texto |
| **Line** | `#9A9389` | 3,04:1 ✅ | – | Bordas de campos, divisórias que precisam ser vistas e ícones de interface | O Stone some como borda sobre o branco |

**Papéis que mudam:**
- **Ivory:** sobre um fundo branco, deixa de ser fundo e vira **superfície de seção**, como blocos, cartões e faixas alternadas. Não precisa de contraste, porque não carrega informação.
- **Stone:** continua como preenchimento de superfície, mas **não** serve como borda sobre o branco. Para isso, use o Line.

### Regras práticas sobre branco

| Elemento | Cor |
|---|---|
| Texto principal | Ink |
| Texto secundário | Graphite (proposta) |
| Link e texto de destaque | Signal |
| Botão primário | fundo Signal + texto branco (4,55:1) |
| Logo e elementos gráficos | Signal |
| Bordas e divisórias funcionais | Line (proposta) |
| Superfícies e blocos | Ivory ou Stone |

---

## Proporção sugerida

| Cor | Proporção aproximada |
|---|---|
| Ivory | ~70% |
| Ink | ~20–25% |
| Neutros (Stone, Warm gray) | ~5% |
| Signal | ≤ 5% |
