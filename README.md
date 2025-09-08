# stylophone
Small electronic instrument controlled with a metal stylus.
This repository contains my course project: building a DIY analog stylophone synthesizer.
A stylophone is a small electronic instrument controlled with a metal stylus touching a resistor-based keyboard. Each contact point defines a different pitch, and the sound is generated electronically through a simple oscillator circuit.

How It Works

The instrument is based on an analog electronic circuit with the following main blocks:

Oscillator (tone generator): Creates the main sound signal using a relaxation oscillator.

Resistor Keyboard: Each resistor sets the frequency of the oscillator; touching with the stylus selects the pitch.

Vibrato Generator (LFO): A low-frequency oscillator modulates the pitch, producing a vibrato effect when enabled.

Signal Filtering: RC filters clean the waveform and reduce unwanted high-frequency noise.

Amplifier + Speaker Output: A transistor amplifier increases the signal strength so it can be heard through a speaker or headphones.

Components Used

Capacitors: 100µF ×1, 100nF ×5, 47nF ×1

Resistors: 10M, 68K, 150K, 33K, 22K, 6.8K, 1.8K, 2.2K ×2, 390K ×2, 13K, 47Ω, plus variable resistors (10K ×22)

Transistors: BC337 ×2, BC557 (PNP) ×1, BC547 (NPN) ×1

Diode: 1N4001 ×1

Potentiometer: 2.5K ×1

Power Supply: 9V battery
