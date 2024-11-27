# Scrum Doesn't Work Simulation

This repository simulates how Scrum doesn't always work in a real-world scenario, where tasks are randomly blocked, workers may be unavailable due to sick leave or vacation, and the priority queue may not be efficiently processed.

## Files

- `backlog_simulation.ipynb`: A Jupyter notebook containing the simulation code.
- `requirements.txt`: A list of dependencies (currently using only standard Python libraries).

## How to Run

1. Clone this repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Open and run `backlog_simulation.ipynb` in a Jupyter notebook.

## Key Concepts Simulated

- **Backlog Items**: Tasks with different priorities and "blocked" statuses.
- **Workers**: Simulated by multiple threads randomly picking tasks.
- **Random Absence**: Workers may "disappear" randomly to simulate sick leave or vacation.

## License

This project is licensed under the [MIT License](LICENSE).
