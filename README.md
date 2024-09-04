NUMERICAL PYTHON (NUMPY)

NORMALIZATION PROBLEM
![image](https://github.com/user-attachments/assets/3ee1fd8f-100f-408d-81fc-4e6ebaa3d12a)

My Code:

![image](https://github.com/user-attachments/assets/84ccab15-753a-40cb-97d3-61156ed453d2)

The code starts by generating a 5x5 numpy array filled with random values. Next, it calculates the mean and standard deviation of all the elements in this array. Then normalizing the array by subtracting the calculated mean from each element and then dividing by the standard deviation.  Finally, the code prints the original random array, followed by the calculated mean, standard deviation, and the normalized array. 

Output:

![image](https://github.com/user-attachments/assets/f9e56b75-e003-4d45-9c6d-cc37d5ce645e)

DIVISIBLE BY 3 PROBLEM:
![image](https://github.com/user-attachments/assets/6cef66de-f92d-498d-a233-474ecd68af27)

My code:

![image](https://github.com/user-attachments/assets/32384ac8-32ba-44e2-8087-e5abe201bcad)

I generate an array of the first 100 positive integers using numpys arange function. Each of these integers is then squared to create a new array z, resulting in a 10x10 ndarray where each element represents the square of numbers from 1 to 100. The problem objective is to identify and extract all elements within this squared array that are divisible by 3. This is achieved by applying a boolean indexing z % 3 == 0, which evaluates each element for divisibility by 3 and retains only those that satisfy the condition. Then the original squared array and elements only the squares divisible by 3is printed.

Output:

![image](https://github.com/user-attachments/assets/5faabbbf-fea5-4f9e-b964-e961fb42e45a)

