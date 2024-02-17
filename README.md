# CALCULATORUSINGHTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Calculator</title>
    <!-- Google Font -->
    <link
      href="https://fonts.googleapis.com/css2?family=Roboto+Mono:wght@500&display=swap"
      rel="stylesheet"
    />
    <!-- Stylesheet -->
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="calculator">
      <div class="display">
        <input type="text" placeholder="0" id="input" disabled />
      </div>
      <div class="buttons">
        <!-- Full Erase -->
        <button value="AC" id="clear" class="operation-button" >AC</button>
        <!-- Erase Single Value -->
        <button value="DEL" id="erase" class="operation-button" >DEL</button>
        <button value="/" class="operation-button button">/</button>
        <button value="*" class="operation-button button" >*</button>

        <button value="7" class="digit-button button" />7</button>
        <button value="8" class="digit-button button" />8</button>
        <button value="9" class="digit-button button" />9</button>
        <button value="-" class="operation-button button" />-</button>

        <button value="6" class="digit-button button" />6</button>
        <button value="5" class="digit-button button" />5</button>
        <button value="4" class="digit-button button" />4</button>
        <button value="+" class="operation-button button" />+</button>

        <button value="1" class="digit-button button" />1</button>
        <button value="2" class="digit-button button" />2</button>
        <button value="3" class="digit-button button" />3</button>

        <button value="=" id="equal" class="operation-button" />=</button>
        <button value="0" class="digit-button button" id="zero" />0</button>
        <button value="." class="digit-button button" />.</button>
      </div>
          <div class="main" >
              <p class="brand">Developed by
                  <a href="https://acecoder.org/" target="_blank">ACE CODER</a> 🔥</p>
          </div>
    </div>
    <!-- Script -->
    <script src="script.js"></script>
  </body>
</html>
