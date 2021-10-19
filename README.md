# On-Chip-8x-Phase-Locked-Loop-PLL-using-OSU-180nm-and-Ngspice

This repository comprises design of on-chip 8X PLL using open source tools like OSU 180nm.

What is a PLL?
A phase-locked loop or phase lock loop (PLL) is a control system that generates an output signal whose phase is related to the phase of an input signal. There are several different types; the simplest is an electronic circuit consisting of a voltage  and a phase detector in a feedback loop. The oscillator generates a periodic signal, and the phase detector compares the phase of that signal with the phase of the input periodic signal, adjusting the oscillator to keep the phases matched.

Keeping the input and output phase in lock step also implies keeping the input and output frequencies the same. Consequently, in addition to synchronizing signals, a phase-locked loop can track an input frequency, or it can generate a frequency that is a multiple of the input frequency. These properties are used for computer clock synchronization, demodulation, and frequency synthesis.

Phase-locked loops are widely employed in radio, telecommunications, computers and other electronic applications.

TOOLS USED -
The design of pll is implemented using the following tools -
1. NGSPICE
2. MAGIC
3. Any PDK (OSU 180nm has been used for this)

The process of designing pll involved two stages Pre layout and Post layout. 

A. Pre Layout Simulations -

![image](https://user-images.githubusercontent.com/87768763/137958332-8305d06c-a3cc-4c66-b895-0feda923589e.png)

Block diagram of PLL



Netlist of PLL 

Simulation of PLL in Ngspice -

![image](https://user-images.githubusercontent.com/87768763/137958612-385dd941-7b17-4857-8fcb-378d7b813f93.png)

