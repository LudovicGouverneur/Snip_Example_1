# Snip_Example_1

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
