# Calculator Application Study

## Application Name

Simple Calculator

## URL

https://dunizb.github.io/sCalc/

## Features Observed

- Performs basic arithmetic operations (Addition, Subtraction, Multiplication, Division)
- Supports decimal number calculations
- Displays results instantly after calculation
- Includes a Backspace button to delete the last entered digit
- Includes a History feature to view previous calculations
- Includes an AC (All Clear) button to reset the calculator

## Buttons Available

- Numbers (0–9)
- Addition (+)
- Subtraction (-)
- Multiplication (×)
- Division (÷)
- Decimal (.)
- Equals (=)
- All Clear (AC)
- Backspace
- History

## Observations

- The calculator has a clean and user-friendly interface.
- The default display value is **0**.
- Pressing **=** without entering any values keeps the display at **0**.
- Dividing a number by **0** displays **Infinity**.
- The calculator does not allow multiple decimal points in the same number (e.g., 1.2.3).
- Keyboard input is not supported; only on-screen buttons can be used.
- Parentheses **( )** are not available for complex expressions.
- The History button stores previous calculations.
- The Backspace button removes the last entered character.

  # Additional Testing Observations

## Large Number Multiplication

- **Input:** 999999999999 × 999999999999
- **Actual Result:** 1.00E+24
- **Observation:** Calculator displays the result in scientific notation.

## Zero Divided by Zero

- **Input:** 0 ÷ 0
- **Actual Result:** NaN
- **Observation:** Calculator returns "NaN" instead of a user-friendly error message.

## Leading Zeros

- **Input:** 0005 + 05
- **Actual Result:** Leading zeros cannot be entered.
- **Observation:** The calculator automatically prevents unnecessary leading zeros.

## Repeated Operator Input

- **Input:** Press + multiple times without entering numbers.
- **Actual Result:** No change; display remains 0.
- **Observation:** The calculator ignores repeated operator input.

## Repeated Equals Input

- **Input:** Perform a calculation and press = multiple times.
- **Actual Result:** Result remains unchanged.
- **Observation:** The calculator does not repeat the last operation.

## Decimal Precision

- **Input:** 1 ÷ 3
- **Actual Result:** 16 decimal places are displayed.
- **Observation:** The calculator provides high decimal precision.

## Backspace on Default Screen

- **Input:** Press Backspace when display shows 0.
- **Actual Result:** No change; display remains 0.
- **Observation:** Backspace is ignored when there is nothing to delete.

## History After AC

- **Input:** Perform a calculation → Press AC → Open History.
- **Actual Result:** Previous calculation is still available in History.
- **Observation:** AC clears the current calculation but does not clear the history.
