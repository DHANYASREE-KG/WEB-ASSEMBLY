# Fibonacci Calculator — JavaScript and WebAssembly (WASM)

## Overview

This project demonstrates Fibonacci calculation using both normal JavaScript and WebAssembly (WASM). It shows execution time and compares the two methods.

## Features

- User input for Fibonacci term.
- Displays result and execution time.
- WASM module compiled from `.wat` using `wat2wasm`.
- Tested with Google Colab.

## How to Use

1. Open the HTML file in a browser.
2. Enter a number (0 to 40 recommended).
3. Click "Calculate" to see Fibonacci and time for JS or WASM.

## Notes

- Recursive Fibonacci is slow for large inputs.
- Input limit of 40 avoids long computations.
- WASM offers faster numeric execution but depends on implementation.

