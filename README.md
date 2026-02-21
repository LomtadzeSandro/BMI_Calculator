# BMI Calculator

BMI Calculator is an iOS application that allows users to calculate their Body Mass Index (BMI) and get advice about their health status.

## Features
- Real-time height and weight sliders
- Graphical BMI display
- Health advice and color indicator based on BMI
- Dynamic UI updates

## How it works
1. The user moves the height and weight sliders.
2. The app updates `heightLabel` and `weightLabel` with the slider values.
3. The user presses the **Calculate** button.
4. `CalculatorBrain` calculates the BMI value, corresponding advice, and color.
5. The data is passed to `ResultViewController`.
6. The UI updates to show the BMI value, advice, and background color.
7. The user can press **Recalculate** to go back to the initial screen.

## Technologies
- Swift 5
- UIKit
- Structs and MVC architecture
- Segues for navigation

## Author
Sandro Lomtadze

# BMI_Calculator
