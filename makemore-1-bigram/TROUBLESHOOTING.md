1. **problem**: Although the sum of N has been executed without keepdim=True, there came the desired result. <br> <br> 
   **cause**: Owing to the trait of the dataset. / At any string in which a character appears the character is followed by a character, at the same time preceded by another. Therefore characters excluding special characters(".") has the same number of followed-by and preceded-by. <br><br>
   **check**: Comparing the result of N.sum(0), N.sum(1), they were same.<br>
2. 