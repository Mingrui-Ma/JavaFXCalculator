# JavaFXCalculator
A simple calculator app written in Java, with GUI created using JavaFX.

Note that JavaFX does not come with Java SE by default, so computers without it installed will not be able to run this application. JavaFX can be downloaded at https://github.com/openjdk/jfx.

Note also that the JavaFX JARs need to be added to the IDE's build path for the JavaFX packages to be recognized.


Run the application from Main.java (or Main.class).
Main.java invokes methods defined in Methods.java.

Features:
- All the basic arithmetic functions, clear and backspace buttons.
- Multiple leading zeros will be trimmed down to 1.
- Consecutive operation button presses will overwrite the last operation (e.g. pressing "1" "+" "/" "1" will input "1/1").



TwoOpsCalculator.java is a separate file. It does not have a GUI, instead uses the console. It accepts input of mathematical operations with two steps (e.g. 1+2\*3) and calculate the result, with operation priorities taken into consideration (e.g. the previous example will calculate 1+(2\*3) ). Each character (except numbers with more than one digit) needs to be followed by a space.
