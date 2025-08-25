# 🎆 Esperienza Premio Interattiva con Audio 🎆

Una bellissima esperienza web immersiva con audio sincronizzato, effetti di avvicinamento 3D e rivelazione premi spettacolare.

## 📁 File Inclusi

- `index.html` - Esperienza completa con overlay e audio
- `sound/` - Cartella con i file audio
  - `complete_sound.mp3` - Audio principale (5 secondi)
  - `start_sound.mp3` - Audio di sfondo (non utilizzato)
  - `final_sound.mp3` - Audio finale (non utilizzato)
- `README.md` - Versione italiana con le istruzioni
- `README_EN.md` - Versione inglese con le istruzioni
- `.gitignore` - Esclude file di sistema

## ✨ Caratteristiche Principali

### 🎵 Esperienza Audio Sincronizzata
- **Audio completo** di 5 secondi che accompagna tutta l'esperienza
- **Sincronizzazione perfetta** tra audio ed effetti visivi
- **Gestione intelligente** dell'autoplay con fallback
- **Volume ottimizzato** per un'esperienza immersiva
- **Crediti audio**: "Jojo N Australia" - No Copyright Sound da YouTube (croppato a 5 secondi)

### 🎬 Effetti Visivi Avanzati
- **Overlay di benvenuto** con messaggio personalizzato
- **Effetto di avvicinamento 3D** dalla lontananza
- **Sfocatura progressiva** che si riduce gradualmente
- **Fuochi d'artificio animati** ultra-realistici
- **Stelle scintillanti** di sfondo
- **Animazioni fluide** e transizioni eleganti

### 🎨 Design Moderno e Responsive
- **Gradienti colorati** e animazioni fluide
- **Tipografia elegante** con effetti glow
- **Design responsive** per tutti i dispositivi
- **Effetti hover** interattivi

## 🚀 Come Pubblicare su GitHub Pages

### Metodo 1: Repository Pubblico
1. Crea un nuovo repository su GitHub
2. Carica tutti i file in questo repository
3. Vai su **Settings** → **Pages**
4. In **Source**, seleziona **Deploy from a branch**
5. Scegli il branch **main** e la cartella **root**
6. Clicca **Save**
7. La tua pagina sarà disponibile su `https://tuousername.github.io/nome-repository`

### Metodo 2: Repository Privato (GitHub Pro)
1. Segui i passaggi del Metodo 1
2. In **Settings** → **Pages**, attiva **GitHub Actions** come source
3. GitHub creerà automaticamente un workflow per il deploy

## 🎯 Come Utilizzare

1. **Apri `index.html`** nel browser
2. **Vedi l'overlay** "Congratulazioni! Hai vinto un premio speciale!"
3. **Clicca il bottone** "Clicca per scoprire 🎁"
4. **Goditi l'esperienza**:
   - Audio inizia immediatamente
   - Il premio appare in lontananza (molto piccolo e sfocato)
   - Si avvicina gradualmente durante l'audio
   - Diventa completamente visibile alla fine dell'audio
5. **Ammira la rivelazione** del viaggio ad Amsterdam con fuochi d'artificio

## 🎬 Timeline dell'Esperienza

### ⏱️ Sequenza Temporale (5 secondi totali)
- **0ms**: Click → Audio inizia
- **0-800ms**: Overlay scompare con fade-out
- **800ms**: Premio appare in lontananza (scale: 0.05, blur: 20px, opacity: 0.1)
- **2000ms**: Si avvicina (blur: 15px, opacity: 0.2)
- **3000ms**: Continua ad avvicinarsi (blur: 8px, opacity: 0.4)
- **4000ms**: Quasi arrivato (blur: 0.8px, opacity: 0.9)
- **5000ms**: Completamente visibile (blur: 0px, opacity: 1)

### 🎵 Sincronizzazione Audio-Visiva
- **Audio**: `complete_sound.mp3` (5 secondi)
- **Effetti**: Sincronizzati perfettamente con la durata dell'audio
- **Climax**: Rivelazione finale coincide con la fine dell'audio

## 🛠️ Personalizzazione

### Cambiare il Messaggio Romantico
Modifica il testo in `index.html`:
```html
<p class="welcome-message">
    Hai vinto un premio speciale!<br>
    (ti amo tanto 💜🫀)
</p>
```

### Cambiare il Premio
Modifica il testo in `index.html`:
```html
<h2 class="amsterdam-text">✈️ Un Viaggio ad Amsterdam! ✈️</h2>
```

### Cambiare l'Audio
Sostituisci `sound/complete_sound.mp3` con un nuovo file audio di 5 secondi.

**Nota**: L'audio attuale è "Jojo N Australia" - No Copyright Sound da YouTube, croppato a 5 secondi per sincronizzazione perfetta.

### Modificare i Tempi
Aggiusta i valori `setTimeout` nel JavaScript per cambiare la timeline.

## 📱 Compatibilità

- ✅ Chrome (raccomandato)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Dispositivi mobili
- ✅ Gestione autoplay intelligente

## 🎨 Tecnologie Utilizzate

- **HTML5** per la struttura
- **CSS3** per animazioni 3D e effetti visivi
- **JavaScript** per sincronizzazione audio-visiva
- **CSS Transforms** per effetti di profondità
- **Audio API** per gestione audio avanzata

## 🔧 Note Tecniche

### Gestione Audio
- **Autoplay detection** automatica
- **Fallback** per browser che bloccano l'autoplay
- **Volume ottimizzato** (40%)
- **Gestione errori** robusta

### Performance
- **Hardware acceleration** per animazioni 3D
- **CSS transforms** per fluidità
- **Ottimizzazione mobile** con riduzione effetti

## 🎊 Caratteristiche Speciali

- **Effetto di profondità 3D** con translateZ
- **Sfocatura progressiva** che si riduce gradualmente
- **Scala dinamica** da 0.05 a 1.0
- **Fuochi d'artificio** ultra-realistici
- **Messaggio romantico** personalizzabile
- **Esperienza immersiva** completa

---

**Buon divertimento con la tua esperienza premio! 🎉💜🫀🎁**

