# Creature Battle Project (OOP + Git Branching Practice)

This project is designed to help me learn **object-oriented programming** in Python — especially **inheritance** — while also practicing key **Git concepts** like branching, merging, conflict resolution, and version history.

I will begin with a base class (`Creature`) and create additional subclasses on separate Git branches to simulate a real development workflow.

---

## Learning Objectives

### Python / OOP
- Understand and implement **classes**
- Use **inheritance** to extend behaviors
- Override and extend methods (e.g., `attack()`)
- Practice writing simple test code in `main`

### Git / Version Control
- Create and switch branches
- Merge branches into `main`
- Resolve merge conflicts
- View commit history (`git log --graph --all`)

---

## Project Structure
oop_creature_code/
│
├── creature_simulation.py # Base class + subclasses
└── README.md

## How to Test and Run
1. Open a terminal and navigate to the `oop_creature_code` directory:
   cd oop_creature_code
2. Run the simulation script using Python 3:
   python3 creature_simulation.py
3. Verify the console output for `Creature`, `FlyingCreature`, `SwimmingCreature`, and `FireCreature` test cases.