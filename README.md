# MiraFoot Manager 6.0

Jogo de manager estilo Brasfoot, offline. Publique `index.html` e `database.json` **juntos** na raiz do GitHub Pages.

## Escudos oficiais (clubes licenciados)
1. Crie a pasta `crests/` ao lado do `index.html`.
2. Salve um arquivo por clube com o nome de `crests-lista.txt` (ex.: `flamengo.png`; PNG, SVG ou WEBP).
3. Rode `python3 gerar-manifest.py` e envie `crests/` (com `manifest.json`) ao GitHub.
O jogo usa o arquivo quando ele existe; sem ele, mostra o escudo desenhado em código (Opções → Escudos oficiais).

## Novidades da 6.0
- **Saves múltiplos** (primeira tela) e início por **continente → liga → clube**.
- **Estádios com nomes reais** no cabeçalho de cada partida (764 clubes).
- **Copas nacionais**, **Copa Intercontinental (Mundial de Clubes)** anual e **Super Mundial** a cada 4 temporadas, com regulamentos.
- Competições continentais ao vivo; tabela ou **chaveamento** atualizado no fim de cada jogo.
- **Taças animadas** ao ganhar títulos.
- **Demissão e propostas**: sem clube, as rodadas continuam ao vivo e 1–2 clubes enviam folhas de contrato por rodada, conforme seu desempenho.
- **Patrocínios** (master e material esportivo obrigatórios, até 5), empréstimo bancário com juros por valor e prazo, negociação com clube e jogador, empréstimo de jogadores de 1 mês a 1 ano.
- Propostas de venda na tela do Elenco e após alguns jogos. Barra de vigor, finanças em aba própria, som de torcida, gols, cliques e apito, e mais opções.
