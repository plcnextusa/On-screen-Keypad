# On-screen-Keypad

1. Download the sample project.
2. Import the "Keypad" eHMI Page and the NumericKeypad Function Block into your project.
3. Add an instance of the "NumericKeypad" Function Block to a Program.  This Program should be scheduled in a Task with an Interval that is twice as fast as the eHMI Data poll        interval.
4. Use a "Text" object, not a "Text Input" object, in your HMI where a numeric value entry field is needed.
5. Add an "Action on Click" dynamic to this "Text" object.
    a. Set the "Action" to "Open dialog".
    b. For "Page" select "Keypad".
    c. Optionally, check the box to "Dim background".
    d. Select your desired variable as the Source Value for the Parameter "Data".
6. Repeat steps 4 and 5 to add as many input fields as needed for your application.
