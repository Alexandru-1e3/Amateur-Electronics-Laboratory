      Amateur Electronics Laboratory

   In this project, I have design and build and electronics laboratory which helped me improve my productivity regarding
projects. It is composed of several working block that are interconnected, that also can be replaced rather easily if
necessary. Those boards are made up of.
      The light system that is directly connected to the mains, via a direct clamp connection. The lights can rather just be
turned on or off or their light intensity can be adjusted via a potentiometer. The circuit switches the LED strip at around
1kHz and with the potentiometer the duty cycle of the signal is changed thus the light intensity.
The main board is divider into to parts taking into the account the mains voltage that each equipment use. Many of the
tools are from the United States of America, and their nominal voltage is not the 230V rms, European standard, but
120V rms, American standard.
      An external 500W power step down transformer was needed, to drive those tools without damaging them. A big
inductor as a transformer comes with a big inrush current at startup, and this problem was solved with a soft started
circuit. The circuit consist in an Arduino based configuration that, reads the moments when the mains voltage passes
through 0. At that point the conde, via more control components, slowly increases the voltage at the gate of a TRIAC
and the overall voltage across the transformer is increased. The current also slowly increases from 0, thus the current
spike is avoided.
