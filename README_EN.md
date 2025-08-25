# 🎆 Interactive Prize Experience with Audio 🎆

A beautiful immersive web experience with synchronized audio, 3D approach effects, and spectacular prize revelation.

## 📁 Included Files

- `index.html` - Complete experience with overlay and audio
- `sound/` - Audio files folder
  - `complete_sound.mp3` - Main audio (5 seconds)
  - `start_sound.mp3` - Background audio (not used)
  - `final_sound.mp3` - Final audio (not used)
- `README.md` - Italian version with instructions
- `README_EN.md` - English version with instructions
- `.gitignore` - Excludes system files

## ✨ Main Features

### 🎵 Synchronized Audio Experience
- **Complete audio** of 5 seconds that accompanies the entire experience
- **Perfect synchronization** between audio and visual effects
- **Intelligent autoplay management** with fallback
- **Optimized volume** for an immersive experience
- **Audio credits**: "Jojo N Australia" - No Copyright Sound from YouTube (cropped to 5 seconds)

### 🎬 Advanced Visual Effects
- **Welcome overlay** with personalized message
- **3D approach effect** from the distance
- **Progressive blur** that gradually reduces
- **Ultra-realistic animated fireworks**
- **Twinkling background stars**
- **Smooth animations** and elegant transitions

### 🎨 Modern and Responsive Design
- **Colorful gradients** and smooth animations
- **Elegant typography** with glow effects
- **Responsive design** for all devices
- **Interactive hover effects**

## 🚀 How to Deploy on GitHub Pages

### Method 1: Public Repository
1. Create a new repository on GitHub
2. Upload all files to this repository
3. Go to **Settings** → **Pages**
4. In **Source**, select **Deploy from a branch**
5. Choose the **main** branch and **root** folder
6. Click **Save**
7. Your page will be available at `https://yourusername.github.io/repository-name`

### Method 2: Private Repository (GitHub Pro)
1. Follow the steps from Method 1
2. In **Settings** → **Pages**, enable **GitHub Actions** as source
3. GitHub will automatically create a workflow for deployment

## 🎯 How to Use

1. **Open `index.html`** in your browser
2. **See the overlay** "Congratulations! You've won a special prize!"
3. **Click the button** "Click to discover 🎁"
4. **Enjoy the experience**:
   - Audio starts immediately
   - The prize appears in the distance (very small and blurred)
   - It gradually approaches during the audio
   - Becomes completely visible at the end of the audio
5. **Admire the revelation** of the trip to Amsterdam with fireworks

## 🎬 Experience Timeline

### ⏱️ Time Sequence (5 seconds total)
- **0ms**: Click → Audio starts
- **0-800ms**: Overlay disappears with fade-out
- **800ms**: Prize appears in distance (scale: 0.05, blur: 20px, opacity: 0.1)
- **2000ms**: Approaches (blur: 15px, opacity: 0.2)
- **3000ms**: Continues approaching (blur: 8px, opacity: 0.4)
- **4000ms**: Almost arrived (blur: 0.8px, opacity: 0.9)
- **5000ms**: Completely visible (blur: 0px, opacity: 1)

### 🎵 Audio-Visual Synchronization
- **Audio**: `complete_sound.mp3` (5 seconds)
- **Effects**: Perfectly synchronized with audio duration
- **Climax**: Final revelation coincides with audio ending

## 🛠️ Customization

### Change the Romantic Message
Modify the text in `index.html`:
```html
<p class="welcome-message">
    You've won a special prize!<br>
    (I love you so much 💜🫀)
</p>
```

### Change the Prize
Modify the text in `index.html`:
```html
<h2 class="amsterdam-text">✈️ A Trip to Amsterdam! ✈️</h2>
```

### Change the Audio
Replace `sound/complete_sound.mp3` with a new 5-second audio file.

**Note**: The current audio is "Jojo N Australia" - No Copyright Sound from YouTube, cropped to 5 seconds for perfect synchronization.

### Modify Timing
Adjust the `setTimeout` values in JavaScript to change the timeline.

## 📱 Compatibility

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile devices
- ✅ Intelligent autoplay management

## 🎨 Technologies Used

- **HTML5** for structure
- **CSS3** for 3D animations and visual effects
- **JavaScript** for audio-visual synchronization
- **CSS Transforms** for depth effects
- **Audio API** for advanced audio management

## 🔧 Technical Notes

### Audio Management
- **Automatic autoplay detection**
- **Fallback** for browsers that block autoplay
- **Optimized volume** (40%)
- **Robust error handling**

### Performance
- **Hardware acceleration** for 3D animations
- **CSS transforms** for fluidity
- **Mobile optimization** with reduced effects

## 🎊 Special Features

- **3D depth effect** with translateZ
- **Progressive blur** that gradually reduces
- **Dynamic scale** from 0.05 to 1.0
- **Ultra-realistic fireworks**
- **Customizable romantic message**
- **Complete immersive experience**

---

**Enjoy your prize experience! 🎉💜🫀🎁**
