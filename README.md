# DiscriminantTI
A program to calculate the Discriminant of a quadratic polynomial and the corresponding zeros for the Texas Instruments TI-84 Plus.

**Disclaimer**: I wrote this program back when I was 16. The code has not been changed ever since, however, I decided to release it now. :)

<h1>Mathematics Refresher</h1>

<h2>Quadratic function</h2>

The quadratic function is one of the form **f(x) = ax² + bx + c**. In the formula, **x** refers to an unknown variable; **a, b, and c** refer to the coefficients representing known real or complex numbers. However, coefficient **a** can not be **0**.
To solve the equation, the unknown variable **x** is also referred to as roots or zeros, can be solved as follows:<br>
<br>
![image](https://github.com/user-attachments/assets/7f61349e-b457-4647-b61e-d35ab87e1b99)
<br>

Whereas the plus-minus symbol should be solved separately, resulting in two roots.<br>
<br>
![image](https://github.com/user-attachments/assets/50b940dc-e1eb-4814-b999-53bc7b9f180b)
![image](https://github.com/user-attachments/assets/085a38da-3b0c-41e5-9128-ac2f54e92ab2)
<br>
<br>
Under the root, the quantity **Δ = b² - 4ac** is known as the discriminant of the quadratic equation.

<h2>Discriminant</h2>
The discriminant in this case refers to a polynomial function of the coefficients of the original polynomial. As referred to above, the program will cover the quadratic polynomial <b>ax² + bx + c = 0</b>, whereas the discriminant of the quadratic polynomial is <b>b² - 4ac</b>.
<br>
<h3>Assumptions</h3>
<b>If a ≠ 0</b>; the discriminant is zero <b>if and only if</b> the polynomial has a double root.<br>
<b>If real coefficients</b>; the discriminant is positive <b>if</b> the polynomial has two disctinct real roots.<br>
<b>If real coefficients</b>; the discriminant is negative <b>if</b> the polynomial has two disctinct complex conjugate roots.<br>

<h2>Coding the program</h2>
<h3>Info</h3>
This program was coded to enhance the efficiency of solving the discriminant and finding the zeros during my classes of mathematics. It's developed to use on the Texas Instruments TI-84 Plus calculators.<br>
<br>
The program captures the quadratic formula by user input of <b>a, b, and c</b>. 
<br>
<h3>Mathematics behind the program</h3>
As an example, in function <b>f(x) = 4x² - 6x + 2</b>, we understand that <b>a = 4</b>, <b>b = -6</b>, and <b>c = 2</b>.<br>
<br>
Solving the Discriminant goes as follows:<br>
<b>f(x) = 4x² - 6x + 2</b><br>
x = (-6)² - 4.4.2<br>
x = 36 - 32<br>
x = 4<br>
<br>
X is positive in this case, meaning that there are two real roots.<br>

<b>x = [-b ± √(b2 - 4ac)]/2a</b><br>
x = [-(-6) ± √((-6)² - 4.4.2)]/2.4<br>
x = [6 ± √4]/8<br>
x = (6 - 2)/8 and (6 + 2)/8<br>
x = 0.5 and x = 1<br>

In the quadratic function <b>f(x) = 4x² - 6x + 2</b> the parabola will have zeros at <b>x = 0.5</b> and <b>x = 1</b>.

<h3>Setup</h3>
Installing programs on the Texas Instruments TI-84 Plus calculator requires you, to install the TI Connect CE software.
Link: https://education.ti.com/en/products/computer-software/ti-connect-ce-sw
