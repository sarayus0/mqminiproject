---
layout: single
author_profile: false
title: Quantum Circuit Escape Room
---
<br>
<p style="margin-top:-2.3em; font-size:1.3rem;">by Sarayu Sirikonda</p>

<ins>Project Idea</ins>:<br>An interactive escape room where players have to use their knowledge on quantum gates to solve logic and probability problems. To "escape" each room, you have to transform a quantum state using allowed gates (like H, X, Z) so that it meets the puzzle's requirement. There are different types of puzzles including reaching a certain measurement probability, creating a target state, or creating entanglement. As you continue playing, and you "level up," the difficulty of the problems increase.

<ins>Project Goal</ins>:<br>The goal of this project is to create a simple, engaging visual representation of quantum problems, making them easier and fun to learn.

<ins>Background</ins>:<br>
**Motivation**
- To make quantum information science concepts easy to understand and memorable through games and hands-on learning. Introduce complex concepts simply. 
- To support all learners and learning styles by using visual and interactive teaching techniques
- To demonstrate how quantum logic can be applied beyond theory (in education, coding, and creative fields).
- To help fill the gap in interactive, puzzle-based resources and making quantum concepts more accessible.
- To allow students to come up their own unique and innovative methods to solve each level, methods most people might not have thought of. New solutions might emerge as a result of this.

**Video Resources**<br>
You can refer to the below videos to learn more about quantum computing concepts and visualization techniques that inspired this project.
<iframe width="560" height="315" src="https://www.youtube.com/embed/JhHMJCUmq28?si=TbYyMoFIY_ZEvCVh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<br>

**References**
1. Qmunity, The Quantum Insider. “Building a Quantum Game.” (2024) [Link](https://qmunity.thequantuminsider.com/2024/06/11/building-a-quantum-game/)
2. Nielsen, M.A. & Chuang, I.L. (2010). Quantum Computation and Quantum Information. Cambridge University Press.
3. [Qiskit Textbook](https://qiskit.org/textbook/ch-states/index.html) (especially the chapters on quantum states, gates, and measurement)

<ins>Math Tools/Techniques</ins>:<br>
- Linear Algebra: State vectors, matrix representations of quantum gates, the Bloch sphere, eigenvalues and eigenvectors.
- Abstract Algebra: Understanding the structure and composition of gates (unitary operations).
- Probability: Calculating measurement probabilities from quantum states.

<ins> Example Problems </ins>
Easy Level: 
- Goal: Make a qubit so that measuring in the Z basis gives a 50% chance of getting |0> and 50% chance of getting |1>.
   Solution: Apply Hadamard gate to |0>

- Goal: Make sure measurement in Z basis always gives |1⟩.
   Solution: Apply X gate to |0>

Intermediate:
- Goal: With two qubits, create a Bell state (measure either and get perfectly correlated outcomes).<br>Solution: Apply Hadamard on the first, CNOT between first and second.

- Goal: Make a qubit so that measurement in the X basis gives 100% chance of |+⟩.<br>Solution: Apply Hadamard gate to |0> (to get |+>)

Advanced:
TBD

<ins> Next steps </ins>
- To further expand/advance my project, I want to increase the complexity and depth of the game by creating more advanced and complex problems. 
- I also want to explore using machine learning to allow the game to adapt to different learning styles and rates.

<ins> My goals </ins>: <br>
Through Math Quantum, I was able to deepen my knowledge of quantum topics like entanglement, interference, gates, and measurements. I got exposed to such a variety of real-world applications and learning methods and was able learn from research students and physicists. In the future, I really want to continue doing research in Math, particularly the application of math in fields like Quantum and Machine Learning. I also want to explore the intersection of mathematics in solving real-world problems across science, technology, and education.
