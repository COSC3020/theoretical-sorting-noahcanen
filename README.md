# Theoretical Sorting

A Computer Science researcher claims to have come up with a sorting algorithm
that can sort arbitrary elements in $O(n)$ time based on comparisons of two
elements at a time. This would be asymptotically faster than any known general
sorting algorithm. The algorithm itself is proprietary and will be sold by a
company.

How would you verify this claim? You may assume that you have access to a
black-box implementation of the sorting algorithm, i.e. you cannot examine the
source code, but you can use it to sort any list you like. Explain in detail
your method for investigating whether X is correct, including any expected
results you would get.

Also give a theoretical argument for why X could or could not be correct, based
on the complexity of the general sorting problem we covered in class.

Add your answers to this markdown file.

How would you verify this claim? 


I would start by running it through lists of various sizes, both sorted and unsorted. Then, if it truly sorts the lists, I will graph how long it took to sort each list. If its claims are true, then this should be linear. 


give a theoretical argument for why X could or could not be correct, based
on the complexity of the general sorting problem we covered in class.


Any algorithm that compares two elements simultaneously cannot achieve a time complexity better than O(nlogn). So, algorithm X cannot be correct; it either doesn't properly sort some types of lists or doesn't do it inside a complexity of O(n).




For this assignment, I used the resources of https://www.geeksforgeeks.org/time-complexities-of-all-sorting-algorithms/, https://www.geeksforgeeks.org/sort-the-array-according-to-their-cubes-of-each-element/, https://www.geeksforgeeks.org/timsort/

"I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice."
