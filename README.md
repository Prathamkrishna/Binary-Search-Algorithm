# Binary-Search-Algorithm

Working of the Binary Search Algorithm:
-> It has a function called "binarysearch" which is going to be our main function for this program.
-> The first step is checking if the rightmost value is greater than leftmost element. If that is not the case, then it returns -1 from the function to the "result section" for      the printing steps.
-> If rightmost value is greater than leftmost elment then the following steps are executed.
-> Now, the "num" variable created with a value is compared with the middle most element.
-> If these values match, then it exits the function, thereby returning this value to "result".
-> When the above case does not match, the next case is executed.
-> This checks if the "num" is located on the right or the left side of the middle element. 
-> If this "num" lies to the right side of the middle element, it returns back to the "binarysearch" function with new parameters.
-> If the above two cases don't match, then the program moves to the last case i.e execute the code for the case that "num" lies to the left side of the middle element.
-> Next, this code returns "binarysearch" function with new parameters.
-> The above steps are repeated until either righmost element is less than or equal to leftmost element to which it returns a value. If any case of "num" matches the "mid"            element, then it returns to "result" section and printing.

Point to note: The file was not opening on github when I saved it with a .ipynb extension so used a .py extension.
Built on Jupyter Notebook.
