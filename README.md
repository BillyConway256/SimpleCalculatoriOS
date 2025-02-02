# Simple Calculator Application

This project is a simple, non-functional calculator designed in Swift to meet the design requirements for Module 3. The primary goal of this project is to demonstrate the use of StackViews and adaptive UI design techniques that work across all device size classes (including iPads) and support landscape orientation.

## Project Overview

- **Non-Functional Calculator:**  
  This project focuses solely on the user interface design. While the layout mimics a traditional calculator (with a display and a grid of buttons), it does not perform any arithmetic calculations.

- **UI Design with StackViews:**  
  The layout is entirely built using `UIStackView` objects. A main vertical stack view organizes the screen into a display area and multiple horizontal rows of buttons, each equally distributed for a consistent look and feel.

- **Responsive Design:**  
  Auto Layout constraints and safe area guides are used to ensure that the interface adapts gracefully to all size classes and orientations, including both portrait and landscape modes.

## Features

- **Display Label:**  
  A top label is used to represent the calculator’s display. It is styled with a large font and right alignment.

- **Button Grid:**  
  Four rows of buttons are implemented (for numbers and basic operations) using nested horizontal stack views, each ensuring equal spacing and size.

- **Adaptive Layout:**  
  The application utilizes Auto Layout to maintain usability across iPhones, iPads, and different orientations.

## Requirements

- **Development Environment:**  
  Xcode with Swift 5 or later

- **Minimum iOS Version:**  
  iOS 13.0


