# UnitConvertulator
![LMCface GHcanvas](screen-shot_01.png)

UnitConvertulator is a hybrid unit converter and calculator designed for product designers, architects, engineers, fabricators, and anyone who regularly works between Imperial and Metric dimensions.

I work in product design for commercial architecture in the US so end up doing a steady stream of annoying unit conversion math. Lots of "how much space is left in the 14' 3 3/8" room if the 62.75in table has 18mm edge brackets on it?" type questions.

Constantly switching between dimension converters and calculators was slowly driving me crazy so I made this **hybrid converter/calculator**.

You can enter basic units and instantly see what they convert to without fussing with a bunch of drop-down menus.

**Math expressions** are supported using `+`, `-`, `*`, and `/` with parentheses grouping using `()`. Unitless scalar multiplication and division are allowed, so **`(1m+1m)*2` is `4m`**.

Addition and subtraction values need a unit type as either abbreviation or standard Imperial foot/inches shorthand: **`1m + 11' 6 2/3" + 250mm`**

**Do not use US architectural shorthand with "-" between feet and inches.** Enter **`1' 8"`** instead of **`1'-8"`**.

**Weights or Lengths** are auto detected and displayed in the correct table.

Click on any number in the conversion table to **copy it to the clipboard**.

## Features

- Instant conversion between Imperial and Metric units
- Built-in calculator with support for:
  - Addition (+)
  - Subtraction (-)
  - Multiplication (*)
  - Division (/)
  - Parentheses grouping ()
- Automatic detection of Length and Weight inputs
- Fractional inch output with selectable rounding
- One-click copy to clipboard for all conversion results
- Input history for quick recall of previous calculations

## Examples

### Basic conversions

```text
250mm
18.5in
1m
10g
5lb
```

### Mixed-unit calculations

```text
1m + 11' 6 2/3" + 250mm
```

### Scalar multiplication and division

```text
(1m + 1m) * 2
```

https://www.pyottdesign.com
