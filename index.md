<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Loan Calculator</title>
</head>
     <body>
        <div id="container">
        <h1>Loan Calculator</h1>
        <br>
        <p>This calculator will help you figure out monthly payments on any loan amount. Just fill in the details below and when you are done hit 'Calculate.'</p>
            <div id="calculator">
        <form>
            <label for="loanAmount">Loan Amount:</label>
            <input type="number" id="loanAmount" name="loanAmount"> <br><br>
            <label for="interestRate">Interest Rate:</label>
            <input type="number" id="interestRate" name="interestRate"><br><br>
            <label for="loanTermOption">Loan Term In </label>
                <input type="radio" id="loanTermOption" name="loanTermOption" value="years">
                <label for="loanTermOption">Years</label>
                <input type="radio" id="loanTermOption" name="loanTermOption" value="years">
                <label for="loanTermOption">Months</label><br><br>
                <label for="loanTerm">Loan Term:</label>
                <input type="number" id="loanTerm" name="loanTerm"><br><br>
            <label for="downPayment">Down Payment:</label>
            <input type="number" id="downPayment" name="downPayment"> <br><br>
            <button type="submit">Calculate</button>
            <button type="submit">Clear Form</button>
        </form>
            </div>
            <div id="calculatorResults">
                <p>For a loan amount of <span class="loanAmount">$_______</span> at an interest rate of <span class="interestRate">____%</span>, your monthly payment should be<span class="monthlyPayment"> $_______</span>.</p>
            </div>
            <div id="amortizationTable">
                <h3>Amortization Schedule</h3>
            </div>
        </div><!--End of container-->
        <script src="script.js"></script>
    </body>
</html>
