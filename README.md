# MiraFoot Manager 3.0

Jogo de manager estilo Brasfoot, 100% offline (sem API). Funciona no navegador e no celular.

## Publicar no GitHub Pages
1. Envie `index.html` e `database.json` para a **raiz** do repositório.
2. Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save.
3. Abra o endereço `https://SEU-USUARIO.github.io/NOME-DO-REPO/`.
(Abrir o index.html direto do celular pode bloquear a leitura do database.json; use o GitHub Pages ou um servidor local.)

## Novidades da 3.0
- Layout refeito nos moldes do Brasfoot: tela do elenco (confiança da diretoria/torcida, caixa, idade, energia, preço/salário), partida com placar, artilheiros, cartões, relógio por tempo e "Jogos da rodada" por divisão, e tela de escalação com campo, banco, estilo de jogo, marcação e concentração de ataque.
- Posições de todos os jogadores revisadas (ex.: Neymar, Schick, De Bruyne, Dybala estavam errados).
- Duplicados removidos e clubes repetidos unificados (ex.: Atlético de Madrid, Vitória, Atlético-MG, Bragantino).
- Escalação automática pelo melhor encaixe jogador/posição; jogador fora de posição rende menos.
- Intervalo com pausa, até 5 substituições, energia por jogador, classificação, mercado (compra/venda), backup.

## Limitações
- Overalls, preços e salários são estimativas do jogo. Idades de jogadores reais não confirmadas aparecem como "--".
- Clubes sem elenco público têm jogadores **fictícios** (real:false), como no Brasfoot, para completar 24 atletas.
- "Concentrar ataque" ainda é só visual. Ligas europeias têm poucos clubes cadastrados.
- Não é cópia do Brasfoot: layout inspirado, sem arquivos ou marcas dele.

Fontes dos dados reais: ver README anterior (CBF, Premier League, clubes europeus).
