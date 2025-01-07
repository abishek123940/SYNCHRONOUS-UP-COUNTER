**NAME : S ABISHEK**

**REG NO: 24900833**

**EXP NO 7:IMPLEMENTATION OF SYNCHRONOUS UP COUNTER**

 
**AIM:**

To implement 4 bit synchronous up counter and validate functionality.

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**4 bit synchronous UP Counter**

If we enable each J-K flip-flop to toggle based on whether or not all preceding flip-flop outputs (Q) are “high,” we can obtain the same counting sequence as the asynchronous circuit without the ripple effect, since each flip-flop in this circuit will be clocked at exactly the same time:

![image](https://github.com/naavaneetha/SYNCHRONOUS-UP-COUNTER/assets/154305477/d5db3fa0-e413-404c-b80e-b2f39d82e7e8)


![image](https://github.com/naavaneetha/SYNCHRONOUS-UP-COUNTER/assets/154305477/52cb61eb-d04b-442d-810c-31185a68410b)

Each flip-flop in this circuit will be clocked at exactly the same time.
The result is a four-bit synchronous “up” counter. Each of the higher-order flip-flops are made ready to toggle (both J and K inputs “high”) if the Q outputs of all previous flip-flops are “high.”
Otherwise, the J and K inputs for that flip-flop will both be “low,” placing it into the “latch” mode where it will maintain its present output state at the next clock pulse.
Since the first (LSB) flip-flop needs to toggle at every clock pulse, its J and K inputs are connected to Vcc or Vdd, where they will be “high” all the time.
The next flip-flop need only “recognize” that the first flip-flop’s Q output is high to be made ready to toggle, so no AND gate is needed.
However, the remaining flip-flops should be made ready to toggle only when all lower-order output bits are “high,” thus the need for AND gates.

**PROCEDURE:**

1.Type the program in Quartus software

2.Compile and run the program.

3.Generate the RTL schematic and save the logic diagram.

4.Create nodes for inputs and outputs to generate the timing diagram.

5.For different input combinations generate the timing diagram.

**PROGRAM:**

![image](https://github.com/user-attachments/assets/e93ae3c6-19bf-4ace-86b4-259740ad362c)


**RTL LOGIC:**

![image](https://github.com/user-attachments/assets/f7527964-8052-41f4-8b59-9dd63900a976)


**TIMING DIAGRAM:**

![image](https://github.com/user-attachments/assets/542baff0-3244-4756-9934-129edb1b2e76)


**TRUTH TABLE:**

![image](https://github.com/user-attachments/assets/9571a2af-d326-4440-b1ef-dd5a8b7e3e23)


**RESULT:**

Thus to implement 4 bit synchronous up counter and validate functionality done successfully.
