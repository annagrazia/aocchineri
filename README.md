# Portfolio Professionale

Sito vetrina statico per **Ingegnere del Software**, **Technical Leader** e **Referente Area Innovazione**.

## Anteprima locale

Apri `index.html` nel browser oppure avvia un server locale:

```bash
# Python
python -m http.server 8080

# Node.js (npx)
npx serve .
```

Poi visita `http://localhost:8080`.

## Pubblicazione su GitHub Pages

1. Crea un nuovo repository su GitHub (es. `portfolio` o `username.github.io`)
2. Carica tutti i file del progetto
3. Vai su **Settings → Pages**
4. In **Source**, seleziona branch `main` e cartella `/ (root)`
5. Salva — il sito sarà disponibile su `https://username.github.io/repository-name/`

> Se il repository si chiama `username.github.io`, il sito sarà raggiungibile direttamente su `https://username.github.io`

## Personalizzazione

Modifica questi elementi in `index.html`:

| Elemento | Dove |
|----------|------|
| Email | Sezione Contatti — `email@example.com` |
| LinkedIn | Sezione Contatti — link profilo |
| GitHub | Sezione Contatti — link profilo |
| Nome (footer) | Footer — aggiungi il tuo nome |

## Struttura

```
├── index.html      # Pagina principale
├── css/
│   └── style.css   # Stili e animazioni
├── js/
│   └── main.js     # Interattività
└── README.md
```

## Tecnologie

- HTML5 semantico
- CSS3 (variabili, grid, flexbox, animazioni)
- JavaScript vanilla (Intersection Observer, scroll reveal)
- Nessuna dipendenza esterna (tranne Google Fonts)
