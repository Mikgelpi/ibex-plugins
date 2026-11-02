# Ibex plugins

Plugin pronti da installare per **Ibex Studio**. Ogni plugin è un file `.ibexplugin`, nella cartella con il suo nome.

*Ready-to-install plugins for **Ibex Studio**: one `.ibexplugin` file each, in the folder named after it. English below.*

## Plugin

| Plugin | Versione | Cosa fa | Ibex Studio |
|---|---|---|---|
| [Premium HMI](premium-hmi/) | 0.4.5 | **Nuovo progetto da Premium HMI…**: legge un progetto Progea / Emerson Premium HMI (Movicon 11) e ne fa un progetto Ibex: tag, allarmi, lingue, ricette, data logger e grafici, eventi, script Basic tradotti, schermate e immagini. | 0.7.1 o successivo |
| [IO-Link](iolink-iodd/) | 0.1.2 | **Pannello da IODD (IO-Link)…**: legge l'IODD di un dispositivo IO-Link (dall'IODDfinder o dal costruttore) e crea un template che decodifica i suoi dati di processo dal dato grezzo del PLC: valori con scala e unità, spie, valori speciali in parole, pulsanti per i dati in uscita e immagine del dispositivo. I valori decodificati sono anche proprietà del template, leggibili dal resto della pagina. | 0.7.1 o successivo |
| [SunSpec](sunspec/) | 0.1.1 | **Dispositivo SunSpec (Modbus)…**: aggiunge un inverter, contatore o batteria SunSpec (Fronius, SMA, SolarEdge…) dalla catena dei suoi modelli: il PLC Modbus, i tag di ogni modello con indirizzi, tipi e unità, e una pagina con i valori già scalati dai loro fattori di scala, gli stati e gli eventi in parole, «--» dove il dispositivo non dà il valore. Dentro ci sono i 112 modelli ufficiali SunSpec. | 0.7.1 o successivo |

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
| `iolink-iodd/iolink-iodd-0.1.2.ibexplugin` | `b2e232c39cd6611de69fa188f672cf59b75a56f9002d8271d619c0916ea03dc1` |
| `sunspec/sunspec-0.1.1.ibexplugin` | `c774fd898c9a7c6958f5b8c91ea6090b88da0467afff2b3a07a7d72a06a427ae` |

## Licenza

[MIT](LICENSE): puoi usare, copiare, modificare e ridistribuire i plugin liberamente, anche per lavoro, mantenendo l'avviso di copyright. Nessuna garanzia.

Il plugin SunSpec contiene i modelli SunSpec di [github.com/sunspec/models](https://github.com/sunspec/models) (© SunSpec Alliance), con la loro licenza [Apache-2.0](sunspec/LICENSE-sunspec-models.txt).

---

## English

**Install**: download the `.ibexplugin` file, then in Ibex Studio open the **puzzle piece** in the top bar → **Manage plugins…** → **Install…**. Before installing, the Studio shows the plugin's name, version, author, commands and **SHA-256 fingerprint**: compare it with the table above. The command then shows in the puzzle menu.

**Premium HMI** (0.4.5, Ibex Studio 0.7.1 or later): **New project from Premium HMI…** reads a Progea / Emerson Premium HMI (Movicon 11) project folder and makes an Ibex project of it — tags, alarms, languages, recipes, data loggers and trends, events, Basic scripts translated, screens and pictures. The preview lists what is made and what is left to do by hand.

**IO-Link** (0.1.2, Ibex Studio 0.7.1 or later): **Panel from an IODD (IO-Link)…** reads the IODD of an IO-Link device (from the IODDfinder or its manufacturer) and makes a template that decodes its process data from the PLC's raw data — values with scale and unit, lamps, special values in words, buttons for the process data out, and the device's picture. The decoded values are properties of the template too, readable by the rest of the page.

**SunSpec** (0.1.1, Ibex Studio 0.7.1 or later): **SunSpec device (Modbus)…** adds a SunSpec inverter, meter or battery (Fronius, SMA, SolarEdge…) from the chain of its models — the Modbus PLC, the tags of every model with addresses, types and units, and a page with the values already scaled by their scale factors, the states and the events in words, «--» where the device gives no value. The 112 official SunSpec models are inside.

A plugin runs isolated: no network, it reads only the folder or file you choose, and what it proposes goes through the preview before it reaches the project, as one step Ctrl+Z takes back.

**License**: [MIT](LICENSE). The SunSpec plugin holds the SunSpec models of [github.com/sunspec/models](https://github.com/sunspec/models) (© SunSpec Alliance), under their [Apache-2.0](sunspec/LICENSE-sunspec-models.txt) license.
