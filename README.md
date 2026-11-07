# MiraFoot Manager 7.0

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

## 6.1
- Ásia (China, Emirados, Catar, Irã, Uzbequistão, Índia, Tailândia, J2, K League 2) e Oceania (A-League e Nova Zelândia) completas, com estádios reais e cores dos clubes.
- Estádio com nome para todos os 954 clubes.
- Libertadores e Sul-Americana com 32 clubes, 8 grupos e oitavas de final.
- Escalação automática com os melhores jogadores; goleiro não se cansa; recuperação de vigor mais rápida.
- Pênaltis calculados contra o goleiro adversário; sem negociação de salário com jogador.
- Tela de escolha do jogo no lugar da lista cinza do navegador.
- Resultado e classificação (ou chaveamento) atualizados ao fim de cada jogo.
- Taças redesenhadas (Libertadores como na referência) em todas as competições.

## 7.0
- Idade em todos os jogadores (mercado e elenco; "~" = idade estimada), aposentadoria entre 36 e 40 anos e renovação anual em todos os clubes (cada aposentado é substituído por um jovem; mínimo de 1 por ano).
- Várias características por jogador, filtro por característica e idade no mercado.
- Academia (base) com níveis pagos, promessas raras, lendas (⚽ dourada) e venda/empréstimo de jogadores sem proposta.
- 26 formações. Rolagem da partida corrigida. Contrato continua de onde parou (mesma rodada e posição); assinatura animada.
- Vigor equilibrado (goleiro não cansa) e times fortes goleiam times fracos.
- Subida e descida pelos regulamentos: Série C e D do Brasileirão (fase final e mata-mata), playoffs de acesso (Inglaterra, Espanha, Itália) e playoffs de MLS, Liga MX e Argentina.
- Mata-mata com "Jogo 1 de 2", prorrogação e disputa de pênaltis.
- MiraNet: feed de notícias estilo rede social (transferências, títulos, aposentadorias, promessas, seu clube).
