# Useful functions for creating art

When recreating an image, there are a few simple functions which can make it easier.
These will be listed on this page.

## Linear functions

For a project like this, these are most easily written in point slope form, as follows

| Equation             | Copyable                    |
|----------------------|-----------------------------|
| \\(y=y_1-m(x_1-x)\\) | `y=y_1-m\left(x_1-x\right)` |

## Quadratic functions

These are easily written in either vertex form or factored form.

| Form     | Equation                | Copyable                                  |
|----------|-------------------------|-------------------------------------------|
| Vertex   | \\(y=a(x-h)^2+k\\)      | `y=m\left(x-h\right)^2+k`                 |
| Factored | \\(y=a(x-r_1)(x-r_2)\\) | `y=a\left(x-r_1\right)\left(x-r_2\right)` |
| Standard | \\(y=ax^2+bx+c\\)       | `y=ax^2+bx+c`                             |

## Exponential functions

Given 
\\[a\\text{ is a real number}\\\\b\gt1\\\\c\ne0\\\\(h,k)\\text{ are real numbers}\\]
You can use the general exponential formula provided below.

| Equation            | Copyable                   |
|---------------------|----------------------------|
| \\(ab^{c(x-h)}+k\\) | `ab^{c\left(x-h\right)}+k` |

The point \\((h,k)\\) defines the vertical and horizontal shift. 
If one equals zero, then it can be omitted. 

\\(a\\) and \\(c\\) are the vertical and horizontal stretch, respectively.
If one equals one, then it can be omitted.
\\(a\\)'s sign (\\(+\\) or \\(-\\)) defines whether it curves up or down.

\\(b\\) is the base of the exponential equation, and defines how "tightly" it curves upwards.
It can never be omitted.

## Rational Functions
Rational functions are written as the ratio between two polynomial functions. 
Note that constants such as \\(2\\) or \\(\pi\\) are still polynomial.

| Equation                    | Copyable                                   |
|-----------------------------|--------------------------------------------|
| \\(\frac{P_1(x)}{P_2(x)}\\) | `\\frac{P\left(x\right)}{Q\left(x\right)}` |

where \\(P_1(x)\\) and \\(P_2(x)\\) are both polynomial functions

### Special case: \\(\frac{1}{x}\\)
Likely the most useful rational equation when making art is \\(\frac{\text{constant}}{\text{linear}}\\)
It's full form is \\(\frac{a}{x-b}+c\\)—or `\frac{a}{x-b}+c`—given the following:
\\[a\ne0\\\\b\text{ and }c\text{ are real numbers}\\]
\\(a\\) defines how closely it curve towards the asymptotes as well as which direction it curves. 
It can never be omitted.
\\(b\\) and \\(c\\) equal the vertical and horizontal asymptotes, respectively. 
If either is zero, it can be left out.

## Implicit Circle Function
It can be written in two main ways: the magnitude of a point, and the distance function.

Given radius \\(r\\), midpoint \\((a,b)\\), and shift \\((x_1,y_1)\\)

| Equation                                                            | Copyable                                                                      |
|---------------------------------------------------------------------|-------------------------------------------------------------------------------|
| \\(\frac{(x-a)}{x_1}^2+\frac{(y-b)}{y_1}^2=r^2\\)                   | `\frac{\left(x-a\right)}{x_{1}}^{2}+\frac{\left(y-b\right)}{y_{1}}^{2}=r^{2}` |
| \\(\left\|\left(\frac{x-a}{x_1},\frac{y-b}{y_1}\right)\right\|=r\\) | `\left\|\left(\frac{x-a}{x_{1}},\frac{y-b}{y_{1}}\right)\right\|=r`           |