# Dataset and Benchmark

RoboVerse provides a large-scale dataset and standardized benchmarks for robot learning research. This section documents our task suite, asset library, and evaluation protocols.

---

## Overview

::::{grid} 3
:gutter: 3

:::{grid-item-card} 200+ Tasks
:text-align: center

Manipulation, locomotion, and navigation tasks across difficulty levels
:::

:::{grid-item-card} 50+ Robots
:text-align: center

Manipulators, mobile robots, humanoids, and dexterous hands
:::

:::{grid-item-card} 1000+ Objects
:text-align: center

Diverse object assets from household items to industrial parts
:::

::::

---

## Dataset Statistics

| Category | Count | Description |
|----------|-------|-------------|
| **Tasks** | 200+ | Manipulation, locomotion, navigation |
| **Robots** | 50+ | Arms, mobile bases, humanoids, hands |
| **Objects** | 1000+ | Household, industrial, articulated |
| **Scenes** | 50+ | Tables, shelves, kitchens, factories |
| **Demonstrations** | 100K+ | Expert trajectories for IL training |

---

## Quick Links

### For Researchers

- [Task Overview](tasks/overview.md) - Browse available tasks by category
- [Benchmark Usage](benchmark/usage.md) - Run standardized evaluations
- [Benchmark Results](benchmark/results.md) - Compare with state-of-the-art

### For Developers

- [Robot Configurations](dataset/robots.md) - Available robot embodiments
- [Object Assets](dataset/objects.md) - Object models and properties
- [Scene Definitions](dataset/scenes.md) - Pre-built simulation scenes

---

## Task Categories

### Manipulation Tasks

Single-arm and bimanual manipulation tasks including:

- **Pick & Place**: Grasping and relocating objects
- **Insertion**: Peg-in-hole and assembly tasks
- **Tool Use**: Using tools to manipulate objects
- **Articulated Objects**: Doors, drawers, buttons, switches

### Locomotion Tasks

Whole-body control and locomotion tasks:

- **Walking**: Forward, backward, turning gaits
- **Running**: High-speed locomotion
- **Terrain Navigation**: Stairs, slopes, rough terrain
- **Recovery**: Fall recovery and balance

### Mobile Manipulation

Combined navigation and manipulation:

- **Fetch Tasks**: Navigate to object, pick, deliver
- **Household Tasks**: Cleaning, organizing, cooking assistance

---

## Benchmark Suite

The RoboVerse Benchmark provides standardized evaluation protocols for:

| Benchmark | Tasks | Metrics | Purpose |
|-----------|-------|---------|---------|
| **RV-Manip** | 50 | Success Rate, SPL | Manipulation generalization |
| **RV-Loco** | 20 | Distance, Energy | Locomotion efficiency |
| **RV-Cross** | 30 | Transfer Success | Cross-embodiment transfer |

See [Benchmark Overview](benchmark/overview.md) for detailed evaluation protocols.

---

## Table of Contents

```{toctree}
:caption: RoboVerse Tasks
:titlesonly:

tasks/overview
tasks/descriptions
tasks/task_groups
```

```{toctree}
:caption: RoboVerse Dataset
:titlesonly:

dataset/robots
dataset/objects
dataset/scenes
```

```{toctree}
:caption: RoboVerse Benchmark
:titlesonly:

benchmark/overview
benchmark/results
benchmark/usage
```
