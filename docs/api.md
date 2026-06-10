# API Documentation

Il sito utilizza la [PokeAPI](https://pokeapi.co/) per il recupero dinamico dei dati.

## Endpoint utilizzati
L'applicazione effettua chiamate asincrone a:
`https://pokeapi.co/api/v2/pokemon/{nome_pokemon}`

## Gestione Dati
- **Metodo:** `GET`
- **Formato Risposta:** JSON
- **Campi estratti:**
  - `name`: Nome del Pokémon.
  - `sprites.front_default`: URL dell'immagine sprite.
  - `types`: Array contenente i tipi del Pokémon.
  - `height`: Altezza (in decimetri).
  - `weight`: Peso (in ettogrammi).

## Fallback
In caso di errore di rete o API non raggiungibile, lo script tenta di caricare i dati da un file locale `data.json` presente nel progetto.