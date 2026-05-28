## SIMULATION OF 1kW SOLAR PV POWERED DC/DC BOOST CONVERTER UNDER OPEN LOOP CONDITION.

## AIM:

To simulate solar powered DC/DC boost converter using MATLAB Simulation and obtain the I-V and P-V characteristics by changing the duty cycle.

## APPARATUS REQUIRED:
 MATLAB 2021 or above 
 
## Theory:

DC-DC boost converters play a crucial role in solar power systems by efficiently increasing the voltage output of solar panels to match the requirements of the load or energy storage system. A boost converter, also known as a step-up converter, is a type of DC-DC converter that increases the output voltage level compared to the input voltage. It operates by storing energy in an inductor and then releasing it to the output at a higher voltage.

1.Input Voltage (Vin): The input voltage is the voltage supplied to the boost converter, typically coming from a source like a battery or a solar panel.

2.Switch (S): The switch is a semiconductor device, often a transistor or a MOSFET, that alternately connects and disconnects the input voltage to the rest of the circuit. It operates in a switching mode, where it is either fully ON (conducting) or fully OFF (non-conducting).

3.Inductor (L): The inductor is a coil of wire wound around a core. It stores energy in its magnetic field when the switch is ON and releases this energy to the output when the switch is OFF. The inductor plays a crucial role in boosting the voltage.

4.Diode (D): A diode is connected in parallel with the load (output) and allows current to flow in one direction only. It prevents backflow of current from the output to the input when the switch is OFF.

5.Output Voltage (Vout): The output voltage is the higher voltage level that you want to achieve.

<img width="431" height="263" alt="image" src="https://github.com/user-attachments/assets/3e552504-3da9-4bfa-a0b8-e18c1ea9a9fe" />

## CIRCUIT DIAGRAM:

<img width="1761" height="730" alt="image" src="https://github.com/user-attachments/assets/82085eda-9608-4251-b248-09485a902bcb" />



## Procedure:

1.Open MATLAB

2.From Simulink library browser, pick the following components

a.Solar Panel
b.Current and voltage measurement
c.MOSFET, Diode, Inductor and capacitor
d.RLC series load
e.Scope, display

3.Connect the Simulink library tools as shown in the circuit diagram.

4.Set the parameters as per the required design.

5.Simulate the work for the duty cycles from 10% to 80%.

6.Note the input and output side parameters and tabulate it.

7.Plot the I-V, P-V graph for the values obtained.

## OUTPUT:

<img width="1918" height="1198" alt="image" src="https://github.com/user-attachments/assets/d68f8b45-af68-4706-8052-637eb039c0c4" />


## RESULT: 
Thus, the solar powered dc/dc boost converter is simulated using MATLAB and the I-V and P-V graphs are plotted for various values of duty cycles.
    
