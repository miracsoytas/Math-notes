# Problem Solutions in Markdown

## Problem 1: By what number should vector \( \mathbf{a} = [3, 4] \) be multiplied so that its length is equal to 1?

### Step 1: Calculate the length (magnitude) of the vector
The formula for the magnitude of a vector \( \mathbf{a} = [x, y] \) is:

$$
\|\mathbf{a}\| = \sqrt{x^2 + y^2}
$$

For \( \mathbf{a} = [3, 4] \):

$$
\|\mathbf{a}\| = \sqrt{3^2 + 4^2} = \sqrt{9 + 16} = \sqrt{25} = 5
$$

### Step 2: Scale the vector
To make \( \mathbf{a} \) a unit vector, divide each component of \( \mathbf{a} \) by its magnitude \( \|\mathbf{a}\| \):

$$
\mathbf{a}_{\text{scaled}} = \frac{\mathbf{a}}{\|\mathbf{a}\|}
$$

Substitute the values:

$$
\mathbf{a}_{\text{scaled}} = \frac{[3, 4]}{5} = \left[ \frac{3}{5}, \frac{4}{5} \right]
$$

### Final Answer:
The unit vector is:

$$
\mathbf{a}_{\text{scaled}} = \left[ \frac{3}{5}, \frac{4}{5} \right]
$$

---

## Problem 2: Calculate the length of vector \( \mathbf{b} = [1, 1] \) and find the unit vector of this vector.

### Step 1: Calculate the magnitude of \( \mathbf{b} \)
Using the magnitude formula:

$$
\|\mathbf{b}\| = \sqrt{x^2 + y^2}
$$

For \( \mathbf{b} = [1, 1] \):

$$
\|\mathbf{b}\| = \sqrt{1^2 + 1^2} = \sqrt{1 + 1} = \sqrt{2}
$$

### Step 2: Find the unit vector
Divide each component of \( \mathbf{b} \) by its magnitude \( \|\mathbf{b}\| \):

$$
\mathbf{b}_{\text{scaled}} = \frac{\mathbf{b}}{\|\mathbf{b}\|}
$$

Substitute the values:

$$
\mathbf{b}_{\text{scaled}} = \frac{[1, 1]}{\sqrt{2}} = \left[ \frac{1}{\sqrt{2}}, \frac{1}{\sqrt{2}} \right]
$$

### Final Answer:
The unit vector is:

$$
\mathbf{b}_{\text{scaled}} = \left[ \frac{1}{\sqrt{2}}, \frac{1}{\sqrt{2}} \right]
$$

---

## Problem 3: Plot the vector and the unit vector from the previous exercise.

### Step 1: Define the vectors
The original vector is \( \mathbf{b} = [1, 1] \), and the unit vector is \( \mathbf{b}_{\text{scaled}} = \left[ \frac{1}{\sqrt{2}}, \frac{1}{\sqrt{2}} \right] \).

### Step 2: Create the plot
Use Python or any plotting tool to visualize the vectors. Here's an example using Python (matplotlib):



# Define vectors
original_vector = np.array([1, 1])
unit_vector = original_vector / np.linalg.norm(original_vector)

# Plot
plt.quiver(0, 0, original_vector[0], original_vector[1], angles='xy', scale_units='xy', scale=1, color='r', label='Original Vector')
plt.quiver(0, 0, unit_vector[0], unit_vector[1], angles='xy', scale_units='xy', scale=1, color='b', label='Unit Vector')

# Formatting
plt.xlim(0, 1.5)
plt.ylim(0, 1.5)
plt.grid()
plt.legend()
plt.title("Vector and Unit Vector")
plt.show()
