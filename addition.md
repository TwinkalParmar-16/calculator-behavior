# Addition

## Scenario: Addition of two positive numbers

- Given: The calculator is turned on
- When: Enter first "positive number",
  and then enter "plus" operator,
  and enter second "positive number",
   and press "equals".
- Then: Display "added number" as the result.

## Scenario: Addition of two negative numbers

- Given: The calculator is turned on
- When: Enter unary minus,
  and then first "number",
  and then enter "plus" operator,
  and enter unary minus,
  and then second "number",
  and press "equals".
- Then: Display "added number" as the result.

## Scenario: Addition of fractions

- Given: The calculator is turned on
- When: Enter first "decimal point number",
  and then enter "plus" operator,
  and enter second "decimal point",
   and press "equals".
- Then: Display "added number" as the result.

## Scenario: Addition of positive and negative number

- Given: The calculator is turned on
- When: Enter first "positive number or negative numberusing unary minus operator",
  and then enter "plus" operator,
  and enter second "negative number using unary minus operator or positive number",
   and press "equals".
- Then: Display "added number" as the result.

## Scenario: Addition of decimals

- Given: The calculator is turned on
- When: Enter first "decimal point number",
  and then enter "plus" operator,
  and enter second "decimal point",
   and press "equals".
- Then: Display "added number" as the result.

## Scenario: Typing operator more than once

- Given: The calculator is turned on
- When: Enter first "number",
  and then enter "plus" operator,
  and enter again any "operator",
   and press "equals".
- Then: Display "error message" as the result.

## Scenario: Addition of more than 2 numbers

- Given: The calculator is turned on
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

- Given: The calculator is turned on
- When: Enter first "number/large size number",
  and then enter "plus" operator,
  and enter second "number/large size number",
   and press "equals".
- Then: Display "Out of range message" as the result.

## Scenario: 6+* is provided as input

- Given: The calculator is turned on
- When: Enter "6",
  and then enter "plus" operator,
  and enter the second "mutiplication" operator,
   and press "equals".
- Then: Display "Invalid input message" as the result.

## Scenario: Identity operation

- Given: The calculator is turned on
- When: Enter first "number",
  and then enter "plus" operator,
   and press "equals".
- Then: Use "Identity element" as a second input and add this with first number.
        Display "added number" as the result.

## Scenario: Converse operation

- Given: The calculator is turned on
- When: Enter first "number",
  and then enter "plus" operator,
  and then enter "second" number,
   and press "equals".
- Then: Interchange given input numbers and
        display "added number" as the result.
