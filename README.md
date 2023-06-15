# PythonEVMCompiler
An EVM/EVMMax mini-compiler written in python.

The compiler's goal is to be able to optimise EVM-contracts at the low-level of Op-codes from an easy-to-use python interface.
It also allows to test EVM extensions such as EVMMax (extra opcodes for efficient modular arithmetics).

The compiler is in Alpha stage and can still evolve dramatically. It includes :

   1. A simple alloc-once Memory Allocator for variables and tensors.
   2. A Jump-Table and address resolver.
