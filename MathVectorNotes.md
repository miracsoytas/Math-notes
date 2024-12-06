## 11. Vectors 1

### 1. By what number should vector \( $\mathbf{a}$ = [3, 4] \) be multiplied so that its length is equal to 1?

#### Step 1: Calculate the length (magnitude) of the vector
The formula for the magnitude of a vector \( $\mathbf{a}$
 = [x, y] \) is:
$$
\|\mathbf{a}\| = \sqrt{x^2 + y^2}
$$

For \( \mathbf{a} = [3, 4] \):
$$
\|\mathbf{a}\| = \sqrt{3^2 + 4^2} = \sqrt{9 + 16} = \sqrt{25} = 5
$$

#### Step 2: Scale the vector
To make \( \mathbf{a} \) a unit vector, divide each component of \( \mathbf{a} \) by its magnitude \( \|\mathbf{a}\| \):
$$
\mathbf{a}_{\text{scaled}} = \frac{\mathbf{a}}{\|\mathbf{a}\|}
$$

Substitute the values:
$$
\mathbf{a}_{\text{scaled}} = \frac{[3, 4]}{5} = \left[ \frac{3}{5}, \frac{4}{5} \right]
$$

#### Final Answer:
$$
\mathbf{a}_{\text{scaled}} = \left[ \frac{3}{5}, \frac{4}{5} \right]
$$

---

### 2. Given vectors \( \mathbf{u} = [2, 3] \) and \( \mathbf{v} = [4, 5] \), find the sum \( \mathbf{u} + \mathbf{v} \).

#### Step 1: Add the vectors component-wise
$$
\mathbf{u} + \mathbf{v} = \begin{bmatrix} 2 \\ 3 \end{bmatrix} + \begin{bmatrix} 4 \\ 5 \end{bmatrix} = \begin{bmatrix} 2 + 4 \\ 3 + 5 \end{bmatrix}
$$

#### Step 2: Simplify the result
$$
\mathbf{u} + \mathbf{v} = \begin{bmatrix} 6 \\ 8 \end{bmatrix}
$$

#### Final Answer:
$$
\mathbf{u} + \mathbf{v} = \begin{bmatrix} 6 \\ 8 \end{bmatrix}
$$

---

### 3. Calculate the dot product of \( \mathbf{a} = [1, 2] \) and \( \mathbf{b} = [3, 4] \).

#### Step 1: Use the dot product formula
$$
\mathbf{a} \cdot \mathbf{b} = a_1 \cdot b_1 + a_2 \cdot b_2
$$

Substitute the values:
$$
\mathbf{a} \cdot \mathbf{b} = (1)(3) + (2)(4) = 3 + 8
$$

#### Step 2: Simplify the result
$$
\mathbf{a} \cdot \mathbf{b} = 11
$$

#### Final Answer:
$$
\mathbf{a} \cdot \mathbf{b} = 11
$$

---

### 4. Find the magnitude of the vector \( \mathbf{c} = [5, 12] \).

#### Step 1: Use the magnitude formula
$$
\|\mathbf{c}\| = \sqrt{c_1^2 + c_2^2}
$$

Substitute the values:
$$
\|\mathbf{c}\| = \sqrt{5^2 + 12^2} = \sqrt{25 + 144}
$$

#### Step 2: Simplify the result
$$
\|\mathbf{c}\| = \sqrt{169} = 13
$$

#### Final Answer:
$$
\|\mathbf{c}\| = 13
$$

---

### 5. Given \( \mathbf{a} = [2, 3, 4] \) and \( \mathbf{b} = [1, 0, -1] \), find the cross product \( \mathbf{a} \times \mathbf{b} \).

#### Step 1: Set up the cross product formula
$$
\mathbf{a} \times \mathbf{b} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ 2 & 3 & 4 \\ 1 & 0 & -1 \end{vmatrix}
$$

#### Step 2: Calculate the cross product
Expand using the determinant formula:
$$
\mathbf{a} \times \mathbf{b} = \mathbf{i} \begin{vmatrix} 3 & 4 \\ 0 & -1 \end{vmatrix} - \mathbf{j} \begin{vmatrix} 2 & 4 \\ 1 & -1 \end{vmatrix} + \mathbf{k} \begin{vmatrix} 2 & 3 \\ 1 & 0 \end{vmatrix}
$$

Evaluate each 2x2 determinant:
$$
\mathbf{a} \times \mathbf{b} = \mathbf{i} (3 \cdot (-1) - 4 \cdot 0) - \mathbf{j} (2 \cdot (-1) - 4 \cdot 1) + \mathbf{k} (2 \cdot 0 - 3 \cdot 1)
$$

Simplify:
$$
\mathbf{a} \times \mathbf{b} = \mathbf{i} (-3) - \mathbf{j} (-2 - 4) + \mathbf{k} (-3)
$$

$$
\mathbf{a} \times \mathbf{b} = \begin{bmatrix} -3 \\ 6 \\ -3 \end{bmatrix}
$$

#### Final Answer:
$$
\mathbf{a} \times \mathbf{b} = \begin{bmatrix} -3 \\ 6 \\ -3 \end{bmatrix}
$$

---

## 12. Vectors 2

### 1. Given \( \mathbf{u} = [1, 2, 3] \) and \( \mathbf{v} = [4, 5, 6] \), find \( \mathbf{u} + \mathbf{v} \).

#### Step 1: Add the vectors component-wise
$$
\mathbf{u} + \mathbf{v} = \begin{bmatrix} 1 \\ 2 \\ 3 \end{bmatrix} + \begin{bmatrix} 4 \\ 5 \\ 6 \end{bmatrix} = \begin{bmatrix} 1 + 4 \\ 2 + 5 \\ 3 + 6 \end{bmatrix}
$$

#### Step 2: Simplify the result
$$
\mathbf{u} + \mathbf{v} = \begin{bmatrix} 5 \\ 7 \\ 9 \end{bmatrix}
$$

#### Final Answer:
$$
\mathbf{u} + \mathbf{v} = \begin{bmatrix} 5 \\ 7 \\ 9 \end{bmatrix}
$$

---

### 2. Calculate the dot product of \( \mathbf{u} = [1, 2, 3] \) and \( \mathbf{v} = [4, 5, 6] \).

#### Step 1: Use the dot product formula
$$
\mathbf{u} \cdot \mathbf{v} = 1 \cdot 4 + 2 \cdot 5 + 3 \cdot 6
$$

#### Step 2: Simplify the result
$$
\mathbf{u} \cdot \mathbf{v} = 4 + 10 + 18 = 32
$$

#### Final Answer:
$$
\mathbf{u} \cdot \mathbf{v} = 32
$$

---

### 3. Find the magnitude of the vector \( \mathbf{w} = [3, 4, 5] \).

#### Step 1: Use the magnitude formula
$$
\|\mathbf{w}\| = \sqrt{3^2 + 4^2 + 5^2}
$$

#### Step 2: Simplify the result
$$
\|\mathbf{w}\| = \sqrt{9 + 16 + 25} = \sqrt{50}
$$

#### Final Answer:
$$
\|\mathbf{w}\| = \sqrt{50}
$$

---

### 4. Find the cross product of \( \mathbf{u} = [1, 2, 3] \) and \( \mathbf{v} = [4, 5, 6] \).

#### Step 1: Set up the cross product formula
$$
\mathbf{u} \times \mathbf{v} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ 1 & 2 & 3 \\ 4 & 5 & 6 \end{vmatrix}
$$

#### Step 2: Calculate the cross product
Expand using the determinant formula:
$$
\mathbf{u} \times \mathbf{v} = \mathbf{i} \begin{vmatrix} 2 & 3 \\ 5 & 6 \end{vmatrix} - \mathbf{j} \begin{vmatrix} 1 & 3 \\ 4 & 6 \end{vmatrix} + \mathbf{k} \begin{vmatrix} 1 & 2 \\ 4 & 5 \end{vmatrix}
$$

Evaluate each 2x2 determinant:
$$
\mathbf{u} \times \mathbf{v} = \mathbf{i} (2 \cdot 6 - 3 \cdot 5) - \mathbf{j} (1 \cdot 6 - 3 \cdot 4) + \mathbf{k} (1 \cdot 5 - 2 \cdot 4)
$$

Simplify:
$$
\mathbf{u} \times \mathbf{v} = \mathbf{i} (12 - 15) - \mathbf{j} (6 - 12) + \mathbf{k} (5 - 8)
$$

$$
\mathbf{u} \times \mathbf{v} = \mathbf{i} (-3) - \mathbf{j} (-6) + \mathbf{k} (-3)
$$

$$
\mathbf{u} \times \mathbf{v} = \begin{bmatrix} -3 \\ 6 \\ -3 \end{bmatrix}
$$

#### Final Answer:
$$
\mathbf{u} \times \mathbf{v} = \begin{bmatrix} -3 \\ 6 \\ -3 \end{bmatrix}
$$

---

### 5. Given \( \mathbf{a} = [1, 1, 1] \), find \( 2\mathbf{a} \).

#### Step 1: Multiply each component by 2
$$
2\mathbf{a} = 2 \cdot \begin{bmatrix} 1 \\ 1 \\ 1 \end{bmatrix} = \begin{bmatrix} 2 \\ 2 \\ 2 \end{bmatrix}
$$

#### Final Answer:
$$
2\mathbf{a} = \begin{bmatrix} 2 \\ 2 \\ 2 \end{bmatrix}
$$

---

### 6. Find \( \mathbf{a} \cdot \mathbf{a} \) for \( \mathbf{a} = [2, 3] \).

#### Step 1: Use the dot product formula
$$
\mathbf{a} \cdot \mathbf{a} = 2^2 + 3^2
$$

#### Step 2: Simplify the result
$$
\mathbf{a} \cdot \mathbf{a} = 4 + 9 = 13
$$

#### Final Answer:
$$
\mathbf{a} \cdot \mathbf{a} = 13
$$


## 13. Vectors 3

### 1. Given vectors \( \mathbf{u} = [1, 2, 3] \) and \( \mathbf{v} = [4, 5, 6] \), find the angle between them.

#### Step 1: Use the dot product formula to find the cosine of the angle
$$
\cos \theta = \frac{\mathbf{u} \cdot \mathbf{v}}{\|\mathbf{u}\| \|\mathbf{v}\|}
$$

Calculate \( \mathbf{u} \cdot \mathbf{v} \):
$$
\mathbf{u} \cdot \mathbf{v} = 1 \cdot 4 + 2 \cdot 5 + 3 \cdot 6 = 4 + 10 + 18 = 32
$$

Calculate \( \|\mathbf{u}\| \) and \( \|\mathbf{v}\| \):
$$
\|\mathbf{u}\| = \sqrt{1^2 + 2^2 + 3^2} = \sqrt{1 + 4 + 9} = \sqrt{14}
$$
$$
\|\mathbf{v}\| = \sqrt{4^2 + 5^2 + 6^2} = \sqrt{16 + 25 + 36} = \sqrt{77}
$$

Substitute these values into the formula:
$$
\cos \theta = \frac{32}{\sqrt{14} \cdot \sqrt{77}}
$$

#### Step 2: Simplify the result to find \( \theta \)
$$
\theta = \cos^{-1} \left(\frac{32}{\sqrt{14} \cdot \sqrt{77}}\right)
$$

#### Final Answer:
$$
\theta = \cos^{-1} \left(\frac{32}{\sqrt{14} \cdot \sqrt{77}}\right)
$$

---

### 2. Find the projection of \( \mathbf{u} = [2, 3] \) onto \( \mathbf{v} = [4, 5] \).

#### Step 1: Use the projection formula
$$
\text{proj}_{\mathbf{v}} \mathbf{u} = \frac{\mathbf{u} \cdot \mathbf{v}}{\mathbf{v} \cdot \mathbf{v}} \mathbf{v}
$$

Calculate \( \mathbf{u} \cdot \mathbf{v} \) and \( \mathbf{v} \cdot \mathbf{v} \):
$$
\mathbf{u} \cdot \mathbf{v} = 2 \cdot 4 + 3 \cdot 5 = 8 + 15 = 23
$$
$$
\mathbf{v} \cdot \mathbf{v} = 4^2 + 5^2 = 16 + 25 = 41
$$

Substitute these values into the projection formula:
$$
\text{proj}_{\mathbf{v}} \mathbf{u} = \frac{23}{41} \begin{bmatrix} 4 \\ 5 \end{bmatrix}
$$

#### Step 2: Simplify the result
$$
\text{proj}_{\mathbf{v}} \mathbf{u} = \begin{bmatrix} \frac{92}{41} \\ \frac{115}{41} \end{bmatrix}
$$

#### Final Answer:
$$
\text{proj}_{\mathbf{v}} \mathbf{u} = \begin{bmatrix} \frac{92}{41} \\ \frac{115}{41} \end{bmatrix}
$$

---

### 3. Find the vector \( \mathbf{u} \) such that \( \mathbf{u} \cdot \mathbf{v} = 0 \) and \( \mathbf{u} \) is perpendicular to \( \mathbf{v} = [3, 4] \).

#### Step 1: Set up the equation for perpendicular vectors
For \( \mathbf{u} = [x, y] \), the condition \( \mathbf{u} \cdot \mathbf{v} = 0 \) means:
$$
3x + 4y = 0
$$

#### Step 2: Solve for \( \mathbf{u} \)
Choose a value for \( x \) and solve for \( y \). For example, let \( x = 4 \):
$$
3(4) + 4y = 0 \implies 12 + 4y = 0 \implies 4y = -12 \implies y = -3
$$

#### Final Answer:
$$
\mathbf{u} = [4, -3]
$$

---

### 4. Verify if \( \mathbf{a} = [1, 2, 3] \) and \( \mathbf{b} = [4, 5, 6] \) are parallel.

#### Step 1: Check if \( \mathbf{a} \) and \( \mathbf{b} \) are multiples of each other
Two vectors are parallel if \( \mathbf{a} = k \mathbf{b} \) for some scalar \( k \).

Calculate the ratio:
$$
k = \frac{a_1}{b_1} = \frac{1}{4}, \quad k = \frac{a_2}{b_2} = \frac{2}{5}, \quad k = \frac{a_3}{b_3} = \frac{3}{6} = \frac{1}{2}
$$

Since the ratios are not equal, \( \mathbf{a} \) and \( \mathbf{b} \) are not parallel.

#### Final Answer:
$$
\text{The vectors } \mathbf{a} \text{ and } \mathbf{b} \text{ are not parallel.}
$$


## 15. Equation of Lines on a Plane

### 1. Find the equation of the line passing through the points \( (1, 2) \) and \( (3, 4) \).

#### Step 1: Calculate the slope \( m \)
$$
m = \frac{y_2 - y_1}{x_2 - x_1} = \frac{4 - 2}{3 - 1} = \frac{2}{2} = 1
$$

#### Step 2: Use the point-slope form \( y - y_1 = m(x - x_1) \)
Substitute \( m = 1 \) and \( (x_1, y_1) = (1, 2) \):
$$
y - 2 = 1(x - 1)
$$

#### Step 3: Simplify to slope-intercept form
$$
y - 2 = x - 1 \implies y = x + 1
$$

#### Final Answer:
$$
y = x + 1
$$

---

### 2. Find the equation of a line that passes through the point \( (2, 3) \) and has a slope of \( -2 \).

#### Step 1: Use the point-slope form \( y - y_1 = m(x - x_1) \)
Substitute \( m = -2 \) and \( (x_1, y_1) = (2, 3) \):
$$
y - 3 = -2(x - 2)
$$

#### Step 2: Simplify to slope-intercept form
$$
y - 3 = -2x + 4 \implies y = -2x + 7
$$

#### Final Answer:
$$
y = -2x + 7
$$

---

### 3. Find the equation of the line parallel to \( y = 3x - 5 \) and passing through the point \( (4, 2) \).

#### Step 1: Identify the slope of the given line
The slope of the line \( y = 3x - 5 \) is \( m = 3 \).

#### Step 2: Use the point-slope form \( y - y_1 = m(x - x_1) \)
Substitute \( m = 3 \) and \( (x_1, y_1) = (4, 2) \):
$$
y - 2 = 3(x - 4)
$$

#### Step 3: Simplify to slope-intercept form
$$
y - 2 = 3x - 12 \implies y = 3x - 10
$$

#### Final Answer:
$$
y = 3x - 10
$$

---

### 4. Find the equation of the line perpendicular to \( y = \frac{1}{2}x + 1 \) and passing through \( (1, 1) \).

#### Step 1: Identify the slope of the given line
The slope of the line \( y = \frac{1}{2}x + 1 \) is \( m = \frac{1}{2} \).

#### Step 2: Find the perpendicular slope
The perpendicular slope is the negative reciprocal:
$$
m_{\text{perpendicular}} = -\frac{1}{\frac{1}{2}} = -2
$$

#### Step 3: Use the point-slope form \( y - y_1 = m(x - x_1) \)
Substitute \( m = -2 \) and \( (x_1, y_1) = (1, 1) \):
$$
y - 1 = -2(x - 1)
$$

#### Step 4: Simplify to slope-intercept form
$$
y - 1 = -2x + 2 \implies y = -2x + 3
$$

#### Final Answer:
$$
y = -2x + 3
$$

---

### 5. Find the equation of the line with a slope of \( 5 \) that passes through the point \( (-3, 4) \).

#### Step 1: Use the point-slope form \( y - y_1 = m(x - x_1) \)
Substitute \( m = 5 \) and \( (x_1, y_1) = (-3, 4) \):
$$
y - 4 = 5(x + 3)
$$

#### Step 2: Simplify to slope-intercept form
$$
y - 4 = 5x + 15 \implies y = 5x + 19
$$

#### Final Answer:
$$
y = 5x + 19
$$

---

### 6. Find the equation of the line passing through the points \( (2, -1) \) and \( (4, 3) \).

#### Step 1: Calculate the slope \( m \)
$$
m = \frac{3 - (-1)}{4 - 2} = \frac{4}{2} = 2
$$

#### Step 2: Use the point-slope form \( y - y_1 = m(x - x_1) \)
Substitute \( m = 2 \) and \( (x_1, y_1) = (2, -1) \):
$$
y + 1 = 2(x - 2)
$$

#### Step 3: Simplify to slope-intercept form
$$
y + 1 = 2x - 4 \implies y = 2x - 5
$$

#### Final Answer:
$$
y = 2x - 5
$$

---

### 7. Write the equation of a line in standard form that passes through \( (1, 2) \) and has a slope of \( \frac{3}{4} \).

#### Step 1: Use the point-slope form \( y - y_1 = m(x - x_1) \)
Substitute \( m = \frac{3}{4} \) and \( (x_1, y_1) = (1, 2) \):
$$
y - 2 = \frac{3}{4}(x - 1)
$$

#### Step 2: Clear the fraction by multiplying by 4
$$
4(y - 2) = 3(x - 1)
$$

#### Step 3: Simplify and write in standard form
$$
4y - 8 = 3x - 3 \implies 3x - 4y = -5
$$

#### Final Answer:
$$
3x - 4y = -5
$$

---

### 8. Find the equation of the line that passes through \( (0, 0) \) and \( (2, 2) \).

#### Step 1: Calculate the slope \( m \)
$$
m = \frac{2 - 0}{2 - 0} = 1
$$

#### Step 2: Use the point-slope form \( y - y_1 = m(x - x_1) \)
Substitute \( m = 1 \) and \( (x_1, y_1) = (0, 0) \):
$$
y - 0 = 1(x - 0)
$$

#### Step 3: Simplify to slope-intercept form
$$
y = x
$$

#### Final Answer:
$$
y = x
$$

---

### 9. Find the equation of the line parallel to \( y = -3x + 5 \) and passing through the point \( (-2, 1) \).

#### Step 1: Identify the slope of the given line
The slope of \( y = -3x + 5 \) is \( m = -3 \).

#### Step 2: Use the point-slope form \( y - y_1 = m(x - x_1) \)
Substitute \( m = -3 \) and \( (x_1, y_1) = (-2, 1) \):
$$
y - 1 = -3(x + 2)
$$

#### Step 3: Simplify to slope-intercept form
$$
y - 1 = -3x - 6 \implies y = -3x - 5
$$

#### Final Answer:
$$
y = -3x - 5
$$

---

### 10. Find the equation of the line perpendicular to \( y = \frac{2}{3}x - 4 \) and passing through \( (3, 2) \).

#### Step 1: Identify the slope of the given line
The slope of \( y = \frac{2}{3}x - 4 \) is \( m = \frac{2}{3} \).

#### Step 2: Find the perpendicular slope
The perpendicular slope is the negative reciprocal:
$$
m_{\text{perpendicular}} = -\frac{3}{2}
$$

#### Step 3: Use the point-slope form \( y - y_1 = m(x - x_1) \)
Substitute \( m = -\frac{3}{2} \) and \( (x_1, y_1) = (3, 2) \):
$$
y - 2 = -\frac{3}{2}(x - 3)
$$

#### Step 4: Simplify to slope-intercept form
$$
y - 2 = -\frac{3}{2}x + \frac{9}{2} \implies y = -\frac{3}{2}x + \frac{13}{2}
$$

#### Final Answer:
$$
y = -\frac{3}{2}x + \frac{13}{2}
$$
