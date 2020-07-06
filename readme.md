Using TypeScript for Front-End App Development
1. VSCode IDE  recommended https://code.visualstudio.com
2. Runtime Engine, Node.js, https://www.nodejs.org

======================================================================
Installing TypeScript
1. npm install -g typescript
   1. The 'npm' the node package manager utility, that downloads the typescript from https://www.npmjs.com and installs in global scope
   2. This provides a CLI of name 'tsc'
      1. The 'tsc' is command for 
         1. TypeScript Language Configuration
         2. TypeScript Compilation and File Merging
2. Compile the TypeSCrit file , the 'Transpilation'
   1. tsc <SOURCE-FILE>.ts
      1. Generate the <SOURCE-FILE>.js
3. The 'tsc -init' command
   1. Generate the 'tsconfig.json' file
      1. The TypeScript Language Configuration file for the application
4. The 'npm init -y', the command generate  the 'package.json'
   1. The package.json is the file that is used for the Front-End runtiome configuration

======================================================================
ES 6
- High-Level JavaScript aka Modern-JavaScript aka ES6
  - ES 2015 library
- TypeScript
- Dart
- ES 7 --> ES 2016
- ES 8 --> ES 2017
- ESNext (ES 9+) --> ES 2018 +

ES 6 --> Complted into  ES 5 --> COmpiled into ES 3 <--- Browser Compatible

Programming with TypeScript with ES 6 Concepts
1. Scope Definition for Variable
   1. the 'let' keyword is used to define a block socpe for a varible declaration in TypeScript
   2. The 'var' is the function-scope declaration, the 'let' is the block scope declaration  
2. DataTypes
   1. Numeric --> number
   2. String --> string
   3. Array --> []
   4. Date --> date / Date
   5. Boolean --> boolean
   6. Object Type --> object and {} (ES 3+)
      1. Everything is object
   7. Union Types
      1. Declaring a varibale using 'More-than-One' datatypes 
   8. any --> any , the runtime Type Setting (late binding)
   9.  void --> void
3.  Iterators aka looping
    1.  for..loop (ES 3+ aka traditional JavaScript)
    2.  for..in loop (ES +)
    3.  for..of loop (ES 6 aka Itarators)
4.  rest parameters
    1.  Dynamic parameters to Method in ES  6
5. Arrays
   1. The Standard Interface in ES 6 with various methods
      1. Simple ES 3, ES 5 maniupulation methods
         1. push(), pop(), indexOf(), shifht(), unshift(), splice(), slice(), etc.
      2. ES 6 methods
         1. sort(), reverse()
         2. filter(), to retuen subset of array  based on condition
         3. forEach(), the itartion
         4. map(), iterate and return each element
         5. find(), search a record, (ES 6 method not by default availabe in TypeScript)    
6. Template String
   1. The new synatx for building the mutable string object with the string HTML expressions
      1. `${<STRING-EXPRESSION>}`
7. Arrow Operators
   1. If a method has input parameter as 'Callback function' then use 'Arrow Operator' for passing the impmentation
   2. SYntax -->
      1. => 
8. Functions
9.  Object Oriented Programming
10. Modules