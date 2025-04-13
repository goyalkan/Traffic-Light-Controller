This project simulates a 2-way traffic light controller using Finite State Machine (FSM) logic written in Verilog HDL.
The module controls traffic signals for two roads (A and B), where only one road can be green at a time. 
The system cycles through:
        Green → Yellow → Red for Road A,
        then Green → Yellow → Red for Road B,
        and the cycle repeats...

All timing is based on a clock input and an internal counter.
