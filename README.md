# Shoo 🧮

A TUI for mathematical training.

## Motivation

I find going online and searching for new practice problems for calculus, linear algebra, and differential equations exhausting. This app generates as many problems as you want (without AI) so you can just focus on learning.

## Goals

### Screen 1

- [ ] Ask if the user wants to practice differentiation, integration, or differential equations

### Screen 2

- [ ] Generate a random problem based on the previous screen's choice
- [ ] Display an Anki-like interface with the problem in the middle of the screen
- [ ] A text box to input your answer (an integer)
- [ ] A "verify" button to check if you were right or wrong
- [ ] A "show answer" button
- [ ] A "skip problem" button to regenerate a new problem.

## Timeline

### 0.1
 - [ ] Generate a random `n` and random `N` and display `y^[N](n)` (the `N`th-order derivative of `y(x)` when `x = n`)
 - [ ] Generate a random `f(x)` of Power rule form `f(x) = m(x^B) + b` for some random `B`
 - [ ] When the user presses space, compute `y^[N](n)` and display it to them
 - [ ] When the user presses space again, clear the screen and display the next problem (goto point 1)
### 1.0
  - [ ] Add the following [types](https://allen.in/jee/maths/derivatives) of questions:
    - [ ] Product rule
    - [ ] Quotient rule
    - [ ] Chain rule
    - [ ] Trig
      - [ ] Sin
      - [ ] Cos
      - [ ] Tan
      - [ ] Cosec
      - [ ] Sec
      - [ ] Cot
      - [ ] Arcsin
      - [ ] Arccos
      - [ ] Arctan
      - [ ] Arccosec
      - [ ] Arcsec
      - [ ] Arccot
