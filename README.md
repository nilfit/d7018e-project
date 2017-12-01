# D7018E - special studies in embedded systems
## Seer and program verification
Nils Fitinghoff, `nilfit-3@student.ltu.se`, 9412164130
## Project description
Many embedded systems are used in situations where incorrect behaviour can cause risk to human lives. The project aims to improve the tools for analysing programs in Rust, centered around [Seer](https://github.com/dwrensha/seer), a symbolic execution engine for MIR, the mid-level internal representation of the Rust compiler.

More specifically, the project will look at

* Generating call graphs
* Using Seer to generate test cases
* Using Seer to compute coverage and find dead code 

## Grading goals
For grade 3:

* Understand and use the Z3 API
* Understand and use the Seer API
* Understand MIR

For grade 4:

* Evaluate the benefits and limitations in using Seer for these purposes

For grade 5:

Create a tool that

* Detects dead code using symbolic execution
* Computes coverage
* Generates a call graph
