# Pokedx

Pokedx è una semplice applicazione web che permette di consultare informazioni sui Pokémon utilizzando i dati forniti dalla PokeAPI. L'obiettivo del progetto è offrire un'interfaccia intuitiva per visualizzare Pokémon, le caratteristiche principali e consultare informazioni sui diversi tipi e debolezze tramite tabella.

## OBIETTIVO

L'applicazione consente di:

* Vedere Alcuni pokemon e una lista di tipi e debolezze.
* Visualizzare informazioni dettagliate tra cui altezza peso etc.
* Consultare i tipi Pokémon e le loro caratteristiche.
* Imparare a utilizzare API REST tramite un progetto pratico.
* Gestire e visualizzare dati JSON in una pagina web.

## REQUISITI

Per eseguire il progetto è necessario:

* Un browser moderno (Chrome, Firefox, Edge, Safari).
* Connessione Internet per accedere alla PokeAPI.
* Un server locale opzionale.

## INSTALLAZIONE

La guida di installazione è sono presente nel file [INSTALLAZIONE](docs/installazione.md).

## FUNZIONALITÀ

### Home

* Pagina introduttiva al sito
* Collegamento alle altre pagine

### Scheda Pokémon

* Nome.
* Immagine ufficiale.
* Altezza e peso.
* Tipi.

### Tabella tipi e debolezze

* Elenco dei tipi di pokemon
* Informazioni sui moltiplicatori del danno

## TECNOLOGIE UTILIZZATE

* HTML5
* CSS3
* JavaScript (Vanilla JS)
* JSON
* PokeAPI

## API UTILIZZATA

L'applicazione utilizza la PokeAPI per recuperare le informazioni sui Pokémon.

Endpoint principale:

```text
https://pokeapi.co/api/v2/pokemon/{id o nome}
```

Documentazione ufficiale:

https://pokeapi.co/

## Struttura del progetto

La cartella **Pokedx** contiene tutti i file del progetto.

```text
Pokedx/
├── README.md
├── index.html
├── pokemon.html
├── tipi.html
├── style.css
├── script.js
├── data.json
├── docs/
│   ├── installazione.md
│   ├── faq.md
│   └── api.md
├── assets/
│   ├── immagini/
│   │   ├── banner.png
│   │   └── logo.png
│   └── screenshots/
│       ├── page1.png
│       ├── page2.png
│       └── page3.png

```

## POSSIBILI MIGLIORAMENTI

* Sistema di preferiti.
* Filtri avanzati per tipo.
* Toggle shiny
* Pulsante per i cries dei pokemon
* Confronto tra Pokémon.
* Modalità scura.
* Paginazione dei risultati.
* Barra di ricerca

## FAQ

Le FAQ sono presenti nel file [FAQ](docs/faq.md).

### Da dove provengono i dati?

I dati vengono recuperati tramite la PokeAPI.

### È necessario installare dipendenze?

No, il progetto utilizza esclusivamente HTML, CSS e JavaScript.

## Reference

* PokeAPI: https://pokeapi.co/

## Autore

**Alessandro Signoroni**

## Contatti

Email: [alino0203@gmail.com](mailto:alino0203@gmail.com)

## Licenza

Questo progetto è distribuito sotto licenza MIT. Per maggiori dettagli consulta il file [LICENSE](LICENSE).

La scelta della licenza MIT è dovuta alla sua semplicità e flessibilità: permette a chiunque di utilizzare, modificare e ridistribuire il codice liberamente, anche in progetti personali o commerciali, a patto di mantenere il copyright originale.

È una licenza molto adatta a progetti didattici o open source come questo, perché favorisce la condivisione e l’apprendimento senza vincoli complessi.
