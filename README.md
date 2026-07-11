# Kinemetric

App al servizio di professionisti sanitari.

## Pagine

- **Home** - Presentazione di Kinemetric e della missione
- **Privacy** - Privacy Policy per l'applicazione mobile Android

## Deployment

Il sito è deployato su Cloudflare Pages con il dominio [kinemetric.eu](https://kinemetric.eu)

## Struttura

```
├── index.html      # Pagina Home
├── privacy.html    # Privacy Policy
├── style.css       # Stili CSS
└── README.md       # Questo file
```

## Come eseguire localmente

Apri `index.html` nel browser o utilizza un server locale:

```bash
# Con Python 3
python -m http.server 8000

# Con Node.js (http-server)
npx http-server
```

Poi vai a `http://localhost:8000`
