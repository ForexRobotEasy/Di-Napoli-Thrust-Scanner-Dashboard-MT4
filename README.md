# Di Napoli Thrust Scanner Dashboard MT4

This code is a sample implementation of the Di Napoli Thrust Scanner Dashboard for MetaTrader 4 (MT4). It is designed to scan for Di Napoli thrust patterns across multiple timeframes and display the results on a customizable dashboard.

## Product Description

The Di Napoli Thrust Scanner Dashboard MT4 is a powerful tool for forex traders. It utilizes the Di Napoli thrust pattern, a popular trading concept, to identify potential trading opportunities. This code provides a sample implementation of the scanner and dashboard functionality, allowing traders to customize their scanning criteria and view the results in a user-friendly dashboard.

## Features
- Scans multiple timeframes: The code is designed to analyze markets on different timeframes, providing a comprehensive view of potential thrust patterns across various trading horizons.
- Customizable thrust definition: Traders can customize the number of bars above and below the DMA (Defined Moving Average) for defining a thrust, allowing for flexibility in pattern identification.
- User-friendly dashboard: The results of the scanning process are displayed on a dashboard, which uses graphical objects, labels, and indicators to present the information in an easy-to-understand format.
- Customization preferences saving: The code also includes functionality to save user-defined customization preferences, allowing traders to retain their preferred settings across different sessions.

## How it Works

The code is structured into several functions, each responsible for a specific task:

1. `OnStart()`: This is the main entry point of the code. It calls the other functions in a specific order to perform the scanning, customization, display, and preference saving tasks.
2. `ScanForDinapoliThrustPatterns()`: This function implements the scanning algorithm. It analyzes markets on different timeframes and detects Di Napoli thrust patterns based on predefined criteria.
3. `CustomizeThrustBars()`: This function provides an interface for users to input the number of bars above and below the DMA for defining a thrust. It updates the global variables `BarsAboveDMA` and `BarsBelowDMA` based on user input.
4. `DisplayResults()`: This function displays the results on the dashboard. It utilizes appropriate graphical objects, labels, and indicators to present the information in a visually appealing and informative manner.
5. `SaveCustomizationPreferences()`: This function saves the user-defined customization preferences. It stores the values of `BarsAboveDMA` and `BarsBelowDMA` in a file or database for future use.

Please note that ForexRobotEasy is not the official developer of this product. This code is provided as a sample implementation that can work as described in the product. To find the official developer of this product, please refer to the MQL5 platform or visit the following link for detailed reviews and trading results: [Di Napoli Thrust Scanner Review - Optimize Forex with MT4 Dashboard](https://forexroboteasy.com/forex-robot-review/di-napoli-thrust-scanner-review-optimize-forex-with-mt4-dashboard/).
