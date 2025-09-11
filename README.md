# Q-Folio: Quantum Optimization for Portfolio Management

Q-Folio is a quantum computing project that applies the **Quantum Approximate Optimization Algorithm (QAOA)** to optimize stock portfolio allocation across the "Magnificent 7" tech stocks. By leveraging quantum-inspired techniques, Q-Folio aims to reduce portfolio variance (risk) while maintaining high returns, outperforming classical brute-force methods in efficiency and scalability.

---

## 🚀 Project Summary

Traditional portfolio optimization becomes computationally expensive as the number of assets grows. This project explores the feasibility of using **quantum algorithms**, particularly QAOA, to find an optimal or near-optimal asset distribution that minimizes risk based on historical volatility.

---

## 🧠 Key Features

- 🔗 **QAOA Implementation**: Optimizes portfolio selection on simulated qubits using `qiskit` and `pennylane`.
- 📈 **Real Market Data**: Integrates with Alpha Vantage API to fetch daily prices of top 7 tech stocks.
- 📊 **Variance Minimization**: Reduces portfolio variance by ~20% compared to brute-force classical solutions.
- 🧪 **Quantum-Classical Comparison**: Benchmarks quantum optimization against exhaustive search for small portfolios.

---

## 🧮 Methodology

1. **Data Collection**  
   - Fetches 100 days of closing price data for the Magnificent 7 (AAPL, MSFT, GOOGL, AMZN, NVDA, META, TSLA).
   - Calculates expected returns and covariance matrix.

2. **Problem Formulation**  
   - Converts portfolio variance minimization into a combinatorial optimization problem.
   - Encodes the objective as a cost Hamiltonian for QAOA.

3. **QAOA Execution**  
   - Uses `qiskit` to define the quantum circuit and simulate qubit behavior.
   - Runs parameterized quantum circuits to find optimal bitstrings (asset inclusion/exclusion).

4. **Evaluation**  
   - Compares variance of QAOA-selected portfolio to classical brute-force and random selection baselines.

---

## 📦 Tech Stack

- **Languages**: Python  
- **Quantum SDKs**: Qiskit, PennyLane  
- **Libraries**: NumPy, Pandas, Matplotlib, Alpha Vantage API  
- **Tools**: Jupyter Notebook, Git, IBM Quantum Simulators

---

## 📊 Results

- Achieved ~**20% reduction in portfolio variance** vs. classical exhaustive methods.
- Demonstrated scalability and efficiency of QAOA for portfolio selection on small asset sets.
- Validated the feasibility of quantum finance tools for real-world problems.

---

## 📚 Future Work

- Extend to larger portfolios using quantum sampling or variational quantum algorithms (VQE).
- Integrate expected returns into the cost function (e.g., Sharpe ratio optimization).
- Deploy on real quantum hardware using IBM Q or AWS Braket.

---

## 🧑‍💻 Author

**Aditya Sunke**  
Computer Science @ Virginia Tech  
🔗 [LinkedIn](https://www.linkedin.com/in/aditya-sunke/) | [GitHub](https://github.com/adityasunke)

