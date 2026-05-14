# Prompt — Rebuild Landing Page ADEPT Corretora de Seguros

Use o seguinte prompt no Claude Code para gerar a landing page melhorada:

---

Recrie a landing page da ADEPT Corretora de Seguros em um único arquivo `index.html` com CSS e JS inline. Mantenha toda a copy exatamente como está abaixo — não altere nenhuma palavra. Apenas melhore o visual, a estrutura e a experiência.

## Identidade visual obrigatória
- Background principal: `#0a0a0a`
- Cor de destaque principal: `#E8820C` (laranja ADEPT)
- Texto principal: `#FFFFFF`
- Texto secundário: `#A0A0A0`
- Fonte de destaque (títulos): Google Fonts — **Bebas Neue** para headings grandes, **Inter** para corpo
- Bordas e detalhes: laranja com baixa opacidade (`rgba(232,130,12,0.3)`)

---

## Seções e copy (reproduza fielmente nesta ordem)

### 1. Header fixo com scroll effect
- Logo ADEPT (texto estilizado com ícone de cadeado) à esquerda
- Nav central: links "ADEPT" e "Contato"
- Botão CTA à direita: **"QUERO MEU SEGURO"** — fundo laranja, texto branco, bordas arredondadas
- Ao scrollar: header ganha `backdrop-filter: blur(12px)` e fundo `rgba(10,10,10,0.85)`

### 2. Hero section
**Título (h1):** `Proteja o que é importante para você!`
**Subtítulo:** `Precisa de um seguro e quer encontrar o melhor preço?`
**Bold:** `A ADEPT te ajuda!`
**Parágrafo:** `Seguros de carros, motos, vida e residencial, além de muitos outros produtos.`
**CTA:** botão `Quero ficar protegido!`

Visual: fundo com partículas sutis animadas em canvas (pontos brancos com linhas conectando — efeito "rede de proteção"). Título entra com animação de fade + slide-up ao carregar.

### 3. Carrossel de seguros — "Nossos principais seguros"
**Título da seção:** `Nossos principais seguros`

Carrossel horizontal com auto-play (4s), navegação por setas e dots. Cada card tem ícone SVG temático, título e descrição curta. Cards com borda laranja no hover, efeito de brilho sutil. Swipe habilitado no mobile.

Cards (use exatamente estes textos):

| Ícone sugerido | Título | Descrição |
|---|---|---|
| 🚗 carro | **Seguro de Automóvel** | Roubos, acidentes, pequenas dores de cabeça vivem acontecendo no trânsito. Saia de carro **sem preocupações.** |
| 🏠 casa | **Seguro Residencial** | Evite dores de cabeça e ainda tenha **benefícios** para pequenas manutenções em casa. |
| ❤️ coração | **Seguro de Vida** | **Tranquilidade** para você e aqueles que você ama. |
| 🏥 saúde | **Plano de Saúde** | Trabalhamos com diversos planos para que você tenha **uma vida saudável.** |
| 🏍️ moto | **Seguro de Moto** | Tenha os melhores seguros de moto com os **menores preços.** |
| 🏢 prédio | **Seguro de Condomínio** | É o dever do síndico prover seu condomínio de um bom seguro. A ADEPT te ajuda e ainda consegue o **menor preço!** |

### 4. Seção "Ainda não tem seguro?"
**Título (h2):** `Ainda não tem seguro?`

**Parágrafos (manter exatos):**
- `Você sabia que no Brasil,` *(laranja)* `um carro é roubado a cada minuto` *(fim laranja)* `?`
- `E esse número só cresce! Em 2020 mesmo com a quarentena houve um` *(laranja)* `aumento de 14,5% no número de roubos.` *(fim laranja)*
- `Não queremos que algo de ruim nos aconteça, mesmo assim acontece. Esteja preparado para que algo ruim não seja ainda pior.`
- `E se o carro que você lutou para comprar fosse roubado?`
- `E se você se acidentasse e além de ter que pagar o conserto, ainda tivesse a saúde debilitada por conta deste acidente?`
- `Nessas horas é melhor ter a segurança de ter se prevenido antes.`
- `A ADEPT entende que o seguro proporciona tranquilidade, e por isso busca fornecer o melhor valor para as necessidades do cliente.`
- `Queremos que você compre um seguro para não usar, por isso buscamos o menor preço!`
- `Somos uma empresa familiar e nos importamos profundamente com o que fazemos e com cada um de nossos clientes.`
- **Bold:** `Venha fazer parte da família ADEPT. O cliente protegido é a nossa maior satisfação!`

Visual: contador animado ao entrar na viewport mostrando "1 carro roubado a cada 60s" com um número decrementando em loop.

### 5. Nossos valores
**Título:** `Nossos valores`

Cards lado a lado com ícone, título e descrição. Animação: cada card entra com delay escalonado (stagger) ao entrar na viewport.

| Título | Descrição |
|---|---|
| **Preço justo** | O nosso compromisso é conseguir as melhores ofertas para você. |
| **Transparência** | Entendemos o que você precisa e passamos todas as informações para que faça a melhor escolha. |
| **Sempre juntos** | Conte conosco sempre que precisar. Acompanhamos os prazos para que você nunca esteja desprotegido. |

### 6. Outros Serviços
**Título:** `Outros Serviços`

3 cards horizontais com ícone laranja, título e descrição:

| Título | Descrição |
|---|---|
| **Consórcio** | Te ajudamos a conseguir comprar seu carro ou sua casa com os melhores Consórcios. |
| **Cartão de crédito** | Conte conosco para conseguir o seu cartão de crédito! |
| **Financiamento** | Tire seu sonho do papel! Consiga sua casa ou carro com nossos financiamentos! |

### 7. Depoimentos
**Título acima:** `Somos uma corretora que coloca o` *(laranja)* `cliente em primeiro lugar.`
**Subtítulo:** `Veja o que os nossos clientes têm a dizer.`

Carrossel de depoimentos com auto-play (6s). Cada card tem foto placeholder circular com iniciais, aspas estilizadas em laranja, texto do depoimento em itálico, nome em laranja bold e tempo como cliente.

**Depoimentos (manter exatos):**

**Lucas Cifuentes** — *Cliente Adept há 2 anos*
> A Adept faz um excelente trabalho de entender as necessidades do cliente e ajuda com informações para que seja feita a melhor escolha. A transparência nas informações enviadas são o diferencial para a confiança de estar fazendo uma boa escolha.

**Nathalya Torquato** — *Cliente Adept há 2 anos*
> Sou cliente há 2 anos, atendimento diferenciado, explicação detalhada para sua necessidade e excelente interface com o cliente. A equipe é fantástica. Bem antes do meu seguro vencer, eles entraram em contato já com todas as possíveis opções para renovação. Se antecipar é marca registrada desta excelente empresa. Recomendadíssima!

**Walter Rangel** — *Cliente Adept há 1 ano*
> Tinha um corretor de confiança por anos, mas a Adept conseguiu um preço R$ 500,00 mais barato que meu corretor antigo. Após confrontar o corretor antigo ele igualou o preço, mas acabou a confiança. Agora sou Adept e é a corretora que tenho confiança e recomendo para os meus familiares.

### 8. CTA final
**Título laranja:** `Já passou da hora de você ter o seu seguro!`
**Subtítulo branco bold:** `Conte com a ADEPT para o que você precisar!`
**Botão:** `Quero meu seguro!`

Fundo com gradiente sutil laranja escuro para preto. Botão pulsa levemente (CSS animation: pulse).

### 9. Footer
Layout 3 colunas:
- Coluna 1: Logo ADEPT + links nav (ADEPT, Contato)
- Coluna 2: **Contato** — (22) 3056-2186 · (22) 99837-7767 · contato@adeptcorretora.com · Rua Pinhalão, n.º 33, Campos dos Goytacazes, Rio de Janeiro, 28030-135
- Coluna 3: Ícones de redes sociais (email, facebook, instagram, whatsapp) em laranja com hover effect

---

## Efeitos e detalhes técnicos obrigatórios

### Animações de entrada (Intersection Observer)
Todos os títulos de seção, cards e parágrafos entram com `opacity: 0 → 1` + `translateY(30px → 0)` ao entrar no viewport. Cards em grid usam stagger delay (0.1s entre cada).

### Scroll suave
`scroll-behavior: smooth` + offset para o header fixo.

### Partículas no hero
Canvas JS simples: 60 pontos brancos com opacidade 0.3, conectados por linhas quando próximos, animação contínua lenta. Não usar bibliotecas externas.

### Carrossel de seguros
JS puro. Auto-play com pausa no hover. Dots clicáveis. Swipe touch. Transição: slide com `transform: translateX`.

### Carrossel de depoimentos
Igual ao de seguros. Cards maiores, fundo levemente mais claro (`#141414`), borda laranja `0.3 opacity`.

### Botões
Todos os botões laranja: `background: #E8820C`, hover `background: #FF9520`, `transition: 0.2s`, `border-radius: 50px`, `font-weight: 600`, `letter-spacing: 0.5px`. CTA principal no hero é maior (padding 18px 40px).

### Linha decorativa laranja
Separador sutil entre seções: `border-top: 1px solid rgba(232,130,12,0.2)` ou linha decorativa de 40px centralizada em laranja sólido.

### Responsividade
Mobile-first. Breakpoint principal: 768px. Carrosseis viram single-card no mobile. Grid de valores vira coluna única. Footer vira stack vertical.

---

## O que NÃO fazer
- Não alterar nenhuma palavra da copy
- Não usar frameworks externos (Bootstrap, Tailwind, etc.)
- Não usar imagens — use gradientes, ícones SVG inline e placeholders com iniciais para fotos de depoimentos
- Não usar jQuery — JS vanilla puro
- Não inventar informações de contato, endereço ou nomes
- Não mudar as cores da identidade visual

---

Entregue um único arquivo `index.html` completo, funcional e pronto para substituir o site atual.
