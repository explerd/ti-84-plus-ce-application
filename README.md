# TI-84 Plus CE Mini Wiki Application

A comprehensive, memory-optimized reference app for the TI-84 Plus CE calculator featuring math formulas, physics constants, computer science concepts, technology information, and TI-BASIC learning materials.

## 📋 Features

### 🎓 Learning Hub
- **TI-BASIC Fundamentals**: Syntax, commands, data types
- **Starter Programs**: Hello World, calculator, number guesser, more
- **Tips & Tricks**: Optimization, common errors, debugging
- **Quick Reference**: Commands and syntax lookup

### 📐 Mathematics
- **Area**: Formulas for common shapes
- **Calculus**: Derivatives, integrals, limits
- **Geometry**: 2D/3D formulas, theorems
- **Number Theory**: Primes, divisibility, modular arithmetic
- **Statistics**: Mean, median, standard deviation, distributions
- **Topology**: Basic concepts and definitions

### 🔬 Physics
- **Maxwell's Equations**: Electromagnetic theory
- **Theory of Relativity**: Special & general relativity basics
- **Quantum Mechanics**: Wave functions, uncertainty principle
- **Chaos Theory**: Fractals, butterfly effect concepts

### ⚛️ Constants & Theorems
- **Pi (π)**: Value and uses
- **Planck's Constant (h)**: Quantum mechanics
- **Speed of Light (c)**: Fundamental constant
- **Pythagorean Theorem**: Proof and applications
- **Bayes' Theorem**: Probability theory

### 💻 Technology
- **Apple Inc.**: Product lines (iPhone, iPad, MacBook, etc.)
- **Samsung Electronics**: Phones, tablets, wearables, displays
- **TSMC**: Chip manufacturing, process nodes
- **NVIDIA**: GPUs, AI chips, architecture
- **Intel**: Processors, technology, competition
- **AMD**: CPUs, GPUs, Ryzen, EPYC lines

## 🎯 Device Specifications

| Constraint | Value |
|------------|-------|
| RAM (User) | ~154 KB |
| Storage | ~3.5 MB Flash |
| Max Program Size | 64 KB per file |
| Screen | 320×220 pixels |
| Language | TI-BASIC |

## 📁 Directory Structure

```
src/
├── main.8xp                 # Main menu launcher
├── learning/
│   ├── tutorial.8xp         # TI-BASIC basics
│   ├── syntax.8xp           # Command reference
│   ├── starter1.8xp         # Hello World
│   ├── starter2.8xp         # Simple calculator
│   ├── starter3.8xp         # Number guesser
│   ├── starter4.8xp         # Factorial program
│   └── tips.8xp             # Tips & optimization
├── math/
│   ├── area.8xp
│   ├── calculus.8xp
│   ├── geometry.8xp
│   ├── number_theory.8xp
│   ├── statistics.8xp
│   └── topology.8xp
├── physics/
│   ├── maxwell.8xp
│   ├── relativity.8xp
│   ├── quantum.8xp
│   └── chaos.8xp
├── constants/
│   ├── pi.8xp
│   ├── planck.8xp
│   └── light_speed.8xp
├── theorems/
│   ├── pythagorean.8xp
│   └── bayes.8xp
└── tech/
    ├── apple.8xp
    ├── samsung.8xp
    ├── tsmc.8xp
    ├── nvidia.8xp
    ├── intel.8xp
    └── amd.8xp
```

## 🚀 Installation

1. **Download files** from this repository
2. **Connect TI-84 Plus CE** to computer via USB
3. **Open TI-Connect CE**
4. **Transfer `.8xp` files** to calculator
5. **Run `MAIN`** program from calculator menu

## 📖 Usage

- Launch `MAIN` program
- Navigate menus with arrow keys
- Press ENTER to select options
- Press 2ND + MODE (QUIT) to exit any program
- Return to main menu from any submenu

## 💡 Tips

- **Memory Limited**: Formulas are condensed for space
- **Readability**: Use CLEAR (2ND + DEL) between programs
- **Speed**: TI-BASIC is interpreted; use for reference, not intensive computation
- **Backup**: Save your own programs separately before installing

## 🔧 Development

All programs use **TI-BASIC** for maximum compatibility and user accessibility.

### Building from Source
- Edit `.8xp` files using TI-Connect CE or compatible editors
- Test programs individually before transferring
- Keep file names under 8 characters for compatibility

## 📝 File Format

- `.8xp` = TI-84 Plus CE Program file
- `.8xl` = List file (data)
- `.8xm` = Matrix file (data)

## ⚠️ Warnings

- Do **NOT** modify system programs (they start with lowercase letters)
- **Archive** your original data before installing
- Some programs may require extra RAM; delete other programs if needed
- Clearing RAM will delete all calculator data

## 📅 Last Updated

2026-05-24

## 📄 License

Educational use. Formulas sourced from Wikipedia and mathematical references.

---

**Questions?** Check the `HELP` menu in the app or review `learning/tutorial.8xp`
