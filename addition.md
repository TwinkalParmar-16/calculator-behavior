# Addition

## Scenario: Addition of two positive numbers

- Given: On the calculator
- When: Enter first "positive number",
  and then enter "plus" operator,
  and enter second "positive number",
   and press "equals".
- Then: Display "added number" as the result.

## Scenario: Addition of two negative numbers

- Given: On the calculator
- When: Enter first "negative number",
  and then enter "plus" operator,
  and enter second "negative number",
   and press "equals".
- Then: Display "added number" as the result.

## Scenario: Addition of fractions

- Given: On the calculator
- When: Enter first "decimal point number",
  and then enter "plus" operator,
  and enter second "decimal point",
   and press "equals".
- Then: Display "added number" as the result.

## Scenario: Addition of positive and negative number

- Given: On the calculator
- When: Enter first "positive number or negative number",
  and then enter "plus" operator,
  and enter second "negative number or positive number",
   and press "equals".
- Then: Display "added number" as the result.

## Scenario: Addition of decimals

- Given: On the calculator
- When: Enter first "decimal point number",
  and then enter "plus" operator,
  and enter second "decimal point",
   and press "equals".
- Then: Display "added number" as the result.

## Scenario: Typing operator more than once

- Given: On the calculator
- When: Enter first "number",
  and then enter "plus" operator,
  and enter again any "operator",
   and press "equals".
- Then: Use last operator and show result accordingly result.

## Scenario: Addition of more than two numbers

- Given: On the calculator
- When: Enter first "number",
  and then enter second "number",
   and press "equals".
- Then: Display "added number" as the intermediate result.
- When: Again press "add" operator,
         then enter third "number",
         then press "equal".
- Then: Use intermediate result as first number and add third
        number with this as second number and
        display the final result.

## Scenario: Adding numbers where the result goes out of range

- Given: On the calculator
- When: Enter first "number",
  and then enter "plus" operator,
  and enter second "number",
   and press "equals".
- Then: Display the result in some power plus number.

## Scenario: 6+* as an input

- Given: On the calculator
- When: Enter "6",
  and then enter "plus" operator,
  and enter "star" operator,
   and press "equals".
- Then: Use * as operator and wait for second operand.

## Scenario: Identity operation

- Given: On the calculator
- When: Enter first "number",
  and then enter "plus" operator,
   and press "equals".
- Then: Use "Identity element" as a second input and add this with first number.
        Display "added number" as the result.

## Scenario: Converse operation

- Given: On the calculator
- When: Enter first "number",
  and then enter "plus" operator,
  and then enter "second" number,
   and press "equals".
- Then: Interchange given input numbers and
        display "added number" as the result.
