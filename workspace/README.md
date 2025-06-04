# Workspace

This directory is used to store workspace-specific files for experimenting with generating output from any file type.

## Structure

The structure of this directory is as follows:

- `[name]/`: Directory for a specific experiment.
    - `input/`: Directory for input files.
    - `expected_output/`: Directory for expected output files (e.g., AST in NDJSON format).

## Example

- `qa/`: Experiment for Question/Answer pairs.
    - `input/`: Contains `.txt` files with Q&A pairs.
    - `expected_output/`: Contains `.ndjson` files with the expected AST.