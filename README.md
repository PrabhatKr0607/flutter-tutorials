# flutter-tutorials
It contains the following components:

MyApp class: This is a stateless widget that returns a MaterialApp widget. The MaterialApp widget sets the title, theme, and home for the app.

Calculator class: This is a stateful widget that returns the _CalculatorState widget.

_CalculatorState class: This is a stateful widget that contains the logic for the calculator. It has several fields like output, _output, num1, num2, and operand to keep track of the calculation.

buttonPressed function: This function is called when a user presses a button on the calculator. It updates the values of _output, num1, num2, and operand based on the button text.

buildButton function: This function returns a button widget for the calculator. It takes in a button text and returns an Expanded widget with an OutlineButton child. The OutlineButton child has a child that displays the button text and an onPressed function that calls the buttonPressed function.

build function: This function returns the body of the calculator app. It contains a Scaffold widget with an app bar and a body. The body of the calculator contains a Column widget with several Container widgets to display the buttons and the output.
