# Javascript the good parts
## Douglaus Crocford

## Worlds most understood Programming language
### Language of contrasts

* Cut and pasters 
* computer scientists

### Complaints
* Java script is not a language I know
* The browser programming experience is awful
* Its not fast enough
    * Google developing faster engine
    * Dom is the problem
* The language is just a pile of mistakes

### Java script influence
* Self
    * prototypical inheritiance
    * dynamice objects
* scheme
    * lamda
    * loose typing
* Perl
    * syntax
    * conventions
* java
    * regular expresssions

### The bad parts
* Global Variables
* + adds and concatenates
* Semicolon insertion
* typeof
* with and eval
* phony arrays
* == and !=
    * crazy transitivity 
* false, null, undefined, NaN
* object return undefined if value not part of object

### Good fetures that interact badly
* Object inherit from other objects
* Functions can be members of objects
* for..in statment mixes inherited functions with the desired data members
### for in is troublesome
* Desgin question should for..in do a shallow skim or a deep dredge
* Decision: Deep Dredge. Thr programmer must explicitly filter out the deep members
* Except they didn't tell anybody
* Consquence: lots of confusion
* Better decision: Don't release language until we know the right answer
### Bad Heritiage
* Blockless statements
* Expression statements
* Floating point  arithmetic
* ++ and --
* switch
### The Good Parts
* Lamda
* Dynamic Objects
* Loose typing
* Object Literals
### Inheritiance
* Inheritance is object-oriented code reuse
* Two schools
    * Classical
    * Prototypal
### Prototypal Inheritance
* Class-free
* Objects inherit from objects
* An object contains a link to another object
    * Delegation, differencial inheritance
    * Object.create
### New
* The new operator is required when calling a constructor function
* if new is omited is omitted, the global object is clobbered by the constructor.
* there is no compiled time or runtime warning
### Global
* use closer
* module pattern
### power constrcutors
1. Make an object
    * Object literal
    * new
    * object.create
    * call another power constructor
2. Define some variables and functions
3. Augment the object with privileged methods
4. return the object
### Closure
* a function object contains
    * a function 
    * reference to the enviornment it was created
### Style
```
block {
...
}
```
Works well in javascript
```
block
{
...
}
```
Does not work well in javascript
## Working with the grain
### Beautiful Code
### JSLint
* Jslint defines a professional subset of JavaScript
* It imposes a programming discipline
* http://www.jslint.com
* JSlint will hurt your feelings
### Unlearning is really hard
* Perfectly Fine == Faulty

### Coming Soon
* ECMAScript Fourth Edition
* Corrections
* Reality
* support for object hardening
* strict mode for reliabilty
* waiting on implimentations

### Not Coming Soon
* ES4 - cancelled
* Instead, [ES-Harmony]
* So for this project has no defined goals or rules
### Safe Subsets
* The most effective way to make this language better is to make it smaller
* FBJS
* Caja and Cajita
* ADsafe
* These subsets will be infoming the design and new secure language to replace javascript.
### Review the good parts
* Your java script application can reach billions
* if you avoid the bad parts JS works really well. There is some brilliance in it
* it is possible to write good programs.


