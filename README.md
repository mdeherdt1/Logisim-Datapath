# Logisim Datapath

A 12-bit processor built from scratch in [Logisim](http://www.cburch.com/logisim/), starting at single logic gates and ending with a fully working datapath that executes instructions.

Coursework for Computer Architecture — Group 33.

## Projects

| # | Project | What it covers |
|---|---------|----------------|
| 1 | Gates and Wires | Truth tables, SOP expressions and basic gate circuits |
| 2 | Adders | Ripple-carry, carry-lookahead and carry-select adders |
| 3 | ALU | 12-bit ALU: arithmetic, logic, shifts and comparisons |
| 4 | Memory | Registers, register file, counters and timing diagrams |
| 5 | S Datapath | Simple datapath: PC, memory, ALU and control signals |
| 6 | F Datapath | Full datapath with control unit, branches and jumps |

Each folder contains the Logisim circuits (`.circ`), a written report (`Verslag.html`) and screenshots of the schematics.

## Getting started

Logisim is included in the later project folders (`logisim-generic-2.7.1.jar`) and needs Java.

```bash
java -jar "Project 6 F Datapath/logisim-generic-2.7.1.jar"
```

Then open a `.circ` file, e.g. `Project 6 F Datapath/FD_Group33.circ`.

> Keep the circuit files of a project in the same folder — the datapath loads the ALU and adder circuits as sub-circuits.

## Testing

Projects 3, 5 and 6 come with a Python test script and test files:

```bash
cd "Project 6 F Datapath"
python Test_2324_zit1_datapath.py
```

The `*_test.txt` files cover arithmetic, boolean, shift, comparison, memory, branch and jump instructions, plus a set of integration tests.

## Reports

Open any `Verslag.html` in a browser for the design decisions, schematics and truth tables behind each project.
