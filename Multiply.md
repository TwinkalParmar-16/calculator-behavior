# Multiplication

## Scenario: Result Overflow

- Given: On the calculator
- When: Enter first "number",
  and then enter "multiply" operator,
  and enter second "number",
   and press "equals".
- Then: Display the result in some power plus addition number.

## Scenario: Both negative number

- Given: On the calculator
- When: Enter first "negative number",
  and then enter "multiply" operator,
  and enter second "negative number",
   and press "equals".
- Then: Display the result in positive number.

## Scenario: If one number is negative

- Given: On the calculator
- When: Enter first "number",
  and then enter "multiply" operator,
  and enter second "number",
   and press "equals".
- Then: Display the result in negative number.

## Scenario: Multiplication with zero

- Given: On the calculator
- When: Enter first "number",
  and then enter "multiply" operator,
  and enter zero,
   and press "equals".
- Then: Display zero as the result.

## Scenario: Multiplication with one

- Given: On the calculator
- When: Enter first "number",
  and then enter "multiply" operator,
  and enter one,
   and press "equals".
- Then: Display first number as the result.

## Scenario: Decimal value multiplication

- Given: On the calculator
- When: Enter first "decimal number",
  and then enter "multiplication" operator,
   then enter second "decimal number",
   and press "equals".
- Then: Display "multiplied number" as the result.

## Scenario: Irrational value multiplication

- Given: On the calculator
- When: Enter first "irrational number",
  and then enter "multiplication" operator,
   then enter second "irrational number",
   and press "equals".
- Then: Display "multiplied number" as the result.

## Scenario: Simple multiplication

- Given: On the calculator
- When: Enter first "number",
  and then enter "multiplication" operator,
  and enter second "number",
   and press "equals".
- Then: Display "multiplied number" as the result.

## Scenario: Rational multiplication

- Given: On the calculator
- When: Enter first "rational number",
  and then enter "multiplication" operator,
  and enter second "rational number",
   and press "equals".
- Then: Display "multiplied number" as the result.

## Scenario: Decimal & integer multiplication

- Given: On the calculator
- When: Enter first "Decimal number",
  and then enter "multiplication" operator,
  and enter second "integer number",
   and press "equals".
- Then: Display "multiplied number" in the decimal as the result.

## Scenario: More than two numbers multiplication

- Given: On the calculator
- When: Enter first "number",
  and enter "multiplication" operator,
  and then enter second "number",
   and press "equals".
- Then: Display "multiplied number" as the intermediate result.
- When: Again press "multiplication" operator,
         then enter third "number",
         then press "equal".
- Then: Use intermediate result as first number and add third
        number with this as second number and
        display the final "multiplied number" as result.

## Scenario: Complex number multiplication

- Given: On the calculator
- When: Switch to complex number multiplication mode.
  Enter first "complex number",
  and then enter "multiplication" operator,
  and enter second "complex number",
   and press "equals".
- Then: Display "multiplied complex number" as the result.

## Scenario: Range of operand exceeds allowed limit

- Given: On the calculator
- When: Enter first "number" in some power plus number,
  and then enter "multiplication" operator,
  and enter second "number" in some power plus number,
   and press "equals".
- Then: Display the result in some power plus addition number.

## Scenario: Pressing "multiply button" multiple times

- Given: On the calculator
- When: Enter first "number",
  and then enter "multiplication" operator,
  and then enter "multiplication" operator,
  and enter second "number",
   and press "equals".
- Then: Use only one multiplication operator and display "multiplied" result.

## Scenario:Interleaving operators

- Given: On the calculator
- When: Enter first "number",
  and then enter "multiplication" operator,
  and then some irrelevant operator.
  and enter second "number",
   and press "equals".
- Then: Prefer the last operator.
       Display result accordingly.

## Scenario: Decimal value capping

- Given: On the calculator
- When: Enter first "decimal number",
  and then enter "multiplication" operator,
  and enter second "decimal number",
   and press "equals".
- Then: Display "multiplied number" with n number after decimal as the result.
