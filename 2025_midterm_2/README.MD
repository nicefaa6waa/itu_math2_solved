# Calculus Problems Solutions - ACING MATH 2

-----

## Problem 1

**What is the slope of the tangent line to a polar curve given by $r = f(\\theta)$ at a point $(r, \\theta)$?**

**Answer:** **(c) $\\frac{dy}{dx}$**

<details>
<summary>Solution Steps</summary>

The slope of the tangent line to a polar curve $r = f(\\theta)$ at a given point is defined by $\\frac{dy}{dx}$. This is derived using the parametric equations for polar coordinates:
$x = r\\cos\\theta = f(\\theta)\\cos\\theta$
$y = r\\sin\\theta = f(\\theta)\\sin\\theta$

Then, $\\frac{dy}{dx} = \\frac{dy/d\\theta}{dx/d\\theta}$.

</details>

-----

## Problem 2

**Which of the following is the polar equation for the circle $(x-2)^2 + (y+3)^2 = 17$?**

**Answer:** **(e) $r^2 = 4r\\cos\\theta - 6r\\sin\\theta + 4$**

<details>
<summary>Solution Steps</summary>

**Step 1:** Substitute $x = r\\cos\\theta$ and $y = r\\sin\\theta$ into the Cartesian equation of the circle.
$$(r\cos\theta - 2)^2 + (r\sin\theta + 3)^2 = 17$$

**Step 2:** Expand the squared terms.
$$(r^2\cos^2\theta - 4r\cos\theta + 4) + (r^2\sin^2\theta + 6r\sin\theta + 9) = 17$$

**Step 3:** Group terms with $r^2$ and use the identity $\\cos^2\\theta + \\sin^2\\theta = 1$.
$$r^2(\cos^2\theta + \sin^2\theta) - 4r\cos\theta + 6r\sin\theta + 4 + 9 = 17$$
$$r^2 - 4r\cos\theta + 6r\sin\theta + 13 = 17$$

**Step 4:** Isolate $r^2$ to find the polar equation.
$$r^2 = 4r\cos\theta - 6r\sin\theta + 17 - 13$$
$$r^2 = 4r\cos\theta - 6r\sin\theta + 4$$

</details>

-----

## Problem 3

**What is the tangent line to the polar curve $r = 4(1-\\cos\\theta)$ at $\\theta = 2\\pi$?**

**Answer:** **(b) $y = 0$**

<details>
<summary>Solution Steps</summary>

**Step 1:** Find the value of $r$ at $\\theta = 2\\pi$.
$$r = 4(1 - \cos 2\pi) = 4(1 - 1) = 0$$
This means the curve passes through the origin (pole) at $\\theta = 2\\pi$.

**Step 2:** For a polar curve passing through the origin, the tangent line at the origin is given by the line $\\theta = \\alpha$ where $r=0$ at $\\theta=\\alpha$, or a line perpendicular to that.
In this case, for a cardioid $r = a(1 - \\cos\\theta)$, the tangent at the origin (when $r=0$) is the line $\\theta = 0$ (which is the positive x-axis, $y=0$). At $\\theta=2\\pi$, it corresponds to the same point as $\\theta=0$ on the polar axis.

Alternatively, use the formula for the slope $\\frac{dy}{dx} = \\frac{\\frac{dr}{d\\theta}\\sin\\theta + r\\cos\\theta}{\\frac{dr}{d\\theta}\\cos\\theta - r\\sin\\theta}$.
First, find $\\frac{dr}{d\\theta}$:
$\\frac{dr}{d\\theta} = 4\\sin\\theta$

At $\\theta = 2\\pi$:
$r = 0$
$\\frac{dr}{d\\theta} = 4\\sin(2\\pi) = 0$

Plugging these into the slope formula:
$\\frac{dy}{dx} = \\frac{0 \\cdot \\sin(2\\pi) + 0 \\cdot \\cos(2\\pi)}{0 \\cdot \\cos(2\\pi) - 0 \\cdot \\sin(2\\pi)} = \\frac{0}{0}$ (indeterminate form).

In cases where the curve passes through the pole, the tangent is given by the line $\\theta = \\alpha$ if $\\frac{dr}{d\\theta} \\neq 0$ at $\\theta = \\alpha$ and $r(\\alpha) = 0$.
Here, $r(2\\pi) = 0$. The tangent line is simply the radial line $\\theta = 2\\pi$, which is the positive x-axis, or $y=0$. For a cardioid, the tangent at the origin is horizontal.

</details>

-----

## Problem 4

**Calculate the area bounded by the polar curve $r = 6\\cos\\theta$ for $-\\frac{\\pi}{4} \\leq \\theta \\leq \\frac{\\pi}{4}$.**

**Answer:** **(d) $\\frac{9\\pi}{2} + 9$**

<details>
<summary>Solution Steps</summary>

**Step 1:** Use the formula for the area in polar coordinates: $A = \\frac{1}{2} \\int\_{\\alpha}^{\\beta} r^2 d\\theta$.
Here, $r = 6\\cos\\theta$, $\\alpha = -\\frac{\\pi}{4}$, and $\\beta = \\frac{\\pi}{4}$.

$$A = \frac{1}{2} \int_{-\frac{\pi}{4}}^{\frac{\pi}{4}} (6\cos\theta)^2 d\theta$$
$$A = \frac{1}{2} \int_{-\frac{\pi}{4}}^{\frac{\pi}{4}} 36\cos^2\theta d\theta$$
$$A = 18 \int_{-\frac{\pi}{4}}^{\frac{\pi}{4}} \cos^2\theta d\theta$$

**Step 2:** Use the power-reducing identity $\\cos^2\\theta = \\frac{1 + \\cos 2\\theta}{2}$.
$$A = 18 \int_{-\frac{\pi}{4}}^{\frac{\pi}{4}} \frac{1 + \cos 2\theta}{2} d\theta$$
$$A = 9 \int_{-\frac{\pi}{4}}^{\frac{\pi}{4}} (1 + \cos 2\theta) d\theta$$

**Step 3:** Integrate the expression.
$$A = 9 \left[ \theta + \frac{1}{2}\sin 2\theta \right]_{-\frac{\pi}{4}}^{\frac{\pi}{4}}$$

**Step 4:** Evaluate the definite integral.
$$A = 9 \left( \left(\frac{\pi}{4} + \frac{1}{2}\sin\left(2 \cdot \frac{\pi}{4}\right)\right) - \left(-\frac{\pi}{4} + \frac{1}{2}\sin\left(2 \cdot -\frac{\pi}{4}\right)\right) \right)$$
$$A = 9 \left( \left(\frac{\pi}{4} + \frac{1}{2}\sin\left(\frac{\pi}{2}\right)\right) - \left(-\frac{\pi}{4} + \frac{1}{2}\sin\left(-\frac{\pi}{2}\right)\right) \right)$$
$$A = 9 \left( \left(\frac{\pi}{4} + \frac{1}{2}(1)\right) - \left(-\frac{\pi}{4} + \frac{1}{2}(-1)\right) \right)$$
$$A = 9 \left( \frac{\pi}{4} + \frac{1}{2} + \frac{\pi}{4} + \frac{1}{2} \right)$$
$$A = 9 \left( \frac{2\pi}{4} + 1 \right)$$
$$A = 9 \left( \frac{\pi}{2} + 1 \right)$$
$$A = \frac{9\pi}{2} + 9$$

</details>

-----

## Problem 5

**Calculate the vector triple product: $(\\mathbf{i} \\times \\mathbf{j}) \\times \\mathbf{j}$.**

**Answer:** **(b) $-\\mathbf{i}$**

<details>
<summary>Solution Steps</summary>

**Step 1:** First, calculate the cross product inside the parentheses, $\\mathbf{i} \\times \\mathbf{j}$.
By definition of the right-hand rule for standard unit vectors:
$$\mathbf{i} \times \mathbf{j} = \mathbf{k}$$

**Step 2:** Now, calculate the second cross product: $\\mathbf{k} \\times \\mathbf{j}$.
Using the right-hand rule (or the cyclic property of cross products, $\\mathbf{j} \\times \\mathbf{k} = \\mathbf{i}$, so $\\mathbf{k} \\times \\mathbf{j} = -\\mathbf{i}$):
$$\mathbf{k} \times \mathbf{j} = -\mathbf{i}$$

</details>

-----

## Problem 6

**Given vectors $\\mathbf{u} = 5\\mathbf{i} + \\mathbf{j} - 3\\mathbf{k}$ and $\\mathbf{v} = 4\\mathbf{i} + 4\\mathbf{j} + 2\\mathbf{k}$, find the angle between $\\mathbf{u}$ and $\\mathrm{proj}\_{\\mathbf{v}} \\mathbf{u}$.**

**Answer:** **(a) $\\cos^{-1}\\left(\\frac{3}{\\sqrt{35}}\\right)$**

<details>
<summary>Solution Steps</summary>

**Step 1:** Understand the geometric meaning of vector projection.
The vector projection of $\\mathbf{u}$ onto $\\mathbf{v}$, denoted as $\\mathrm{proj}*{\\mathbf{v}} \\mathbf{u}$, is a vector that is **parallel** to $\\mathbf{v}$.
Therefore, the angle between $\\mathbf{u}$ and $\\mathrm{proj}*{\\mathbf{v}} \\mathbf{u}$ is the same as the angle between $\\mathbf{u}$ and $\\mathbf{v}$.

**Step 2:** Use the dot product formula to find the angle $\\theta$ between $\\mathbf{u}$ and $\\mathbf{v}$:
$$\cos\theta = \frac{\mathbf{u} \cdot \mathbf{v}}{|\mathbf{u}||\mathbf{v}|}$$

**Step 3:** Calculate the dot product $\\mathbf{u} \\cdot \\mathbf{v}$.
$$\mathbf{u} \cdot \mathbf{v} = (5)(4) + (1)(4) + (-3)(2) = 20 + 4 - 6 = 18$$

**Step 4:** Calculate the magnitudes of $\\mathbf{u}$ and $\\mathbf{v}$.
$$|\mathbf{u}| = \sqrt{5^2 + 1^2 + (-3)^2} = \sqrt{25 + 1 + 9} = \sqrt{35}$$
$$|\mathbf{v}| = \sqrt{4^2 + 4^2 + 2^2} = \sqrt{16 + 16 + 4} = \sqrt{36} = 6$$

**Step 5:** Substitute the values into the cosine formula.
$$\cos\theta = \frac{18}{\sqrt{35} \cdot 6} = \frac{3}{\sqrt{35}}$$

**Step 6:** Express the angle.
$$\theta = \cos^{-1}\left(\frac{3}{\sqrt{35}}\right)$$

</details>

-----

You are absolutely correct\! My apologies for rewriting the whole thing and for the persistent LaTeX issues. I will provide only the corrected Problem 7 and Problem 8, ensuring the LaTeX for the determinant matrices is properly formatted this time.

Here are the corrected problems:

-----

## Problem 7

**What are all values of $b$ for which the volume of the parallelepiped formed by the vectors $\mathbf{u} = \langle b, 1, -1 \rangle$, $\mathbf{v} = \langle -2, 3, b \rangle$, and $\mathbf{w} = \langle 0, 4, 0 \rangle$ is 8 cubic units?**

**Answer:** **(a) $\{-2, 0, 2\}$**

<details>
<summary>Solution Step</summary>

**Step 1:** The volume of a parallelepiped formed by three vectors $\mathbf{u}, \mathbf{v}, \mathbf{w}$ is given by the absolute value of their scalar triple product:

$$
V = |\mathbf{u} \cdot (\mathbf{v} \times \mathbf{w})|
$$

**Step 2:** Calculate the cross product $\mathbf{v} \times \mathbf{w}$:

$$
\mathbf{v} \times \mathbf{w} =
\begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
-2 & 3 & b \\
0 & 4 & 0
\end{vmatrix}
= \mathbf{i}(3 \cdot 0 - b \cdot 4) - \mathbf{j}(-2 \cdot 0 - b \cdot 0) + \mathbf{k}(-2 \cdot 4 - 3 \cdot 0)
$$

$$
= \mathbf{i}(-4b) - \mathbf{j}(0) + \mathbf{k}(-8)
= \langle -4b, 0, -8 \rangle
$$

**Step 3:** Compute the scalar triple product:

$$
\mathbf{u} \cdot (\mathbf{v} \times \mathbf{w}) = \langle b, 1, -1 \rangle \cdot \langle -4b, 0, -8 \rangle
= -4b^2 + 0 + 8 = -4b^2 + 8
$$

**Step 4:** Solve for $b$ such that:

$$
| -4b^2 + 8 | = 8
$$

**Case 1:**

$$
-4b^2 + 8 = 8 \Rightarrow -4b^2 = 0 \Rightarrow b^2 = 0 \Rightarrow b = 0
$$

**Case 2:**

$$
-4b^2 + 8 = -8 \Rightarrow -4b^2 = -16 \Rightarrow b^2 = 4 \Rightarrow b = \pm 2
$$

**Step 5:** Final result:

$$
b \in \{-2, 0, 2\}
$$

</details>

---

## Problem 8

**Find the equation of the plane that is parallel to the vector $\mathbf{u} = \mathbf{i} - \mathbf{k}$ and contains the line $L$ given by the parametric equations $x = 1 - 2t, y = 4 + 3t, z = 9 - 4t$.**

**Answer:** **(a) $x + 2y + z = 18$**

<details>
<summary>Solution Steps</summary>

**Step 1:** Identify a normal vector to the plane.

* The line $L$ lies in the plane, so its direction vector is:

  $$
  \mathbf{d}_L = \langle -2, 3, -4 \rangle
  $$
* The plane is parallel to $\mathbf{u} = \langle 1, 0, -1 \rangle$, so $\mathbf{u}$ also lies in the plane.

A vector perpendicular to both $\mathbf{u}$ and $\mathbf{d}_L$ is the normal vector $\mathbf{n}$, found via the cross product:

$$
\mathbf{n} = \mathbf{u} \times \mathbf{d}_L =
\begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
1 & 0 & -1 \\
-2 & 3 & -4
\end{vmatrix}
= \mathbf{i}(0 \cdot -4 - (-1) \cdot 3) - \mathbf{j}(1 \cdot -4 - (-1) \cdot -2) + \mathbf{k}(1 \cdot 3 - 0 \cdot -2)
$$

$$
= \mathbf{i}(3) - \mathbf{j}(-4 - 2) + \mathbf{k}(3)
= \langle 3, 6, 3 \rangle
$$

We can simplify this to $\mathbf{n'} = \langle 1, 2, 1 \rangle$.

**Step 2:** Use a point on the plane.
When $t = 0$, the point on $L$ is $(1, 4, 9)$.

**Step 3:** Use the point-normal form of a plane:

$$
A(x - x_0) + B(y - y_0) + C(z - z_0) = 0
$$

With $\langle A, B, C \rangle = \langle 1, 2, 1 \rangle$ and point $(1, 4, 9)$:

$$
1(x - 1) + 2(y - 4) + 1(z - 9) = 0
\Rightarrow x - 1 + 2y - 8 + z - 9 = 0
\Rightarrow x + 2y + z = 18
$$

</details>

-----

## Problem 9

**Find the point on the line $x = 1 + t, y = -2t, z = 2 + 3t$ that is closest to the point $(1, 1, 2)$.**

**Answer:** **(a) $\\left(\\frac{6}{7}, \\frac{2}{7}, \\frac{11}{7}\\right)$**

<details>
<summary>Solution Steps</summary>

**Step 1:** Let a general point on the line be $P(t) = (1 + t, -2t, 2 + 3t)$.
Let the given point be $Q = (1, 1, 2)$.
The vector connecting $P(t)$ to $Q$ is $\\vec{QP(t)} = \\langle (1+t)-1, -2t-1, (2+3t)-2 \\rangle = \\langle t, -2t-1, 3t \\rangle$.

**Step 2:** The shortest distance between a point and a line occurs when the vector connecting the point to the line is perpendicular to the direction vector of the line.
The direction vector of the line is $\\mathbf{d} = \\langle 1, -2, 3 \\rangle$.
So, $\\vec{QP(t)} \\cdot \\mathbf{d} = 0$.

$$\langle t, -2t-1, 3t \rangle \cdot \langle 1, -2, 3 \rangle = 0$$
$$t(1) + (-2t-1)(-2) + 3t(3) = 0$$
$$t + 4t + 2 + 9t = 0$$
$$14t + 2 = 0$$
$$14t = -2$$
$$t = -\frac{2}{14} = -\frac{1}{7}$$

**Step 3:** Substitute the value of $t$ back into the parametric equations of the line to find the closest point.
$$x = 1 + \left(-\frac{1}{7}\right) = \frac{7}{7} - \frac{1}{7} = \frac{6}{7}$$
$$y = -2 \left(-\frac{1}{7}\right) = \frac{2}{7}$$
$$z = 2 + 3 \left(-\frac{1}{7}\right) = \frac{14}{7} - \frac{3}{7} = \frac{11}{7}$$
The closest point is $\\left(\\frac{6}{7}, \\frac{2}{7}, \\frac{11}{7}\\right)$.

</details>

-----

## Problem 10

**Identify the type of surface represented by the equation $z - x^2 - 4y^2 = 0$.**

**Answer:** **(c) Elliptic paraboloid**

<details>
<summary>Solution Steps</summary>

**Step 1:** Rearrange the equation to the standard form:
$$z = x^2 + 4y^2$$

**Step 2:** Analyze the form of the equation.
This equation is of the general form $z = \\frac{x^2}{a^2} + \\frac{y^2}{b^2}$.

  - If we set $z = k$ (a constant, where $k \> 0$), we get $k = x^2 + 4y^2$, which represents ellipses (or a point if $k=0$).
  - If we set $y = 0$, we get $z = x^2$, which is a parabola opening upwards along the xz-plane.
  - If we set $x = 0$, we get $z = 4y^2$, which is a parabola opening upwards along the yz-plane.

**Step 3:** Conclude the type of surface.
Since the cross-sections perpendicular to the z-axis are ellipses and the cross-sections parallel to the xz-plane or yz-plane are parabolas, the surface is an **elliptic paraboloid**.

</details>

-----

## Problem 11

**The set of points $(x, y)$ in the domain of a function $f(x, y)$ where $f(x, y) = c$ (for a constant $c$) is called a...**

**Answer:** **(d) level curve**

<details>
<summary>Solution Steps</summary>

**Explanation:**

  - A **level curve** is the set of points in the domain of a multivariable function where the function has a constant value. For a function $f(x,y)$, setting $f(x,y) = c$ gives a curve in the xy-plane where the output (z-value) is constant.
  - A level surface is the analogous concept for functions of three variables, $f(x,y,z) = c$.
  - A trace is the intersection of a surface with a plane, often one of the coordinate planes.
  - A contour plot is a collection of level curves displayed on a 2D plane.

Therefore, the correct term is **level curve**.

</details>

-----

## Problem 12

**Consider the function $f(x, y) = \\sqrt{\\frac{x^2}{y+2}}$. Which of the following statements are true?**
**I. The domain of $f$ is ${(x, y) : y \> -2 }$.**
**II. The level curves of $f$ are parabolas.**
**III. For $x = 0$, $f(0, y) = 0$ for all $y \> -2$.**

**Answer:** **(e) I, II, III**

<details>
<summary>Solution Steps</summary>

**Statement I: The domain of $f$ is ${(x, y) : y \> -2 }$.**
For $f(x, y) = \\sqrt{\\frac{x^2}{y+2}}$ to be defined:

1.  The expression under the square root must be non-negative: $\\frac{x^2}{y+2} \\geq 0$. Since $x^2 \\geq 0$ for all real $x$, this requires $y+2 \> 0$ (because the denominator cannot be zero).
2.  So, $y \> -2$.
    Thus, the domain is indeed ${(x, y) : y \> -2 }$. This statement is **TRUE**.

**Statement II: The level curves of $f$ are parabolas.**
Set $f(x, y) = c$ for some constant $c \\geq 0$.
$$\sqrt{\frac{x^2}{y+2}} = c$$
Square both sides:
$$\frac{x^2}{y+2} = c^2$$
Rearrange to solve for $y$:
$$x^2 = c^2(y+2)$$
$$y+2 = \frac{1}{c^2} x^2$$
$$y = \frac{1}{c^2} x^2 - 2$$
For any $c \> 0$, this is the equation of a parabola opening upwards with its vertex at $(0, -2)$. If $c=0$, then $x=0$, which is a line (degenerate parabola). However, typically, level curves refer to $c\>0$. So, the statement is generally **TRUE**.

**Statement III: For $x = 0$, $f(0, y) = 0$ for all $y \> -2$.**
Substitute $x = 0$ into the function:
$$f(0, y) = \sqrt{\frac{0^2}{y+2}} = \sqrt{\frac{0}{y+2}} = \sqrt{0} = 0$$
This holds for all $y \> -2$. This statement is **TRUE**.

Since all three statements are true, the correct option is (e).

</details>

-----

## Problem 13

**Consider the function $g(x, y) = \\frac{\\sin(xy)}{e^x - y^2}$. Which of the following statements are true?**
**I. It is continuous on its domain.**
**II. $\\lim\_{(x, y) \\to (0, 0)} g(x, y) = 0$.**
**III. $\\lim\_{(x, y) \\to (0, 1)} g(x, y) = 1$.**

**Answer:** **(c) I, II**

<details>
<summary>Solution Steps</summary>

**Statement I: It is continuous on its domain.**
The numerator $\\sin(xy)$ is a composition of continuous functions ($xy$ and $\\sin u$), so it is continuous everywhere.
The denominator $e^x - y^2$ is a difference of continuous functions ($e^x$ and $y^2$), so it is continuous everywhere.
A quotient of continuous functions is continuous wherever the denominator is not zero.
The domain of $g(x, y)$ is defined by $e^x - y^2 \\neq 0$. Therefore, $g(x, y)$ is continuous on its domain. This statement is **TRUE**.

**Statement II: $\\lim\_{(x, y) \\to (0, 0)} g(x, y) = 0$.**
Substitute $(x, y) = (0, 0)$ into the function:
Numerator: $\\sin(0 \\cdot 0) = \\sin(0) = 0$.
Denominator: $e^0 - 0^2 = 1 - 0 = 1$.
Since the denominator is not zero at $(0,0)$, the limit can be found by direct substitution.
$$\lim_{(x, y) \to (0, 0)} \frac{\sin(xy)}{e^x - y^2} = \frac{\sin(0)}{e^0 - 0^2} = \frac{0}{1} = 0$$
This statement is **TRUE**.

**Statement III: $\\lim\_{(x, y) \\to (0, 1)} g(x, y) = 1$.**
Substitute $(x, y) = (0, 1)$ into the function:
Numerator: $\\sin(0 \\cdot 1) = \\sin(0) = 0$.
Denominator: $e^0 - 1^2 = 1 - 1 = 0$.
This is an indeterminate form $\\frac{0}{0}$, so we need to investigate the limit further.
Consider approaching $(0, 1)$ along the line $y=1$.
$$\lim_{x \to 0} g(x, 1) = \lim_{x \to 0} \frac{\sin(x)}{e^x - 1}$$
This is a standard limit that can be evaluated using L'Hôpital's Rule or Taylor series approximations:
Using L'Hôpital's Rule:
$$\lim_{x \to 0} \frac{\cos(x)}{e^x} = \frac{\cos(0)}{e^0} = \frac{1}{1} = 1$$
This implies that if we approach along $y=1$, the limit is 1.

However, for the limit to exist, it must be the same along all paths. The question asks if the limit *is* 1. Since we found a path that yields 1, and the function is well-behaved, let's verify if there is another path that yields a different value.
The issue is that the problem text claims the answer is (c) I, II. This implies statement III is FALSE.
Let's consider if it's possible for the limit not to be 1. If we approach $(0,1)$ along the curve $y = \\sqrt{e^x}$, the denominator becomes $0$.
The problem implies that this is a trick question.
Let's re-examine my reasoning: $\\lim\_{x \\to 0} \\frac{\\sin(x)}{e^x - 1} = 1$ is correct. If the limit exists, it must be 1.
The statement "$\\lim\_{(x, y) \\to (0, 1)} g(x, y) = 1$" seems true.

Let's assume the provided answer (c) is correct and there's a reason why statement III is false. The only way it could be false is if the limit does not exist, or if it is not 1 along ALL paths.

If the denominator $e^x - y^2$ is $0$, the function is not defined. The set $e^x - y^2 = 0$ is $y^2 = e^x$, or $y = \\pm e^{x/2}$. The point $(0,1)$ is on the curve $y=e^{x/2}$ since $1 = e^{0/2}$. This means $(0,1)$ is a point where the denominator is zero.

The statement is **TRUE** as the limit along $y=1$ is 1, and there is no simple argument that suggests the limit might not exist or be different along other paths. For a function defined in a neighborhood *excluding* the point itself, the limit could still be 1.

Given the multiple choice answer implies I and II are true, and III is false. This would mean that even though the limit is 1 along some paths, it is not 1 (or does not exist) along all paths. This would happen if the approach to $(0,1)$ along $y^2=e^x$ means the limit does not exist. However, the limit $\\frac{\\sin(xy)}{e^x-y^2}$ often requires a specific technique like linearization around the point.
Let's re-evaluate using a different approach.
If we set $y^2 = e^x - \\epsilon$ for small $\\epsilon$, this still approaches 0.
The most likely scenario for III to be false, despite the L'Hopital result, is that the limit does not exist due to approaching along the boundary where the denominator is zero. However, it's typical for such problems that if a direct L'Hopital path gives a value, that's the limit.

Let's stick with the solution steps in the original context, which say that statement III is false. This means the limit either doesn't exist or is not 1 for some other path. Without further information, and given the provided answers, it is most likely that the question implies the limit *does not exist* generally, even if it's 1 along $y=1$.

Final check:
If we approach along $x=0$, $g(0,y) = \\frac{\\sin(0)}{1-y^2} = 0$ for $y \\neq 1$. So as $(0,y) \\to (0,1)$, $g(0,y) \\to 0$. This conflicts with the limit being 1 along $y=1$.
Therefore, the limit does not exist. So statement III is **FALSE**.

Thus, only I and II are true.

</details>

-----

## Problem 14

**Given $f(x, y) = 2x + xy^2 - \\sqrt{|3x(y-1)|}$, find $f\_x(0, 1)$.**

**Answer:** **(d) 3**

<details>
<summary>Solution Steps</summary>

**Step 1:** Calculate the partial derivative of $f$ with respect to $x$, $f\_x(x, y)$.
$$f_x(x, y) = \frac{\partial}{\partial x} (2x) + \frac{\partial}{\partial x} (xy^2) - \frac{\partial}{\partial x} (\sqrt{|3x(y-1)|})$$
$$f_x(x, y) = 2 + y^2 - \frac{\partial}{\partial x} (\sqrt{|3x(y-1)|})$$

**Step 2:** Analyze the derivative of the square root term.
The term $\\sqrt{|3x(y-1)|}$ involves an absolute value. We need to be careful when differentiating.
If $y=1$, then $3x(y-1) = 3x(0) = 0$. So, $\\sqrt{|3x(y-1)|} = 0$ for $y=1$.
Thus, $f(x, 1) = 2x + x(1)^2 - \\sqrt{|3x(1-1)|} = 2x + x - 0 = 3x$.

**Step 3:** Evaluate $f\_x(0, 1)$ using the simplified form when $y=1$.
Since we are evaluating at $(0, 1)$, where $y=1$, we can use $f(x, 1) = 3x$.
$$f_x(x, 1) = \frac{d}{dx}(3x) = 3$$
Therefore, $f\_x(0, 1) = 3$.

Alternatively, by the definition of the partial derivative:
$$f_x(0, 1) = \lim_{h \to 0} \frac{f(0+h, 1) - f(0, 1)}{h}$$
$$f(h, 1) = 2h + h(1)^2 - \sqrt{|3h(1-1)|} = 2h + h - \sqrt{0} = 3h$$
$$f(0, 1) = 2(0) + 0(1)^2 - \sqrt{|3(0)(1-1)|} = 0$$
$$f_x(0, 1) = \lim_{h \to 0} \frac{3h - 0}{h} = \lim_{h \to 0} 3 = 3$$

</details>

-----

## Problem 15

**If $w(x, y, z) = f(xz, yz)$, what is the value of $x \\frac{\\partial w}{\\partial x} + y \\frac{\\partial w}{\\partial y}$?**

**Answer:** **(e) $z \\frac{\\partial w}{\\partial z}$**

<details>
<summary>Solution Steps</summary>

**Step 1:** Define intermediate variables for the function $f$.
Let $u = xz$ and $v = yz$. So, $w = f(u, v)$.

**Step 2:** Use the Chain Rule to find $\\frac{\\partial w}{\\partial x}$.
$$\frac{\partial w}{\partial x} = \frac{\partial f}{\partial u} \frac{\partial u}{\partial x} + \frac{\partial f}{\partial v} \frac{\partial v}{\partial x}$$
$$\frac{\partial u}{\partial x} = z$$
$$\frac{\partial v}{\partial x} = 0$$
So, $\\frac{\\partial w}{\\partial x} = \\frac{\\partial f}{\\partial u} (z) + \\frac{\\partial f}{\\partial v} (0) = z f\_u $ (where $f\_u = \\frac{\\partial f}{\\partial u}$).

**Step 3:** Use the Chain Rule to find $\\frac{\\partial w}{\\partial y}$.
$$\frac{\partial w}{\partial y} = \frac{\partial f}{\partial u} \frac{\partial u}{\partial y} + \frac{\partial f}{\partial v} \frac{\partial v}{\partial y}$$
$$\frac{\partial u}{\partial y} = 0$$
$$\frac{\partial v}{\partial y} = z$$
So, $\\frac{\\partial w}{\\partial y} = \\frac{\\partial f}{\\partial u} (0) + \\frac{\\partial f}{\\partial v} (z) = z f\_v $ (where $f\_v = \\frac{\\partial f}{\\partial v}$).

**Step 4:** Substitute these partial derivatives into the expression $x \\frac{\\partial w}{\\partial x} + y \\frac{\\partial w}{\\partial y}$.
$$x \frac{\partial w}{\partial x} + y \frac{\partial w}{\partial y} = x (z f_u) + y (z f_v)$$
$$= xz f_u + yz f_v$$
$$= z (x f_u + y f_v)$$

**Step 5:** Now consider $\\frac{\\partial w}{\\partial z}$ using the Chain Rule.
$$\frac{\partial w}{\partial z} = \frac{\partial f}{\partial u} \frac{\partial u}{\partial z} + \frac{\partial f}{\partial v} \frac{\partial v}{\partial z}$$
$$\frac{\partial u}{\partial z} = x$$
$$\frac{\partial v}{\partial z} = y$$
So, $\\frac{\\partial w}{\\partial z} = \\frac{\\partial f}{\\partial u} (x) + \\frac{\\partial f}{\\partial v} (y) = x f\_u + y f\_v $.

**Step 6:** Compare the results from Step 4 and Step 5.
We found $x \\frac{\\partial w}{\\partial x} + y \\frac{\\partial w}{\\partial y} = z (x f\_u + y f\_v)$ and $\\frac{\\partial w}{\\partial z} = x f\_u + y f\_v$.
Therefore, $x \\frac{\\partial w}{\\partial x} + y \\frac{\\partial w}{\\partial y} = z \\frac{\\partial w}{\\partial z}$.

</details>

-----

## Problem 16

**Given the equation $z^5 + x y e^z + e^{2x} = 0$, find $\\frac{\\partial z}{\\partial x}$ at the point $(0, e, -1)$.**

**Answer:** **(c) $-\\frac{3}{5}$**

<details>
<summary>Solution Steps</summary>

**Step 1:** Differentiate both sides of the equation with respect to $x$, treating $z$ as a function of $x$ and $y$ (i.e., $z(x, y)$).
$$\frac{\partial}{\partial x}(z^5) + \frac{\partial}{\partial x}(xy e^z) + \frac{\partial}{\partial x}(e^{2x}) = \frac{\partial}{\partial x}(0)$$

**Step 2:** Apply the chain rule and product rule where necessary.
$$5z^4 \frac{\partial z}{\partial x} + (1 \cdot y e^z + xy e^z \frac{\partial z}{\partial x}) + 2e^{2x} = 0$$
$$5z^4 \frac{\partial z}{\partial x} + y e^z + xy e^z \frac{\partial z}{\partial x} + 2e^{2x} = 0$$

**Step 3:** Group terms containing $\\frac{\\partial z}{\\partial x}$.
$$(5z^4 + xy e^z) \frac{\partial z}{\partial x} = -y e^z - 2e^{2x}$$

**Step 4:** Solve for $\\frac{\\partial z}{\\partial x}$.
$$\frac{\partial z}{\partial x} = \frac{-y e^z - 2e^{2x}}{5z^4 + xy e^z}$$

**Step 5:** Substitute the given point $(x, y, z) = (0, e, -1)$ into the expression for $\\frac{\\partial z}{\\partial x}$.
$$\frac{\partial z}{\partial x} = \frac{-(e) e^{-1} - 2e^{2(0)}}{5(-1)^4 + (0)(e) e^{-1}}$$
$$\frac{\partial z}{\partial x} = \frac{-1 - 2(1)}{5(1) + 0}$$
$$\frac{\partial z}{\partial x} = \frac{-3}{5}$$

</details>

-----

## Problem 17

**Find the directional derivative of $f(x, y, z) = x^2 e^y - \\frac{3}{2} \\sqrt[3]{z^4}$ at the point $(-6, 0, 8)$ in the direction toward the origin.**

**Answer:** **(b) $-4$**

<details>
<summary>Solution Steps</summary>

**Step 1:** Calculate the gradient of $f$, $\\nabla f$.
$$f(x, y, z) = x^2 e^y - \frac{3}{2} z^{4/3}$$
$$\nabla f = \left\langle \frac{\partial f}{\partial x}, \frac{\partial f}{\partial y}, \frac{\partial f}{\partial z} \right\rangle$$
$$\frac{\partial f}{\partial x} = 2x e^y$$
$$\frac{\partial f}{\partial y} = x^2 e^y$$
$$\frac{\partial f}{\partial z} = -\frac{3}{2} \cdot \frac{4}{3} z^{(4/3)-1} = -2z^{1/3}$$
So, $\\nabla f = \\langle 2x e^y, x^2 e^y, -2z^{1/3} \\rangle$.

**Step 2:** Evaluate the gradient at the point $(-6, 0, 8)$.
$$\nabla f(-6, 0, 8) = \langle 2(-6) e^0, (-6)^2 e^0, -2(8)^{1/3} \rangle$$
$$= \langle -12 \cdot 1, 36 \cdot 1, -2 \cdot 2 \rangle$$
$$= \langle -12, 36, -4 \rangle$$

**Step 3:** Determine the direction vector.
The direction is from $(-6, 0, 8)$ toward the origin $(0, 0, 0)$.
The vector representing this direction is $\\mathbf{v} = (0 - (-6))\\mathbf{i} + (0 - 0)\\mathbf{j} + (0 - 8)\\mathbf{k} = \\langle 6, 0, -8 \\rangle$.

**Step 4:** Normalize the direction vector to find the unit vector $\\mathbf{u}$.
$$|\mathbf{v}| = \sqrt{6^2 + 0^2 + (-8)^2} = \sqrt{36 + 0 + 64} = \sqrt{100} = 10$$
$$\mathbf{u} = \frac{\mathbf{v}}{|\mathbf{v}|} = \frac{\langle 6, 0, -8 \rangle}{10} = \langle 0.6, 0, -0.8 \rangle$$

**Step 5:** Calculate the directional derivative $D\_{\\mathbf{u}}f = \\nabla f \\cdot \\mathbf{u}$.
$$D_{\mathbf{u}}f(-6, 0, 8) = \langle -12, 36, -4 \rangle \cdot \langle 0.6, 0, -0.8 \rangle$$
$$= (-12)(0.6) + (36)(0) + (-4)(-0.8)$$
$$= -7.2 + 0 + 3.2$$
$$= -4$$

</details>

-----

## Problem 18

**In what direction is the derivative of $f(x, y) = x \\log\_2 y - x$ at the point $(\\ln 16, 4)$ equal to zero?**

**Answer:** **(d) $\\mathbf{i} - \\mathbf{j}$**

<details>
<summary>Solution Steps</summary>

**Step 1:** Find the gradient of $f(x, y)$, which points in the direction of the maximum rate of increase of $f$. The derivative in a direction perpendicular to the gradient will be zero.
$$\nabla f = \left\langle \frac{\partial f}{\partial x}, \frac{\partial f}{\partial y} \right\rangle$$
$$\frac{\partial f}{\partial x} = \frac{\partial}{\partial x}(x \log_2 y - x) = \log_2 y - 1$$
$$\frac{\partial f}{\partial y} = \frac{\partial}{\partial y}(x \log_2 y - x) = x \cdot \frac{1}{y \ln 2}$$
So, $\\nabla f = \\left\\langle \\log\_2 y - 1, \\frac{x}{y \\ln 2} \\right\\rangle$.

**Step 2:** Evaluate the gradient at the given point $(\\ln 16, 4)$.
Remember that $\\ln 16 = \\ln(2^4) = 4\\ln 2$ and $\\log\_2 4 = 2$.
$$\frac{\partial f}{\partial x}(\ln 16, 4) = \log_2 4 - 1 = 2 - 1 = 1$$
$$\frac{\partial f}{\partial y}(\ln 16, 4) = \frac{\ln 16}{4 \ln 2} = \frac{4 \ln 2}{4 \ln 2} = 1$$
So, $\\nabla f(\\ln 16, 4) = \\langle 1, 1 \\rangle = \\mathbf{i} + \\mathbf{j}$.

**Step 3:** The directional derivative is zero in any direction perpendicular to the gradient vector.
If $\\nabla f = \\langle A, B \\rangle$, then a perpendicular vector is $\\langle -B, A \\rangle$ or $\\langle B, -A \\rangle$.
For $\\nabla f = \\langle 1, 1 \\rangle$, a perpendicular direction is $\\langle -1, 1 \\rangle$ or $\\langle 1, -1 \\rangle$.
In terms of unit vectors, these are $-\\mathbf{i} + \\mathbf{j}$ or $\\mathbf{i} - \\mathbf{j}$.

Comparing with the options, (d) $\\mathbf{i} - \\mathbf{j}$ is one such direction.

</details>

-----

## Problem 19

**Find the equation of the tangent plane to the surface $z = 3x^2 + 2y^2 - 3xy$ at the point $(1, 1, 2)$.**

**Answer:** **(b) $3x + y - z = 2$**

<details>
<summary>Solution Steps</summary>

**Step 1:** The equation of a tangent plane to a surface $z = f(x, y)$ at a point $(x\_0, y\_0, z\_0)$ is given by:
$$z - z_0 = f_x(x_0, y_0)(x - x_0) + f_y(x_0, y_0)(y - y_0)$$

**Step 2:** Calculate the partial derivatives $f\_x(x, y)$ and $f\_y(x, y)$.
$$f(x, y) = 3x^2 + 2y^2 - 3xy$$
$$f_x(x, y) = \frac{\partial}{\partial x}(3x^2 + 2y^2 - 3xy) = 6x - 3y$$
$$f_y(x, y) = \frac{\partial}{\partial y}(3x^2 + 2y^2 - 3xy) = 4y - 3x$$

**Step 3:** Evaluate the partial derivatives at the given point $(x\_0, y\_0, z\_0) = (1, 1, 2)$.
$$f_x(1, 1) = 6(1) - 3(1) = 6 - 3 = 3$$
$$f_y(1, 1) = 4(1) - 3(1) = 4 - 3 = 1$$

**Step 4:** Substitute these values into the tangent plane equation.
$$z - 2 = 3(x - 1) + 1(y - 1)$$
$$z - 2 = 3x - 3 + y - 1$$
$$z - 2 = 3x + y - 4$$

**Step 5:** Rearrange the equation into the standard form $Ax + By + Cz = D$.
$$3x + y - z = 4 - 2$$
$$3x + y - z = 2$$

</details>

-----

## Problem 20

**Which of the following expressions make sense for vectors $\\mathbf{u}, \\mathbf{v}, \\mathbf{w}$ in $\\mathbb{R}^3$?**
**I. $(\\mathbf{u} \\times \\mathbf{v}) \\cdot \\mathbf{w}$**
**II. $\\mathbf{u} \\times (\\mathbf{v} \\cdot \\mathbf{w})$**
**III. $\\mathbf{u} \\times (\\mathbf{v} \\times \\mathbf{w})$**
**IV. $\\mathbf{u} \\cdot (\\mathbf{v} \\cdot \\mathbf{w})$**

**Answer:** **(b) I, III**

<details>
<summary>Solution Steps</summary>

Let's analyze each expression:

**I. $(\\mathbf{u} \\times \\mathbf{v}) \\cdot \\mathbf{w}$**

  - $\\mathbf{u} \\times \\mathbf{v}$ results in a **vector** (the cross product of two vectors is a vector).
  - The dot product of a vector and a vector results in a **scalar**.
  - This expression represents the scalar triple product, which calculates the volume of the parallelepiped formed by the three vectors. This operation **makes sense**.

**II. $\\mathbf{u} \\times (\\mathbf{v} \\cdot \\mathbf{w})$**

  - $\\mathbf{v} \\cdot \\mathbf{w}$ results in a **scalar**.
  - The cross product is defined between two vectors, not a vector and a scalar. You cannot take the cross product of a vector ($\\mathbf{u}$) and a scalar ($\\mathbf{v} \\cdot \\mathbf{w}$). This operation **does not make sense**.

**III. $\\mathbf{u} \\times (\\mathbf{v} \\times \\mathbf{w})$**

  - $\\mathbf{v} \\times \\mathbf{w}$ results in a **vector**.
  - The cross product of two vectors results in a **vector**.
  - This expression represents the vector triple product, which is a valid operation and results in a vector. This operation **makes sense**.

**IV. $\\mathbf{u} \\cdot (\\mathbf{v} \\cdot \\mathbf{w})$**

  - $\\mathbf{v} \\cdot \\mathbf{w}$ results in a **scalar**.
  - The dot product is defined between two vectors, not a vector and a scalar. You cannot take the dot product of a vector ($\\mathbf{u}$) and a scalar ($\\mathbf{v} \\cdot \\mathbf{w}$). This operation **does not make sense**.

Therefore, only expressions I and III make sense.

</details>

-----

## Summary of Answers

1.  (c) $\\frac{dy}{dx}$
2.  (e) $r^2 = 4r\\cos\\theta - 6r\\sin\\theta + 4$
3.  (b) $y = 0$
4.  (d) $\\frac{9\\pi}{2} + 9$
5.  (b) $-\\mathbf{i}$
6.  (a) $\\cos^{-1}\\left(\\frac{3}{\\sqrt{35}}\\right)$
7.  (a) ${-2, 0, 2}$
8.  (a) $x + 2y + z = 18$
9.  (a) $\\left(\\frac{6}{7}, \\frac{2}{7}, \\frac{11}{7}\\right)$
10. (c) Elliptic paraboloid
11. (d) level curve
12. (e) I, II, III
13. (c) I, II
14. (d) 3
15. (e) $z \\frac{\\partial w}{\\partial z}$
16. (c) $-\\frac{3}{5}$
17. (b) $-4$
18. (d) $\\mathbf{i} - \\mathbf{j}$
19. (b) $3x + y - z = 2$
20. (b) I, III
