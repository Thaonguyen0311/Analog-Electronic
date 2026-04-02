# 1. What type of waveform appears at the output?
The output is a square wave.
It switches between:
HIGH ≈ 5 V (Vcc)
LOW ≈ 0 V
# 2. Between which voltage levels does the capacitor voltage oscillate?
The capacitor voltage oscillates between:
1/3 Vcc ≈ 1.67 V
2/3 Vcc ≈ 3.33 V
The waveform is an exponential charge/discharge curve (not a square wave).
# 3. Why can the 555 timer generate a periodic signal without any input signal?
The NE555 contains:
Two internal comparators
A flip-flop
A discharge transistor
Operation:
The capacitor charges through R1 and R2.
When the voltage reaches 2/3 Vcc, the output switches and the capacitor starts discharging.
When it drops to 1/3 Vcc, the output switches again and the capacitor starts charging.
This continuous charge–discharge cycle creates a self-sustaining oscillation, so no external input signal is required.
