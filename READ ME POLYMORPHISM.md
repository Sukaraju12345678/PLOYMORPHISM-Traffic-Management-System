# POLYMORPHISM–Traffic-Management-System

## Classes

| Class | Description |
|-------|-------------|
| `TrafficDevice` | Parent/base class with default `activate()` method |
| `TrafficLight` | Overrides `activate()` to cycle through signal colors |
| `SpeedCamera` | Overrides `activate()` to monitor vehicle speeds |
| `PedestrianSignal` | Overrides `activate()` to control pedestrian crossing |
| `EmergencySiren` | Added later without modifying the main activation loop |

## Key Concepts Demonstrated

- **Method Overriding**: Each child class provides its own implementation of `activate()`
- **Dynamic Method Dispatch**: Python determines the correct method at runtime
- **Extensibility**: `EmergencySiren` was added without changing the loop that calls `activate()`
- **No Type Checking**: The main loop treats all devices uniformly via the shared interface

## How to Run

### Jupyter Notebook
```bash
jupyter notebook SUKARAJU POLYMORHISM.ipynb
```


## Author

SUKARAJU SURAJI MOHAMMED

