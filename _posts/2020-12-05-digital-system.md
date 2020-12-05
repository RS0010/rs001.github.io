# **Binary Number Representation**
<!-- * ### 1.1 Introduction to Digital Systems
 * Digital systems are those that handle information encoded in binary form.
* ### 1.2 Digital circuits and Waveforms
 * -->
* ### Terms
 * ##### MSB
     * Most Significant Bit
 * ##### LSB
     * Least Significant Bit
* ### Binary-decimal conversion
* ### Dealing with Fractions
* ### Binary Arithmetic
* ### Dealing with Negative Numbers
 * ##### 1's complement
 * ##### 2's complement
* ### converting Signed Numbers to Decimal
* ### Hexadecimal Representation
* ### Binary Codes
 * ##### BCD
    * 8421
    * 2421
 * ##### Gray code
 * ##### ASCII code

# **Bolean Logic & Basic Gates**
 * ### Boolean Logic
  * ##### truth table
 * ### Basic Logic Gates
  * ##### The NOT gate
  * ##### The AND gate
  * ##### The OR gate
  * ##### The NAND gate (NOT-AND)
  * ##### The NOR gate (NOT-OR)
  * ##### The XOR gate (Exclusive-OR)
  * ##### The XNOR gate (Exclusive-NOR)

* ### Preliminary Definitions
 * ##### canonical truth table
 * ##### variable
 * ##### complement
 * ##### literal
 * ##### canonical product term
 * ##### canonical sum term
 * ##### canonical expression
 * ##### sum-of-products (SOP)
 * ##### product-of-sums (POS)
 * ##### simplified or minimised Boolean function

# **Boolean Minimisation Using Boolean Algebra**
 * ### Boolean Analysis of Logic Circuits
 * ### Boolean Algebra – Rules and
   * ##### properties of the OR gate
     >A + 0 = A  
     >A + 1 = 1  
     >A' + A = A  
     >A + A = A
   * ##### properties of the AND gate
     >A · 0 = 0  
     >A · 1 = 1  
     >A' · A = 0  
     >A · A = A  
   * ##### property of the NOT gate
     >A = A

     >A + AB = A  
     >A (A + B) = A  
     >A + AB= A + B  
   * ##### Commutative – order of variables does not matter when using the AND and OR operations
     >A + B = B + A  
     >A · B = B · A
   * ##### Associative – the result of applying an operation over 3 variables is not affected by the order taken
     >A (BC) = (AB) C  
     A + (B + C) = (A + B) + C
   * ##### De Morgan’s theorems
    >(A + B) = A'  · B'  
    >(AB)'  =A' + B'

* ### Boolean Algebra – Minimisation

# **Boolean Minimisation Using Karnaugh Maps**
* ### Minterms and Maxterms
* ### Don't Care Conditions

# **Implementation Using NAND / NOR Gates**
* ### Universal Gates
   * NOT gate using NAND
   * NOT gate using NOR
   * AND gate using NAND
   * AND gate using NOR
   * OR gate using NOR
   * OR gate using NAND
* ### Implementing Logic using NAND / NOR gates

# **Sequential Logic & Flipflops**
* ### Combinational & Sequential Logic
  * ##### Combinational logic
  * ##### Sequential logic
  * ##### synchronous
  * ##### asynchronous
* ### The Asynchronous SR Flipflop
* ### Clocked version of the SR Flipflop
* ### The D (Data) Flipflop
* ### The JK Flipflop
* ### The T (Toggle) Flipflop
* ### Flipflops v Latches
* ### Master-Slave Flipflops
* ### Asyuchronous inputs
 * ##### asynchronous inputs
   * preset (PRE)
   * clear (CLR)
* ### Application Examples
 * ##### Contact bounce
 * ##### Frequency division

#  **Counters & Registers**
* ### Counter
* ### Registers

# **Multi-Output Networks & 7-Segment Displays**
* ### Multi-output Minimisation
* ### The 7-segment display
  * ##### Common Cathode Mode
  * ##### Common Anode Mode
  * ##### BCD to 7-segment decoder

# **Programmable Logic Devices (PLDs)**
* ### Read Only Memory (ROM)
* ### Programmable Logic Array (PLA)
* ### Programmable Array Logic (PAL)
