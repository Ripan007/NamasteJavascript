# How javaScript works and how the code is executed ?

## _Everything in javaScript happens inside an "Execution Context"_

-we can assume that "Execution Context" to be a big box or a container in which whole javaScript code is executed.

<img align="center" width="500" height="300" src="https://miro.medium.com/max/1052/1*2oAKZtsRSn_vWfJeHHWwYQ.png">

---

- Execution context has two components:

1. Memory component
   - Where all the variables and funtions are stored as key-value pairs
   - Also called as 'variable environment'
2. Code component
   - where whole js code is executed
   - Code is executed one line at a time
   - Also called as 'thread of execution'
   - it is just like a thread in which the whole code is executed one line at a time

---

## _javaScript is a synchronous single-threaded language_

- Single-threaded : execute one command at a time
- Synchronous-singleThreaded : execute one command at a time in specific order
- it can only goes to the next line ones executing the 'currentLine'

---

<img align="center" width="500" height="300" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQOSYeQ6tce8fI2zSlPos1osMg9GybUergPtQ&usqp=CAU">

## _Summary_

1. As soon as the whole javaScript code is run , 'Execution-context' is created or the 'Gobal-execution' context is created
2. It has two components memory && code => created in two phases

---

## Memory creation phases(1)

- Allocating memory to all variables and functions inside the 'global-space(inside the whole program)'
- In case of variables undefined assigned
- In case of functions whole copy of the function

---

## Code execution phase(2)

- replace variable undefined with the value
- encounter a function(function envocation) => Execution context is created and ones again same process repeat '{(1)(2)}'

---

## Call Stack:

- Every time in the bottom of the stack have 'Global exection context'
- whenever js code is run => whole 'Execution context is pushed to the stack'
- function is envoked => execution context is created => it again pushed to the stack
- ones functtion is executed it pop out of the stack => control goes to 'Global execution context'
- ones whole code get executed call stack get empty => global execution context also gone
- this way we are done with our javaScript program
- call stack also called by different name:

  - Execution context stack
  - program stack
  - control stack
  - Runtime Stack
  - machine stack

  ***

## _Call stack maintains the order of execution of execution context_
