# Regular Languages

## Overview
The purpose of this Jupyter Notebook is to showcase the usage of the `pyfoma` finite state library, a tool that is designed to work with finite state machines (FSM) and regular expressions. It explores how to create and manipulate finite state transducers (FSTs) for processing text, with a focus on validation and transformation.

## Features
- **Regular Expression Examples**: Demonstrations of how to define regular expressions using `pyfoma` for tasks such as date validation.
- **Unit Testing**: Inclusion of `ipytest` for running unit tests directly within the notebook.

## Usage
- Execute notebook cells sequentially from top to bottom.
- Users can modify the regular expressions or Python functions to experiment with different FST behaviors.
- The notebook includes predefined tests that can be run to ensure the regular expressions perform as expected.

## Prerequisites
- Python 3.x
- Jupyter Notebook or JupyterLab

## Input
Users can input various strings to test against the defined regular expressions, checking for patterns such as valid dates.

## Output
- **Validation Results**: Whether the input strings match the patterns defined by the FSTs.
- **Test Results**: Outputs from running the unit tests included in the notebook.

## Notes
- It might be necessary to restart the Jupyter kernel after installing new packages to ensure they are properly loaded.
- Links to extra documentation on `pyfoma` and its capabilities are included for more in-depth exploration.