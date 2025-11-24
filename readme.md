# Jogos Família Santos — Portal

Página inicial moderna e responsiva que organiza os jogos da família. A home (`home.html`) apresenta cards para “Jogos da Lais” e “Jogos do JP”, com navegação simples e visual infantil.

## Destaques
- Layout moderno com gradientes, vidro fosco e ícones.
- Responsivo para celular e computador (tipografia e elementos com `clamp()` e media queries).
- Menu com botões: “Jogos da Lais” (`jogosLais.html`) e “Jogos do JP` (`jogosJP.html`).
- `index.html` redireciona automaticamente para `home.html`.

## Visão Geral
- Interações com **arrastar e soltar** itens nas zonas corretas de cada sala.
- Navegação entre **Quarto**, **Cozinha**, **Sala**, **Banheiro**, **Quintal** e **Mercado**.
- Sons sintetizados via WebAudio para cada ação, feedback visual com **partículas**, **emojis** e **textos flutuantes**.
- Salvamento automático do progresso em `localStorage`.

## Como Jogar
- Use os botões no topo para trocar de sala.
- Clique no cachorro para dar carinho e aumentar a felicidade.
- Arraste:
  - Comida até a tigela na **Cozinha** para o cachorro comer.
  - Itens de higiene até a **Banheira** no **Banheiro**.
  - Bagunças até as **zonas** corretas para limpar e ganhar dinheiro.
- No **Mercado**, arraste itens até o **Carrinho**, depois clique em **Comprar** para entregar nas salas.
- Leve o cachorro até o **Vaso** para “alívio” e até a **Casinha** para descansar um pouco.
- Se a energia chegar a 0, aparece a tela de **Game Over**; use “Recomeçar” para reiniciar.

## Salas e Zonas
- Quarto: `Roupas`, `Caminha`, `Brinquedos`
- Cozinha: `Geladeira`, `Tigela`
- Sala: `TV`, `Estante`, `Sofá`, `Mesa lateral`
- Banheiro: `Banheira`, `Vaso`
- Quintal: `Casinha`, `Jardim`
- Mercado: `Carrinho` e prateleiras categorizadas

## Mecânicas
- Loop do jogo reduz as barras ao longo do tempo.
- Limpar bagunças rende dinheiro (`R$`) para compras no Mercado.
- Itens comprados são entregues nas salas e podem ser usados.
- Feedback visual e sons para ações:
  - `pop` ao posicionar,
  - `coin` ao ganhar dinheiro,
  - `eat` ao comer,
  - `water` para banho,
  - `flush` no vaso,
  - `bark` ao carinho.

## Execução
- Basta abrir `index.html` no navegador (duplo clique).
- Funciona offline; não requer servidor.

## Persistência
- Progresso salvo automaticamente em `localStorage` (chave `dogHouseSave`).
- Para reiniciar do zero, use o botão “Recomeçar” ou limpe o `localStorage`.

## Assets
- Imagens opcionais (fallback para emojis se faltarem): `cachorro.png`, `guardaroupa.png`, `camacachorro.png`, `baubrinquedo.png`, `geladeira.png`, entre outras referenciadas.
- Caso alguma imagem não esteja presente, o jogo substitui por um emoji automaticamente.

## Tecnologias
- HTML + CSS + JavaScript puro
- WebAudio API
- `localStorage`

## Ideias Futuras
- Missões e objetivos com recompensas
- Inventário persistente e uso de itens
- Balanceamento das taxas do loop para sessões mais longas
- Dicas de zonas destino ao arrastar

## Jogo: Dog House — Mundo do Cachorro

Um jogo de uma página onde você cuida de um cachorrinho, mantendo **Energia**, **Higiene** e **Felicidade**, limpando bagunças para ganhar dinheiro e comprando itens no **Mercado**.

### Visão Geral
- Arrastar e soltar itens nas zonas corretas (quarto, cozinha, sala, banheiro, quintal, mercado).
- Sons via WebAudio, feedback com partículas, emojis e textos flutuantes.
- Salvamento automático do progresso em `localStorage`.

### Mercado
- Abas: `Comida`, `Higiene`, `Casa`, `Diversão`.
- Itens adicionados:
  - Higiene: `🧼`, `🧴`, `🪥`, `🧽` (Banheiro → `Banheira`).
  - Casa: `🪴`, `🖼️`, `🪑`, `🪞` (Sala → `Estante`/decoração, `Sofá`/conforto).
  - Diversão: `🎲`, `🪁`, `🦴`, `🧸`, `🎾` (Sala, Quarto, Quintal).

### Como Jogar
- Troque de sala pelos botões do topo.
- Clique no cachorro para aumentar a felicidade.
- Comida: leve até a tigela na cozinha ou diretamente ao cachorro na cozinha.
- Higiene: leve itens à banheira; banho também ao arrastar o cachorro.
- Diversão/Casa: posicione nas zonas destino para organizar ou decorar.

### Responsividade
- Elementos principais usam `clamp()` e `vw` para escalar.
- Media queries:<br>Mobile (`max-width: 600px`) com HUD compacto e navegação centralizada;<br>Desktop (`min-width: 1200px`) com tipografia ajustada.

### Execução
- Abra `home.html` para iniciar no portal.
- `index.html` redireciona automaticamente para `home.html`.
- Funciona offline; não requer servidor.

### Estrutura
- `home.html` — Página inicial do portal.
- `index.html` — Jogo do cachorro (entry com redirecionamento para a home).
- `jogosLais.html` — Lista/entrada dos jogos da Lais.
- `jogosJP.html` — Lista/entrada dos jogos do JP.

### Tecnologias
- HTML, CSS, JavaScript puro; WebAudio; `localStorage`.

### Ideias Futuras
- Missões e objetivos com recompensas.
- Catálogo de jogos completo nas páginas da Lais e do JP.
- Inventário persistente e dicas visuais nas zonas de drop.

Divirta-se em família! #FamiliaSantos