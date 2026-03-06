# TuneX 🎵 - Unified Media Player

Un moderno media player web con interfaccia elegante, equalizzatore a 15 bande, supporto HLS e YouTube, ricerca vocale e molto altro!

## ✨ Caratteristiche Principali

- 🎬 **Supporto Multi-Format**: Video, Audio, Stream HLS, YouTube
- 🎚️ **Equalizzatore Professionale**: 15 bande regolabili + 12 preset (Bass, Treble, Rock, Pop, Jazz, etc.)
- 🎙️ **Ricerca Vocale**: Comandi vocali in italiano con Web Speech API
- 🌈 **Design Moderno**: Tema scuro con gradient neon (pink/cyan), interfaccia responsive
- 🎵 **Gestione Canali**: Sidebar con lista canali, filtro ricerca in tempo reale
- 📱 **Visualizzatore Audio**: Animazione dinamica con bande che reagiscono al suono
- ⚡ **Perfomante**: JavaScript vanilla, nessuna dipendenza esterna (tranne HLS.js per i stream)

## 🚀 Come Usare

1. Scarica o clona il repository
2. Apri "tunex.html` in un browser moderno
3. Aggiungi i tuoi canali modificando l'array `channels` nel file
4. Personalizza i colori nel CSS `:root`

## 📝 Struttura Canali

Modifica la sezione `var channels = [...]` per aggiungere i tuoi canali:

```javascript
var channels = [
  { name: "Nome Canale", url: "https://example.com/stream.m3u8", type: "standard" },
  { name: "YouTube", url: "https://www.youtube.com/watch?v=VIDEO_ID", type: "youtube-link" }
];
```

### Tipi Supportati:
- `standard`: Video/Audio normali
- `youtube-link`: Link YouTube

## 🎨 Personalizzazione

### Colori (nel CSS :root)
```css
--primary: #6407de;        /* Colore principale */
--primary-dark: #980332;   /* Variante scura */
--primary-light: #ff3366;  /* Variante chiara */
--accent: #00ff33;         /* Colore accento */
--tunex-pink: #ff3366;     /* Rosa TuneX */
--tunex-cyan: #00ccff;     /* Cyan TuneX */
```

### Font & Layout
Modifica le variabili CSS per cambiare font, spaziature, raggio border, etc.

## 🛠️ Tecnologie Utilizzate

- **HTML5**: Struttura semantica
- **CSS3**: Gradient, Flexbox, Animazioni
- **JavaScript Vanilla**: Senza dipendenze (eccetto HLS.js)
- **HLS.js**: Supporto per stream HLS
- **Font Awesome 6**: Icone vettoriali
- **Web Speech API**: Ricerca vocale

## 📋 Equalizzatore Preset

Il player include 12 preset eq:
- ✅ Flat (neutro)
- 🔊 Bass (bassi potenziati)
- 📢 Treble (acuti potenziati)
- 🎤 Vocal (voce ottimizzata)
- 🎸 Rock
- 🎹 Pop
- 🎷 Jazz
- 🎼 Classical
- 🎧 Electronic
- 💃 Dance
- 🎙️ Podcast
- 🎬 Live

## 🌐 Browser Supportati

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Opera 76+

⚠️ Ricerca vocale: Funziona su Chrome/Edge. Su Firefox usare versione inglese.

## 📦 Installazione Locale

```bash
# Clona il repo
git clone https://github.com/TUO_USERNAME/TuneX.git

# Entra nella cartella
cd TuneX

# Apri in un server locale (Python 3)
python -m http.server 8000

# O con Node.js
npx http-server
```

Poi apri `http://localhost:8000` nel browser.

## 📄 Licenza

MIT License - Usa liberamente nei tuoi progetti

## 👨‍💻 Contributi

I contributi sono benvenuti! Se trovi bug o hai suggerimenti:
1. Fork il repository
2. Crea un branch (`git checkout -b feature/AmazingFeature`)
3. Commit le modifiche (`git commit -m 'Add AmazingFeature'`)
4. Push al branch (`git push origin feature/AmazingFeature`)
5. Apri una Pull Request

## 💡 Idee per Miglioramenti

- [ ] Playlist personali salvate
- [ ] Temi scuri/chiari switchabili
- [ ] Cronologia riproduzione
- [ ] Sincronizzazione cloud
- [ ] Plugin per server IPTV
- [ ] Visualizzatore 3D avanzato
- [ ] App mobile (React Native)

## 📞 Supporto

Trova un bug? Apri un [Issue](https://github.com/TUO_USERNAME/TuneX/issues)!

---

**Fatto con ❤️ da [Tuo Nome]**
