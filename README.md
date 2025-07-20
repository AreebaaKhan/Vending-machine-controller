# Vending-machine-controller
Tools:
Electronic Workbench or Multisim

🧃 Vending Machine Controller – FSM Simulation
This project simulates a vending machine controller designed using Finite State Machine (FSM) logic. It accepts coins of Rs. 10, Rs. 20, and Rs. 50 to dispense an item worth Rs. 30, and returns the remaining amount when required.

🔧 Inputs
Two binary inputs represent coin values:

Input (X, Y)	Coin Value
00	Rs. 10
01	Rs. 20
10	Rs. 50
11	Don't Care

⚙️ Simulation Overview
The circuit is implemented using 7476 JK flip-flop ICs to hold the current state of the FSM.

A clock pulse (shown in red bulbs) triggers the state change.

State transitions are indicated by the blue bulb (Q1).

When Rs. 30 or more is inserted:

The "DISPENSE ITEM" output turns ON.

If Rs. 50 is inserted, the "RETURNED AMOUNT" output also turns ON.

FSM resets after dispensing.

▶️ How to Use the Simulation
Open the provided Proteus simulation file.

Use the switches labeled X and Y to select the input coin:

e.g., X = 0, Y = 1 → Rs. 20

Press the clock switch to generate a pulse.

Observe:

The blue bulb shows the FSM state transition.

"DISPENSE ITEM" glows when Rs. 30 is collected.

"RETURNED AMOUNT" glows if Rs. 50 is entered.
