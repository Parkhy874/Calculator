# Calculator
It calculate two integers.

<!doctype html>
<html>
   <head>
      <title> 계산기 </title>
   </head>
   <body>
<script>
    var num1 = Number(prompt("첫 번째 정수를 입력하세요:"));
    var num2 = Number(prompt("두 번째 정수를 입력하세요:"));
    
    document.write("<h2> 사칙연산 계산기 </h2>");
    document.write("<hr>" + "<br>");
    document.write("첫 번째 수: " + num1 + "<br>");
    document.write("두 번째 수: " + num2 + "<br><br>");
    
    document.write("덧셈: " + num1 + " + " + num2 + " = " + (num1 + num2) + "<br>");
    document.write("뺄셈: " + num1 + " - " + num2 + " = " + (num1 - num2) + "<br>");
    document.write("곱셈: " + num1 + " × " + num2 + " = " + (num1 * num2) + "<br>");
    document.write("나눗셈: " + num1 + " / " + num2 + " = " + (num1 / num2) + "<br>");
</script>
   </body>
</html>
