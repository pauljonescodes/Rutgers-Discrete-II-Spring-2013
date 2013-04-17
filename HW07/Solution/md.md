Paul Jones\
Rutgers University\
CS206: Introduction to Discrete Structures II, Spring 2013\
Professor David Cash\

Homework 7

**Instructions:** Point values for each problem are listed. Write your
solutions neatly or type them up. Typed solutions will also be accepted
via Sakai.

1.  (1.5 points each) Find the generating function for the sequence
    $a_0, a_1, a_2, \ldots$, where $a_k$ is each of the following. Your
    solution does not need to be closed form.

    1.  $a_k = $ the number of solutions to $e_1 + e_2 + e_3 = k,$ where
        $0 \leq e_i \leq 4$ for each $i$.

        $$(1 + x^1 + x^2 + x^3 + x^4)^3$$

    2.  $a_k = $ the number of solutions to $e_1 + e_2 + e_3 + e_4 = k,$
        where $0 \leq e_i < 4$ for each $i$, $e_1$ is odd, and $e_2$ is
        even.

        $$(x^1 + x^3)(x^0 + x^2)(1 + x^1 + x^2 + x^3 + x^4)^2$$

    3.  $a_k = $ the number of solutions to $e_1 + e_2 + e_3 + e_4 = k,$
        where $0 \leq e_i$ for each $i$.

        $$\left(\sum_{i = 0}^{\infty} x^i \right)^4$$

    4.  $a_k = $ the number of solutions to
        $e_1 + e_2 + e_3 + e_4 + e_5= k,$ where $0 \leq e_i$ for each
        $i$, $e_1$ and $e_3$ are odd, and $e_2$ is even.

        $$\left(\sum_{i = 0}^{\infty} x^{2i + 1} \right)^2 \times \left(\sum_{i = 0}^{\infty} x^{2i} \right) \times \left(\sum_{i = 0}^{\infty} x^{i} \right)^2$$

2.  (3 points each) Model the following problems using a generation
    function, which does not need to be in closed form:

    1.  Count the number of outcomes of rolling $6$ dice that sum to
        $r$.

        $$(x_1 + x_2 + x_3 + x_4 + x_5 + x_6)^6, \: 1 \le x_i \le 6$$

    2.  Count the number of outcomes of rolling $6$ dice that sum to
        $r$, where the first three dice are odd and the last three are
        even.

        $$(x_1 + x_3 + x_5)^3 \times (x_2 + x_4 + x_6)^3, \: 1 \le x_{2i + 1} \le 3, 0 \le x_{2i} \le 2$$

    3.  Count the number of outcomes of rolling $6$ dice that sum to
        $r$, where for each $i$ the $i$-th dice is not equal to $i$ (so
        the first die is not $1$, the second is not $2$, and so on).

        $$= (x^2 + x^3 + x^4 + x^5 + x^6) \times (x^1 + x^3 + x^4 + x^5 + x^6) \times$$
        $$(x^1 + x^2 + x^4 + x^5 + x^6) \times (x^1 + x^2 + x^3 + x^5 + x^6) \times$$
        $$(x^1 + x^2 + x^3 + x^4 + x^6) \times (x^1 + x^2 + x^3 + x^4 + x^5)$$

3.  (1.5 points each) Find the following coefficients. Show your work.

    1.  The coefficient of $x^{10}$ in the series expansion of
        $(x^5+x^6 + x^7+ \cdots)^8$.

        $$\mathrm{DNE}$$

    2.  The coefficient of $x^{20}$ in the series expansion of
        $(x+x^2 + x^3+x^4+x^5) (x+x^2 + x^3+x^4+\cdots)^5 $.

        $$18 \choose 14$$

    3.  The coefficient of $x^{12}$ in the series expansion of
        $x^2/(1+x)^8$.

        $$8 + 10 - 1 \choose 10$$

    4.  The coefficient of $x^{12}$ in the series expansion of
        $1/(1+x^3)^2$.


