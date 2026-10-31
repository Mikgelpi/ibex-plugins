# Ibex plugins

Plugin pronti da installare per **Ibex Studio**. Ogni plugin è un file `.ibexplugin`, nella cartella con il suo nome.

*Ready-to-install plugins for **Ibex Studio**: one `.ibexplugin` file each, in the folder named after it. English below.*

## Plugin

| Plugin | Versione | Cosa fa | Ibex Studio |
|---|---|---|---|
| [Premium HMI](premium-hmi/) | 0.4.5 | **Nuovo progetto da Premium HMI…**: legge un progetto Progea / Emerson Premium HMI (Movicon 11) e ne fa un progetto Ibex: tag, allarmi, lingue, ricette, data logger e grafici, eventi, script Basic tradotti, schermate e immagini. | 0.7.1 o successivo |

## Installare un plugin

1. Scarica il file `.ibexplugin` dalla cartella del plugin.
2. In Ibex Studio: il **pezzo di puzzle** nella barra in alto → **Gestisci plugin…** → **Installa…** → scegli il file.
3. Prima di installarlo lo Studio mostra nome, versione, autore, comandi e **impronta SHA-256**: confrontala con quella qui sotto.
4. Il comando compare nel menu del pezzo di puzzle.

Un plugin gira isolato: niente rete, legge solo la cartella o il file che scegli tu, e le modifiche che propone passano dall'anteprima prima di finire nel progetto, in un solo passo che Ctrl+Z annulla.

## Impronte SHA-256

| File | SHA-256 |
|---|---|
| `premium-hmi/premium-hmi-0.4.5.ibexplugin` | `611b487780f28dc83a1646ff78a04b2171b7b23aa8edefdd6ff685a1d406be25` |

## Licenza

[MIT](LICENSE): puoi usare, copiare, modificare e ridistribuire i plugin liberamente, anche per lavoro, mantenendo l'avviso di copyright. Nessuna garanzia.

---

## English

**Install**: download the `.ibexplugin` file, then in Ibex Studio open the **puzzle piece** in the top bar → **Manage plugins…** → **Install…**. Before installing, the Studio shows the plugin's name, version, author, commands and **SHA-256 fingerprint**: compare it with the table above. The command then shows in the puzzle menu.

**Premium HMI** (0.4.5, Ibex Studio 0.7.1 or later): **New project from Premium HMI…** reads a Progea / Emerson Premium HMI (Movicon 11) project folder and makes an Ibex project of it — tags, alarms, languages, recipes, data loggers and trends, events, Basic scripts translated, screens and pictures. The preview lists what is made and what is left to do by hand.

A plugin runs isolated: no network, it reads only the folder or file you choose, and what it proposes goes through the preview before it reaches the project, as one step Ctrl+Z takes back.

**License**: [MIT](LICENSE).
