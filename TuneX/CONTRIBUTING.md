# Contribuire a TuneX 🎵

Grazie per l'interesse in TuneX! Sei il benvenuto nel contribuire al progetto.

## Come Iniziare

1. **Fork il repository** sul tuo account GitHub
2. **Clone** il fork: `git clone https://github.com/TUO_USERNAME/TuneX.git`
3. **Crea un nuovo branch**: `git checkout -b feature/mia-feature`
4. **Fai le tue modifiche**
5. **Commit**: `git commit -m 'Aggiungi mia feature'`
6. **Push**: `git push origin feature/mia-feature`
7. **Apri una Pull Request** su GitHub

## Linee Guida

### Per i Bug Report 🐛
- Descrivi il problema chiaramente
- Fornisci i passaggi per riprodurlo
- Specifica il browser e la versione
- Allega screenshot se utili

### Per i Feature Request ✨
- Descrivi la feature desiderata
- Spiega il caso d'uso
- Proponi come dovrebbe funzionare

### Per il Codice 💻
- Usa nomi di variabili chiari
- Commenta il codice complesso
- Mantieni il codice coerente con lo stile esistente
- Test il codice su browser diversi

## Aree di Contribuzione

- 🎨 **Design**: Migliora l'interfaccia
- 🐛 **Bug Fix**: Correggi problemi
- 🚀 **Features**: Aggiungi nuove funzionalità
- 📚 **Documentazione**: Migliora i README
- 🌐 **Localizzazione**: Traduzioni in altre lingue
- ⚡ **Performance**: Ottimizzazioni

## Struttura del Progetto

```
TuneX/
├── index.html          # File principale
├── README.md           # Documentazione
├── CONTRIBUTING.md     # Questa file
├── LICENSE             # Licenza MIT
└── .gitignore          # File da ignorare
```

## Stileguida

### JavaScript
```javascript
// Usa var/let/const chiaramente
var myVariable = value;

// Commenta il codice complesso
function importantFunction() {
  // Descrivi cosa fa
}

// Usa nomi descrittivi
var channelName = 'Name';  // ✅ BENE
var c = 'Name';            // ❌ MALE
```

### CSS
```css
/* Usa variabili CSS */
color: var(--text);

/* Organizza i selettori logicamente */
.element {
  /* Layout */
  display: flex;
  
  /* Box Model */
  padding: 10px;
  
  /* Colori */
  color: var(--text);
  
  /* Transizioni */
  transition: all 0.2s;
}
```

## Testing

Prima di fare un PR, testa il codice su:
- Chrome/Chromium
- Firefox
- Safari
- Edge

Su dispositivi:
- Desktop
- Tablet
- Mobile

## Licenza

Contribuendo a TuneX, accetti che il tuo codice sia distribuito sotto licenza MIT.

---

Grazie ancora per il tuo supporto! 🙏
