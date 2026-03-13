# Linux System Call Monitor

A lightweight tool to monitor and analyze Linux system calls for security research.

> **Status:** 🚧 Work in Progress - Bachelor Graduation Project

## What It Does

Monitors system calls from running processes and analyzes patterns to detect unusual behavior.

**Use Cases:**
- Learning about system-level security
- Understanding process behavior
- Educational purposes

## Planned Features

- ✅ Real-time syscall capture
- ✅ Pattern analysis (frequencies, sequences)
- ✅ Simple anomaly detection
- ✅ Baseline comparison
- ⏳ Visualization tools
- ⏳ Configuration system

## Tech Stack

- **C** - Core monitoring engine (performance-critical)
- **Bash** - Automation scripts
- **Linux** - ptrace/strace for syscall capture

## Project Structure
```
linux-syscall-monitor/
├── src/          # C source files
├── scripts/      # Bash automation
├── data/         # Logs and results
└── docs/         # Documentation
```

## Why This Project

> *"Lightweight Intrusion Detection for Linux Systems Using System Call Analysis"*

**Goals:**
1. Learn system-level programming
2. Understand syscall-based security monitoring
3. Create a useful tool for the community

## Future Enhancements

After graduation, I plan to:

- Add machine learning for pattern detection
- Support for eBPF (modern Linux tracing)
- Network traffic correlation
- Resource optimization for constrained environments
- Integration with existing security tools

## Development Timeline

- **Phase 1** (Current): Project setup and basic structure
- **Phase 2**: Core syscall capture implementation
- **Phase 3**: Pattern analysis engine
- **Phase 4**: Testing and documentation
- **Phase 5**: Final polish for graduation

## Requirements

- Linux (Ubuntu 24.04+ LTS)
- GCC compiler
- Make
- Root access (for ptrace)

## License

MIT

## Contact

Questions or suggestions? Feel free to open an issue!

