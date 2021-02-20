# Fairy-Random

## Overview

Fairy-Random is a chess variant random mover derived from [Fairy-Stockfish](https://github.com/ianfab/Fairy-Stockfish/) designed for the support of fairy chess variants and easy extensibility with more games. It can play various regional, historical, and modern chess variants as well as [games with user-defined rules](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration). For [compatibility with graphical user interfaces](https://github.com/ianfab/Fairy-Stockfish/wiki/Usage) it supports the UCI, UCCI, USI, and CECP/XBoard protocols.

The goal of the project is to create a random mover supporting a large variety of chess-like games. Due to its multi-protocol support Fairy-Random works with almost any chess variant GUI.

## Installation
You can download the [Windows executable](https://github.com/Fulmene/Fairy-Random/releases/latest/download/fairy-random-largeboard_x86-64.exe) or [Linux binary](https://github.com/Fulmene/Fairy-Random/releases/latest/download/fairy-random-largeboard_x86-64) from the [latest release](https://github.com/ianfab/Fairy-Stockfish/releases/latest) or [compile the program from source](https://github.com/ianfab/Fairy-Stockfish#compiling-stockfish-yourself-from-the-sources). The program comes without a graphical user interface, so you perhaps want to use it together with a [compatible GUI](https://github.com/ianfab/Fairy-Stockfish/wiki/Usage#guis).

## Supported games

The games currently supported besides chess are listed below. Fairy-Stockfish can also play user-defined variants loaded via a variant configuration file, see the file [`src/variants.ini`](https://github.com/ianfab/Fairy-Stockfish/blob/master/src/variants.ini) and the [wiki](https://github.com/ianfab/Fairy-Stockfish/wiki/Variant-configuration).

### Regional and historical games
- [Xiangqi](https://en.wikipedia.org/wiki/Xiangqi), [Manchu](https://en.wikipedia.org/wiki/Manchu_chess), [Minixiangqi](http://mlwi.magix.net/bg/minixiangqi.htm), [Supply chess](https://en.wikipedia.org/wiki/Xiangqi#Variations)
- [Shogi](https://en.wikipedia.org/wiki/Shogi), [Shogi variants](https://github.com/ianfab/Fairy-Stockfish#shogi-variants)
- [Janggi](https://en.wikipedia.org/wiki/Janggi)
- [Makruk](https://en.wikipedia.org/wiki/Makruk), [ASEAN](http://hgm.nubati.net/rules/ASEAN.html), Makpong, Ai-Wok
- [Ouk Chatrang](https://en.wikipedia.org/wiki/Makruk#Cambodian_chess), [Kar Ouk](https://en.wikipedia.org/wiki/Makruk#Cambodian_chess)
- [Sittuyin](https://en.wikipedia.org/wiki/Sittuyin)
- [Shatar](https://en.wikipedia.org/wiki/Shatar), [Jeson Mor](https://en.wikipedia.org/wiki/Jeson_Mor)
- [Shatranj](https://en.wikipedia.org/wiki/Shatranj), [Courier](https://en.wikipedia.org/wiki/Courier_chess)

### Chess variants
- [Capablanca](https://en.wikipedia.org/wiki/Capablanca_Chess), [Janus](https://en.wikipedia.org/wiki/Janus_Chess), [Modern](https://en.wikipedia.org/wiki/Modern_Chess_(chess_variant)), [Chancellor](https://en.wikipedia.org/wiki/Chancellor_Chess), [Embassy](https://en.wikipedia.org/wiki/Embassy_Chess), [Gothic](https://www.chessvariants.com/large.dir/gothicchess.html), [Capablanca random chess](https://en.wikipedia.org/wiki/Capablanca_Random_Chess)
- [Grand](https://en.wikipedia.org/wiki/Grand_Chess), [Shako](https://www.chessvariants.com/large.dir/shako.html), [Centaur](https://www.chessvariants.com/large.dir/contest/royalcourt.html)
- [Chess960](https://en.wikipedia.org/wiki/Chess960), [Placement/Pre-Chess](https://www.chessvariants.com/link/placement-chess)
- [Crazyhouse](https://en.wikipedia.org/wiki/Crazyhouse), [Loop](https://en.wikipedia.org/wiki/Crazyhouse#Variations), [Chessgi](https://en.wikipedia.org/wiki/Crazyhouse#Variations), [Pocket Knight](http://www.chessvariants.com/other.dir/pocket.html), Capablanca-Crazyhouse
- [Bughouse](https://en.wikipedia.org/wiki/Bughouse_chess), [Koedem](http://schachclub-oetigheim.de/wp-content/uploads/2016/04/Koedem-rules.pdf)
- [Seirawan](https://en.wikipedia.org/wiki/Seirawan_chess), Seirawan-Crazyhouse
- [Amazon](https://en.wikipedia.org/wiki/Amazon_(chess)), [Chigorin](https://en.wikipedia.org/wiki/Chigorin_Chess), [Almost chess](https://en.wikipedia.org/wiki/Almost_Chess)
- [Hoppel-Poppel](http://www.chessvariants.com/diffmove.dir/hoppel-poppel.html), New Zealand
- [Antichess](https://lichess.org/variant/antichess), [Giveaway](http://www.chessvariants.com/diffobjective.dir/giveaway.old.html), [Suicide](https://www.freechess.org/Help/HelpFiles/suicide_chess.html), [Losers](https://www.chessclub.com/help/Wild17), [Codrus](http://www.binnewirtz.com/Schlagschach1.htm)
- [Extinction](https://en.wikipedia.org/wiki/Extinction_chess), [Kinglet](https://en.wikipedia.org/wiki/V._R._Parton#Kinglet_Chess), Three Kings Chess
- [King of the Hill](https://en.wikipedia.org/wiki/King_of_the_Hill_(chess)), [Racing Kings](https://en.wikipedia.org/wiki/V._R._Parton#Racing_Kings)
- [Three-check](https://en.wikipedia.org/wiki/Three-check_chess), Five-check
- [Los Alamos](https://en.wikipedia.org/wiki/Los_Alamos_chess)
- [Horde](https://en.wikipedia.org/wiki/Dunsany%27s_Chess#Horde_Chess)
- [Knightmate](https://www.chessvariants.com/diffobjective.dir/knightmate.html)

### Shogi variants
- [Minishogi](https://en.wikipedia.org/wiki/Minishogi), [EuroShogi](https://en.wikipedia.org/wiki/EuroShogi), [Judkins shogi](https://en.wikipedia.org/wiki/Judkins_shogi)
- [Kyoto shogi](https://en.wikipedia.org/wiki/Kyoto_shogi), [Microshogi](https://en.wikipedia.org/wiki/Micro_shogi)
- [Dobutsu shogi](https://en.wikipedia.org/wiki/Dōbutsu_shōgi), [Goro goro shogi](https://en.wikipedia.org/wiki/D%C5%8Dbutsu_sh%C5%8Dgi#Variation)

### Related games
- [Amazons](https://en.wikipedia.org/wiki/Game_of_the_Amazons)
- [Ataxx](https://en.wikipedia.org/wiki/Ataxx)
- [Breakthrough](https://en.wikipedia.org/wiki/Breakthrough_(board_game))
- [Clobber](https://en.wikipedia.org/wiki/Clobber)
