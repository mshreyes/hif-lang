# HiF-Lang: High-Frequency Language Lexicon

I created **HiF-Lang** because I wanted a clean, distraction-free way to learn the highest-frequency words across different languages as my very first step when advancing into a new language. 

In any natural language, the top 100 words make up nearly half of all daily written and spoken communication, and the top 1,000 words unlock over 80% of everyday comprehension. By focusing on these core building blocks, alongside words borrowed from English that I already recognize, I can build a practical foundation before diving deeper into grammar and conversation.

---

## Features

- **100 & 1,000 High-Frequency Word Sets:** Curated core vocabulary for **Spanish, French, German, Italian, and Portuguese**.
- **Borrowed Words from English:** A dedicated list of common English loanwords (anglicisms) used in each language for quick vocabulary wins.
- **Native Browser Audio (TTS):** Click any word to hear its pronunciation using high-quality native browser speech synthesis, with normal (`1.0x`) and slow learner (`0.8x`) playback speeds.
- **Interactive Study Tools:** Includes part-of-speech filtering, instant search, grid/table views, and a **Quiz Blur** mode to test recall.
- **Easy to Expand (`words.json`):** Built to run on GitHub Pages with a simple JSON structure (`French100`, `French1000`, `FrenchBorrowed`, etc.) so I can easily append new languages over time.

---

## How to Use / Update

1. Clone or fork this repository and host it via **GitHub Pages**.
2. Keep `index.html` and `words.json` in the root directory.
3. To add a new language, simply append keys like `"Dutch100": [...]`, `"Dutch1000": [...]`, or `"DutchBorrowed": [...]` to `words.json`—the homepage will detect and display the new language automatically.

---

## Acknowledgments & Resources

A huge thank you to the open-access linguistic corpora, institutions, and web tools that made compiling and building this project possible:

- **[OPUS / OpenSubtitles Corpus](https://opus.nlpl.eu/) & [FrequencyWords](https://github.com/hermitdave/FrequencyWords):** For conversational and subtitle-based word frequency distributions.
- **[Leipzig Corpora Collection](https://corpora.uni-leipzig.de/) & [Wiktionary Frequency Lists](https://en.wiktionary.org/wiki/Wiktionary:Frequency_lists):** For written and web-based lexical frequency data.
- **National Language Academies & Lexical Databases:**
  - **Spanish:** [Real Academia Española (RAE — CREA / CORPES XXI)](https://www.rae.es/)
  - **French:** [Lexique 3](http://www.lexique.org/)
  - **German:** [IDS Mannheim (DeReKo)](https://www.ids-mannheim.de/) & [DWDS](https://www.dwds.de/)
  - **Italian:** [Accademia della Crusca](https://accademiadellacrusca.it/) & Tullio De Mauro's *Nuovo vocabolario di base (NVdB)*
  - **Portuguese:** [Corpus do Português](https://www.corpusdoportugues.org/) & [Linguateca](https://www.linguateca.pt/)
- **Web Technologies:** [Tailwind CSS](https://tailwindcss.com/), [Google Fonts](https://fonts.google.com/) (*Newsreader*, *Plus Jakarta Sans*, & *JetBrains Mono*), and the [W3C Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/SpeechSynthesis).
- **Coding Assistance:** Built with the help of **Google Gemini** for coding assistance.
