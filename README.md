# Laboratório da Conjectura de Collatz - Collatz Lab ♾️

[Português](#português) | [English](#english)

---

## Português

Um ambiente computacional interativo projetado para explorar, visualizar e documentar o comportamento do problema <i>3n+1</i> (Conjectura de Collatz), um dos enigmas mais notórios e fascinantes da Teoria dos Números e dos Sistemas Dinâmicos.

### 🎯 Sobre o Projeto

A Conjectura de Collatz propõe que, ao aplicar uma regra simples a qualquer número inteiro positivo, a sequência inevitavelmente alcançará o ciclo trivial 4 → 2 → 1.

* **A Regra:** Se o número for par, dividir por 2; caso seja ímpar, multiplicar por 3 e somar 1, ou seja:

<blockquote>
  <i>f(n)</i> = <br>
  &nbsp;&nbsp;&nbsp;&nbsp; <b><i>n</i> / 2</b>, se <i>n</i> é par <br>
  &nbsp;&nbsp;&nbsp;&nbsp; <b>3<i>n</i> + 1</b>, se <i>n</i> é ímpar
</blockquote>

> **💡 Curiosidade Computacional:** Até o momento, projetos de supercomputação já testaram e confirmaram a conjectura para todos os números inteiros até 2<sup>68</sup> (aproximadamente 2,95 × 10<sup>20</sup>, ou 295 quintilhões). Nenhum contraexemplo foi encontrado nessa vasta imensidão de números, todos eles eventualmente retornam para 1!

Apesar de sua formulação elementar, a prova matemática formal desta conjectura tem desafiado os maiores matemáticos do mundo por décadas. Este laboratório foi construído para investigar a anatomia visual, algorítmica e algébrica desse comportamento irredutível.

### ✨ Funcionalidades e Visualizações

* 🏠 **Homepage:** Introdução contextual sobre a Irredutibilidade Computacional.
* 📈 **Órbita Única:** Gráfico de linha interativo com cálculo de tempo de parada e picos de altitude.
* 🌌 **Distribuição de Parada:** Scatter plot de alto desempenho revelando padrões de "nuvens" e fios emergentes.
* 🔭 **Espaço de Fase:** Visualização log-log demonstrando as fronteiras lineares e transições do sistema.
* ⚔️ **Divergência das 4 Forças:** Comparativo visual em escala logarítmica detalhando o embate entre o colapso exponencial (2<sup>n</sup>), o crescimento linear (3<i>n</i>+1), o passo acelerado ((3<i>n</i>+1)/2) e a divisão única (<i>n</i>/2).
* ⚙️ **Algoritmos & Complexidade:** Análise detalhada de implementações (Iterativa vs. Recursiva), limites assintóticos empíricos (≈ O(log <i>n</i>)), visualização da pilha de chamadas (<i>Call Stack</i>) e testes de performance de estresse em tempo real.
* 📚 **Matemática & Provas:** Mergulho rigoroso na falha dos métodos tradicionais de prova, no Teorema do 1-Ciclo e no colapso da propriedade multiplicativa nos fatores primos.

### 🛠️ Tecnologias Utilizadas

* **HTML5 / CSS3:** Estruturação semântica e Dark Mode nativo.
* **Vanilla JavaScript (ES6+):** Lógica matemática e motores de simulação otimizados para o navegador.
* **[Chart.js](https://www.chartjs.org/):** Renderização de alta performance para milhares de pontos.
* **[MathJax](https://www.mathjax.org/):** Renderização profissional de equações matemáticas.

### 🚀 Como Acessar e Executar

Acesse online: [https://jluckmay.github.io/Collatz-Lab/](https://jluckmay.github.io/Collatz-Lab/))

Para rodar localmente (*zero-setup*):
1. Clone o repositório: `git clone https://github.com/jluckmay/collatz-lab.git`
2. Abra o arquivo `collatz.html` em seu navegador moderno de preferência.

---

## English

An interactive computational environment designed to explore, visualize, and document the behavior of the <i>3n+1</i> problem (Collatz Conjecture), one of the most notorious enigmas in Number Theory and Dynamical Systems.

### 🎯 About the Project

The Collatz Conjecture proposes that by applying a simple rule to any positive integer, the sequence will inevitably reach the trivial cycle 4 → 2 → 1.

* **The Rule:** If the number is even, divide it by 2; if it is odd, multiply it by 3 and add 1:

<blockquote>
  <i>f(n)</i> = <br>
  &nbsp;&nbsp;&nbsp;&nbsp; <b><i>n</i> / 2</b>, if <i>n</i> is even <br>
  &nbsp;&nbsp;&nbsp;&nbsp; <b>3<i>n</i> + 1</b>, if <i>n</i> is odd
</blockquote>

> **💡 Computational Curiosity:** To date, supercomputing projects have tested and verified the conjecture for all integers up to 2<sup>68</sup> (approximately 2.95 × 10<sup>20</sup>, or 295 quintillion). Not a single counterexample has been found in this vast ocean of numbers; they all eventually drop back to 1!

Despite its elementary formulation, a formal mathematical proof has eluded the world's greatest mathematicians for decades. This lab investigates the visual, algorithmic, and algebraic anatomy of this irreducible behavior.

### ✨ Features and Visualizations

* 🏠 **Homepage:** Contextual introduction regarding Computational Irreducibility.
* 📈 **Single Orbit:** Interactive line chart tracing the chaotic path, stopping time, and peak altitude values.
* 🌌 **Stopping Distribution:** High-performance scatter plot mapping emergent "cloud" and thread patterns for thousands of numbers.
* 🔭 **Phase Space:** Log-log visualization mapping <i>n<sub>i</sub></i> → <i>n<sub>i+1</sub></i> transitions and linear boundaries.
* ⚔️ **The 4 Forces Divergence:** Visual log-scale comparison detailing the clash between exponential collapse (2<sup>n</sup>), linear growth (3<i>n</i>+1), the accelerated step ((3<i>n</i>+1)/2), and the single division (<i>n</i>/2).
* ⚙️ **Algorithms & Complexity:** Detailed breakdown of iterative vs. recursive implementations, empirical asymptotic bounds (≈ O(log <i>n</i>)), step-by-step Call Stack visualization, and live JS engine stress tests.
* 📚 **Math & Proofs:** Rigorous deep dive into the failure of traditional proof methods, the 1-Cycle Theorem, and the collapse of the multiplicative property in prime factors.

### 🛠️ Technologies Used

* **HTML5 / CSS3:** Semantic structure and native Dark Mode.
* **Vanilla JavaScript (ES6+):** Math logic and simulation engines optimized for the browser.
* **[Chart.js](https://www.chartjs.org/):** Core rendering library with heavy parsing optimizations.
* **[MathJax](https://www.mathjax.org/):** Clean and professional mathematical equation rendering.

### 🚀 How to Access and Run

Live Demo: [https://jluckmay.github.io/collatz-lab](https://jluckmay.github.io/collatz-lab)

To run locally (*zero-setup*):
1. Clone the repository: `git clone https://github.com/jluckmay/collatz-lab.git`
2. Double-click `collatz.html` to open it in any modern browser.

---

## 👨‍💻 Autor / Author

**João Lucas Mayrinck**
* Computer Scientist & Software Developer
* [LinkedIn](https://www.linkedin.com/in/jluckmay) | [GitHub](https://github.com/jluckmay)

## 📄 Licença / License

This project is under the MIT License. See the [LICENSE](LICENSE) file for details.

---
*“Mathematics may not be ready for such problems.”* — Paul Erdős
