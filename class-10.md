### JavaScript, Chapter 10

7 types of built-in error objets
| Object | Description |
|---|---|
Error | Generic error
Syntax Error | Syntax has not been followed
Reference Error | Tried to reference a variable that is not declared/within scope
TypeError | An unexpected data type that could not be coerced
RangeError | Numbers not in an acceptable range
URIError | encodeURI(), decodeURI(), and similar methods used incorrectly
EvalError | eval() function used incorrectly

* The word `debugger` in your code will make a breakpoint there.  
* If you know your code might fail, you can use try, catch, and finally:  
```
try {
    // Try to execute the code
} catch (exception) {
    // If there is an exception, run this code
} finally {
    // This always gets executed
}
```

