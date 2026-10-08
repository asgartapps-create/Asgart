# Asgar Tech — sito completo

Sito statico in inglese, pronto per GitHub Pages o per il caricamento su un hosting web. Non richiede installazioni né compilazione.

## Contenuto

- `index.html`: landing page.
- `style.css`: stili condivisi.
- `privacy/index.html`: Privacy Policy del sito.
- `privacy1/index.html`: Privacy Policy Remit in inglese.
- `assets/`: logo, immagini, font locali e licenze dei font.
- `.nojekyll`: pubblicazione statica senza Jekyll.
- `CNAME`: dominio previsto, `www.asgart.it`.

## Caricamento su GitHub

1. Estrai lo ZIP.
2. Carica **il contenuto della cartella Asgar-Tech-Website** nella radice del repository: `index.html` deve essere direttamente nella radice, non in una sottocartella.
3. In **Settings → Pages**, scegli **Deploy from a branch**, il branch **main** e la cartella **/ (root)**.
4. Per il dominio definitivo, imposta **www.asgart.it** come Custom domain e configura i DNS secondo le indicazioni di GitHub. Il file CNAME non cambia da solo i DNS.
5. Abilita **Enforce HTTPS** quando disponibile.

Se desideri prima usare soltanto l’indirizzo github.io, elimina il file CNAME. I collegamenti relativi funzionano anche sotto il percorso del repository.

## URL

Pubblicando sul dominio indicato:

- Landing: https://www.asgart.it/
- Privacy sito: https://www.asgart.it/privacy
- Privacy Remit: https://www.asgart.it/privacy1

Le privacy sono salvate come cartelle con index.html. Un hosting statico può normalizzare `/privacy1` in `/privacy1/`: la pagina resta accessibile dal collegamento originale `/privacy1`.

## Se utilizzi Aruba come hosting

Carica gli stessi file e cartelle nella radice pubblica del dominio. GitHub può essere usato per conservare il codice; la sola presenza del repository non aggiorna il sito su Aruba. Il file CNAME è dedicato a GitHub Pages.

## Verifica dell’informativa

La privacy del sito conserva l’indicazione di bozza da verificare. Aruba è il provider indicato dal titolare: se scegli GitHub Pages come hosting effettivo, aggiorna questa indicazione e verifica le relative condizioni di trattamento, cookie tecnici e conservazione dei log. La privacy Remit è la traduzione del testo originale, con la data 25 marzo 2026 conservata.

## Font

DM Sans e Manrope sono inclusi localmente con le rispettive licenze SIL Open Font License. La pagina non carica Google Fonts da server esterni.

## Riferimenti ufficiali

https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site
