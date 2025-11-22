# Contribuire a Person Tracker Card

Grazie per l'interesse nel contribuire! Ogni contributo è benvenuto.

## 🎯 Come Contribuire

### Segnalare Bug

Se trovi un bug, apri una [Issue](https://github.com/yourusername/person-tracker-card/issues) includendo:

- **Descrizione chiara** del problema
- **Passi per riprodurlo**
- **Comportamento atteso** vs comportamento effettivo
- **Screenshot** (se applicabile)
- **Versione** di Home Assistant e della card
- **Configurazione** (YAML anonimizzato)
- **Log della console** (F12 in browser)

### Suggerire Funzionalità

Per nuove funzionalità, apri una Issue con:

- **Descrizione dettagliata** della funzionalità
- **Casi d'uso** concreti
- **Mock-up o sketch** (opzionale ma apprezzato)
- **Benefici** per gli utenti

### Contribuire Codice

1. **Fork** il repository
2. **Crea un branch** per la tua feature:
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Sviluppa** la tua funzionalità
4. **Testa** accuratamente
5. **Committa** con messaggi chiari:
   ```bash
   git commit -m '✨ Add: Nuova funzionalità amazing'
   ```
6. **Push** al tuo fork:
   ```bash
   git push origin feature/AmazingFeature
   ```
7. **Apri una Pull Request**

## 📝 Linee Guida Codice

### Stile JavaScript

- Usa **ES6+** quando possibile
- **Indentazione** con 2 spazi
- **Nomi variabili** descrittivi in camelCase
- **Commenti** per logica complessa
- **JSDoc** per funzioni pubbliche

Esempio:
```javascript
/**
 * Calcola la distanza tra due punti
 * @param {number} lat1 - Latitudine punto 1
 * @param {number} lon1 - Longitudine punto 1
 * @param {number} lat2 - Latitudine punto 2
 * @param {number} lon2 - Longitudine punto 2
 * @returns {number} Distanza in km
 */
_calculateDistance(lat1, lon1, lat2, lon2) {
  // Implementazione...
}
```

### Convenzioni Commit

Usa [Conventional Commits](https://www.conventionalcommits.org/):

- `✨ feat:` Nuova funzionalità
- `🐛 fix:` Correzione bug
- `📝 docs:` Documentazione
- `🎨 style:` Formattazione, punto e virgola mancanti, etc
- `♻️ refactor:` Refactoring codice
- `⚡ perf:` Miglioramento performance
- `✅ test:` Aggiunta test
- `🔧 chore:` Manutenzione, dipendenze

Esempi:
```
✨ feat: Aggiungi supporto per immagini GIF animate
🐛 fix: Correggi posizionamento elementi sovrapposti
📝 docs: Aggiorna README con nuovi esempi
♻️ refactor: Semplifica logica rendering stati
```

### CSS

- Usa **CSS custom properties** per temi
- **Mobile-first** approach
- **BEM-like** naming quando appropriato
- Mantieni **specificità bassa**

### Testing

Prima di inviare una PR:

1. Testa su **Home Assistant recente**
2. Verifica su **diversi browser** (Chrome, Firefox, Safari)
3. Testa su **dispositivi mobile**
4. Controlla **console per errori**
5. Verifica **temi chiari e scuri**

## 🏗️ Struttura Progetto

```
person-tracker-card/
├── dist/                          # File distribuiti
│   ├── person-tracker-card.js     # Card principale
│   └── person-tracker-card-editor.js  # Editor
├── images/                        # Screenshot e demo
│   ├── preview.png
│   ├── editor-*.png
│   └── state-*.png
├── .gitignore
├── CHANGELOG.md                   # Storico modifiche
├── CONTRIBUTING.md                # Questa guida
├── hacs.json                      # Config HACS
├── info.md                        # Info breve HACS
├── LICENSE
└── README.md                      # Documentazione
```

## 🔍 Processo Review

Le Pull Request verranno revisionate per:

1. **Funzionalità** - Fa quello che promette?
2. **Qualità codice** - È leggibile e manutenibile?
3. **Performance** - Introduce lag o problemi?
4. **Compatibilità** - Funziona su diverse versioni HA?
5. **Documentazione** - README e commenti aggiornati?
6. **Breaking changes** - Richiede aggiornamento versione major?

## 📋 Checklist Pull Request

Quando apri una PR, assicurati di:

- [ ] Testato su Home Assistant recente
- [ ] Nessun errore in console
- [ ] Funziona con editor visuale
- [ ] Funziona con configurazione YAML
- [ ] Documentazione aggiornata
- [ ] CHANGELOG.md aggiornato
- [ ] Screenshot per modifiche UI
- [ ] Commit messages seguono convenzioni
- [ ] Nessun file non necessario incluso

## 🎨 Risorse Design

Per contributi UI/UX:

- Usa i **colori del tema** Home Assistant
- Segui le **linee guida Material Design**
- Mantieni **consistenza** con altre card
- Prioritizza **accessibilità**

## 🐛 Debug

Per debuggare la card:

1. Apri DevTools (F12)
2. Vai su Console
3. Cerca messaggi della card:
   ```javascript
   console.log('%c PERSON-TRACKER-CARD', ...)
   ```
4. Usa `console.log()` liberamente durante sviluppo
5. Rimuovi log prima del commit finale

## 📞 Comunicazione

- **Issue** per bug e feature request
- **Discussions** per domande generali
- **PR** per contributi codice
- Sii **rispettoso** e **costruttivo**

## 🙏 Riconoscimenti

Tutti i contributori verranno menzionati nel README!

## ❓ Domande?

Se hai domande, apri una Discussion o contatta i maintainer.

Grazie per contribuire! 🎉
