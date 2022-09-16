# compiler
The Stealify Compiler Tooling

# DETERMENISTIC AOT Compiler

# AOT Compiler

# JIT Compiler

# Stealify Compiler
Stealify does introduse a new Compiler Paradigm compare able with the behavior of a multi pass AOT or JIT Compiler it can run in both modes
Stealify Compiler Toolkit uses AI Algorythms like bayesian to produce the correct result.

## What makes it diffrent?
It does not Compile CODE=>EXECUTEABLE it does Compile CODE=>RUNTIME_ENVIRONMENTS or to use a other Term Running Deployment. While it can be used to produce simple optimized Executables. 

lets look into a example:
rustc => ELF_BINARY (Linux)
Stealfiy Compiler => Docker,BAREMETAL,Cloud (Hybrid,Multi)
Stealify Compiler => AOT_BINARY_WITHRUNTIME

At the Most Raw Representation Stealify Is a data structure that is Language Indipendent which represents a serialized stack machine so a hash table
...header meta (engine kernel)
symbol or hash => value (modules components)

we mix the terminologie so strange because most people come from a linux or windows mac os Background Stealify is diffrent it uses the b8g concept which stands for big engine this implements a minimum runable binary foundation that is highly modular and able to do ITC (Inter Thread Communication) 

at present the compiler has this output flavors 
- graaljs graalvm-native-image, 
- llvm (v8) justjs api, 
- electron mksnapshot builds.
