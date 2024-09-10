# Special Indexing 

Lists are indexed by by surrounding an index with \\([\\) and \\(]\\) after a list.

| Note                                                                       | 
|----------------------------------------------------------------------------|
| Contrary to a programmer's first instinct, indices begin at one, not zero. |


Assume the following variables in the table

\\[L_1=[1...10]\\\\L_2=[1,3...9]\\\\j=3\\]

| Indexing                    | Copyable                | Purpose                                                    | Result            |
|-----------------------------|-------------------------|------------------------------------------------------------|-------------------|
| \\(L_1[j]\\)                | `L_1\left[j\right]`     | Standard indexing: Gets the \\(j\\)-*th* index of the list | \\(3\\)           |
| \\(L_1[L_2]\\)              | `L_1\left[L_2\right]`   | Get elements, where indices are defined by a list.         | \\([1,3,5,7,9]\\) |
| \\(L_1[1\dots\kern2px j]\\) | `L_1\left[1...j\right]` | Gets all elements from \\(1\\) to \\(j\\), in a list       | \\([1,2,3]\\)     |
