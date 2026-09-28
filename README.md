<img width="1400" height="396" alt="SMT3_HD_PTBR_Nexus_1400x396" src="https://github.com/user-attachments/assets/e58c7982-6836-4716-886d-69bce316e1e2" />
# Shin Megami Tensei III Nocturne HD Remaster — Tradução PT-BR v1.2

Tradução para português do Brasil de **Shin Megami Tensei III Nocturne HD Remaster**
(PC / Steam).

Traduz **o jogo inteiro**: todo o texto, as cenas das DLCs, **as imagens** — menus,
letreiros de área, tela de título, aviso de ficção — e o **vídeo de abertura**.

> ⚠️ **O jogo precisa estar em ESPANHOL.** Esta tradução reescreve os arquivos do
> idioma espanhol — ela não adiciona um idioma novo. Com o jogo em outro idioma, a
> tradução simplesmente não aparece.

---

## Novidades da v1.2

- **Descrições na batalha sem palavras grudadas**: na barra de ajuda da batalha o jogo
  junta as linhas da descrição numa só, e algumas palavras saíam coladas
  («físicoe», «mágicode»). O espanhol deixa um espaço no fim de cada linha dessas
  descrições; agora o português também. Corrigido nas 568 descrições de habilidades e
  itens.

**Já tem a v1.1?** Só um arquivo mudou: `smt3hd_Data\StreamingAssets\PC\common_es`.
Vindo da v1.0, copie o pacote inteiro por cima.

### O que veio na v1.1

- **Nenhuma arte sai mais cortada**: todas as imagens com texto — inclusive os
  letreiros de área, como o do Parque de Yoyogi — agora cabem na largura do original
  espanhol (o jogo recorta a imagem com uma máscara do tamanho do texto espanhol).
- 本院 do hospital agora é sempre **«Prédio Principal»** nos nomes de local.
- Explicação dos **andares do elevador** (veja «O que ficou de fora»).

---

## Feita a partir do japonês

A base é o **texto japonês**, não o inglês nem o espanhol. Onde o espanhol resumiu ou
mudou o sentido, vale o original:

> JP 「衆生は大悲にて　赤き霊となり」 · ES «sus almas, rojas de pecado»
> **PT** — `Por grande compaixão, todos os seres se tornarão espíritos rubros,`

- A terminologia segue a **tradução oficial em português da Atlus em *Shin Megami
  Tensei V: Vengeance***: **Semi-infernante**, **Infernante**, **Concepção**,
  **Macca**, **Menorá** — e o Jack Frost diz **`Hi-ho`**.
- A negociação com demônios mantém a voz de cada personalidade: o registro arcaico
  dos senhores, a fala quebrada das feras, os tiques sob Kagutsuchi cheio.
- Onde o espanhol errou, o português acerta: o letreiro `TÚNEL DE YARAKUCHO` é
  **Túnel de Yurakucho**; a fase 静天 é **APAGADO** (o espanhol pôs «NUEVA»), como no
  resto do texto.

**Recomendamos jogar com a dublagem em japonês.**

---

## O texto

| | |
|---|---|
| História, cenas, exploração, Labirinto de Amala, instalações, batalha, menus, Compêndio | **33.390 entradas**, revisadas duas vezes contra o japonês |
| Negociação com demônios — todas as personalidades | completa |
| Cenas das DLCs | completas |

## As imagens e o vídeo

**136 imagens refeitas**, com as letras montadas a partir das próprias fontes do jogo
(de várias línguas da mesma textura) e com o brilho e o contorno de cada tela:

- **Menus** — comandos de batalha, avisos de golpe, resultado da luta, status, fusão,
  lojas, salvar, mapa e bússola, configurações, tela de nome, minijogo.
- **Fases de Kagutsuchi** — `MORTO`, `CHEIO`, `MEIO`, `APAGADO`.
- **Letreiros de área** — 48 imagens, nos dois tamanhos.
- **Tela de título** e **aviso de ficção**.
- **Vídeo de abertura** — as duas versões, com o texto em português na mesma animação
  do original.

---

## Instalação

1. Deixe o jogo em **espanhol** pela Steam (*Propriedades* → *Geral* → *Idioma* →
   *Español — España*) e espere a Steam terminar de atualizar.
2. **Feche o jogo** e faça backup das pastas `smt3hd_Data\StreamingAssets\PC` e `dlc`.
3. Extraia o `.zip` e copie a pasta `smt3hd_Data` dele para a pasta do jogo,
   **substituindo** os arquivos — normalmente `...\steamapps\common\smt3hd\`.
4. Copie também a pasta `dlc`, **só se o seu jogo já tiver uma pasta `dlc`**.

São **255 arquivos**; a lista com o MD5 de cada um está em `ARQUIVOS.txt`.

Abra o jogo: o aviso de abertura, a tela de título e os menus devem aparecer em
português.

### Não funcionou?

| O que você vê | Causa quase certa |
|---|---|
| Jogo em espanhol, sem nada em português | Os arquivos não foram para `smt3hd\smt3hd_Data\StreamingAssets\PC\` |
| Jogo em inglês ou outro idioma | O jogo não está em espanhol |
| Cenas das DLCs em espanhol | A pasta `dlc` do pacote não foi copiada |
| O português sumiu depois de um tempo | A Steam verificou os arquivos; reinstale |
| O jogo não abre | Restaure o backup e reporte |

Para desinstalar, restaure o backup ou use *Verificar integridade dos arquivos* na
Steam.

---

## O que ficou de fora

- **`DESHACER`**, no minijogo das caixas — a fonte dessa imagem não tem as letras para
  «DESFAZER».
- **O `ã` minúsculo no teclado da tela de nome** — erro do jogo original, presente
  também em espanhol e inglês. Use o `Ã` maiúsculo; nos diálogos o `ã` aparece
  normalmente.
- **Andares do elevador em sigla espanhola** (`A`, `P2`, `P1`, `S1`) — o próprio código
  do jogo monta esses nomes, e não dá para trocá-los sem modificar o executável.
  **A** = *Azotea* (terraço), **P2** = 2º andar, **P1** = 1º andar (térreo),
  **S1** = subsolo 1.
- Alguns textos de menu em imagem ficaram levemente **condensados** para caber no
  espaço do original.

Encontrou algo? Abra uma issue com um print e a tela ou o lugar onde apareceu.

---

*Shin Megami Tensei III Nocturne HD Remaster* © ATLUS © SEGA. Todos os direitos
reservados. Projeto de fã, gratuito e sem fins lucrativos, sem vínculo com Atlus ou
SEGA.

