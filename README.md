# UD - x64dbg Modded Edition

Modified build of x64dbg for Windows x64 reverse engineering and dynamic analysis.

## Included Plugins

The following plugins are pre-installed and integrated in this modded release:

| Plugin | File | Features |
|--------|------|----------|
| Scylla | `Scylla.dll` | Process dumping, import table reconstruction (IAT fix), and unpacking support for protected binaries. |
| DeviceNameResolver | `DeviceNameResolver.dll` | Resolves device and driver names during debugging sessions. |
| TitanEngine | `TitanEngine.dll` | Debugging engine integration with enhanced breakpoint and exception handling. |
| XEDParse | `XEDParse.dll` | Instruction decoding and disassembly using Intel XED (X86 Encoder Decoder). |
| jansson | `jansson.dll` | JSON parsing and data handling for script and plugin communication. |
| lz4 | `lz4.dll` | High-speed compression and decompression support. |
| dbghelp | `dbghelp.dll` | Windows Debug Help library integration for symbol resolution and stack tracing. |
| ldconvert | `ldconvert.dll` | Data and format conversion utilities for debugging workflows. |

## Mod Notes

- Pre-configured plugin loadout ready to use out of the box.
- Supports both x32 and x64 targets via the included `x32` and `x64` runtime folders.
- Custom themes available under `themes/`.