# 🌟 Optical Carrier ODU Assignment Optimization 🌟

## 🚀 Project Overview
Welcome to **Optical ODU Assignment Optimization**, where we leverage **cutting-edge optimization techniques** to enhance **optical data transmission efficiency**. This project aims to strategically assign **Optical Data Units (ODUs)** to **multi-carrier transponder framers**, ensuring **balanced traffic distribution**, **efficient resource utilization**, and **minimal unassigned traffic**, all while adhering to strict hardware constraints.

## ✨ Features & Capabilities
✅ **Smart Traffic Generation**: Generates diverse ODU traffic scenarios to evaluate optimization methods.

✅ **Multiple Optimization Algorithms**:
- **📊 Integer Linear Programming (ILP)** – Guarantees optimal results but is computationally heavy.
- **🔎 Brute-Force** – Exhaustively evaluates all assignments (impractical for large datasets).
- **⚡ Greedy Algorithm** – Fast execution but may yield suboptimal assignments.
- **🧬 Genetic Algorithm (GA)** – Evolutionary approach for near-optimal results.
- **🔥 Simulated Annealing (SA)** – Inspired by metal cooling to refine solutions probabilistically.
- **🐦 Particle Swarm Optimization (PSO)** – Swarm intelligence for adaptive optimization.
- **🐜 Ant Colony Optimization (ACO)** – Pheromone-based learning for solution reinforcement.

✅ **📈 Interactive Visualization**: Provides insightful graphical comparisons of traffic allocation, execution times, and method efficiency.

## 📂 Project Structure
```
├── config.py                  # Configuration settings (framers, ODUs, constraints)
├── generator_traffic.py       # Generates dynamic traffic scenarios
├── optimization_methods.py    # Implements optimization algorithms
├── run_project.py             # Runs optimizations and compares results
├── visualization.py           # Displays performance graphs & insights
├── requirements.txt           # Lists required dependencies
```

## 🛠️ Installation & Setup
1️⃣ Clone the repository:
   ```sh
   git clone https://github.com/yourusername/optical-odu-optimization.git
   cd optical-odu-optimization
   ```

2️⃣ Install required dependencies:
   ```sh
   pip install -r requirements.txt
   ```
   *🔔 Note:* **Gurobi** is required for ILP. If unavailable, ILP optimization will be skipped.

## ▶️ Running the Project
To execute the optimization pipeline, simply run:
```sh
python run_project.py
```
This will **generate traffic scenarios**, **apply all optimization techniques**, and **visualize performance metrics**.

## 📊 Results & Key Insights
✨ **ILP** provides the most optimal solution but struggles with scalability.
✨ **Heuristic approaches** (GA, SA, PSO, ACO) balance speed and near-optimal results.
✨ **Greedy and Brute-Force** serve as baseline methods for comparison.
✨ **Execution time and unassigned traffic** vary significantly based on method efficiency.

## 🔮 Future Enhancements
🚀 **Hybrid Approaches** – Combining ILP with heuristics for improved efficiency.
🚀 **Real-Time Adaptation** – Dynamic optimization for evolving network demands.
🚀 **Scalability Improvements** – Enhancing ACO & PSO for larger-scale performance.

## 👥 Contributors
- **Fatemeh Asadi Tirtashi** 📩 [Email](mailto:Fatemeh.asadi@mail.polimi.it)
- **Kasra Alizadeh** 📩 [Email](mailto:kasra.alizadeh@mail.polimi.it)

## 💡 Acknowledgments
A heartfelt **thank you** to **Prof. Massimo Tornatore**, **Aryanaz Attarpour.PhD**, **Prof. Mëmëdhe Ibrahimi**, and **Nokia Coporation** for their invaluable guidance and support.

---

