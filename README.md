# HDLBits Solutions

My solutions to every problem on [HDLBits](https://hdlbits.01xz.net/), written in Verilog, starting from the very first problem and updated day by day.

Each solution file begins with a short comment block explaining the problem, my approach, and anything that tripped me up. Each problem folder also holds screenshots of my submission and, where available, my handwritten notes.

## Progress

| # | Problem | Section | Solution | Notes |
|---|---------|---------|----------|-------|
| 000 | Getting Started | Getting Started | [code](000_getting_started/top_module.v) | — |
| 001 | Output Zero | Getting Started | [code](001_output_zero/top_module.v) | — |
| 002 | Simple wire | Verilog Language > Basics | [code](002_simple_wire/top_module.v) | — |
| 003 | Four wires | Verilog Language > Basics | [code](003_four_wires/top_module.v) | — |
| 004 | Inverter | Verilog Language > Basics | [code](004_inverter/top_module.v) | — |
| 005 | AND gate | Verilog Language > Basics | [code](005_and_gate/top_module.v) | — |
| 006 | NOR gate | Verilog Language > Basics | [code](006_nor_gate/top_module.v) | — |
| 007 | XNOR gate | Verilog Language > Basics | [code](007_xnor_gate/top_module.v) | — |
| 008 | Declaring wires | Verilog Language > Basics | [code](008_declaring_wires/top_module.v) | — |
| 009 | 7458 chip | Verilog Language > Basics | [code](009_7458_chip/top_module.v) | — |
| 010 | Vectors | Verilog Language > Vectors | [code](010_vectors/top_module.v) | — |
| 011 | Vectors in more detail | Verilog Language > Vectors | [code](011_vectors_in_more_detail/top_module.v) | — |
| 012 | Vector part select | Verilog Language > Vectors | [code](012_vector_part_select/top_module.v) | — |
| 013 | Bitwise operators | Verilog Language > Vectors | [code](013_bitwise_operators/top_module.v) | — |
| 014 | Four-input gates | Verilog Language > Vectors | [code](014_four_input_gates/top_module.v) | — |

## Folder layout

```
hdlbits-solutions/
├── README.md
├── .gitignore
├── 000_getting_started/
│   ├── top_module.v
│   ├── code.png
│   ├── timing.png
│   └── notes.jpg
├── 001_output_zero/
│   └── ...
└── ...
```

Every problem folder uses the same file names:

- `top_module.v`: the solution, with a comment header (problem, section, link, goal, approach, gotchas)
- `code.png`: screenshot of my submission
- `timing.png`: screenshot of the timing diagram or result
- `notes.jpg`: my handwritten notes (added once posted)

## Tools

Solutions are checked on the HDLBits site. For sequential and FSM problems I may also add a local testbench simulated with Icarus Verilog.
