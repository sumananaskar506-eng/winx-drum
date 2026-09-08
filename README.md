# 🥁 Winx Drum

An AI-powered web app that analyzes drum audio files and generates step-by-step beat instructions for recreating patterns in BandLab.

## ✨ Features

✅ **Upload & Analyze** - Drag & drop or click to upload drum audio files (MP3, WAV, OGG)
✅ **Beat Detection** - Automatically detects kick, snare, and hi-hat patterns
✅ **BPM Estimation** - Calculates beats per minute from the audio
✅ **Step-by-Step Instructions** - Shows drum patterns in easy-to-follow format
✅ **BandLab Ready** - Output format matches BandLab drum sequencer notation
✅ **Copy Pattern** - One-click copy of the analyzed pattern

---

## 🚀 How to Use

### **Step 1: Open the App**
Go to: https://sumananaskar506-eng.github.io/winx-drum/

(Or download `index.html` and open it in your browser)

### **Step 2: Upload Audio**
- Click the upload area
- Select a drum audio file (MP3, WAV, OGG)
- Or drag & drop the file

### **Step 3: Analyze**
- Click **"Analyze Drum Pattern"**
- Wait for the analysis to complete

### **Step 4: Get Instructions**
- See the step-by-step drum pattern
- Copy the pattern to your clipboard

### **Step 5: Recreate in BandLab**
- Open BandLab
- Use the drum sequencer
- Follow the instructions to place drums

---

## 📋 Output Format

The analyzer generates patterns like this:

```
🎵 Bar 1:
1.1: A (Kick) + L (Hi-Hat)
1.1.3: L (Hi-Hat)
1.2: J/K (Snare) + L (Hi-Hat)
1.2.3: L (Hi-Hat)
1.3: A (Kick) + L (Hi-Hat)
1.3.3: L (Hi-Hat)
1.4: J/K (Snare) + L (Hi-Hat)
1.4.3: L (Hi-Hat)

🎵 Bar 2:
2.1: A (Kick) + L (Hi-Hat)
2.1.3: L (Hi-Hat)
2.2: J/K (Snare) + L (Hi-Hat)
2.2.3: L (Hi-Hat)
...and so on
```

### **Key Mapping (for BandLab)**

- **A** = Kick (Bass Drum) 🥁
- **J/K** = Snare 🎯
- **L** = Hi-Hat (Closed) ✨

Each beat is shown as: `Bar.Beat.SubBeat`

Example: `1.1.3` means Bar 1, Beat 1, Sub-beat 3

---

## 🎵 Supported Audio Formats

- MP3 ✓
- WAV ✓
- OGG ✓
- FLAC ✓

**Maximum file size:** 50MB

---

## 🔧 How It Works

1. **Onset Detection** - Identifies drum hits using spectral flux analysis
2. **BPM Estimation** - Analyzes energy peaks to estimate tempo
3. **Instrument Classification** - Categorizes drums based on frequency content
4. **Pattern Generation** - Creates readable step-by-step instructions

---

## 💡 Tips for Best Results

✓ Use clear, isolated drum tracks (less background noise)
✓ Bedroom pop drums work great (90-130 BPM range)
✓ 2-4 bars of audio gives best accuracy
✓ Avoid heavily compressed or heavily EQ'd drums
✓ Use the first 10-30 seconds of a song

---

## 🌐 Browser Compatibility

Works on:
- ✅ Chrome/Chromium
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

---

## 🎓 Use Cases

🎓 **Learning** - Understand drum patterns step-by-step
🎵 **Creation** - Recreate patterns in BandLab
🎚️ **Production** - Study drum arrangements
🔄 **Practice** - Replicate favorite songs' drum beats

---

## 📖 Example Workflow

1. Find a bedroom pop song you like (e.g., on YouTube, Spotify)
2. Extract just the drum audio (or use a 10-30 second clip)
3. Upload to Winx Drum
4. Get the step-by-step pattern
5. Open BandLab and recreate it using the pattern
6. Modify and remix to make your own version!

---

## 🔗 Quick Links

- **GitHub Repository**: https://github.com/sumananaskar506-eng/winx-drum
- **Live App**: https://sumananaskar506-eng.github.io/winx-drum/
- **BandLab**: https://www.bandlab.com

---

## 📝 License

Open source - Feel free to use and modify!

---

## 🤝 Feedback

Having issues? Want to suggest features? Let me know! 

Made for bedroom pop producers learning music production. 🎧

Happy learning! 🥁✨
