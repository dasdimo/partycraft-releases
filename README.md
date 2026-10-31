**NOT AN OFFICIAL MINECRAFT PRODUCT. NOT APPROVED BY OR ASSOCIATED WITH MOJANG OR MICROSOFT.**

# Partycraft

*English below.*

Ein Party-Brettspiel mit Minigames für 2 bis 4 Spieler, direkt in **Minecraft 26.3**. Würfelt euch über das Brett,
sammelt Münzen und kauft Sterne. Nach jeder Runde tretet ihr in einem Minigame gegeneinander an, und freie Plätze
füllen Bots auf.

## So bekommst du die Mod

Über den **[DasDimo Launcher](https://github.com/dasdimo/dasdimo-launcher-releases)**: Er legt die Mod in dein
Minecraft-Profil (Minecraft Launcher, Modrinth App, NoRisk Client, CurseForge, Prism), hält sie aktuell und zeigt dir,
was noch fehlt.

Wer Mods selbst verwaltet: die `.jar` aus dem
[neuesten Release](https://github.com/dasdimo/partycraft-releases/releases/latest) in den `mods`-Ordner legen, dazu
Fabric API.

## Was du brauchst

- Minecraft **26.3** mit **Fabric Loader 0.19.5** oder neuer (Java 25 bringt Minecraft selbst mit)
- **[Fabric API](https://modrinth.com/mod/fabric-api)** 0.162.0+26.3 oder neuer

Im Multiplayer braucht der Server die Mod und Fabric API, und jeder Spieler dieselbe Version der Mod.

## Stand der Mod

Partycraft ist spielbar, aber noch nicht fertig (Testversion).

- **Fertig:** das Brettspiel von der ersten Runde bis zur Siegerehrung, das Brett Dorffest, 7 Minigames, 9 Items, Bots
  und ein Editor für eigene Bretter
- **Als Nächstes:** neue Felder und Händler, ein Spielleiter, der alles erklärt, Minigames für Teams, zwei weitere Bretter
- **Später:** weitere Spielmodi, noch mehr Minigames und Kostüme

## Erste Schritte

1. `/party create` erstellt eine Party.
2. `/party addbot` holt Bots dazu, Freunde treten mit `/party join <spieler>` bei.
3. `/party start` startet das Spiel.
4. Mit Mausrad oder W/A/S/D wählst du, mit Linksklick bestätigst und würfelst du.

`/party` zeigt alle Befehle. `/party test <minigame>` startet ein einzelnes Minigame.

## Lizenz

Die Mod steht unter der MIT-Lizenz (`LICENSE` in der `.jar`). Der Quellcode ist nicht öffentlich. In der `.jar` steckt die Bibliothek **Fantasy** von den
Nucleoid Contributors unter der [LGPL-3.0](https://github.com/NucleoidMC/fantasy) (`THIRD_PARTY_NOTICES.md` in der `.jar`).

Fehler und Wünsche bitte direkt an DasDimo schicken.

## Alle Änderungen

### 0.4.5 (2026-10-31)
- Erste Version im DasDimo Launcher!
- Minigames gemeinsam testen: /party test geht jetzt auch aus einer Lobby mit Freunden, danach seid ihr wieder zusammen in der Lobby.
- Stand der Mod: spielbar, aber noch nicht fertig. Dabei sind das Brettspiel, 1 Brett, 7 Minigames, 9 Items und Bots. Als Nächstes kommen neue Felder, ein Spielleiter und Team-Minigames.

### 0.4.4 (2026-10-13)
- Wer in einem Minigame rausfliegt, schaut frei fliegend zu und kann per Linksklick einem Spieler folgen.
- Slime-Sumo nutzt jetzt echte Minecraft-Schläge, Leben verliert man dabei nicht.
- Baumeister: Du kannst fliegen, jeder bleibt in seiner Zone, die Bots bauen langsamer.
- Der Wunschwürfel geht jetzt von 1 bis 10. Das Zugmenü passt sich großen Auflösungen an.

### 0.4.3 (2026-10-13)
- Neues Zugmenü links mit Würfeln, Items und Spielbrett. Beim Spielbrett fliegst du frei über das Brett.
- Deine Figur mit deinem Skin steht groß im Bild, winkt und macht sich zum Würfeln bereit.
- Die untere Leiste zeigt die Zugreihenfolge, dazu ein Zeichen, wann das Minigame kommt.

### 0.4.2 (2026-10-13)
- Ambossregen, Creeper-Chaos, Slime-Sumo und Baumeister sind schwerer und abwechslungsreicher geworden.

### 0.4.1 (2026-10-13)
- Vier neue Minigames: Slime-Sumo, Ambossregen, Creeper-Chaos und Baumeister, alle mit Bots.
- Jedes Minigame hat jetzt eine eigene Umgebung, vom Marktplatz bis zur Lavaschlucht.

### 0.4.0 (2026-10-13)
- Items steigen funkelnd auf, wenn man sie bekommt, und der Händler erklärt seine Angebote.
- Die Kamera zeigt zu jeder Runde das ganze Brett. Viele Fehler bei Melodien, Klängen und Bots sind behoben.

### 0.3.4 (2026-10-13)
- Würfeln in zwei Schritten: Im Menü wählen, dann hält ein Klick den Würfel an.
- Animationen beim Gewinnen und Verlieren von Münzen und Sternen, großer Auftritt für den Wither-König.
- Größere Arenen für alle Minigames.

### 0.3.3 (2026-10-12)
- Kamerafahrten über das Brett und bei der Siegerehrung.
- Eigene Melodien aus Notenblock-Klängen.

### 0.3.2 (2026-10-12)
- Runde, leuchtende Felder, echter Würfel, eigene Münzen und Sterne, Karten beim Händler und ein buntes Glücksrad.

### 0.3.1 (2026-10-12)
- Eigene Grafiken für alle Fenster und Spielerkarten, dazu weiche Übergänge und Animationen.

### 0.3.0 (2026-10-12)
- Ein komplettes Partyspiel: Brett, Felder, Items, Minigames und Siegerehrung spielen sich von Anfang bis Ende.

### 0.2.3 (2026-10-12)
- Viele Fehler behoben, unter anderem bei Menüs, Geräuschen und Items.

### 0.2.2 (2026-10-12)
- Das Brett Dorffest mit 47 Feldern, Abzweigungen, Glücksrad, Wither-König, Händler und 9 Items.
- Finale in den letzten Runden und Siegerehrung mit Bonus-Sternen.

### 0.2.1 (2026-10-12)
- Minigames einzeln starten mit /party test.

### 0.2.0 (2026-10-12)
- Minigames! Nach jeder Runde dreht sich das Roulette. Dabei sind Bröckelboden, TNT-Kartoffel und Münzregen.

### 0.1.0 (2026-10-12)
- Erster Playtest: Lobby-Anzeige und viele Fehler rund um Bots und Inventar behoben.

### 0.0.4 (2026-10-12)
- Brett-Kamera, Würfelblock per Klick, Spielerkarten und ein Editor für eigene Bretter.

### 0.0.3 (2026-10-12)
- Bots bleiben standfest auf dem Brett.

### 0.0.2 (2026-10-12)
- Partys erstellen, würfeln, Münzen und Sterne sammeln, Bots spielen mit.

### 0.0.1 (2026-10-12)
- Die Mod lädt und antwortet auf /party.

---

# Partycraft (English)

A party board game with minigames for 2 to 4 players, right inside **Minecraft 26.3**. Roll your way across the board,
collect coins and buy stars. After every round you face off in a minigame, and bots fill empty seats.

## How to get it

Through the **[DasDimo Launcher](https://github.com/dasdimo/dasdimo-launcher-releases)**: it puts the mod into your
Minecraft profile (Minecraft Launcher, Modrinth App, NoRisk Client, CurseForge, Prism), keeps it up to date and shows
what else you need.

If you manage your mods yourself: put the `.jar` from the
[latest release](https://github.com/dasdimo/partycraft-releases/releases/latest) into your `mods` folder, together with
Fabric API.

## What you need

- Minecraft **26.3** with **Fabric Loader 0.19.5** or newer (Minecraft brings Java 25 itself)
- **[Fabric API](https://modrinth.com/mod/fabric-api)** 0.162.0+26.3 or newer

In multiplayer the server needs the mod and Fabric API, and every player the same version of the mod.

## Current status

Partycraft is playable, but not finished yet (test version).

- **Done:** the board game from the first round to the award ceremony, the Dorffest board, 7 minigames, 9 items, bots
  and an editor for your own boards
- **Coming next:** new spaces and shops, a game host who explains everything, team minigames, two more boards
- **Later:** more game modes, even more minigames and costumes

## First steps

1. `/party create` creates a party.
2. `/party addbot` adds bots, friends join with `/party join <player>`.
3. `/party start` starts the game.
4. Choose with the mouse wheel or W/A/S/D, confirm and roll with left click.

`/party` shows all commands. `/party test <minigame>` starts a single minigame.

## License

The mod is under the MIT license (`LICENSE` in the `.jar`). The source code is not public. The `.jar` contains the library **Fantasy** by Nucleoid Contributors under the
[LGPL-3.0](https://github.com/NucleoidMC/fantasy) (`THIRD_PARTY_NOTICES.md` in the `.jar`).

Bugs and wishes: please send them to DasDimo directly.

## All changes

### 0.4.5 (2026-10-31)
- First version in the DasDimo Launcher!
- Test minigames together: /party test now also works from a lobby with friends, and afterwards you are back in the lobby together.
- Status: playable, but not finished yet. It has the board game, 1 board, 7 minigames, 9 items and bots. Next up: new spaces, a game host and team minigames.

### 0.4.4 (2026-10-13)
- If you drop out of a minigame you can fly around freely and left-click a player to follow them.
- Slime Sumo now uses real Minecraft hits, and you don't lose health.
- Pixel Builder: you can fly, everyone stays in their own zone, and bots build slower.
- The Wish Dice now goes from 1 to 10. The turn menu adapts to large resolutions.

### 0.4.3 (2026-10-13)
- New turn menu on the left with Roll, Items and Board. With Board you fly freely above the board.
- Your figure with your skin stands big on screen, waves and gets ready to roll.
- The bottom bar shows the turn order, plus a marker for when the minigame comes.

### 0.4.2 (2026-10-13)
- Anvil Rain, Creeper Chaos, Slime Sumo and Pixel Builder got harder and more varied.

### 0.4.1 (2026-10-13)
- Four new minigames: Slime Sumo, Anvil Rain, Creeper Chaos and Pixel Builder, all with bots.
- Every minigame now has its own setting, from a market square to a lava gorge.

### 0.4.0 (2026-10-13)
- Items rise up sparkling when you get them, and the shop explains its offers.
- The camera shows the whole board at the start of each round. Many bugs with melodies, sounds and bots are fixed.

### 0.3.4 (2026-10-13)
- Rolling in two steps: pick it in the menu, then a click stops the dice.
- Animations for winning and losing coins and stars, and a big entrance for the Wither King.
- Bigger arenas for all minigames.

### 0.3.3 (2026-10-12)
- Camera moves across the board and at the award ceremony.
- Our own melodies made of note block sounds.

### 0.3.2 (2026-10-12)
- Round glowing spaces, a real dice, custom coins and stars, shop cards and a colourful lucky wheel.

### 0.3.1 (2026-10-12)
- Custom graphics for all windows and player cards, plus smooth transitions and animations.

### 0.3.0 (2026-10-12)
- A complete party game: board, spaces, items, minigames and award ceremony play from start to finish.

### 0.2.3 (2026-10-12)
- Many bugs fixed, among them in menus, sounds and items.

### 0.2.2 (2026-10-12)
- The Dorffest board with 47 spaces, forks, lucky wheel, Wither King, shop and 9 items.
- A finale in the last rounds and an award ceremony with bonus stars.

### 0.2.1 (2026-10-12)
- Start single minigames with /party test.

### 0.2.0 (2026-10-12)
- Minigames! The roulette spins after every round. Featuring Crumbling Floor, Hot Potato TNT and Coin Rain.

### 0.1.0 (2026-10-12)
- First playtest: a lobby display and many fixes around bots and inventory.

### 0.0.4 (2026-10-12)
- Board camera, dice block by click, player cards and an editor for your own boards.

### 0.0.3 (2026-10-12)
- Bots stay firmly on the board.

### 0.0.2 (2026-10-12)
- Create parties, roll, collect coins and stars, bots join in.

### 0.0.1 (2026-10-12)
- The mod loads and answers to /party.
