# Create Reports

## Description

Log data about deuplicate records generated by the "dedupe" step.

## Requirements

### Objectives

- Create Log table if it doesn't already exist.
- Wire up the ability to export logs from the dedupe process step.

The output from `pandas-dedupe` is a CSV stored at the root of its project folder. The logging step will include:
- Parsing the CSV.
- Adding additional information (foreign keys for our DB, for example).
- Writing results to the `log` table in our POC.

Reference the supplemental story "Defining_Logs.md" for the shape of log data.

### Constraints

- N/A

## Resources

Reference the supplemental story "Defining_Logs.md" for the shape of log data.

## Documentation Protocol
First, include a readme that describes what your code does and explains difficult bits.

Second, use descriptive variables and method names so that the code is readable and obvious.

Third, comment each function or method along with inputs and returns, and use other inline comments to make particularly opaque or unavoidably clever code clear.

A story is absolutely __not__ complete until time has been spent at the end revewing, updating, and tidying up documentation.

## Get Help
Questions? Check around to see who's available, and ask:
- cskyleryoung
- devcshort
- greggish

### Washington State Resource Data SiloBuster 08/2022