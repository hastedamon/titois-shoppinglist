🛒 Shopping List / Llista de la Compra

A shared shopping list web app that syncs between two people via Google Drive.

Una aplicació web de llista de la compra compartida que es sincronitza entre dues persones a través de Google Drive.

English
What is this?

A simple, mobile-friendly shopping list that two people can share. One person adds "milk", the other sees it on their phone instantly. Items are organized by category (produce, dairy, bakery, etc.) and can be checked off as you shop.

All data is stored as a JSON file in Google Drive — no external servers, no accounts to create, no subscriptions.

Features
Shared in real time — changes sync every 5 seconds via Google Drive
Organized by category — produce, dairy, meat, bakery, frozen, drinks, snacks, household
Check off items — tap to mark as "got it", with a collapsible done section
Edit inline — tap any item to rename it
Works on Android & iOS — add to home screen for an app-like experience
Privacy-first — your data lives in your own Google Drive, nowhere else
Setup
Create a free Google Cloud project and OAuth Client ID (setup guide)
Open index.html and replace YOUR_CLIENT_ID.apps.googleusercontent.com with your actual Client ID
Host on GitHub Pages (or any static hosting)
Share the link with your partner

The first person to sign in creates the list. Tap 👥 in the header to share it with the other person by email.

Tech stack

Single HTML file. No build step, no dependencies, no framework. Uses Google Identity Services for authentication and the Google Drive API for storage.

Català
Què és això?

Una llista de la compra senzilla, pensada per al mòbil, que dues persones poden compartir. Una persona hi afegeix "llet" i l'altra ho veu al seu telèfon al moment. Els articles s'organitzen per categoria (fruita i verdura, lactis, forn, etc.) i es poden marcar com a comprats mentre fas la compra.

Totes les dades es guarden com a fitxer JSON al Google Drive — sense servidors externs, sense comptes addicionals, sense subscripcions.

Funcionalitats
Compartida en temps real — els canvis se sincronitzen cada 5 segons via Google Drive
Organitzada per categories — fruita i verdura, lactis, carn, forn, congelats, begudes, snacks, llar
Marca els articles — toca per marcar com a "comprat", amb una secció plegable d'articles fets
Edició directa — toca qualsevol article per canviar-ne el nom
Funciona a Android i iOS — afegeix-la a la pantalla d'inici per una experiència d'aplicació
Privacitat — les teves dades viuen al teu propi Google Drive, enlloc més
Configuració
Crea un projecte gratuït a Google Cloud amb un OAuth Client ID (guia de configuració)
Obre index.html i substitueix YOUR_CLIENT_ID.apps.googleusercontent.com pel teu Client ID real
Publica-ho a GitHub Pages (o qualsevol hosting estàtic)
Comparteix l'enllaç amb la teva parella

La primera persona que hi entri crea la llista. Toca 👥 a la capçalera per compartir-la amb l'altra persona per correu electrònic.

Stack tècnic

Un sol fitxer HTML. Sense compilació, sense dependències, sense framework. Utilitza Google Identity Services per a l'autenticació i l'API de Google Drive per a l'emmagatzematge.

License / Llicència

MIT
