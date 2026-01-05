# BOBO BINGO 2026

Un'applicazione web personale per tracciare i miei obiettivi per il 2026 sotto forma di una scheda bingo 5x5.

## Descrizione

Questa è una scheda bingo interattiva con 25 obiettivi personali che voglio raggiungere nel 2026. Ogni cella rappresenta un obiettivo, e puoi marcarla cliccando quando completata. Include una X rossa per indicare il completamento.

Gli obiettivi sono:
1. Giocare 50 partite
2. Comprare 20 manga
3. Scrivere una canzone
4. 1000 foto
5. Viaggio
6. Arrivare a 100 giochi in scatola
7. Leggere tutti i manga in libreria
8. 30 giorni di studio consecutivo di Sax (filmati)
9. Scrivere e registrare un corto
10. Visitare [luogo]
11. Guardare Star Wars (tutti)
12. Creare uno spartito
13. FREE
14. Progetto DALIA
15. Partecipare a una fiera
16. Guadagnare 12 Platini
17. Creare un fumetto
18. Blender – modellare personaggi
19. Stampante 3D
20. Progetto di robotica
21. Giocare tutta la serie di giochi Pokémon ufficiali
22. Scrivere l'accademia per un'avventura D&D
23. Inventare e creare un gioco da tavolo / videogioco
24. Magistrale e Doc
25. M

## Come Usare

1. Apri `index.html` in un browser web.
2. Clicca sulle celle per marcarle come completate (appare una X rossa).
3. Usa **Save** per scaricare il file `progresso.json` con il tuo progresso.
4. Sposta `progresso.json` nella stessa cartella di `index.html` per caricamento automatico al refresh.
5. Usa **Load** per caricare un file `progresso.json` esistente.

Il progresso viene anche salvato localmente nel browser (`localStorage`), quindi rimane tra sessioni.

## Funzionalità

- Griglia 5x5 cliccabile
- Salvataggio/caricamento progresso via JSON
- Design responsive con sfondo personalizzabile (`sfondo.jpg`)
- Caricamento automatico da `progresso.json` se presente


## Tecnologie

- HTML5
- CSS3
- JavaScript (vanilla)

## Note

- Per browser locali, il caricamento automatico da `progresso.json` richiede un server (es. `python -m http.server`).
- Il progresso è salvato in `localStorage` per persistenza locale.