# micrograd
Karpathy's micrograd - 20th Summer Project by Han 2024 

This is my note on learning micrograd. 
Written in Indonesian+English

Mistakes made during learning:
    1. Forgot to add radd => reverse add to the class so when summing up the forward pass it gets error
    2. Forgot to **reset gradients** before each backward pass since the backward pass accumulates +=, it will accumulate all passes not changing each gradient for each pass/iteration


Noted and Created by Han Summer 2024

Part of The 20th Summer Project
