# Interrupts

This section describes the interrupts implemented in the design. For each interrupt, specify its name, the associated interrupt controller, number, priority, type (e.g., level or edge), triggering mechanism (e.g., rising/falling edge or high/low level), handling method (e.g., synchronous or asynchronous), and a brief description.

## Interrupt Table

| Interrupt Name | Controller | Number | Priority | Type   | Triggers | Handling     | Description         |
|----------------|------------|--------|----------|--------|----------|--------------|---------------------|
| IRQ_1          | Main       | 0      | 1        | Edge   | Falling  | Synchronous  | Description of IRQ_1|
| IRQ_2          | Aux        | 1      | 3        | Level  | High     | Asynchronous | Description of IRQ_2|
