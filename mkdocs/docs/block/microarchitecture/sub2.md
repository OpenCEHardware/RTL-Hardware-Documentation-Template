# Submodule 2

## Description

Provide a description of the submodule here. Explain its function, role within the larger system, and any important design considerations or features.

## I/O Table

Detail the submodule's input and output signals, including their name, direction, type, and description.

### Input Table

| Input Name           | Direction | Type    | Description                    |
|----------------------|-----------|---------|--------------------------------|
| `input_signal_1`     | Input     | `logic` | Description of `input_signal_1`|
| `input_signal_2`     | Input     | `logic` | Description of `input_signal_2`|

### Output Table

| Output Name          | Direction | Type    | Description                    |
|----------------------|-----------|---------|--------------------------------|
| `output_signal_1`    | Output    | `logic` | Description of `output_signal_1`|
| `output_signal_2`    | Output    | `logic` | Description of `output_signal_2`|

## Submodule Diagram

Include a diagram of the submodule here, showing its inputs, outputs, and how they are connected internally. Ensure the diagram is clear and properly labeled to facilitate understanding.

{!diagrams/sub1.html!}

## SystemVerilog Implementation

Include a brief description of the SystemVerilog code for the submodule, highlighting key parts of the implementation if needed for a clearer understanding.

!!! tip

    Mkdocs allows a plethora of highlighting and cues for better code documentation. [Read more](https://squidfunk.github.io/mkdocs-material/reference/code-blocks/?h=code).

### Example Code

```systemverilog
module Submodule (
    input  logic input_signal_1,
    input  logic input_signal_2,
    output logic output_signal_1,
    output logic output_signal_2
);
  // Description of the submodule's functionality

  // Module logic
  always_ff @(posedge clk) begin
    // Implementation of the functionality
  end
endmodule
```
