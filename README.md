Bracket Matching Web Code Analyzer

This is a C program that analyzes mixed web code (HTML, CSS, JavaScript) for balanced brackets.

 Features
- Reads input until `#` is found.
- Counts and matches:
  - `{}` Curly braces
  - `()` Round brackets
  - `<>` Angle brackets
- Checks balance and reports mismatches.
- Classifies pairs as:
  - INSUFFICIENT (<5)
  - MODERATE (5–10)
  - SUFFICIENT (>10)

## Example
Input:
```html
<html>
 <head>
 <style>
 body { background-color: lightblue; }
 h1 { color: navy; }
 </style>
 </head>
 <body>
 <h1 onclick="alert('Hi!')">Click me</h1>
 <script>
 function sayHello() {
 alert("Hello!");
 }
 </script>
 </body>
</html>
#
