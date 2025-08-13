This Flutter application fulfills the requirements of the Solid Software test task for the Junior Flutter Engineer position. The app displays the text "Hello there" in the center of the screen. Tapping anywhere on the screen changes the background to a random RGB color with a smooth animation.
Features

Displays "Hello there" in the center of the screen.
Changes the background to a random RGB color (16,777,216 possible colors) on tap.
Uses AnimatedContainer for a smooth 500ms color transition.
Compliant with solid_lints for clean code practices.
No external libraries used for color generation (relies on dart:math for random values).

Requirements

Flutter SDK (version 3.0.0 or higher)
Dart SDK (version 2.12.0 or higher)
solid_lints for static code analysis

Setup Instructions

Clone the repository:git clone https://github.com/EissaShehab/SolidSoftwareTestTask.git


Navigate to the project directory:cd SolidSoftwareTestTask


Install dependencies:flutter pub get


Run the app:flutter run



Code Analysis

The code adheres to solid_lints guidelines, ensuring clean and maintainable code.
Run flutter analyze to verify no warnings or errors.

Notes

The app uses dart:math for random color generation, which is a core Dart library and not an external package.
The animation duration is set to 500ms for a smooth user experience.
