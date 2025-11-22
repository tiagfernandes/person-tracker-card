# Changelog

Tutte le modifiche notevoli a questo progetto saranno documentate in questo file.

Il formato è basato su [Keep a Changelog](https://keepachangelog.com/it/1.0.0/),
e questo progetto aderisce al [Semantic Versioning](https://semver.org/lang/it/).

## [2.1.0] - 2024-11-22

### Aggiunto
- ✨ Supporto completo per immagini PNG con trasparenza
- ✨ Supporto per GIF animate come immagini di stato
- 📱 Possibilità di posizionare elementi in 8 posizioni diverse
- 🎨 Immagini personalizzate per ogni stato
- 📐 Controllo dimensione immagine in percentuale
- 🔧 Editor visuale completo per tutte le opzioni

### Modificato
- 🎨 Migliorato rendering immagini personalizzate
- 🐛 Fix rendering immagini con sfondo trasparente
- 📱 Ottimizzato layout responsive
- 🎯 Migliorata gestione aspect ratio

### Corretto
- 🐛 Fix editor che non salvava alcune opzioni
- 🐛 Fix posizionamento elementi sovrapposti
- 🐛 Fix caricamento immagini custom in stati
- 🔧 Fix validazione valori nell'editor

## [2.0.0] - 2024-11-20

### Aggiunto
- 🎉 Prima release pubblica
- ✨ Editor visuale completo con tab organizzate
- 📱 Supporto per tutti i sensori Companion App:
  - Batteria con icona dinamica
  - Attività fisica con riconoscimento tipo
  - Tipo di connessione (WiFi/Mobile)
  - Distanza da casa
  - Tempo di viaggio
- 🎨 Stati personalizzabili:
  - Nomi custom con emoji
  - Colori personalizzabili
  - Immagini per stato (base)
- 📍 Integrazione Waze per calcolo distanze
- 🎯 Posizionamento libero elementi
- 📐 Aspect ratio configurabile
- 🎨 Stili completamente personalizzabili:
  - Background card
  - Border radius
  - Font size per ogni elemento
  - Colori elementi
- 🔄 Controllo modalità aggiornamento (all/entity/custom)
- 📱 Design responsive
- 🌙 Supporto temi scuri/chiari

### Caratteristiche Tecniche
- ⚡ Ottimizzato con `shouldUpdate()` per performance
- 🔧 Supporto configurazione YAML e UI
- 🎨 CSS modulare e manutenibile
- 📝 Codice ben documentato
- 🧪 Testato su varie configurazioni

## [1.0.0] - 2024-11-15 (Versione Interna)

### Aggiunto
- 📱 Versione base della card
- 🎨 Visualizzazione stato persona
- 📊 Sensori base (batteria, attività)
- 🖼️ Immagine persona

---

## Tipi di Modifiche

- `Aggiunto` per nuove funzionalità
- `Modificato` per cambiamenti a funzionalità esistenti
- `Deprecato` per funzionalità che verranno rimosse
- `Rimosso` per funzionalità rimosse
- `Corretto` per bug fix
- `Sicurezza` per vulnerabilità corrette

## Link Versioni

- [2.1.0]: https://github.com/yourusername/person-tracker-card/releases/tag/v2.1.0
- [2.0.0]: https://github.com/yourusername/person-tracker-card/releases/tag/v2.0.0
