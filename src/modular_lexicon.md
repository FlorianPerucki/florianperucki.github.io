# Modular Synth Terminology Reference

## 🎚️ Control and Modulation Terms

| Label | Meaning | Description |
|--------|----------|-------------|
| **CV** | Control Voltage | Analog voltage (often 0–5V or -5V to +5V) controlling parameters such as pitch or cutoff. |
| **LFO** | Low-Frequency Oscillator | Generates a slow cyclic waveform (below ~20 Hz) used for modulation. |
| **ENV / EG** | Envelope / Envelope Generator | Produces a voltage contour (ADSR, AR, etc.) in response to a gate or trigger. |
| **ADSR** | Attack, Decay, Sustain, Release | Classic 4-stage envelope shape used for amplitude or filter. |
| **AR / ASR** | Attack-Release / Attack-Sustain-Release | Simpler envelope forms. |
| **PWM** | Pulse Width Modulation | Modulates a square wave’s width for richer timbres. |
| **FM** | Frequency Modulation | One signal modulates another’s frequency. |
| **AM** | Amplitude Modulation | One signal modulates another’s amplitude. |
| **RM** | Ring Modulation | Multiplies two signals, producing sum/difference frequencies. |
| **S&H** | Sample and Hold | Captures and holds voltage values, creating stepped/random signals. |
| **VCA** | Voltage Controlled Amplifier | Controls amplitude via CV. |
| **VCF** | Voltage Controlled Filter | Controls filter cutoff via CV. |
| **VCO** | Voltage Controlled Oscillator | Oscillator whose pitch is controlled by voltage. |
| **VC** | Voltage Controlled | Prefix meaning voltage-controllable (VC Delay, VC Mixer, etc.). |

---

## 🎛️ Signal & Audio Path Labels

| Label | Meaning | Description |
|--------|----------|-------------|
| **IN / OUT** | Input / Output | Where audio or CV enters/leaves a module. |
| **AUDIO** | Audio signal path | Indicates this connection carries audio. |
| **CV IN** | Control Voltage Input | Modulation input controlling a parameter. |
| **GATE** | Binary on/off signal | Triggers or sustains an envelope or note. |
| **TRIG / TRIGGER** | Trigger pulse | Very short signal to start an event. |
| **CLOCK / CLK** | Clock signal | Periodic pulse used for synchronization. |
| **RESET** | Reset input | Restarts an LFO, sequence, or envelope. |
| **SYNC** | Synchronize | Aligns phase between oscillators or modulators. |
| **ATT / ATTEN** | Attenuator | Reduces CV or audio level. |
| **OFFSET** | Adds constant DC voltage | Shifts the baseline voltage. |
| **MIX / MIXER** | Combines signals | Blends multiple sources. |
| **INV** | Invert | Flips the signal polarity. |
| **SUM** | Summing output | Combines multiple voltages. |

---

## 🔉 Oscillator & Waveform Labels

| Label | Meaning | Description |
|--------|----------|-------------|
| **SIN / SINE** | Sine Wave | Smooth waveform, pure tone. |
| **TRI / TRIANGLE** | Triangle Wave | Linear rise/fall; gentle harmonics. |
| **SAW / SAWTOOTH** | Sawtooth Wave | Bright, buzzy harmonic content. |
| **SQR / SQUARE** | Square Wave | Alternates high/low; hollow timbre. |
| **PULSE** | Pulse Wave | Variable-width square wave. |
| **SUB** | Sub-Oscillator | Output one or more octaves below the main oscillator. |
| **NOISE** | Noise Generator | Random signal (white, pink, etc.). |
| **PW** | Pulse Width | Controls duty cycle of pulse wave. |
| **PWM IN** | Pulse Width Modulation Input | CV input to modulate pulse width. |

---

## 🧠 Sequencing & Logic Terms

| Label | Meaning | Description |
|--------|----------|-------------|
| **SEQ** | Sequencer | Outputs a series of voltages over time. |
| **STEP** | Step | Single stage in a sequence. |
| **CLK IN / OUT** | Clock Input/Output | Timing sync signals. |
| **DIV / MULT** | Clock Divider / Multiplier | Alters clock rate by ratio. |
| **RND / RANDOM** | Random Output | Generates random voltages or triggers. |
| **LOGIC** | Logic Functions | Combines triggers (AND, OR, XOR, etc.). |
| **GATE OUT** | Gate Output | Sends gate signals per step or event. |

---

## 🎚️ Filter & Effect Terms

| Label | Meaning | Description |
|--------|----------|-------------|
| **CUTOFF** | Filter Cutoff Frequency | Frequency where filter begins attenuating. |
| **RES / RESO / Q** | Resonance | Emphasizes frequencies near cutoff. |
| **HP / HPF** | High-Pass Filter | Removes low frequencies. |
| **LP / LPF** | Low-Pass Filter | Removes high frequencies. |
| **BP / BPF** | Band-Pass Filter | Passes a mid-frequency band. |
| **NOTCH** | Notch / Band-Stop Filter | Removes a narrow frequency band. |
| **DRY / WET** | Dry/Wet Mix | Balance between original and processed signal. |
| **FB / FEEDBACK** | Feedback | Amount of output fed back into input. |
| **DELAY / REVERB** | Delay / Reverb | Time-based effects. |

---

## ⚙️ Utility and Misc Terms

| Label | Meaning | Description |
|--------|----------|-------------|
| **ATT / ATTENUATE** | Attenuator | Reduces signal level. |
| **OFFSET** | DC Offset | Adds a fixed voltage. |
| **INV / INVERT** | Inverter | Flips signal polarity. |
| **MIX / SUM / ADD** | Mixer | Combines voltages or audio. |
| **MUTE** | Mute | Silences signal. |
| **PAN** | Panning | Controls left-right balance. |
| **LEVEL / VOL** | Level / Volume | Output gain control. |
| **BI / UNI** | Bipolar / Unipolar | Indicates signal polarity range (e.g. ±5V vs 0–5V). |
| **LIN / EXP** | Linear / Exponential | Response curve type (VCAs, envelopes, etc.). |
| **EXP FM / LIN FM** | FM Type | Specifies exponential or linear frequency modulation input. |

---

## 💡 Power and Connectivity

| Label | Meaning | Description |
|--------|----------|-------------|
| **+12V / -12V / +5V** | Power Rails | Eurorack standard supply voltages. |
| **GND** | Ground | Common voltage reference. |
| **BUS** | Bus Connection | Shared power or CV bus line. |
| **MIDI / USB** | Connectivity Ports | Digital communication or control interfaces. |
