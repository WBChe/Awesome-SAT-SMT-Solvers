# 🧮 Awesome-SAT-SMT-Solvers
A curated collection of **SAT and SMT solver** resources — aimed at researchers in **formal verification**, **constraint solving**, and **program synthesis**.

---

## 📘 Overview

Many problems in computer science — from software and hardware verification to AI planning and optimization — can be reduced to **satisfiability** problems.

- **SAT (Boolean Satisfiability):** Decide whether a propositional formula can be satisfied.
- **SMT (Satisfiability Modulo Theories):** Extend SAT solving with *theories* such as arithmetic, bit-vectors, arrays, and quantifiers.

This repository collects open-source tools, papers, benchmarks, and tutorials to help you explore and compare modern SAT/SMT solvers.

---

## 🧩 SAT Solvers

| Solver | Description | GitHub / Website | Paper |
|:--------|:-------------|:----------------|:-------|
| **MiniSat** | Classic minimalistic CDCL SAT solver; widely used in research. | [github.com/niklasso/minisat](https://github.com/niklasso/minisat) | *An extensible SAT-solver* (Eén & Sörensson, 2003) |
| **Glucose** | Derived from MiniSat; focuses on clause learning and restart strategies. | [github.com/audemard/glucose](https://github.com/audemard/glucose) | *Predicting Learnt Clauses Quality in Modern SAT Solvers* (Audemard & Simon, 2009) |
| **Lingeling** | Advanced CDCL solver optimized for sequential solving. | [fmv.jku.at/lingeling](https://fmv.jku.at/lingeling) | *Lingeling, Plingeling and Treengeling entering the SAT competition 2013* (Biere, 2013) |
| **CryptoMiniSat** | Efficient solver with XOR reasoning, good for cryptographic problems. | [github.com/msoos/cryptominisat](https://github.com/msoos/cryptominisat) | *The CryptoMiniSat 5 set of solvers at SAT Competition 2016* (Soos et al., 2016) |
| **CaDiCaL** | Modern and efficient SAT solver developed by Armin Biere. | [github.com/arminbiere/cadical](https://github.com/arminbiere/cadical) | *Cadical, lingeling, plingeling, treengeling and yalsat entering the sat competition 2018* (Biere, 2018) |
| **Kissat** | Highly optimized SAT solver written in C99; fast and compact. | [github.com/arminbiere/kissat](https://github.com/arminbiere/kissat) | *Cadical, kissat, paracooba, plingeling and treengeling entering the sat competition 2020* (Biere, 2020) |

---

## 🧠 SMT Solvers

| Solver | Description | GitHub / Website | Paper |
|:--------|:-------------|:----------------|:-------|
| **Z3** | General-purpose SMT solver from Microsoft Research. Supports many theories and languages. | [github.com/Z3Prover/z3](https://github.com/Z3Prover/z3) | *Z3: An Efficient SMT Solver* (de Moura & Bjørner, TACAS 2008) |
| **CVC5** | Successor to CVC4; fast, modular, and supports quantifiers, FP, and strings. | [github.com/cvc5/cvc5](https://github.com/cvc5/cvc5) | *cvc5: A Versatile and Industrial-Strength SMT Solver* (Barrett et al., CAV 2022) |
| **Boolector** | Specializes in bit-vector and array logic; widely used in hardware verification. | [github.com/Boolector/boolector](https://github.com/Boolector/boolector) | *Boolector: An efficient SMT solver for bit-vectors and arrays* (Brummayer & Biere, TACAS 2015) |
| **Yices 2** | Developed by SRI; supports linear arithmetic, arrays, and bit-vectors. | [github.com/SRI-CSL/yices2](https://github.com/SRI-CSL/yices2) | *Yices 2.2* (Dutertre, CAV 2014) |
| **STP** | Early SMT solver focusing on bit-vector and array theories. | [stp.github.io](https://stp.github.io/) | *A decision procedure for bit-vectors and arrays* (Ganesh & Dill, CAV 2007) |
| **MathSAT 5** | Strong support for arithmetic and floating-point. | [mathsat.fbk.eu](https://mathsat.fbk.eu) | *The mathsat5 smt solver* (Cimatti et al., TACAS 2013) |
| **SMTInterpol** | Incremental SMT solver for linear arithmetic and uninterpreted functions. | [ultimate.informatik.uni-freiburg.de/smtinterpol](https://ultimate.informatik.uni-freiburg.de/smtinterpol/) | *SMTInterpol: An Interpolating SMT Solver* (Christ et al., SPIN 2012) |
| **Bitwuzla** | Next-gen bit-vector SMT solver, successor to Boolector. | [github.com/bitwuzla/bitwuzla](https://github.com/bitwuzla/bitwuzla) | *Bitwuzla* (Niemetz & Preiner, CAV 2023) |

---

## 🧪 Benchmarks & Competitions

| Resource | Description | Link |
|-----------|-------------|------|
| **SAT Competition** | Annual SAT solver competition since 2002. | [satcompetition.github.io](https://satcompetition.github.io/) |
| **SMT-COMP** | Annual SMT solver competition hosted at CAV. | [smt-comp.github.io](https://smt-comp.github.io/) |
| **SMT-LIB** | Standardized benchmark suite and input format for SMT solvers. | [smtlib.cs.uiowa.edu](http://smtlib.cs.uiowa.edu/) |
| **SV-COMP** | Software Verification Competition (uses SMT backends). | [sv-comp.sosy-lab.org](https://sv-comp.sosy-lab.org/) |

---

## 🧰 Tutorials & Learning

- [Z3 Guide (Official)](https://theory.stanford.edu/~nikolaj/programmingz3.html)
- [CVC5 Documentation](https://cvc5.github.io/docs/)

---

## 🤝 Contributing

Contributions are **very welcome!**  
You can help by:
- Adding new solver entries (name + link + short intro + paper)
- Sharing benchmark datasets or comparison results
- Writing usage tutorials (Python/Z3, C++/CVC5 examples)
- Translating documentation or fixing formatting

To contribute:
1. Fork the repo  
2. Add your content
3. Submit a pull request 💡

---

## 📜 License

This repository is released under the [MIT License](https://opensource.org/licenses/MIT).

---

> *If you find this useful, please ⭐ star the repo and share!*
