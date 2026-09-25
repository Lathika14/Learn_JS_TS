Datatypes
-->type of information you store
primitive and non primitive
-->0bject specific array
decimdl
number -> whole
string -> name, address
boolean - > true, false
undefined-> variable declared but no value assigned var data

null-->intentionally to make the varible null (not using the value)
var data-null

biglnt-->long numbers

symbol-- > unique information-->accessed in the way of object type

var tr=Symb01("id")


var(1995) -->keyword to declare a variable to 2015 till ES6 intoduce
var

var data=98
var -> variable declaration
data - > variable name
98-> value assigned

var
=====
What
Var is the oldest way to declare variables in JavaScript (before ES6).
2015 - intro let, const

Scope behavior
  Function-scoped
  Not block-scoped (ignores { } blocks like if,
Redeclaration & reassignment
Redeclaration allowed
Reassi nment allowed
for)

var comName="TestLeaf"
var comName="Qeag1e"
Problems
 Can cause unexpected bugs
 Values may change unintentionally
 Not recommended in modern JavaScript

let
What
let is a modern variable declaration introduced in ES6
Scope behavior
Block-scoped
Limited to { } block (if, for, while, etc.)
Redeclaration & reassignment
Redeclaration not allowed in same scope
Reassignment allowed
Why let is better than var
Prevents accidental overwrites
ore predictable behavior
Recommended for variables that change 


const 
What
const is used to declare constant values.
Scope behavior
Block-scoped (same as let)
Redeclaration & reassignment
Redeclaration not allowed
Reassignment not allowed
Must be initialized at declaration
Important note (Objects & Arrays)
const prevents reassignment, not modification


Why const preferred
Ensures safety
Improves readability
Prevents accidental reassignment