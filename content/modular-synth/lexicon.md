---
title: "Modular Synth Lexicon"
date: "2025-10-19"
categories: ["reference"]
tags: ["terminology", "glossary", "modular-synth"]
---

<div style="margin-bottom: 30px; position: relative;">
  <input type="text" id="lexiconSearch" placeholder="🔍 Search terminology..." style="width: 100%; padding: 12px 15px; font-size: 16px; border: 2px solid #e0e0e0; border-radius: 8px; box-sizing: border-box; background-color: #fafafa; transition: all 0.3s ease;" />
</div>

<style>
#lexiconSearch:focus {
  outline: none;
  border-color: #007bff;
  background-color: white;
  box-shadow: 0 0 0 3px rgba(0, 123, 255, 0.1);
}

#lexiconSearch::placeholder {
  color: #999;
}

table tr.hidden-row {
  display: none !important;
}

.no-results {
  text-align: center;
  padding: 20px;
  color: #666;
  font-style: italic;
}
</style>

<br />

# Modular Synth Terminology Reference

### 🎚️ Control and Modulation Terms

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
| **MOD** | Modulation | A control signal (usually CV) affecting a parameter (e.g. filter cutoff, pitch, PWM). |
| **MOD POLARITY** | Modulation Polarity | Determines whether modulation adds to (positive), subtracts from (negative), or affects both directions (bipolar) around the base value. |
| **KB** | Keyboard Control Voltage | CV output from a keyboard, usually 1V/oct, used to track pitch across modules. |

<br />

### 🎛️ Signal & Audio Path Labels

| Label | Meaning | Description |
|--------|----------|-------------|
| **IN / OUT** | Input / Output | Where audio or CV enters/leaves a module. |
| **AUDIO** | Audio Signal Path | Indicates this connection carries audio. |
| **CV IN** | Control Voltage Input | Modulation input controlling a parameter. |
| **GATE** | Binary On/Off Signal | Triggers or sustains an envelope or note. |
| **TRIG / TRIGGER** | Trigger Pulse | Very short signal to start an event. |
| **CLOCK / CLK** | Clock Signal | Periodic pulse used for synchronization. |
| **RESET** | Reset Input | Restarts an LFO, sequence, or envelope. |
| **SYNC** | Synchronize | Aligns phase between oscillators or modulators. |
| **ATT / ATTEN** | Attenuator | Reduces CV or audio level. |
| **OFFSET** | Adds Constant DC Voltage | Shifts the baseline voltage. |
| **MIX / MIXER** | Combines Signals | Blends multiple sources. |
| **INV** | Invert | Flips the signal polarity. |
| **SUM** | Summing Output | Combines multiple voltages. |
| **MULT** | Multiple | Passive or buffered splitter that duplicates one signal to several outputs. Each numbered group (e.g. **MULT 1**, **MULT 2**) is independent. Unlike stacked cables, multiples provide cleaner, more reliable duplication—especially important for accurate pitch or modulation signals. |
| **HOLD** | Hold | Maintains the current voltage while active (used in S&H, EG sustain, or track/hold circuits). |

<br />

### 🔉 Oscillator & Waveform Labels

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

<br />

### 🧠 Sequencing & Logic Terms

| Label | Meaning | Description |
|--------|----------|-------------|
| **SEQ** | Sequencer | Outputs a series of voltages over time. |
| **STEP** | Step | Single stage in a sequence. |
| **CLK IN / OUT** | Clock Input/Output | Timing sync signals. |
| **DIV / MULT** | Clock Divider / Multiplier | Alters clock rate by ratio. |
| **RND / RANDOM** | Random Output | Generates random voltages or triggers. |
| **LOGIC** | Logic Functions | Combines triggers (AND, OR, XOR, etc.). |
| **GATE OUT** | Gate Output | Sends gate signals per step or event. |

<br />

### 🎚️ Filter & Effect Terms

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

<br />

### ⚙️ Utility and Misc Terms

| Label | Meaning | Description |
|--------|----------|-------------|
| **ATT / ATTENUATE** | Attenuator | Reduces signal level. |
| **OFFSET** | DC Offset | Adds a fixed voltage. |
| **INV / INVERT** | Inverter | Flips signal polarity. |
| **MIX / SUM / ADD** | Mixer | Combines voltages or audio. |
| **MUTE** | Mute | Silences signal. |
| **PAN** | Panning | Controls left-right balance. |
| **LEVEL / VOL** | Level / Volume | Output gain control. |
| **BI / UNI** | Bipolar / Unipolar | Indicates whether a signal swings around zero (bipolar, e.g. –5V to +5V) or only stays positive (unipolar, e.g. 0V to +5V). Bipolar signals can modulate parameters both above and below a center point, while unipolar signals only add or increase values. |
| **LIN / EXP** | Linear / Exponential | Response curve type (VCAs, envelopes, etc.). |
| **EXP FM / LIN FM** | FM Type | Specifies exponential or linear frequency modulation input. |

<br />

### 💡 Power and Connectivity

| Label | Meaning | Description |
|--------|----------|-------------|
| **+12V / -12V / +5V** | Power Rails | Eurorack standard supply voltages. |
| **GND** | Ground | Common voltage reference. |
| **BUS** | Bus Connection | Shared power or CV bus line. |
| **MIDI / USB** | Connectivity Ports | Digital communication or control interfaces. |

<br />

<script>
document.addEventListener('DOMContentLoaded', function() {
    const searchInput = document.getElementById('lexiconSearch');
    const tables = document.querySelectorAll('table');
    let totalRows = 0;
    let visibleRows = 0;
    
    // Count total rows initially
    tables.forEach(table => {
        const rows = table.querySelectorAll('tbody tr');
        totalRows += rows.length;
    });
    
    function filterTables() {
        const searchTerm = searchInput.value.toLowerCase().trim();
        visibleRows = 0;
        
        if (searchTerm === '') {
            // Show all rows and sections
            tables.forEach(table => {
                const rows = table.querySelectorAll('tbody tr');
                rows.forEach(row => {
                    row.style.display = '';
                    row.classList.remove('hidden-row');
                });
                
                // Show the section header
                let sectionHeader = table.previousElementSibling;
                while (sectionHeader && sectionHeader.tagName !== 'H3') {
                    sectionHeader = sectionHeader.previousElementSibling;
                }
                
                if (sectionHeader && sectionHeader.tagName === 'H3') {
                    sectionHeader.style.display = '';
                    // Also show any br elements before the header
                    let brElement = sectionHeader.previousElementSibling;
                    if (brElement && brElement.tagName === 'BR') {
                        brElement.style.display = '';
                    }
                }
                
                // Show the table header row
                const tableHeader = table.querySelector('thead tr');
                if (tableHeader) {
                    tableHeader.style.display = '';
                }
            });
            
            return;
        }
        
        tables.forEach(table => {
            const rows = table.querySelectorAll('tbody tr');
            let hasVisibleRows = false;
            
            rows.forEach(row => {
                const text = row.textContent.toLowerCase();
                const isVisible = text.includes(searchTerm);
                
                if (isVisible) {
                    row.style.display = '';
                    row.classList.remove('hidden-row');
                    hasVisibleRows = true;
                    visibleRows++;
                } else {
                    row.style.display = 'none';
                    row.classList.add('hidden-row');
                }
            });
            
            // Hide/show the section header if no rows are visible
            // Look for the H3 header that precedes this table
            let sectionHeader = table.previousElementSibling;
            while (sectionHeader && sectionHeader.tagName !== 'H3') {
                sectionHeader = sectionHeader.previousElementSibling;
            }
            
            if (sectionHeader && sectionHeader.tagName === 'H3') {
                sectionHeader.style.display = hasVisibleRows ? '' : 'none';
                // Also hide any br elements before the header
                let brElement = sectionHeader.previousElementSibling;
                if (brElement && brElement.tagName === 'BR') {
                    brElement.style.display = hasVisibleRows ? '' : 'none';
                }
            }
            
            // Hide/show the table header row when no data rows are visible
            const tableHeader = table.querySelector('thead tr');
            if (tableHeader) {
                tableHeader.style.display = hasVisibleRows ? '' : 'none';
            }
        });
        
        // Hide search results counter
        searchResults.style.display = 'none';
    }
    
    searchInput.addEventListener('input', filterTables);
    
    // Clear search on Escape key
    searchInput.addEventListener('keydown', function(e) {
        if (e.key === 'Escape') {
            searchInput.value = '';
            filterTables();
            searchInput.blur(); // Remove focus
        }
    });
    
    // Focus search on Ctrl+F or Cmd+F
    document.addEventListener('keydown', function(e) {
        if ((e.ctrlKey || e.metaKey) && e.key === 'f') {
            e.preventDefault();
            searchInput.focus();
        }
    });
});
</script>
