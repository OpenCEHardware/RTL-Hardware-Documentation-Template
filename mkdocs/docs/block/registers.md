# Registers

This section contains all the registers of the block, organized in tables. This includes user registers, CSRs, and other registers (e.g., debugging).

## User Registers

### User Registers Table

| Register Name | Abbreviation | Address | Fields and Offsets     | Access Permissions (HW/SW) | Description                        |
|---------------|--------------|---------|------------------------|----------------------------|------------------------------------|
| USER_REG_1    | UR1          | 0x0100  | FIELD1 (0-7)           | R/W                        | Description of User Register 1     |
| USER_REG_2    | UR2          | 0x0104  | FIELD1 (0-15)          | R                          | Description of User Register 2     |

## CSRs (Configuration/Status Registers)

List major categories of configuration/status registers (CSRs). Define all CSRs here or link to an external document. Every CSR should define its name, address, fields and offsets, hardware and software access permissions, and a description of what each field does [[1]](references.md#ref1).

!!! note

    Ideally, this subsection should link to CSR documentation that is auto-generated from a single-source-of-truth source code. An open-source industry tool used for this purpose is [PeakRDL](https://github.com/SystemRDL/PeakRDL?tab=readme-ov-file).

### CSRs Table

| CSR Name   | Abbreviation | Address | Fields and Offsets                        | Access Permissions (HW/SW) | Description            |
|------------|--------------|---------|-------------------------------------------|----------------------------|------------------------|
| CSR_NAME_1 | CSR1         | 0x0000  | FIELD1 (0-7), FIELD2 (8-15)               | R/W                        | Description of CSR 1   |
| CSR_NAME_2 | CSR2         | 0x0004  | FIELD1 (0-3), FIELD2 (4-7), FIELD3 (8-15) | R/W                        | Description of CSR 2   |

## Other Registers

### Other Registers Table

| Register Name   | Abbreviation | Address | Fields and Offsets                        | Access Permissions (HW/SW) | Description                     |
|-----------------|--------------|---------|-------------------------------------------|----------------------------|---------------------------------|
| DEBUG_REG_1     | DR1          | 0x0200  | FIELD1 (0-7), FIELD2 (8-15)               | R/W                        | Description of Debug Register 1 |
| DEBUG_REG_2     | DR2          | 0x0204  | FIELD1 (0-3), FIELD2 (4-7), FIELD3 (8-15) | R/W                        | Description of Debug Register 2 |
