# Automatic Street Light Control System using LDR
An **Automatic Street Light System** that turns **ON lights at night** and **OFF during the day** using an **LDR (Light Dependent Resistor)** and a **transistor switch**.  
This system is designed to **save energy** and eliminate the need for manual operation.

## Working Principle of the Circuit
The automatic street light circuit works based on **the change in LDR resistance** with light intensity.
### During Day time (Light Present)
- When bright light falls on the LDR, its **resistance becomes low**.  
- Very little voltage reaches the **base (B)** of the **transistor (A2222)**.  
- The transistor remains **OFF**, preventing current from flowing to the LEDs.  
- Therefore, **LEDs stay OFF**.
### During Night time (Darkness)
- When it becomes dark, the **LDR resistance increases**.  
- Voltage across the LDR rises, sending a higher base current to the transistor.  
- The transistor turns **ON** (acts as a closed switch).  
- Current flows from the battery to the LEDs, and **LEDs turn ON** automatically.
  
## Components Used
| Component | Description |
|------------|-------------|
| **9V Battery** | Supplies electrical power to the circuit |
| **Transistor (A2222)** | NPN transistor acting as an electronic switch |
| **Resistor (1KΩ)** | Limits base current and forms a voltage divider with LDR |
| **LDR (Light Dependent Resistor)** | Senses light intensity |
| **LEDs** | Represent street lights that turn ON/OFF automatically |
| **Connecting Wires** | Used to connect circuit components |

## Circuit Explanation
The **LDR and 1K resistor** form a **voltage divider** that determines how much voltage goes to the transistor’s base:
- When light intensity is high → base voltage is low → transistor OFF → LEDs OFF  
- When light intensity is low → base voltage is high → transistor ON → LEDs ON
Thus, the **LDR acts as the light sensor**, and the **transistor as the automatic switch**.

## Conclusion
This project provides a **simple, low-cost, and efficient** way to control street lights automatically.  
It helps **save electricity**, reduces **manual labor**, and ensures reliable **day/night light control** using basic electronic components.

