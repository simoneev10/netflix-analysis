# netflix-analysis
🎬  Analisi esplorativa dei film anni '90 su Netflix. Scopri durata, generi e trend per produzioni nostalgiche. 

![Netflix logo](https://upload.wikimedia.org/wikipedia/commons/7/77/Netflix_2015_logo.svg)

## Descrizione del Progetto
Questo progetto analizza i film degli anni '90 presenti su Netflix, con particolare focus sulle caratteristiche che potrebbero interessare una casa di produzione specializzata in contenuti nostalgici. L'analisi esplorativa dei dati (EDA) investiga durata, generi e tendenze cinematografiche del decennio.

## Obiettivi
- Identificare la durata tipica dei film anni '90
- Trovare film d'azione "corti" (≤90 minuti)
- Scoprire pattern e tendenze nei dati
- Fornire insights utili per produzioni cinematografiche nostalgiche

## Dataset
Il dataset `netflix_data.csv` contiene:
- 6,683 record (film e serie TV)
- 12 colonne tra cui genere, anno di uscita, durata, paese, ecc.
- Dati aggiornati al 2021

## Metodologia
Tecniche utilizzate:
- Filtraggio dati con pandas
- Analisi statistica di base
- Calcolo delle frequenze
- Visualizzazione dati con matplotlib

## Risultati Chiave 🔑
1. **Durata tipica**: 94 minuti è la durata più frequente
2. **Film d'azione corti**: Identificati 7 titoli tra cui:
   - *Rumble in the Bronx*
   - *Passenger 57*
   - *The Bare-Footed Kid*
3. **Generi principali**: Drammi, Commedie e Film Horror dominano il decennio

## Come Usare il Codice
1. Clona il repository
2. Installa le dipendenze:
   ```bash
   pip install pandas matplotlib
