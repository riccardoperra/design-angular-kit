# Contribuire a Design Angular Kit

Prenditi un momento per leggere questo documento così da rendere il processo semplice e consistente con quello utilizzato
dal resto della comunità degli sviluppatori.

## Creare una issue

L'[issue tracker](https://github.com/italia/design-angular-kit/issues) è il posto giusto dove inserire segnalazioni di bug,
richieste di nuove funzionalità e creazione di pull request, nel rispetto di queste condizioni:

- Per favore, **non** usare l'issue tracker per richieste di supporto personali.
  [Slack di Developers Italia](https://slack.developers.italia.it/) o Stack Overflow sono i posti giusti a cui fare riferimento, dove sarà anche più facile troverete risposte immediate.

- Allo stesso modo, per favore **non** provocare gli altri o "trollare" nei commenti alle issue.
  Mantenere la discussione pertinente e rispettare le opinioni di tutti. Per confronti o questioni più articolate,
  è sempre auspicabile usare [Slack di Developers Italia](https://slack.developers.italia.it/) o il [Forum di Developers Italia](https://forum.italia.it/).
  
- Rispettare le indicazioni che trovate di seguito per l'utilizzo di label, la segnalazione di bug, e la creazione di pull request.

## Lavorazione di una issue

Per prendere in carico una issue, è necessario effettuare il fork del repository sul proprio account, secondo normale flusso GitHub.

Nel caso di contributor con accesso in scrittura al repository, è consigliabile creare un branch nominato in questo modo: `feature/##-descrizione-issue`, dove `##` è il numero di issue lavorata.

Al termine della lavorazione, per proporre il proprio codice per l'approvazione, è sufficiente aprire una Pull Request ([qui](https://help.github.com/articles/creating-a-pull-request-from-a-fork/) le istruzioni nel caso di fork), assicurandosi di rispettare la checklist descritta nel [template preimpostato](https://github.com/italia/bootstrap-italia/blob/master/.github/PULL_REQUEST_TEMPLATE.md).

**design-angular-kit** usa i messaggi di commit per determinare il tipo di cambiamento nella codebase. Seguendo una convenzione per i messaggi di commit è possibile determinare automaticamente il prossimo numero di [versione semantica](https://semver.org/), generare un changelog e pubblicare la release.

La condizione necessaria per l'approvazione di una Pull Request, dunque, è usare la [Angular Commit Message Conventions](https://github.com/angular/angular.js/blob/master/DEVELOPERS.md#-git-commit-guidelines). Strumenti come [commitizen](https://github.com/commitizen/cz-cli) e [semantic-git-commit-cli](https://github.com/JPeer264/node-semantic-git-commit-cli) possono essere usati per aiutare i contributor e ottenere messaggi di commit validi.

## Issue e label

Il repository di Design Angular Kit usa alcune label per identificare le issue (criticità):

- `accessibility` - Criticità riguardanti accessibilità.
- `bug` - Segnalazione di malfunzionamenti nel codice o problemi tecnici con i tool di compilazione.
- `design` - Criticità riguardanti il design dei componenti e la loro conformità alle [linee guida di design per i servizi web delle Pubbliche Amministrazioni](https://design-italia.readthedocs.io/it/stable/index.html).
- `docs` - Criticità riguardanti la documentazione dei componenti.
- `duplicate` - Criticità o pull request duplicata.
- `enhancement` - Criticità che possono riguardare nuovi componenti o nuove funzionalità.
- `good first issue` - Criticità particolarmente semplici da prendere in carico per chi non ha conoscenza approfondita del progetto.
- `help wanted` - Criticità pronte per ricevere contributi da parte della comunità e di nuovi aspiranti sviluppatori.
- `invalid` - Criticità considerata invalida.
- `question` - Indica una criticità o pull request per la quale si ha bisogno di maggiori informazioni.
- `wontfix` - Indica che la criticità o la pull request viene chiusa senza alcun lavoro aggiuntivo.

## Licenza

Contribuendo al codice o alla documentazione accetti di rilasciare il tuo codice secondo la licenza open source già presente nel repository.
