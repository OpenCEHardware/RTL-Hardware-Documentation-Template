# Clock Domains

This section provides a detailed overview of the clock domains used in the design. For each clock, indicate its nominal frequency and the supported dynamic range. Include the same top-level block diagram as before, but this time annotate it to show which submodules are in each clock domain. Clock domain crossings in the data path should be explicitly drawn and encapsulated within one or more submodules. For clocks used for "backbone" functions spanning many submodules (e.g., a CSR bus in its own clock domain), indicate this clearly and refer to another document or appropriate section for details [[1]](references.md#ref1).

## Clock Domain Table

| Clock Domain       | Nominal Frequency | Supported Dynamic Range |
|--------------------|--------------------|-------------------------|
| Clock Domain 1     | XX MHz             | YY MHz - ZZ MHz         |
| Clock Domain 2     | AA MHz             | BB MHz - CC MHz         |
| Clock Domain 3     | DD MHz             | EE MHz - FF MHz         |

## Annotated Block Diagram

{!diagrams/clocks.html!}
