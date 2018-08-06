# Name : Snip_Example_1

## Description :
This example is the first of the class, which help us understand different primitive coercion and primitive types.


## Main learning objective
1. primitive coercion 
2. primitive types
3. Creating our first end-to-end snippet exercice

the code it, copy pasted for later reference

exercises & study links.  
	pytut: live link
	replit: complete link, step-throughs, exercises
	debugger: snippets directly in the text
	sketches you made

helpful link.  urls to good online resources that cover this feature of js

example: https://github.com/elewa-academy/block-scope-let-vs-var#index
## Code
~~~~
typeof (typeof Number(void Boolean(null))).toString();
  // S0 : (Null, null)
  Boolean(null);
  
  
  // S1 : (Boolean, false)
  void false;
  // S2 : (Undefined, undefined)
  Number(undefined);
  // S3 : (Number, NaN);
  (typeof NaN);
  // S4 : (String, "number")
  ("number").toString();
  // S5 : (String,"number")
  typeof "number";
  // S6 : (String,"String")
~~~~

<iframe height="400px" width="100%" src="https://repl.it/@Ludovic7127/IroncladWebbedOutcome?lite=true" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>
