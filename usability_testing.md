# Automata Editor Test Plan

This document describes test plan for undergoing usability testing for Automata Editor app for iPad.

# Questionnaire

Before the usability test, users will be asked to fill the following questionnaire: https://docs.google.com/forms/d/16YkE5JZvU2bGc1R7KDfI15QZhxEB7MHhzYkodjPQfmY

This questionnaire will be used to assess users' previous experience that can then result in different results when performing test tasks and can help with identifying the underlying design and UX issues the app might have.

# Introduction to the Test

The participants should be instructed to perform tasks described below.
Tasks will be in a random order and the participants will not know the tasks in advance. This is to simulate as much as possible how users would interact with the app outside of the testing environment.

Participants will be asked to share their thought process aloud - if they are comfortable with it.

# Tasks to Perform

### Task A:

Create the following automaton:

![](basic_automaton.png)

Simulate following inputs:
- AA
- BA
- B

### Task B:

Create the following automaton:

![](automaton_cycle.png)

Simulate following inputs:
- DDE
- DEF
- DE

### Task C:

Create the following automaton:

![](bidirectional_automaton.png)

- 010101
- 001011
- 1001


### Task D:

Create the following automaton:

![](epsilon_automaton.png)

- A
- BA
- AB
- ABB

### Task E:
Create automaton for the following language:
L = {(10)^n : n ε Ν}

Simulate following inputs:
- 101
- 1010
- 101010
- 1

### Task F:

Create automaton for the following language: 
L = { w : w ε {0,1}* Λ w starts with the string 011}

Simulate following inputs:
- 01
- 0111
- 0110