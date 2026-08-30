# Stepper — Design system

A numeric input control with increment and decrement buttons — for adjusting a value by discrete steps, such as quantity, duration, or count.

Source: https://www.checklist.design/design-system/stepper

## Items

### Increment and decrement controls
Buttons on either side of the numeric display for adjusting the value up or down by a fixed step

### Direct text entry
The ability to type a value directly into the display field, in addition to using the buttons.

_Tip: Suitable for use case where value change could have large jumps e.g. more than 10_

### Min and max bounds
Defined minimum and maximum values the stepper will not exceed, with the relevant button visually disabled when a boundary is reached

_Tip: Disable the stepper at the minimum/maximum when reached, instead of hiding the controls_

### Step size
The amount by which the value changes per button press — typically 1, but configurable for units like 5, 10, or 0.5

### Input validation
Handling of values entered directly that fall outside the min/max range or contain non-numeric characters

### Size variants (if needed)
Small, medium, and large sizes for different contexts — a compact quantity selector in a product card vs. a settings input

### Keyboard support
Arrow keys incrementing and decrementing the value when the input is focused
