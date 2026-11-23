# pizzeriaWeb
Menu web della pizzeria, realizzato in gruppo con Git e GitHub seguendo il GitHub Flow.

## Gruppo di lavoro

| Ruolo | Utente | Compito | Branch |
|---|---|---|---|
| Project Manager | @thomas-addamo | creazione repository, template, review e merge | main |
| Sviluppatore A | @DanyMazze | menu pizze | menuPizza |
| Sviluppatore B | @Alice-Orlando | menu dolci | menuDolci |
| Sviluppatore C | @maggybersaglio | menu bevande | menuBibite |

Ogni sviluppatore doveva aggiungere due portate nel proprio menu.

## Regole del GitHub Flow
1. il branch main contiene solo la versione pubblicabile, nessuno lavora direttamente su main
2. ognuno lavora su un branch con un nome descrittivo
3. si fa push sul proprio branch appena si ha qualcosa di pronto
4. quando il lavoro è finito si apre una pull request, la revisione e il merge li fa il PM

## Struttura del progetto
```
pizzeriaWeb/
├── index.html      pagina del menu
├── css/style.css   stile della pagina
└── img/            immagini delle portate
```

## Menu
- **Pizze:** Margherita, Diavola
- **Dolci:** Tiramisù, Panna cotta
- **Bevande:** Caffè Espresso (esempio del template), Acqua minerale, Birra artigianale

## Svolgimento
1. il PM ha creato il repository, scritto il README e caricato il template
2. il PM ha invitato i tre sviluppatori come collaboratori
3. ogni sviluppatore ha lavorato sul proprio branch e ha aperto una pull request
4. nella PR #1 il PM ha chiesto di sostituire l'immagine della margherita, lo sviluppatore A l'ha corretta e la PR è stata approvata
5. le PR #3 (dolci) e #2 (bevande) erano in conflitto con il main: il PM ha risolto i conflitti su index.html e ha fatto il merge

## Come vedere il sito
Scaricare il repository e aprire `index.html` nel browser.
