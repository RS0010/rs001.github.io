
---

# **Introduction**

## outline
**Introduction and Motivation**: Electronics in Society, Scientific Notation and Exponents,Engineering Notation  
**Basic Electromagnetics**: Charge, Vectors and Coulombs Law and Applications  
**Electricity**: Voltage and Current, Resistance and Conductance, Resistivity, Fundamental  
Relations: Ohm’s Law, Energy, Power  
**Very Simple Circuit Analysis**: Voltage Division, Current Division, Series and Parallel Circuits  
**More Circuit Analysis**: Kirchhoff’s Laws, Circuit Theorems, Source Transformations: Thevenin’s Theorem & Norton’s Theorem  
**Even more circuits analysis**: Multiloop Circuits, Nodal Analysis, Mesh Analysis  
**Basic Electronics**: Ideal Diodes, Transistors, simple circuits  
**Electrical Safety**: at home and at work  
**The Environment, Social Responsibility**: the impact of our decisions on our peers and the environment  
**Communication**: communication networks, principles of wireless communications, receivers and transmitter  

## Engineering Notation
* Scaling units(down)
  * **m** milli (10<sup>-3</sup>)
  * **μ** micro (10<sup>-6</sup>)
  * **n** nano (10<sup>-9</sup>)
  * **p** pico (10<sup>-12</sup>)
  * **f** femto (10<sup>-15</sup>)
* Scaling units(up)
  * **k** kilo (10<sup>+3</sup>)
  * **M** mega (10<sup>+6</sup>)
  * **G** giga (10<sup>+9</sup>)
  * **T** terra (10<sup>_12</sup>)

## Fundamental Units
1. Kilogram (**kg**): the unit of mass.
2. Ampere (**A**): the unit of current.
3. Metre (**m**): the unit of distance.
4. Second (**s**): the unit of time.
5. Kelvin (**K**): the unit of heat.
6. Mole (**mol**): the unit of amount of a substance.
7. Candela (**cd**): the unit of light.

## Derived Engineering Units
1. Watt (**W**): the unit of power. (m<sup>2</sup>·kg·s<sup>−3</sup>)
2. Newton (**N**): the unit of force. (m·kg·s<sup>−2</sup>)
3. Joule (**J**): the unit of energy, heat. (m<sup>2</sup>·kg·s<sup>−2</sup>)
4. Hertz (**Hz**): the unit of frequency. (s<sup>-1</sup>)
5. Celsius (**℃**): an unofficial unit of heat. (K - 273.15)
6. Coulomb (**C**): the unit of electric charge. (s·A)
7. Volt (**V**): the unit of voltage, potential difference. (m<sup>2</sup>·kg·s<sup>−3</sup>·A<sup>−1</sup>)
8. Ohm (**Ω**): the unit of electrical resistance. (V·A<sup>-1</sup>)
9. Farad (**F**): the unit of electrical capacitance. (C·V<sup>-1</sup>)
10. Siemens (**S**): the unit of electrical conductance. (Ω<sup>-1</sup>)
11. Henry (**H**): the unit of electrical inductance. (V·s·A<sup>-1</sup>)

---

# **Electrostatics**

## Electricity
Phenomenon of electric charge in motion.

## Charge
an electrical property of the atomic particles of which matter consists and it is measured in coulombs (**C**).
* Charge *is conserved*. It may move but it cannot be destroyed.
* Charge *is quantised* and it comes in units of electron charge, which means that we can’t break an electron.
>* **Conductors** (eg metal) are very good at facilitating the movement of
electrons.
>* **Insulators** (eg plastic) resist the movement of electrons.

## Forces between Charges
* Similar charges repel
* Opposite charges attract
### Coulomb’s Law
* ![Coulomb’s Law](https://s3.ax1x.com/2021/01/06/sAcveU.jpg)
  * **k** = 8.987×10<sup>9</sup> *Nm* <sup>2</sup>C<sup>-2</sup> Coulomb's Constant
  * ***ε***<sub>0</sub> = 8.854×10<sup>-12</sup> *Fm* <sup>-1</sup> Free Space Permitivity
* The effect of multiple charges are added in **vectorised** form.
* Actually all forces act on **each other**!

## Electric Field
Defined as the electric force per unit charge. The direction of the field is taken to be the direction of the force it would exert on a positive test charge.
* ![Electric Field](https://s3.ax1x.com/2021/01/06/sAgonK.jpg)
* Direction of the electric field is the same as the direction of the electric force if q is positive.

### Different Electric Fields
An infinitely long charged wire
* ![An infinitely long charged wire](https://s3.ax1x.com/2021/01/06/sAgj1I.jpg)

A charged sheet
* ![A charged sheet](https://s3.ax1x.com/2021/01/06/sAgxjP.jpg)

Parallel Plates
* ![Parallel Plates](https://s3.ax1x.com/2021/01/06/sA2Snf.jpg)

## Electric Flux (**Φ**)
Defined as the electric field times the component of the area perpendicular to the field.
* For a point charge, the electric field radiate evenly from that point. If we define a sphere enclosing the point, then all electric field lines are perpendicular to the surface. Then all you need to do is calculate the field and multiply by the area.
* ![Electric Flux](https://s3.ax1x.com/2021/01/06/sA2nBT.jpg)
  * The total electric flux is independent of sphere radius and is only dependent on Q. This can be generalised to Gauss’ Law.

### Gauss' Law
The total of the electric flux out of a closed surface is equal to the
charge enclosed divided by the permittivity.
* ![Gauss' Law](https://s3.ax1x.com/2021/01/06/sA2l4J.jpg)
* If the net charged enclosed is zero, then the electric flux is zero. This is something that is used a lot in practice.

### Example
* ![Example](https://s3.ax1x.com/2021/01/06/sA2I8s.jpg)

## Electro-potential Difference
* ![Electro-potential Difference](https://s3.ax1x.com/2021/01/06/sA2qbT.jpg)
  * To move the charge Q against the “**electric field**” requires work.  
  * As I push it up the electric field, I’m giving *potential energy* to the charge.  
  * **Define**: Electrical “potential difference” or voltage between two points in an electrical field is defined as the work per unit charge required to move between those two points.  
    * voltage = work/Q  
    * voltage = electric field * distance

---

# **Current, Voltage and Resistance**

## Ohm’s Law
Ohm’s law states that the current (I) through a resistive path is
directly proportional to the potential difference or voltage (V)
across the two points, and inversely proportional to the
resistance (R) between them.
* ![Ohm’s Law](https://s3.ax1x.com/2021/01/06/sARCKx.jpg)

### Electrical Power
* ![Electrical Power](https://s3.ax1x.com/2021/01/06/sARkVO.jpg)
  * This (and Ohm’s Law) are fundamental equations.
  * **You will need to always know these equations!**

## Some Rules for Circuits and Resistors
**Rule 1**: All points on a wire are assumed to be the same point as the wire
has perfect conductivity.  
**Rule 2**: A point in the circuit where 2 or more components are connected is called a node. A 2-path **node** is trivial, the more interesting ones are 3 or more (*note that ground is always a node*).  
**Rule 3**: All circuits must have at least one loop so that current can flow back to where it started.  
**Rule 4**: If 2 circuit elements are connected only by a **2-path node** (ie a wire), then they are said to be in **SERIES**.  
**Rule 5**: If 2 or more circuit elements are connected between the same nodes, then they are said to be in **PARALLEL**.  
**Rule 6**: If the current must pass through two resistors (assuming that there is no other path of escape), then the total voltage drop is shared across the two resistors. (SERIES)  
**Rule 7**: If the voltage across two resistors is equal, then the current in each path is inversely proportional to the resistance in each path. (PARALLEL)  

**Node** is a **point** in the circuit where two or more elements are connected.  
**Branch** is a **single component**, such as resistor/source.In other words,
a branch represents any two-terminal element.
**loop** is a **closed path** through a circuit that visits each element no more than once.

## Measuring Current and Voltage
* **Ohmmeters** : measure resistance.
* **Voltmeters** : sense the voltage difference between two points.
* **Ammeters**: measure the current flowing through a wire.

## Drawing schematics and circuits
**Schematic** is the term for the diagram that represents an electrical circuit.
1. Wires in schematics are deemed to be ideal.
2. It should not matter how the schematic is drawn, but it does.
3. It is good practice to draw a schematic to enhance understanding as much as possible – there are some guidelines on good practice.
* ![symbols](https://s3.ax1x.com/2021/01/06/sARzTS.jpg)
  * Use the right symbols, give them labels (R1, C3, X2)
* Try to use a vertical/horizontal drawing plan, not one with random orientations.
* Space the elements well apart, keep it visually simple!
* If two wires are connected, show it with a solid dot! Two crossing wires are often assumed to be connected, but best to be sure.
* If two wires are passing each other but not connected, a dot is not used and where possible, a bridge is shown. It is best to minimise cross-overs where possible.

### Rules
* Always note the voltage supplies and earth on the schematic.
* Place the battery/power source to the left hand side of the schematic (not always possible).
* Try to place parallel and series circuit elements and sections of circuits in vertical/horizontal modular forms.
* Place the positive voltage to the top, ground to the bottom.
* Mark wire connections clearly, and label them.
* Wires connect and bend at right angles (90o).
* Use correct symbols and appropriately label components (try to list component values on the schematic if space permits).
