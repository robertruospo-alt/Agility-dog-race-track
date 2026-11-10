# Percorsi Agility

App web per disegnare, numerare e salvare percorsi di **agility dog**, pensata per iPhone e iPad. Funziona anche offline al campo.

**Apri l'app:** https://robertruospo-alt.github.io/Agility-dog-race-track/

## Installazione

1. Apri il link in **Safari** (su Android in Chrome).
2. Tocca **Condividi → Aggiungi alla schermata Home**.
3. L'app compare con la sua icona e si apre a schermo intero.

Non serve nessun account.

## Cosa si può fare

- **Ostacoli:** salto, salto doppio, muro, ruota, salto in lungo, tunnel (lunghezza e curvatura regolabili), slalom (6–12 paletti), passerella, palizzata, altalena, partenza e arrivo. Si trascinano sul campo e si ruotano. Con due dita si fa zoom.
- **Numerazione:** si toccano gli ostacoli nell'ordine del percorso e i numeri compaiono sul campo, con la linea del cane e le distanze. Lo stesso ostacolo si può ripetere, e per tunnel, zone e slalom si può invertire il verso.
- **Note di conduzione** per ogni numero: In, Out, Wrap, Spin, Backside, Threadle, Serpentina, Front/Rear/Blind cross, Ketschker, lato SX/DX e una nota libera.
- **Dati e tempi:** dimensioni del campo, tipo, grado e categoria. L'app calcola lunghezza, TPS e TPM; si può inserire anche la lunghezza ufficiale del giudice.
- **I miei cani:** inserendo la velocità media di ogni cane si vede il tempo stimato e se resta entro il TPS.
- **Condivisione:** il percorso si può mandare come immagine PNG (WhatsApp, Foto) o come file da reimportare.

## I miei percorsi e la Libreria

- **I miei** sono salvati solo sul proprio telefono. Ogni tanto conviene fare **⬇︎ Backup completo**, per esempio su iCloud Drive, e usare **⬆︎ Ripristina backup** per passarli su un altro dispositivo.
- **Libreria** contiene percorsi di gara ricostruiti dalle mappe pubblicate dai giudici, ed è uguale per tutti. Con **Apri e copia nei miei** se ne crea una copia personale da modificare.

### Percorsi in Libreria

| Percorso | Tipo | Giudice | Lunghezza |
|---|---|---|---|
| ProsecCup 2026 – Agility 2 (S/M/I/L) | Agility | Gabriel Arriagada Osses | ≈178 m (misurata) |
| ProsecCup 2026 – Jumping 3 Large | Jumping | Gabriel Arriagada Osses | ≈189 m (misurata) |
| HAM 26 – Jumping 3 Inter/Large | Jumping | – | ≈220 m (misurata) |
| European Open 2026 – Jumping Individuale Large | Jumping | Cédric Bargoin | 197,3 m |
| European Open 2026 – Jumping Individuale Intermediate | Jumping | Gabriel Arriagada Osses | 201,4 m |
| Prague Agility Party – Agility Individuale Medium | Agility | Max Glover | 244,1 m |
| Breizh Cup – Agility G3 Inter/Large | Agility | – | 228,3 m |
| IconiX Summer Fiesta 2025 – Agility G6-7 | Agility | Stefanie Semkat | 225,3 m |
| 4S Agility – Campo completo (50 numeri) | Allenamento | – | 563,9 m |

Le ricostruzioni hanno una precisione di circa mezzo metro. Dove la mappa non aveva la griglia, le dimensioni del campo sono stimate. Le mappe originali restano opera dei rispettivi giudici e servono qui solo come riferimento per l'allenamento.

## File del progetto

| File | A cosa serve |
|---|---|
| `index.html` | l'app intera |
| `library.json` | i percorsi della Libreria |
| `manifest.webmanifest`, `sw.js`, `icon-*.png`, `apple-touch-icon.png` | installazione sulla Home e funzionamento offline |

Per aggiungere percorsi alla Libreria si aggiornano le voci in `library.json`. Chi apre l'app li riceve al successivo avvio con la rete attiva.
