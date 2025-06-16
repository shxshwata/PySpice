# PySpice
project on pyspice on jupyter nb

# How does PySpice help in the study of core electronics

PySpice helps in understanding core electronics by offering a Python-based interface to simulate and analyze electronic circuits using the well-established SPICE simulation engine.
	One can build and simulate analog and digital circuits directly in Python without needing physical hardware like breadboards or a lab setup. Voltages, currents and waveforms can be visualized. Any value and configuration is safe to experiment with.
	We can tweak parameters dynamically and re-run to check the outputs. This helps to build our intuition about how circuits behave under changes. We can simulate KVL/KCL and immediately see how voltages and currents distribute. We can also see how capacitors charge and discharge or inductors build current over time. It also helps in understanding RC, RL, RLC time constants and comparing analytical vs simulated results. For example: to watch exponential charging of a capacitor and relate it to: V(t)=V0​(1−e−t/RC). 
	It helped with the visualisation of Bode plots, cutoff frequency and how circuits behave with sinusoidal inputs: phase shift, gain and resonance. We also simulated non-linear devices which include diodes, BJTs, MOSFETs and observed I-V characteristics.
