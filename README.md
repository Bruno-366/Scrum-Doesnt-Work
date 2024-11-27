# Scrum Doesn't Work Simulation [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Forward-Lang/Scrum-Doesnt-Work/HEAD)

This repository simulates how Scrum doesn't always work in a real-world scenario, where tasks are randomly blocked, workers may be unavailable due to sick leave or vacation, and the priority queue may not be efficiently processed.

## Files

- `backlog_simulation.ipynb`: A Jupyter notebook containing the simulation code.

## How to Run

Locally:
1. Clone this repository.
2. Open and run `backlog_simulation.ipynb` in a Jupyter notebook.

You can also use [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Forward-Lang/Scrum-Doesnt-Work/HEAD) to run this notebook.

## Key Concepts Simulated

- **Backlog Items**: Tasks with different priorities and "blocked" statuses.
- **Workers**: Simulated by multiple threads randomly picking tasks.
- **Random Absence**: Workers may "disappear" randomly to simulate sick leave or vacation.

## License

This project is licensed under the [MIT License](LICENSE).
