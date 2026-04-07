# Telemetry Data Converter

## About the Project
This project is about converting telemetry data from two different JSON formats into a single, unified format.

Both input files represent the same data but are structured differently. The goal was to read each format and transform it so that the final output matches a common structure.

---

## What I Did
- Read JSON data from files
- Handled two different input formats
- Extracted and mapped required fields
- Converted ISO timestamp into milliseconds (epoch time)
- Structured the output exactly as required
- Verified the solution using unit tests

---

## Files in the Project
- main.py → contains the logic and test cases  
- data-1.json → first input format  
- data-2.json → second input format  
- data-result.json → expected output format  

---

## How to Run
Make sure Python is installed, then run:

```bash
py main.py
