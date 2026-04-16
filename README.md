# Production Line Calculator (P03)

A x86 Assembly Language (MASM) program that determines the number of production lines needed to meet a required output amount and calculates the total input materials required per minute for each of the 5 input types.

**Author:** DN MBOYI  
**Student Number:** 222019179  
**Practical:** P03  
**Course:** Assembly Language Programming

---

## Problem Description

The program performs the following tasks:

- Accepts the **Required Output Amount**
- Accepts the **Output Per Minute** per production line
- Accepts **5 different Input Per Minute** values (one for each input material)
- Calculates the **minimum number of production lines** required (rounding up if necessary)
- Calculates the **total required input** for each of the 5 materials based on the number of lines
- Displays all results in a clean, formatted manner
- Allows the user to run the program multiple times

---

## Features

- User-friendly console input prompts with clear numbering
- Proper array handling for 5 input materials
- Correct ceiling division for number of production lines
- Formatted output with brackets and commas (e.g. `[10, 20, 30, 40, 50]`)
- Loop to allow multiple calculations in one run
- Clean and structured code with meaningful labels

---

## Technologies Used

- **Assembly Language** (x86)
- **MASM** (Microsoft Macro Assembler)
- **io.inc** library for input/output

---

## How to Run

1. Open the project in **Visual Studio** with MASM support enabled
2. Build the solution
3. Run the executable (`.exe`)
4. Follow the on-screen prompts:
   - Enter Required Amount
   - Enter Output Per Minute
   - Enter the 5 Input Per Minute values

---


