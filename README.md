# 💧 Water Tank & Water Pouring Problem Solver

## 📌 Project Overview

The **Water Tank & Water Pouring Problem Solver** is a Python-based problem-solving application designed to solve water pouring problems using search algorithms and calculate water tank filling time using flow-rate calculations.

The project combines **Artificial Intelligence-based search techniques**, mathematical calculations, performance analysis, and an interactive user interface into a single working model.

---

## 🎯 Objectives

- Solve classic water pouring problems automatically.
- Find a valid sequence of pouring operations to reach a target quantity.
- Implement **Breadth-First Search (BFS)** for state-space exploration.
- Implement **A* Search** for goal-oriented problem solving.
- Calculate water tank filling time using inlet and outlet flow rates.
- Provide an interactive interface for entering problem parameters.
- Analyze solver performance using multiple test cases.
- Validate the system using different input conditions.

---

## 🧠 Algorithms & Methods

### 1. Breadth-First Search (BFS)

BFS explores possible water states level by level.

Each state represents the amount of water present in the two containers.

Possible operations include:

- Fill a container
- Empty a container
- Pour water from one container to another

BFS continues exploring the possible states until the required target quantity is reached.

### 2. A* Search

A* is a heuristic-based search algorithm that prioritizes promising states.

It evaluates states using:

```text
f(n) = g(n) + h(n)
```

where:

- `g(n)` = cost of reaching the current state
- `h(n)` = estimated cost to reach the goal

---

## 💧 Water Pouring Problem

For example:

```text
Jug A Capacity = 4 L
Jug B Capacity = 3 L
Target Amount = 2 L
```

The system searches through possible states and generates a valid sequence of operations to reach the target.

The solution is represented as a sequence of water states and pouring operations.

---

## 🚰 Water Tank Calculation

The Water Tank module calculates the time required to reach a target water level based on the inlet and outlet flow rates.

### Example

```text
Tank Capacity = 1000 L
Current Level = 200 L
Target Level = 800 L
Inlet Rate = 100 L/min
Outlet Rate = 20 L/min
```

Calculation:

```text
Net Flow Rate = Inlet Rate - Outlet Rate
              = 100 - 20
              = 80 L/min

Water Needed = Target Level - Current Level
             = 800 - 200
             = 600 L

Time Required = Water Needed / Net Flow Rate
              = 600 / 80
              = 7.50 minutes
```

Therefore, the calculated time required to reach the target level is **7.50 minutes**.

---

## 🖥️ Interactive Interface

The project includes an interactive interface that allows users to enter the required problem parameters and obtain the corresponding solution.

The interface supports both the **Water Pouring** and **Water Tank** problem-solving workflows.

---

## 📊 Testing & Performance

The system was tested using multiple test cases.

| Metric | Result |
|---|---:|
| Total Test Cases | 5 |
| Successful Cases | 5 |
| Success Rate | 100% |
| Average Execution Time | 0.0329 ms |

All **5 tested validation cases passed successfully**.

> **Note:** The 100% success rate refers to the five test cases used during project validation.

---

## 📈 Performance Analysis

The project measures execution time for different test cases and generates a performance graph using **Matplotlib**.

This helps analyze the execution performance of the solver for different inputs.

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Jupyter Notebook
- Breadth-First Search (BFS)
- A* Search
- Gradio
- Matplotlib
- Pandas

---

## ✨ Key Features

- 💧 Water pouring problem solver
- 🚰 Water tank filling-time calculator
- 🧠 BFS search
- 🔎 A* search
- 🖥️ Interactive interface
- 📊 Performance analysis
- 🧪 Multiple test cases
- 📈 Execution-time visualization
- ✅ Final validation

---

## 📂 Project Structure

```text
Water-Tank-Pouring-Problem-Solver/
│
├── Water_tank_pouring_problem_solver.ipynb
└── README.md
```

The Jupyter Notebook contains the complete implementation, testing, validation, and performance analysis.

---

## ▶️ How to Run

### Using Google Colab

1. Open the `.ipynb` notebook.
2. Open the notebook using Google Colab.
3. Run the cells sequentially.
4. Enter the required inputs.
5. View the generated solution and results.

### Using Jupyter Notebook

1. Download the `.ipynb` file.
2. Open it using Jupyter Notebook or JupyterLab.
3. Run the cells sequentially.
4. Provide the required inputs.
5. View the results.

---

## 🔮 Future Enhancements

Possible future improvements include:

- Supporting more than two water containers.
- Adding additional search algorithms.
- Providing animated state transitions.
- Improving search-process visualization.
- Supporting more complex tank-flow scenarios.
- Deploying the application as a standalone web application.

---

## 📌 Project Outcome

The project demonstrates how **state-space search algorithms and mathematical modelling** can be applied to water-management problems.

The implemented system successfully solved the tested water pouring cases, performed water tank calculations, provided an interactive interface, and completed the final validation with **5 out of 5 test cases passing**.

---

## 👨‍💻 Authors

**Durairaj S**
**Ganesh S**
**Gokulkrishnan**
**Gummadi yeswanth**
**Hema P**

**The solution is represented as a sequence of water states and pouring operations.

---

## 🚰 Water Tank Calculation

The Water Tank module calculates the time required to reach a target water level based on the inlet and outlet flow rates.

### Example

### Project Type

**Mini Project — Artificial Intelligence / Problem Solving**
