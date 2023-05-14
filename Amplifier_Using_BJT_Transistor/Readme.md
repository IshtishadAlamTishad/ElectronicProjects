
## Introduction :
A BJT amplifier consists of a BJT transistor and a set of passive components, such as resistors and capacitors, arranged in a specific configuration.
The amount of amplification provided by the BJT amplifier can be controlled by adjusting the values of the biasing components, such as the DC voltage and the emitter resistor, as well as the load resistor.
NPN BJTs are commonly used in electronic circuits as amplifiers and switches, and can be found in a variety of applications such as audio amplifiers, power supplies, and radio receivers.
The transistor has three terminals: the emitter, the base, and the collector. The emitter is connected to a source of electrons, the base is the control terminal, and the collector is connected to a load resistor or other device.
The transistor acts as a current amplifier, with the amount of current flowing from the collector to the emitter being proportional to the current flowing into the base

## Components Required :

![capacitor](https://github.com/IshtishadAlamTishad/ElectronicProjects/assets/96460346/59e8aa13-5573-4e84-ba9c-8d46bd7bc6af)
![NPN_Transistor](https://github.com/IshtishadAlamTishad/ElectronicProjects/assets/96460346/4e4794b9-93d8-4ad3-858c-4d110be507af)
![Resistor](https://github.com/IshtishadAlamTishad/ElectronicProjects/assets/96460346/f090a9fd-b410-48a1-8de2-70b16e406722)
<img width="131" alt="Battery" src="https://github.com/IshtishadAlamTishad/ElectronicProjects/assets/96460346/3850f9e3-88d6-4e32-8e91-8cdd7bbc47b2">
![Speaker](https://github.com/IshtishadAlamTishad/ElectronicProjects/assets/96460346/708a5fbf-09bd-4ae7-97b5-541150fbea52)
<img width="142" alt="Wires" src="https://github.com/IshtishadAlamTishad/ElectronicProjects/assets/96460346/7f09fcf1-c19d-46a2-9e5d-c14883883f51">


## Capacitors :
Coupling: Capacitors are used to couple the input signal to the base of the transistor, while blocking any DC component from the input signal.
Decoupling/Bypassing: Capacitors are used to bypass or decouple AC signals around specific resistors, such as the emitter resistor, which reduces negative feedback and increases gain.
Filtering: Capacitors are used to filter unwanted frequencies from the input or output signals, such as high-frequency noise or low-frequency hum. 

## Resistor :
Biasing: Resistors are used to provide a stable DC bias voltage to the base of the transistor, which is required to ensure proper operation of the transistor.
Gain Control: Resistors are used to set the gain of the amplifier by controlling the amount of feedback in the circuit.
Load Resistance: Resistors are used as load resistors to ensure that the transistor operates in the correct region of its characteristic curve, ensuring the amplifier is operating within a linear region.

## Source :
the DC voltage plays a crucial role in the common emitter BJT amplifier circuit by establishing the bias point for the transistor, which determines the amount of current flowing through the transistor even when there is no input audio signal. This bias current allows the transistor to operate in its linear region, amplifying the input signal effectively without causing distortion. 

## Circuit Diagram :

![circuit](https://github.com/IshtishadAlamTishad/ElectronicProjects/assets/96460346/d46ef768-8039-4278-ab7d-81af01ce7c84)

## Simulation on Multism :

![sim](https://github.com/IshtishadAlamTishad/ElectronicProjects/assets/96460346/9b1c2f9a-cee5-4df7-a29f-3e9bd67ac2aa)

## Working Mechanism :
1.  The input audio signal is first coupled to the base of the transistor using a coupling capacitor. The capacitor blocks any DC component in the input signal and allows only the AC component of the signal to pass through to the base of the transistor. 
2.  The DC voltage applied to the base-emitter junction of the transistor establishes the bias point which determines the amount of current flowing through the transistor even when there is no input audio signal. 
3.  When an AC signal is applied to the base of the transistor, it modulates the bias current flowing through the transistor, causing a proportional change in the collector current. This produces an amplified AC signal at the collector of the transistor.
4.   The amplified AC signal is then passed through a load resistor connected to the collector of the transistor. This load resistor converts the current signal into a voltage signal, which is then available as an amplified output signal across the load resistor. 
5.   The amount of amplification provided by the transistor can be controlled by adjusting the values of the biasing components, such as the DC voltage and the emitter resistor. The choice of load resistor also affects the amount of amplification, with a larger load resistor resulting in higher gain but lower output power.


## Conclusion: 
In conclusion, BJT amplifiers are a popular choice for audio amplification due to their high gain, low noise, and simple design. However, their limitations need to be carefully considered when designing audio circuits to ensure that the desired performance is achieved.
