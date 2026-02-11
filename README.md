# 言語学習 Language Audio Builder

A simple web application for creating audio files from English-Japanese sentence pairs for language learning practice using text-to-speech synthesis.

## Features

- 📄 **CSV Upload**: Drag-and-drop or click to upload CSV files
- 🎧 **Audio Generation**: Converts sentence pairs to continuous audio using text-to-speech
- ⚙️ **Customizable Settings**:
  - Adjustable pause duration between sentences (0.5-5 seconds)
  - Multiple repetitions per sentence (1-5 times)
  - Voice selection for English and Japanese
  - Adjustable speech rate (0.5x-1.5x)
- 🔊 **Playback**: Listen to generated audio directly in your browser

## How to Use

1. **Open the Application**
   - Open `jp-en-lang-learning-audio-player.html` in any modern web browser (Chrome, Firefox, Safari, Edge)
   - No installation or server required - runs entirely in your browser

2. **Prepare Your CSV File**
   - Create a CSV file with two columns: `English` and `Japanese`
   - Example:
     ```csv
     English,Japanese
     Hello,こんにちは
     How are you?,お元気ですか？
     Thank you,ありがとう
     ```

3. **Upload Your File**
   - Click the upload area or drag and drop your CSV file
   - Preview your sentences to verify they loaded correctly

4. **Configure Audio Settings**
   - Choose your preferred English and Japanese voices
   - Adjust pause duration, repetitions, and speech rate
   - Click "Generate Audio"

5. **Listen to Your Audio**
   - Audio will play automatically in your browser
   - Use the audio player controls to pause, play, or scrub through the audio

## CSV Format

Your CSV file must include:
- A header row with columns named `English` and `Japanese`
- One sentence pair per row

Example:
```csv
English,Japanese
Good morning,おはようございます
Good night,おやすみなさい
See you later,また後で
```

## Browser Compatibility

- ✅ Chrome/Edge 
- ✅ Firefox
- ✅ Safari
- ⚠️ Requires a browser that supports Web Speech API

## Technical Details

- Built with vanilla HTML, CSS, and JavaScript
- Uses Web Speech API for text-to-speech synthesis and playback
- No external dependencies or server required
- No recording or microphone access needed
- Audio plays directly through the browser

## License

Feel free to use and modify for your language learning needs!
