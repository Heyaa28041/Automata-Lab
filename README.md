# Automata-Lab
ATM Transaction Simulator using Finite State Machine (FSM)

# Overview

This project implements an ATM transaction workflow using a Finite State Machine (FSM). The simulator models the logical sequence of ATM operations and ensures that transitions occur only in the correct order. The system prevents invalid actions and visually demonstrates state transitions in an interactive web interface.

This project illustrates the real-world application of automata theory in modeling ATM transaction systems.

# Features

1. Finite State Machine based ATM workflow
2. Card insertion simulation
3. PIN authentication state
4. Transaction selection
5. Cash withdrawal simulation
6. Session termination
7. Invalid transition prevention
8. Interactive visual state highlighting
9. Web-based simulator
10. FSM States

# The system consists of the following states:

1. Idle State
2. Card Inserted
3. PIN Entered
4. Transaction Selected
5. Cash Dispensed
6. Session End

Each state transitions only through valid user actions.

# Technologies Used
HTML
CSS
JavaScript
Finite State Machine (FSM) Logic

# How to Run
Download or clone the repository
Open the HTML file in any browser
Use the buttons to simulate ATM operations
Observe state transitions visually

# Project Structure
ATM-FSM/
|-Code.html
│-README.md

# Working Logic

The system starts in the Idle state.
When the card is inserted, it moves to PIN authentication.
After correct PIN entry, the user selects a transaction.
Upon withdrawal selection, cash is dispensed.
Finally, the session ends and returns to Idle state.

Invalid transitions are blocked by FSM rules.

# Contributors

1. Pakhi Mittal

Designed FSM model
Defined states and transitions, 
Implemented JavaScript FSM logic, 
Integrated UI with state transitions, 
Implemented dynamic state highlighting, 
Debugged transition validation

2. Priyasha Das

Developed HTML structure, 
Designed UI using CSS, 
Assisted in UI integration, 
Tested transaction flows, 
Documentation support

# Application
1. ATM workflow simulation
2. Automata theory demonstration
3. FSM learning tool
4. Educational visualization
