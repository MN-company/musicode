![MusicCode Banner](banner-placeholder.png)
[![Apple Intelligence](https://img.shields.io/badge/Apple%20Intelligence-required-lightgrey.svg)]()
[![Shortcuts](https://img.shields.io/badge/Shortcut-ready-green.svg)]()


MusiCode è un progetto ispirato agli _Spotify Codes_, ma senza le loro limitazioni. Consente di usare qualsiasi immagine, simbolo, logo o oggetto come codice visivo per aprire un link. Scegli un tuo visual, caricalo nella repo e MusicCode farà il resto.

## Come funziona

MusiCode utilizza il riconoscimento multimodale di Apple Intelligence.

1. Lo shortcut scarica dalla vostra repo GitHub l’immagine di riferimento chiamata img.jpeg.
2. Quando lo avviate, apre la fotocamera e vi chiede di inquadrare il vostro codice visivo.
3. Lo shortcut invia l’immagine di riferimento e la foto scattata al modello cloud di Apple Intelligence.
4. Se il modello riconosce la corrispondenza, apre l’URL contenuto in url.txt.
5. Se non la riconosce, mostra una notifica di errore.

## [Device supportati](https://www.apple.com/it/apple-intelligence/)

| Dispositivo | Supporto |
|-------------|----------|
| iPhone 15 Pro | ✔️ |
| iPhone 15 Pro Max | ✔️ |
| iPhone 16 | ✔️ |
| iPhone 16e | ✔️ |
| iPhone 16 Plus | ✔️ |
| iPhone 16 Pro | ✔️ |
| iPhone 16 Pro Max  | ✔️ |
| iPhone 17 | ✔️ |
| iPhone Air | ✔️ |
| iPhone 17 Pro | ✔️ |
| iPhone 17 Pro Max | ✔️ |
| iPad Air M1+ | ✔️ |
| iPad Pro M1+ | ✔️ |
| iPad Mini | ✔️ |


## Posso cambiare modello

Sì.

- Modello locale Apple: funziona, ma con accuratezza inferiore.
- ChatGPT Vision: funziona, ma presenta più latenza e richiede un abbonamento compatibile.
- Modello cloud Apple (consigliato): migliore combinazione di velocità e precisione.

# Come si usa

1. Fate il fork di questa repo.
2. Sostituite il file img.jpeg con l’immagine che volete usare come codice visivo. Non cambiate il nome del file. Ottenete il link RAW del nuovo file.
3. Modificate url.txt inserendo il link che desiderate aprire. Ottenete anche il RAW di questo file.
4. Importate lo shortcut su iPhone o iPad.
5. Avviatelo e, alla prima esecuzione, inserite gli URL RAW richiesti.
6. Il sistema è pronto. Potete stampare o mostrare il vostro codice visivo dove desiderate.

## A cosa serve

- Aprire playlist o contenuti musicali
- Creare biglietti da visita digitali
- Collegare oggetti fisici a link online
- Esperienze interattive, giochi, treasure hunt
- Branding, merchandising e installazioni creative

## Licenza
Non è possibile copiare questo progetto e dichiarare di averlo creato senza averlo modificato in modo sostanziale.  
In ogni caso sono richiesti i crediti al autore originale.
