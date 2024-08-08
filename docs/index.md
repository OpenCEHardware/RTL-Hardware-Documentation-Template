# Home

Welcome to the OpenCEHardware RTL hardware module documentation template. This document provides a standardized structure for documenting hardware designs based on RTL. The template is designed to assist in organizing and presenting technical documentation for hardware modules, facilitating a clear and comprehensive description of the design.

## Description

This documentation template is based on multiple sources and industry best practices. It includes detailed sections to cover all important aspects of an RTL hardware design, from the general description of the module to specific details of its HDL implementation.

Even though this template is designed for complex desings, its principles can be applied to smaller, simpler designs. It may also guide novice hardware architects toward potential upgrades for their designs.

!!! warning "Disclaimer"

    This template excludes any post-silicon or physical design implementation details, such as reliability floorplans, pin mapping, SRAM placement, chip area, power, physical debugging, etc. The focus of this template is on FPGA constraint RTL designs.

## Navigation

The template is organized into the following sections, each explaining its purpose, general structure, tips, and examples.

!!! note

    The References and Revisions sections serve a dual purpose, serving both as a example and keeping the actual revisions and references for the template.

<div class="grid cards" markdown>

- :fontawesome-solid-book: [Revisions](block/revisions.md): Documentation on previous versions and changes made.
- :fontawesome-solid-gavel: [Document Conventions](block/conventions.md): Definitions and abbreviations used in the document.
- :fontawesome-solid-lightbulb: [Introduction](block/introduction.md): General description of the block and its features.
- :fontawesome-solid-diagram-project: [Block Diagram](block/diagram.md): Visual representation of the block's microarchitecture.
- :fontawesome-solid-gear: [Configuration](block/configuration.md): Information about parameters, typedefs, and RTL interfaces.
- :fontawesome-solid-network-wired: [Protocols](block/protocols.md): Details of communication and operation protocols.
- :fontawesome-solid-memory: [Memory Map](block/memory.md): Distribution of memory and resource allocation.
- :fontawesome-solid-clipboard-list: [Registers](block/registers.md): Description of the registers used in the system.
- :fontawesome-solid-clock: [Clock Domains](block/clocks.md): Information about clocks and their management in the system.
- :fontawesome-solid-wave-square: [Reset Domains](block/resets.md): Information about reset mechanisms and their domains.
- :fontawesome-solid-bell: [Interrupts](block/interrupts.md): Management and handling of interrupts in the system.
- :fontawesome-solid-flag: [Arbitration](block/arbitration.md): Arbitration mechanisms for access to shared resources.
- :fontawesome-solid-bug: [Debugging](block/debugging.md): Techniques and tools for system debugging.
- :fontawesome-solid-table: [Synthesis](block/synthesis.md): Summary and results of the design synthesis.
- :fontawesome-solid-table: [Verification](block/verification.md): Test environments, verification and testbenches applied to the system.
- **Microarchitecture:**
    - :fontawesome-solid-cube: [Sub-module 1](block/microarchitecture/sub1.md): Details of the first sub-module of the microarchitecture.
    - :fontawesome-solid-cube: [Sub-module 2](block/microarchitecture/sub2.md): Details of the second sub-module of the microarchitecture.

</div>

## Using the Template

This template is designed to be downloaded and adapted to the specific needs of each project. It is recommended to follow the provided structure and customize it according to the design requirements and project standards. Simpler designs may not require documentation for all sections. In such cases, it is recommended to indicate that the section is not needed rather than leaving it blank or excluding it from the document.

This template was created using [MkDocs](https://www.mkdocs.org/), a widely used tool for code documentation (e.g., [ReadTheDocs](https://about.readthedocs.com/?ref=readthedocs.org)). MkDocs uses Markdown, which is excellent for creating interactive, easy-to-understand documentation. It also integrates seamlessly with GitHub and can be published as a web page (e.g., using GitHub Pages). Additionally, it can be rendered as a PDF, as provided in this template. MkDocs supports themes that offer further customizability and aesthetics. This template uses [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/), which offers a comprehensive guide for styling that is well worth exploring.

## Acknowledgements

This template has been developed from various sources and industry standards to ensure comprehensive and useful documentation for RTL hardware design. Please check the [References](block/references.md) section for more information.
