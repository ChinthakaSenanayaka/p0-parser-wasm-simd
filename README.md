# CAS-6TB3 project - Web Assembly partial arrays

## Build
Checkout this project to Jupiter Hub then run in this sequence.
- SC.ipynb
- ST.ipynb
- P0.ipynb
- CGWat.ipynb
- PartialFunction.ipynb

PartialFunction.ipynb has the main P0 code to run. CGWat.ipynb has WASM code generation and P0.ipynb has P0 language grammar and implementation.

project question.txt file has the question.

## TODO
Due to time limitation and scope of the change the following are set to TODO.
- For each loop is not working since allocVar function to generate local variables creates local variables in the beginning
	as WASM wants but for loop defines variables within loop block cannot be defined at the beginning.
- WASM SIMD is not added for the for each loops.