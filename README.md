# SparkitRaw — one-knob MIDI arpeggiator

![SparkitRaw](https://raw.githubusercontent.com/RemiBlaze/SparkitRaw/main/sparkitraw-ui-screenshot.png)

**Hold a chord, turn one knob, get an arpeggio.**

SparkitRaw is a MIDI arpeggiator: it takes the chord you hold and outputs a tempo-synced arpeggio of MIDI notes. Because it's a MIDI effect, you place it *before* an instrument — as a MIDI effect ahead of your instrument in your DAW.

Fully **signed and notarized** for macOS as **AU, VST3, and Standalone**.

---

## 🚀 Download & Install
1. Go to the [latest release](https://github.com/RemiBlaze/SparkitRaw/releases/latest).
2. Download **`SparkitRaw_Installer.pkg`**.
3. Double-click it and follow the installer. Signed & notarized by Apple — installs cleanly, no security warnings.
4. Restart your DAW and rescan plug-ins.

Full guide: **[remiblaze.com/support](https://remiblaze.com/support/)**.

---

## 🎛️ What It Does
SparkitRaw turns a held chord into a running arpeggio, all locked to your host tempo. There's one big **ENERGY** knob: turn it up and the arp gets faster and bigger — the note rate climbs (1/4 → 1/8 → 1/16 → 1/32), it spans more octaves (up to 4), and the pattern opens up from a simple upward run into an up-and-down motion. Turn it down and the arp settles into a slow, sparse pulse.

Hold a chord and it plays; let go and it stops. Any non-note MIDI (like pitch bend or CC) passes straight through. As you ride the knob, the **Fire Head** mascot climbs and a spark fires up it on every note, so you can see the pattern play.

Being a MIDI effect, SparkitRaw doesn't make sound on its own — it sends MIDI to whatever instrument sits after it in the chain.

---

## 💻 System Requirements
- macOS 15.0 or later
- Apple Silicon or Intel Mac (Universal Binary)
- Any AU or VST3 host that supports MIDI FX (your DAW of choice)

---

## 🐛 Bugs & Issues
Open an issue on the **[Issues](https://github.com/RemiBlaze/SparkitRaw/issues)** tab with your macOS version, DAW + version, and steps to reproduce.

---

## 📄 License & Credits
- **Developer:** [Remi Blaze](https://remiblaze.com).
- **Framework:** [JUCE](https://juce.com).
- **License:** free under a proprietary [Freeware License](LICENSE) (see also our [terms](https://remiblaze.com/terms/)). Reverse-engineering, repackaging, binary redistribution, or reselling the compiled installer is strictly prohibited.

---

## Trademarks

All product names, company names, and logos mentioned herein are trademarks or registered trademarks of their respective owners. Any such references are used for descriptive or compatibility purposes only and do not imply affiliation with, endorsement by, or sponsorship from their owners.

VST is a trademark of Steinberg Media Technologies GmbH, registered in Europe and other countries.

Apple, macOS, Audio Units (AU), and Apple Silicon are trademarks of Apple Inc., registered in the U.S. and other countries.
