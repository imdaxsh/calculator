<h2>Simple Calculator Using HTML, CSS, and JavaScript </h2> 
<h2>Index</h2>
    This description contains the following title  
    <h6> Introduction</h6>
    <h6> Plan</h6>
    <h6> Execution</h6> 
<h2>Introduction</h2>

This calculator can perform basic mathematical operations like addition, subtraction, multiplication, and division.

![pic 1](https://user-images.githubusercontent.com/88918534/165801269-adce15a5-c8e1-4fad-911a-5f8938c11bb6.png)
 
<h2>Plan</h2>
 
Here, the structure and buttons of this calculator are basically made using HTML programming code. The CSS code helped to transform it into a Neumorphism design. This calculator is enabled using JavaScript code.
To create it, first, you need to create an HTML and CSS file. Of course, you can attach the CSS file to the HTML file. Then copy the structure below and add it to the HTML file. In the structure below I have given complete information on how you can add other codes to the file.

<h2> Execution </h2>
Step 1: Create the basic structure of the calculator 

  HTML Code:
   
   
    <!DOCTYPE html>
    <html lang="en">
    <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Darshan calculator</title>
    <link rel="stylesheet" type="text/css" href="darshancalc.css">
    </head>
     <body>
    <form class="calculator" name="calc">
        <input type="text" readonly class="value" name="txt"/>
        <span class="num clear" onclick="calc.txt.value = '' ">c</span>
        <span class="num" onclick="document.calc.txt.value +='/'">/</span>
        <span class="num" onclick="document.calc.txt.value +='*'">*</span>
        <span class="num" onclick="document.calc.txt.value +='7'">7</span>
        <span class="num" onclick="document.calc.txt.value +='8'">8</span>
        <span class="num" onclick="document.calc.txt.value +='9'">9</span>
        <span class="num" onclick="document.calc.txt.value +='-'">-</span>
        <span class="num" onclick="document.calc.txt.value +='4'">4</span>
        <span class="num" onclick="document.calc.txt.value +='5'">5</span>
        <span class="num" onclick="document.calc.txt.value +='6'">6</span>
        <span class="num plus" onclick="document.calc.txt.value +='+'">+</span>
        <span class="num" onclick="document.calc.txt.value +='1'">1</span>
        <span class="num" onclick="document.calc.txt.value +='2'">2</span>
        <span class="num" onclick="document.calc.txt.value +='3'">3</span>
        <span class="num" onclick="document.calc.txt.value +='0'">0</span>
        <span class="num" onclick="document.calc.txt.value +='00'">00</span>
        <span class="num" onclick="document.calc.txt.value +='.'">.</span>
        <span class="num equal" onclick="document.calc.txt.value =eval(calc.txt.value)">=</span>
    </form> 
</body>
</html>



 CSS Code:
   
    @import url();

    *
    {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
    }

    body
    {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background:#091921 ;
    }

    .calculator
    {
    position: relative;
    display: grid;
    }

    .calculator .value
    {
    grid-column: span 4;
    height: 100px;
    text-align: right;
    border: none;
    outline: none;
    padding: 10px;
    font-size: 18px;
    }

    .calculator span
    {
    display: grid;
    width: 60px;
    height: 60px;
    color: #fff;
    background: #0c2835;
    place-items: center;
    border: 1px solid rgba(0, 0, 0, .1);
    }

    .calculator span:active
    {
    background: #74ff3b;
    color: #111;
    }

    .calculator span.clear
    {
    grid-column: span 2;
    width: 120px;
    background: #ff3077;
    }

    .calculator span.plus
    {
    grid-row: span 2;
    height: 120px;
    }

    .calculator span.equal
    {
     background: #03b1ff; 
     }
 
 
These are the CSS programming code with which the basic structure for making this calculator has been designed. It has been converted to a Neumorphism design using its CSS code.






Step 2: Create a result box for viewing calculations
Any calculator has a box for viewing calculations. In the same way, a box is made in this calculator. Here all kinds of calculations can be seen beautifully in that box. The following programming codes have been used to create and design this box.


Step 3: Create the buttons in the calculator
Many buttons have been used for calculations. The following codes have been used to construct those buttons.

 Step 4 : Activate the buttons on the calculator 
So far we have designed this calculator but it has not been made effective. You must use JavaScript programming code to make it work. 
Using the following programming codes, I have activated these calculator push buttons, which means that when you press the buttons, the numbers at the top of the screen will appear.

Step 5: Add the following JavaScript code to calculate the inputs
I have shown above how to activate the numbers. Now I have shown how to calculate those inputs and show the results.

</body>
</html>

 


