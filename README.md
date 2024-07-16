JS-Interpreter
==============

A sandboxed JavaScript interpreter in JavaScript.  Execute arbitrary ES5
JavaScript code line by line in isolation and safety.

> This fork is mainly a copy of the original [JS-Interpreter](https://github.com/NeilFraser/JS-Interpreter), made (somewhat) importable as an ECMAscript module:
> 
> `import 'https://rozek.github.io/JS-Interpreter/dist/acorn_interpreter.esm.js'` <br>
> `const { Interpreter } = window`
> 
> or (dynamically)
>
> `await import('https://rozek.github.io/JS-Interpreter/dist/acorn_interpreter.esm.js')` <br>
> `const { Interpreter } = window`
>
> which I need to import the interpreter on demand only.

Live demo:
https://neil.fraser.name/software/JS-Interpreter/

Documentation:
https://neil.fraser.name/software/JS-Interpreter/docs.html

Developers using JS-Interpreter should subscribe to the announcement newsgroup.
Security issues and major changes will be posted here:
https://groups.google.com/g/js-interpreter-announce
