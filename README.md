### NAME : PRAJAN SS
### REG NO : 24009412
# EXPERIMENT :  IMPLEMENTATION OF JK FLIPFLOP 

# AIM: 

To implement  JK flipflop using verilog and validating their functionality using their functional tables

# SOFTWARE REQUIRED:

Quartus prime

# THEORY

# JK Flip-Flop

JK flip-flop is the modified version of SR flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of JK flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/a649c30b-232b-4558-b188-fd6c09845180)


This circuit has two inputs J & K and two outputs Qtt & Qtt’. The operation of JK flip-flop is similar to SR flip-flop. Here, we considered the inputs of SR flip-flop as S = J Qtt’ and R = KQtt in order to utilize the modified SR flip-flop for 4 combinations of inputs. The following table shows the state table of JK flip-flop.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/c4360742-e8a8-4937-b089-c46c0433f9a3)

 
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, JK flip-flop can be used for one of these four functions such as Hold, Reset, Set & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of JK flip-flop. Present Inputs Present State Next State
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/6c275261-a6d5-4c37-a3a7-1e88ca11c4cd)

By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. Three variable K-Map for next state, Qt+1t+1 is shown in the following figure.
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/5174f41b-0ce0-4329-a372-6d1943ea6673)

The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=JQ(t)′+K′Q(t)Q(t+1)=JQ(t)′+K′Q(t)

# Procedure

Implementing JK_flipflop in Verilog HDL (Hardware Description Language) involves translating the
simplified Boolean expressions into Verilog code to describe the behavior of digital circuits. The
basic building blocks in Verilog is module. The module represent a combinational circuit. Use
logical operators (&, |, ~, ^) to implement Boolean functions directly. Use built-in gate primitives
for basic functions. Use University program VWF to verify the functionality of your Verilog modules.
Create waveform and check outputs against expected results.

# PROGRAM

![Screenshot 2024-12-09 112817](https://github.com/user-attachments/assets/9ed1147b-a9c2-4ff0-8052-ec5bab557f31)


/* Program for flipflops and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/

# RTL LOGIC FOR FLIPFLOPS

![Screenshot 2024-12-09 112827](https://github.com/user-attachments/assets/54e3cf5b-3904-4f20-b206-080266de536b)


# TIMING DIGRAMS FOR FLIP FLOPS

![Screenshot 2024-12-09 112837](https://github.com/user-attachments/assets/b7a26780-66d7-4248-96e9-08f3c5c73544)


# RESULTS

Implemented JK flipflop using verilog and validating their functionality using their functional tables
