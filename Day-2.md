# Hoisting:

- _Hoisting is a phenomenon in javaScript by which we can access the variables and functions even before we have initialized it or put some value in it, without getting any error_

<img align="center" width="500" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQDd8wjzWTO-Z1PLtQF1r6a9hTxzvoY31oIxg&usqp=CAU">

---

# SHORTEST JS Program 🔥window & this keyword

- this point to the window object
- window is actually a global object which was created along with the global execution context
- when a js program is run global object is created , global execution context is created and this variable is created
- this === window
- whenEver a execution context created , this created along with it , this is created in case of functional execution context as well global execution context
- Global space => any code we have written in js , which in not inside a function
- anything which is not inside any function is called global space

---

# undefined vs not defined in JS 🤔

<img align="center" width="500"  src="https://i.stack.imgur.com/0YSyJ.jpg">

---

- not defined => not been allocated memory
- undefined => js allocated undefined to memory , it is like a placeholder , consume memory
- js is a loosely typed language , it doesn,t attach to a variable of specific dataType
- also called as weekly typed language

  ***

# The Scope Chain, 🔥Scope & Lexical Environment

<img width="500" align="center" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTpXavc1ckOjh-AkflA_TyjgYUwTmb1fbiBJg&usqp=CAU">

---

- scope => where we can access a specific variables and function of code
- scope is directly depend upon lexical environment
- whenever a execution context is created , lexical environment is also created
- lexical environment is the local memory along with the lexical environment of the parent
- lexical => where the code present physically inside the code
- scope chain => the chain of all lexical environment and the parent
