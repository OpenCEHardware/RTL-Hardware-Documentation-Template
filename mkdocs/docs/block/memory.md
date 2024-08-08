# Memory Map

This section provides a clear and organized overview of how memory is distributed in the system. It includes a table that shows memory addresses, specific regions assigned to different system components (such as ROM, RAM, peripherals, CSRs, etc.), and any relevant details about the size, access permissions, and purpose of each region. Detailed memory resource allocation facilitates the design, development, use, and debugging of the system.

## Memory Map Table

| Memory Address          | Size   | Region          | Description                                       |
|-------------------------|--------|-----------------|---------------------------------------------------|
| 0x00000000 - 0x0000FFFF | 64 KB  | ROM (Firmware)  | Contains the boot code and firmware.              |
| 0x00010000 - 0x0001FFFF | 64 KB  | RAM (Data)      | Stores variable data and stacks.                  |
| 0x00020000 - 0x0002FFFF | 64 KB  | Peripheral A    | Control and data registers of Peripheral A.       |
| 0x00030000 - 0x0003FFFF | 64 KB  | Peripheral B    | Control and data registers of Peripheral B.       |
| 0x00040000 - 0x0004FFFF | 64 KB  | RAM (Stack)     | Reserved space for the stack and temporary storage. |
