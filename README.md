# SparkitRaw: one-knob MIDI arpeggiator

![SparkitRaw free one-knob MIDI arpeggiator UI](https://raw.githubusercontent.com/RemiBlaze/SparkitRaw/main/sparkitraw-ui-screenshot.png)

**Hold a chord, turn one knob, get an arpeggio.**

SparkitRaw is a MIDI arpeggiator: it takes the chord you hold and outputs a tempo-synced arpeggio of MIDI notes. Because it's a MIDI effect, you place it *before* an instrument, as a MIDI effect ahead of your instrument in your DAW.

**macOS** (Apple Silicon and Intel): AU, VST3, CLAP, AAX, Standalone. Signed and notarized by Apple.

**Windows** 10 and 11, 64-bit: VST3, CLAP, Standalone. Authenticode signed.

AAX ships on macOS only.

---

## 🚀 Download & Install

Go to the [latest release](https://github.com/RemiBlaze/SparkitRaw/releases/latest) and pick your platform.

**macOS**
1. Download **`SparkitRaw_Installer.pkg`**.
2. Double-click it and follow the installer. It is signed and notarized by Apple, so it installs cleanly with no security warnings.
3. Restart your DAW and rescan plug-ins. SparkitRaw appears under **Remi Blaze**.

**Windows 10 and 11, 64-bit**
1. Download **`SparkitRaw_Installer.exe`**.
2. Run it and follow the installer. It is Authenticode signed.
3. Restart your DAW and rescan plug-ins. SparkitRaw appears under **Remi Blaze**.

No dongle and no extra account on either platform.

Full guide: **[remiblaze.com/support](https://remiblaze.com/support/)**.

---

## 🎛️ What It Does
SparkitRaw turns a held chord into a running arpeggio, all locked to your host tempo. There's one big **ENERGY** knob: turn it up and the arp gets faster and bigger: the note rate climbs (1/4 → 1/8 → 1/16 → 1/32), it spans more octaves (up to 4), and the pattern opens up from a simple upward run into an up-and-down motion. Turn it down and the arp settles into a slow, sparse pulse.

Hold a chord and it plays; let go and it stops. Any non-note MIDI (like pitch bend or CC) passes straight through. As you ride the knob, the **Fire Head** mascot climbs and a spark fires up it on every note, so you can see the pattern play.

Being a MIDI effect, SparkitRaw doesn't make sound on its own. It sends MIDI to whatever instrument sits after it in the chain.

---

## 💻 System Requirements

**macOS**
- macOS 15.0 or later
- Apple Silicon or Intel Mac (Universal Binary)
- An AU, VST3, CLAP or AAX host

**Windows**
- Windows 10 or Windows 11, 64-bit
- A VST3 or CLAP host

---

## 🐛 Bugs & Issues
Open an issue on the **[Issues](https://github.com/RemiBlaze/SparkitRaw/issues)** tab with your macOS or Windows version, DAW + version, and steps to reproduce.

---

## 📄 License & Credits
- **Plugin page:** [remiblaze.com/plugins/sparkit-raw/](https://remiblaze.com/plugins/sparkit-raw/).
- **Developer:** [Remi Blaze](https://remiblaze.com).
- **Framework:** [JUCE](https://juce.com).
- **License:** free under a proprietary [Freeware License](LICENSE) (see also our [terms](https://remiblaze.com/terms/)). Reverse-engineering, repackaging, binary redistribution, or reselling the compiled installer is strictly prohibited.

---

## Trademarks

All product names, company names, and logos mentioned herein are trademarks or registered trademarks of their respective owners. Any such references are used for descriptive or compatibility purposes only and do not imply affiliation with, endorsement by, or sponsorship from their owners.

VST is a trademark of Steinberg Media Technologies GmbH, registered in Europe and other countries.

Apple, macOS, Audio Units (AU), and Apple Silicon are trademarks of Apple Inc., registered in the U.S. and other countries.

AAX, Avid, and Pro Tools are trademarks or registered trademarks of Avid Technology, Inc. in the U.S. and other countries.

Microsoft and Windows are trademarks of the Microsoft group of companies.
