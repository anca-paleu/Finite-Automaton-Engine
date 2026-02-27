# Finite-Automaton-Engine
[cite_start]A program that constructs a Deterministic Finite Automaton $M=(Q,\Sigma,\delta,q_{0},F)$ for a given regular expression.[cite: 305]

## 📌 Features
* **Regex Parsing:** [cite_start]Reads a regular expression from a text file[cite: 315] and [cite_start]converts it into its postfix Polish notation.[cite: 317]
* **Syntax Tree:** [cite_start]Builds and displays the syntax tree corresponding to the regular expression.[cite: 318]
* **DFA Construction:** [cite_start]Implements a `RegexToDFA` function to generate the automaton[cite: 313] and [cite_start]defines the core `Deterministic Finite Automaton` class with its states (Q), alphabet ($\Sigma$), transition function ($\delta$), initial state ($q_0$), and final states (F).[cite: 308, 309]
* **Validation:** [cite_start]Includes a `Verify Automaton` method to ensure valid transitions and states[cite: 310], and [cite_start]a `Check Word` method to test input strings.[cite: 312]
* **Export:** [cite_start]Prints the transition table to the console and exports it to an output file.[cite: 311, 319]

## 🚀 How to Run
1. Compile the source code using your preferred C++ compiler.
2. Ensure the input text file containing the regular expression is in the working directory.
3. Run the executable and use the interactive menu to process the regex and check words.
