# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## 🧠 Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## 🧾 Program

    x=np.array([10, 20, 30, 40, 50])
    y = np.array([15, 20, 25, 35, 60])
    indices = np.where(x >= y)

    indices=np.where(x>=y)
    print("Indices where x >= y :",indices)
## Output

<img width="1247" height="58" alt="image" src="https://github.com/user-attachments/assets/1d8e8e19-35ac-4720-9075-7e5ef293a00a" />

## Result

Thus the python program using numpy to find the indices where elements i array 'x' are graeter than or equal to corressponding elements in array 'y'
, is written and executed successfully.
