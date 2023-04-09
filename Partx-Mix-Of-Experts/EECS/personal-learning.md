EECS: Electrical Engineering and Computer Science Development and Usage
Author: Yiyun
Date: 2022-08-29

Part 1: Electrical Engineering and Electronics
Humans have developed an understanding of electromagnetic fields through phenomena such as magnetic effects, electric effects, electromagnetism, and electromagnetic induction. The widespread use of electricity has led to the emergence of electrical engineering and electronics as a discipline. With a stable power supply, we can achieve numerous applications through electrification, with electronics playing a major role.

We define devices based on the voltage-current relationship across their terminals. Different topologies of two-port devices form networks, which can be described using systems of equations (e.g., node analysis) and linear algebra. Some devices have voltage-current relationships involving time derivatives (e.g., capacitors and inductors), which are described using calculus. The introduction of these devices leads to nonlinear equations, and we employ various methods to analyze them. In these analyses, we study mathematical physics to specifically analyze circuits and electromagnetic field-related equations.

Classical signal and system theories are highly effective in these analyses. Definitions of input-output, time domain, and frequency domain are application-oriented abstractions that are very practical. These ideas are very beneficial in advanced fields such as image and audio processing, as well as high-frequency circuits and antennas.

Part 2: Computer Science
A bit is an object that can have two states, either 0 or 1. By arranging 0s and 1s, we can achieve various different states. In some applications, we use mathematical bases to represent these objects.

We have basic input-output units such as diodes, transistors, and logic gates. These units can map specific input (arrangements of 0s and 1s) to different outputs. Although circuits are static from input to output, they fundamentally change over time.

By introducing the concept of time and digital circuits with clocks, we create finite state machines with small memory units that change states between different clock cycles. To enable our finite state machines to handle more complex problems, we use instructions to characterize the direction of state changes, memory (registers) to store the units uniformly, and processors (more complex combinational logic circuits) to transform the current state into the next state.

As our state machines grow larger, we use linear address memory (registers) to store the current state, processors to transform the current state into the next state according to the current instruction, and matching software instructions. Our instructions can perform mathematical operations (defined by combinational circuits), logical operations (defined by combinational circuits), and data movement (defined by combinational circuits).

The arrangements of bits represent data, which can characterize images, audio, video, text, and other information combinations through the definition of input and output devices (specific encoding and decoding methods).

By transforming these arrangements, performing mathematical operations, and inventing networks for data transmission (communication) between different machines, we can achieve different results.

In the process of practical implementation, we often use specific paradigms of instruction set combinations.

Functions
We refer to a series of instructions that process some inputs to outputs as a function. When processing another input, the same set of instructions can be used. To avoid writing the same code, we use function calls to solve this problem, saving storage space for code and the programmer's effort. The concept of functions first appears in assembly language.

Iteration and Recursion
We often perform similar or identical operations on an object multiple times, arranging instructions in a loop to save space and the programmer's effort. In this process, we often use a memory unit for counting. In assembly language, we often use this method.

Recursion occurs when a function calls itself, greatly simplifying the problem