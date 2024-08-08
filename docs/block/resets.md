# Reset Domains

This section provides an overview of the reset domains used in the design. For each reset, specify whether it is synchronous or asynchronous, its active level (high or low), and, if synchronous, the associated clock. Include the same top-level block diagram as before, but this time annotate it to show which submodules are in each reset domain. Reset domain crossings in the datapath should be explicitly shown and encapsulated within one or more submodules. For resets used for "backbone" functions that span multiple submodules (e.g., a CSR bus in its own reset domain), clearly indicate this and defer detailed information to an appropriate document or section. If the reset protocol is custom to this block, include a subsection defining the relevant procedures. Otherwise, cite other documents that provide these details [[1]](references.md#ref1).

## Reset Domains Table

| Reset Name | Synchronous/Asynchronous | Active High/Low | Associated Clock (if synchronous) | Description              |
|------------|--------------------------|-----------------|-----------------------------------|--------------------------|
| RESET_1    | Synchronous              | Active Low      | CLK1                              | Description of RESET_1   |
| RESET_2    | Asynchronous             | Active High     | N/A                               | Description of RESET_2   |

## Annotated Block Diagram

{!diagrams/resets.html!}

## Custom Reset Procedures

If the reset protocol is custom for this block, provide a detailed description of the procedures and mechanisms here. Otherwise, cite the relevant documentation.

### Custom Reset Procedure

1. Step 1 of the procedure.
2. Step 2 of the procedure.
3. Step 3 of the procedure.

## References to External Documents

For standard reset protocols, refer to the following documents:

- [Standard Reset Protocol Document 1](path/to/document1)
- [Standard Reset Protocol Document 2](path/to/document2)
