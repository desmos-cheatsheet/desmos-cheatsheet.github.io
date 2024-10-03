# List Broadcasting

List broadcasting allows for lists to interact with scalar values and other lists.
Additionally, a list can be passed into a function which would normally only accept a scalar value, and the value will be broadcasted into the function.
This causes the function to be called on each element of the list, and then to return a list of each output.

Assume the following variables in the table:

\\[L=[1,2,3]\\\\L_2=[4,5,6]\\]

| Example                       | Copyable                             | Output        |
|-------------------------------|--------------------------------------|---------------|
| \\(L^2\\)                     | `L^2`                                | \\([1,4,9]\\) |
| \\(\operatorname{mod}(L,2)\\) | `\operatorname{mod}\left(L,2\right)` | \\([1,0,1]\\) |
| \\(\operatorname{mod}(L)+1\\) | `\operatorname{mod}\left(L\right)+1` | \\([4,5,6]\\) |
| \\(L_2-L\\)                   | `L_2-L`                              | \\([3,3,3]\\) |

# List Comprehension

