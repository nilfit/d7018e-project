# D7018E - special studies in embedded systems
## Seer and program verification
Nils Fitinghoff, `nilfit-3@student.ltu.se`, 9412164130
## Project description
Many embedded systems are used in situations where incorrect behaviour can cause risk to human lives. Formal verification of programs is a powerful tool for ensuring correct behavior. The process of verifying a program can be cumbersome, but the burden can be eased using tools that automate some steps. The project aims to improve the tools for program verification in Rust, based on [seer](https://github.com/dwrensha/seer), a symbolic execution engine for MIR, the mid-level internal representation of the Rust compiler.

Because of the limited time allotted to the project, the scope will be limited to generating verification conditions for loops using annotations that state loop invariants. In order to reach this goal, it is neccessary to

* Study and understand the Z3 API
* Study and understand the Seer API
* Study and understand MIR
* Study outsets for program verification using Seer

## Grading goals
For grade 3:

* Understand and use the Z3 API
* Understand and use the Seer API

For grade 4:

* Evaluate the possibilities and limitations in using Seer for formal verification

For grade 5:

* Create a proof-of-concept that uses Seer to generate input for Z3 to verify correctness of loops
