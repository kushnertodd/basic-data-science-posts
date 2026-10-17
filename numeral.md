## Positional numeral systems

A *positional* or *place value* numeral system consists of numerals made of one or more symbols from a limited set, called **digits**. Each digit has an inherent value, called its face value, but its contribution to the overall number changes depending on its position within the numeral.

A positional system is classified by its **base** (*b*), which is the number of unique digits used by the system. These digits correspond to the whole numbers from *0* up to *b-1*.
The *radix point* is a symbol within the numeral used to separate the whole number part from the fractional part (a value between 0 and 1).
The place value of a position is the base raised to an [exponent]([*exponent*](https://colab.research.google.com/github/kushnertodd/basic-data-science-posts/blob/main/basic_data_science_python_mathematics_exponents.ipynb)) based on its position relative to the radix point (e.g., $b^2, b^1, b^0$ to the left; $b^{-1}, b^{-2}$ to the right).
The total value contributed by a single digit is its face value multiplied by its place value.

| position | $2$ | $1$ | $0$ | .   | $-1$ | $-2$ | $-3$ |
| :-      | :-: | :-: | :-: | :-: | :-:  | :-:  | :-: |
| digit | $$d_2$$ | $$d_1$$ | $$d_0$$ |  | $$d_{-1}$$ | $d_{-2}$ | $d_{-3}$ |
| exponents | $b^2$ | $b^1$ | $b^0$ | | $b^{-1}$ | $b^{-2}$ | $b^{-3}$ |
| value | $d_2 \cdot b^2$ | $d_1 \cdot b^1$ | $d_0 \cdot b^0$ | | $d_2 \cdot b^{-1}$ | $d_1 \cdot b^{-2}$ | $d_0 \cdot b^{-3}$ |

