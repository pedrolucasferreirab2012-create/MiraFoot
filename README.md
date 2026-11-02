# MiraFoot Offline 2026

Esta versão não usa API, chave, backend ou chamadas externas durante o jogo. `database.json` fica no mesmo repositório e é carregado localmente pelo navegador.

## Publicar no GitHub Pages
1. Crie um repositório público ou privado no GitHub.
2. Envie `index.html` e `database.json` para a raiz do repositório.
3. Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save.
4. Abra o endereço publicado.

## Conteúdo
- Interface responsiva para celular e PC.
- Escolha de clube e carreira local.
- Elencos selecionados com jogadores reais de clubes europeus em 2026/27 e jogadores brasileiros identificados na artilharia oficial de 2026.
- Overall 1–99 estimado pelo jogo; não é nota oficial.
- Mercado com preço calculado a partir do overall.
- Presets de escalação: Titular, Reservas e Copa.
- Simulação simples de partidas e finanças.
- Regulamentos 2026 resumidos e os 16 grupos reais da Série D 2026.
- Backup e restauração da carreira.

## Limitações importantes
Esta é uma base estática curada, não um cadastro completo de todos os atletas profissionais do mundo. A lista de jogadores contém atletas confirmados nas fontes oficiais consultadas, mas não representa todos os jogadores de cada elenco. Vários clubes brasileiros e divisões inferiores aparecem com seus clubes e regulamentos, mas sem elenco individual completo. Não inventamos nomes para preencher lacunas.
As idades não foram incluídas quando não estavam confirmadas nas fontes utilizadas. Overalls, salários e valores de mercado são estimativas de jogo criadas pelo MiraFoot.
O simulador ainda não executa temporadas completas de todos os torneios nem aplica automaticamente toda a progressão/rebaixamento. Os formatos e regulamentos estão documentados na seção Competições.

## Fontes de dados consultadas
- CBF — Série A 2026: https://www.cbf.com.br/futebol-brasileiro/tabelas/campeonato-brasileiro/serie-a/2026?documento=Regulamento
- CBF — grupos Série D 2026: https://www.cbf.com.br/futebol-brasileiro/noticias/amistoso/amistosos/cbf-divulga-grupos-da-serie-d-de-2026
- CBF — Série B 2026: https://www.cbf.com.br/futebol-brasileiro/noticias/undefined/botafogo-x-paysandu/brasileirao-serie-b-comeca-com-novo-formato
- CBF — Série C 2026: https://www.cbf.com.br/futebol-brasileiro/noticias/undefined/sao-bernardo-fc-x-anapolis/cbf-publica-documentos-tecnicos-da-serie-c-de-2026
- Premier League — plantéis 2026/27: https://www.premierleague.com/en/news/4725682
- FC Barcelona — números 2026/27: https://www.fcbarcelona.com/en/football/first-team/news/4570894/202627-first-team-jersey-numbers-confirmed/featured
- Real Madrid — números 2026/27: https://www.realmadrid.com/en-US/news/football/first-team/latest-news/dorsales-del-real-madrid-para-la-temporada-2026-27-10-08-2026
- Bayern / Bundesliga — elenco 2026/27: https://www.bundesliga.com/en/bundesliga/clubs/fc-bayern-muenchen
- PSG — elenco 2026/27: https://www.psg.fr/pt/futebol-masculino/jogadores
- Inter — elenco: https://www.inter.it/it/squadra/prima-squadra
- AC Milan — elenco 2026/27: https://www.acmilan.com/en/teams/men-first-team
- CONMEBOL — Libertadores 2026: https://gol.conmebol.com/libertadores/pt-br/sorteo-3
- FIFA — Copa Intercontinental 2026: https://www.fifa.com/pt/tournaments/mens/intercontinentalcup/2026/


## Atualização 2.0 — jogadores
A base foi ampliada para 1075 jogadores e 205 clubes. Inclui jogadores de profundidade e jovens com OVRs baixos, além de craques e estrelas. Os overalls são estimativas de gameplay do MiraFoot; não são notas oficiais. A lista foi montada a partir de plantéis publicados de 2026/27 e dados públicos de clubes brasileiros de 2026.

## Configurações de partida
Na aba **Configurações**, escolha a duração real de cada partida: 1, 3, 5, 8, 10, 15 ou 20 minutos. O relógio do jogo avança de 0 a 90 minutos dentro do tempo escolhido. Durante a partida é possível pausar e continuar. A escolha fica salva no navegador e vale para os próximos jogos.

## Publicar pelo celular Android
1. Baixe e extraia o arquivo ZIP no celular.
2. Entre em https://github.com e abra sua conta.
3. Crie um repositório chamado `mirafoot` (ou abra o repositório que você já criou).
4. Na página do repositório, toque em **Add file** → **Upload files**.
5. Abra a pasta extraída `MiraFoot-Offline-2026` e selecione `index.html`, `database.json` e os arquivos `.md` se quiser. O essencial é enviar `index.html` e `database.json`.
6. Confirme que `index.html` e `database.json` aparecem diretamente na página principal do repositório, e não dentro de uma pasta adicional.
7. Toque em **Commit changes** para salvar os arquivos.
8. Abra **Settings** → **Pages**.
9. Em **Build and deployment**, escolha **Deploy from a branch**. Selecione a branch `main` e a pasta `/(root)`, depois toque em **Save**.
10. Aguarde a publicação e abra o endereço mostrado na seção Pages. Normalmente ele termina em `github.io/mirafoot/`.

Se o site abrir mas mostrar erro de banco de dados, confira se `database.json` está no mesmo nível de `index.html` e se o nome está escrito exatamente assim, em letras minúsculas.


## MiraFoot 2.2 — interface Manager

Esta versão reorganiza a apresentação para lembrar a estrutura de um manager clássico de futebol, com menu lateral no computador e navegação inferior no celular. Não reproduz os arquivos, marcas ou telas proprietárias do Brasfoot, mas usa a mesma lógica de navegação direta e informação compacta.

### Melhorias desta versão
- Interface clássica de manager: menu lateral, painéis compactos, tabelas e cabeçalhos de seção.
- Partida abre em uma tela exclusiva, com placar ao vivo, relógio de 0 a 90 minutos, pausa/continuação e narração de lances.
- Eventos de gol, cartão amarelo, ataques, faltas e intervalo; a força média da escalação influencia as chances de gol.
- Campo tático ilustrado: os 11 jogadores aparecem posicionados conforme 4-3-3, 4-4-2, 4-2-3-1 ou 3-5-2.
- Troca de jogador diretamente no campo e salvamento separado das escalações.
- Substituições durante a partida, com limite de cinco.
- Mercado com busca por nome, filtro por posição e faixa de overall mínimo/máximo.
- Layout adaptado para Android: menu vira barra inferior e os painéis se reorganizam.

### Limites que continuam existindo
A narração e os resultados ainda são uma simulação simplificada, não um motor tático completo. As competições e temporadas automáticas, calendário integral, classificação rodada a rodada e regulamentos executáveis ainda precisam ser desenvolvidos em uma próxima etapa. A base contém jogadores selecionados e não garante elenco completo/atualizado de todos os clubes.

## Atualização 2.3 — preparação, tática e fadiga
- Nova tela de preparação antes do pontapé inicial, com escolha dos 11 titulares e formação.
- Botão de recomendação de escalação, priorizando posição e overall.
- Correções manuais de posições de vários jogadores conhecidos (incluindo Neymar, Kevin De Bruyne, Paulo Dybala, Jonathan David e outros).
- Sistema de energia/fadiga: o rendimento cai conforme a energia diminui; o estilo ofensivo consome mais energia.
- Pausa automática no intervalo (45 minutos), permitindo substituições e ajustes de formação/estilo antes do segundo tempo.
- Estilos: defensivo, equilibrado, ofensivo, contra-ataque e posse de bola.

Observação: as posições revisadas são uma camada de correção para os nomes conhecidos presentes na base; ainda não equivalem a uma auditoria completa e oficial de todos os 1.075 registros. O simulador continua sendo uma simulação simplificada, não o motor original do Brasfoot.
