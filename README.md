# 2D Translation in Computer Graphics

## 📌 Description

2D Translation is a fundamental operation in computer graphics used to move an object from one location to another in a 2D plane. It is simple and effective. This transformation works by adding specific values to the x and y coordinates of each point of the object. These values, known as the **translation factors**, determine how far the object moves along the horizontal and vertical axes. 

By incrementally updating the coordinates, 2D translation efficiently shifts the entire shape without altering its size, orientation, or shape. This technique is often used in animation, object positioning, and interaction design.

In this project, we have illustrated how a square can be translated (moved) on a 2D plane using Python and Matplotlib.

---

## 📊 Algorithm: 2D Translation of a Square

**Step 1:** Define the original square using its four corner points `(x, y)`.  
**Step 2:** Set the translation values:  
- `move_right` → how much to move along the X-axis  
- `move_up` → how much to move along the Y-axis  

**Step 3:** For each point in the square, apply translation:  
- `new_x = x + move_right`  
- `new_y = y + move_up`  
Store the translated points in a new list.  

**Step 4:** To close the square properly, append the first point at the end of both the original and translated point lists.  

**Step 5:** Separate x and y coordinates from both lists for plotting.  

**Step 6:** Plot both the original and translated squares using Matplotlib.  
- Use different colors for clarity (e.g., green for original, magenta for translated).  

**Step 7:** Add labels, axis, grid, and display the final figure showing the translated square.

---

## 🖼 Output

The output will show the original square and the translated square on a 2D coordinate plane with proper labels and color distinction.

---

## 📁 Technologies Used

- Python
- Matplotlib

