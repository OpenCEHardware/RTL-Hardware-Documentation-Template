# Configuration

This section includes tables of typedefs, design parameters, and interfaces. In general, it addresses any configurability encoded into the design via RTL. Include the main parameters of the block (both private and shared), the top-level module parameters, and preprocessor macros that set global constants. Do not include parameters or macros that are derived from others. Ensure to describe any constraints and assumptions about reasonable or default values. Only explain the types that are necessary to fully define the parameters and interfaces [[1]](references.md#ref1).

## Parameters

| Parameter Name | Type   | Description                          | Default Value | Range/Possible Values |
|----------------|--------|--------------------------------------|---------------|-----------------------|
| `PARAM1`       | `int`  | Brief description of the parameter.  | `10`          | `0` to `100`          |
| `PARAM2`       | `float`| Brief description of the parameter.  | `0.5`         | `0.0` to `1.0`        |
| `PARAM3`       | `bool` | Brief description of the parameter.  | `true`        | `true`, `false`       |

## Typedefs

| Typedef Name   | Type    | Description                                    |
|----------------|---------|------------------------------------------------|
| `typedef_name1`| `struct`| Brief description of what the typedef defines. |
| `typedef_name2`| `enum`  | Brief description of what the typedef defines. |
| `typedef_name3`| `union` | Brief description of what the typedef defines. |

## Interfaces

This section includes a table of top-level module interfaces. Group related ports as a single interface. Show the directions and types of the ports, describe the interface's purpose, and follow common naming conventions. Mention the use of any standard protocols. Avoid excessive abbreviations. The directions, types, and names of the ports should match the RTL ports 1:1. The port directions should be from the block's perspective (as in the RTL) [[1]](references.md#ref1).

### Interface 1

| Port Name  | Direction | Type       | Description                                       |
|------------|-----------|------------|---------------------------------------------------|
| `port_name`| Input     | `type`     | Brief description of what this port does.         |
| `port_name`| Output    | `type`     | Brief description of what this port does.         |
| `port_name`| In/Out    | `type`     | Brief description of what this port does.         |

**Protocol Use**: Mention any standard protocol used by this interface here, if applicable.

### Interface 2

| Port Name  | Direction | Type       | Description                                       |
|------------|-----------|------------|---------------------------------------------------|
| `port_name`| Input     | `type`     | Brief description of what this port does.         |
| `port_name`| Output    | `type`     | Brief description of what this port does.         |
| `port_name`| In/Out    | `type`     | Brief description of what this port does.         |

**Protocol Use**: Mention any standard protocol used by this interface here, if applicable.
