# Op-Amp as Comparator – Output Behavior
## Comparator Circuit

![Comparator](images/comparator.png)

1. Case Vin​>Vref
When the input voltage Vin becomes greater than the reference voltage Vref, the voltage at the non-inverting input is higher than the voltage at the inverting input.
V+​>V−
Because an operational amplifier has a very large open-loop gain, this small positive difference between the inputs is amplified significantly. As a result, the output voltage increases rapidly and reaches the positive saturation level, which is close to the positive supply voltage.
Vout​≈+Vsat​
Therefore, when Vin​>Vref​, the output of the comparator switches to the positive saturation state.

2. Case 
Vin < Vref
When the input voltage Vin becomes lower than the reference voltage Vref, the voltage at the non-inverting input becomes smaller than the voltage at the inverting input.
V+​<V−​
In this situation, the difference between the inputs is negative. Due to the large open-loop gain of the op-amp, the output voltage rapidly decreases until it reaches the negative saturation level, which is close to the negative supply voltage.
Vout​≈−Vsat​
Thus, when Vin < Vref, the output switches to the negative saturation state.

3. Reason for Switching Between Saturation Levels

An operational amplifier used as a comparator operates without negative feedback, meaning it functions in open-loop mode. 
Because the gain is extremely high, even a very small voltage difference between the inputs causes the output to quickly move toward one of the supply limits. Since the output cannot exceed the supply voltages, it saturates near the positive or negative rail.
Consequently, the output effectively switches between two states:

This behavior allows the operational amplifier to function as a voltage comparator, converting an analog input signal into a two-level output signal.
