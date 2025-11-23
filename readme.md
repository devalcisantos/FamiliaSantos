# Dog House — Mundo do Cachorro

Um jogo web feito em uma única página (`index.html`) onde você cuida de um cachorrinho, mantendo suas barras de **Energia**, **Higiene** e **Felicidade**, limpando bagunças para ganhar dinheiro e comprando itens no **Mercado**.

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

Divirta-se cuidando do seu amigão!# Dog House — Mundo do Cachorro

Um jogo web feito em uma única página (`index.html`) onde você cuida de um cachorrinho, mantendo suas barras de **Energia**, **Higiene** e **Felicidade**, limpando bagunças para ganhar dinheiro e comprando itens no **Mercado**.

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

Divirta-se cuidando do seu amigão!