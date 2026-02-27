# Regex to Deterministic Finite Automaton (DFA)

A C++ engine that converts regular expressions into Deterministic Finite Automata. The project parses regex input, builds the underlying abstract syntax tree, and generates a state machine to evaluate and validate strings.

## 📌 Features
* **Regex Parsing & Conversion:** Processes standard regular expressions and converts them into postfix notation for easier tree construction.
* **AST Generation:** Builds a visual syntax tree representation of the parsed expression.
* **DFA Construction:** Generates the complete automaton, mapping out states, alphabets, transition functions, and accept/reject states.
* **String Evaluation:** Simulates the generated DFA against input words to check if they belong to the language defined by the regex.
* **Console & File Export:** Outputs the state transition table both to the console and to an external text file for further analysis.

## 🚀 How to Run
1. Build the project using your preferred C++ compiler.
2. Ensure your regex input text file is located in the executable's directory.
3. Run the program and follow the interactive console menu to generate the DFA and test your strings.
