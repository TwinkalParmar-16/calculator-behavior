# Subtraction

## Scenario: Subtraction of two positive numbers

- Given: On the calculator
- When: Enter first "positive number",
  and then enter "minus" operator,
  and enter second "positive number",
   and press "equals".
- Then: Display "subtracted number" as the result.

## Scenario: Subtraction of two negative numbers

- Given: On the calculator
- When: Enter first "negative number",
  and then enter "minus" operator,
  and enter second "negative number",
   and press "equals".
- Then: Display "subtracted number" as the result.

## Scenario: Subtraction of fractions

- Given: On the calculator
- When: Enter first " fraction number",
  and then enter "minus" operator,
  and enter second "fraction point",
   and press "equals".
- Then: Display "subtracted number" as the result.

## Scenario: Subtraction of positive and negative number

- Given: On the calculator
- When: Enter first "positive number or negative number",
  and then enter "subtract" operator,
  and enter second "negative number or positive number",
   and press "equals".
- Then: Display "subtracted number" as the result.

## Scenario: Subtraction of decimals

- Given: On the calculator
- When: Enter first "decimal point number",
  and then enter "minus" operator,
  and enter second "decimal point",
   and press "equals".
- Then: Display "subtracted number" as the result.

## Scenario: Typing operator more than once

- Given: On the calculator
- When: Enter first "number",
  and then enter "plus" operator,
  and enter again any "operator",
   and press "equals".
- Then: Will prefer the first operator and display "subtracted number"
        as the result.

## Scenario: Subtraction of more than 2 numbers

- Given: On the calculator
- When: Enter first "number",
  and enter "minus" operator,
  and then enter second "number",
   and press "equals".
- Then: Display "subtracted number" as the intermediate result.
- When: Again press "minus" operator,
         then enter third "number",
         then press "equal".
- Then: Use intermediate result as first number and add third
        number with this as second number and
        display the final "subtracted number" as result.

## Scenario: Subtraction of numbers where the result goes out of range

- Given: On the calculator
- When: Enter first "number/large size number",
  and then enter "minus" operator,
  and enter second "number/large size number",
   and press "equals".
- Then: Display the result within range.

## Scenario: 6+* as an input

- Given: On the calculator
- When: Enter "6",
  and then enter "plus" operator,
  and enter "star" operator,
   and press "equals".
- Then: Will prefer the first operator and wait for next input.

## Scenario: Identity operation

- Given: On the calculator
- When: Enter first "number",
  and then enter "minus" operator,
   and press "equals".
- Then: Use "Identity element" as a second input and add this with first number.
        Display "subtracted number" as the result.

## Scenario: Converse operation

- Given: On the calculator
- When: Enter first "number",
  and then enter "minus" operator,
  and then enter "second" number,
   and press "equals".
- Then: Display "subtracted number" as the result.
