# Development of simple Flexray Driver

*2021 — CEIC-C/CEIC-M (Central Exterior Interior Controller - Main / Co)*

Tags: FlexRay, Embedded C, Interrupt/Polling, CEIC

Implemented an optimized Flexray Driver for driving one specific Flexray controller, enabling only one channel with a limited number of configured frames
This was needed to enable Flexray communication in a particular project with as minimal memory footprint as possible with as fast run-time as possible
This bare metal Flexray driver did not follow AUTOSAR standards, dint implement all AUTOSAR APIs and is not reusable as-is in other projects (That's the way it was intended to be developed)
