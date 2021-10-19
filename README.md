# On-Chip-8x-Phase-Locked-Loop-PLL-using-OSU-180nm-and-Ngspice

The following is a project completed for a 1 day workshop conducted by VLSI System Design. 

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

![PLLnetlist](https://user-images.githubusercontent.com/87768763/137961936-b2195510-341f-4781-859e-eb3535a03dfa.png)

Netlist of PLL 

Simulation of PLL in Ngspice -

![image](https://user-images.githubusercontent.com/87768763/137958612-385dd941-7b17-4857-8fcb-378d7b813f93.png)

B. Post Layout Simulations -

i. Phase Frequency Detector

![image](https://user-images.githubusercontent.com/87768763/137962106-f8f74955-9dfb-4f0d-90ce-135b4a4790e6.png)

![pfdpost](https://user-images.githubusercontent.com/87768763/137962181-aafd0e24-04e6-4aeb-9de1-8fdcab2133c1.png)

ii. Voltage Controlled Oscillator

![image](https://user-images.githubusercontent.com/87768763/137962264-d69039e6-013c-4513-a17e-e1e1a695c28b.png)

![vcofinal](https://user-images.githubusercontent.com/87768763/137962297-fa5cef00-7809-4147-a3a3-4e5cfba7b68b.png)

iii. Frequency Divider by 8

![image](https://user-images.githubusercontent.com/87768763/137962366-bb1ae54f-04a1-4f27-8ce2-0bcd00d617f9.png)

![freqdivpost](https://user-images.githubusercontent.com/87768763/137962388-7b26bf0b-3acd-45f8-afdb-10c7ae410af2.png)

iv. MUX 2:1

![image](https://user-images.githubusercontent.com/87768763/137962422-845ac4cb-5c43-415e-ad5d-828a6d0956e4.png)

![mux21](https://user-images.githubusercontent.com/87768763/137962457-eeffa5f8-dffd-432b-82d0-fae996d1ad41.png)

v. Phase Lock Loop (PLL)

![image](https://user-images.githubusercontent.com/87768763/137962519-f951e04e-237d-4f2c-8823-f9a1a4497187.png)

![image](https://user-images.githubusercontent.com/87768763/137962566-b0767ce7-bc23-414e-bffe-8b54fc7e9169.png)

![image](https://user-images.githubusercontent.com/87768763/137962596-9bd7ed86-0c4d-460d-ae57-6bb20c3ef2da.png)

C. Acknowledgments

Kunal Ghosh, Co-founder VSD Corp. Pvt. Ltd.

Paras Gidd, VSD Intern 

FOSSEE, IIT Bombay 

I would like to express my gratitude towards them for providing me with this opportunity.

