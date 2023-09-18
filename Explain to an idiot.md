Key Words:
- Matrix
- Vector
- Scalar
- Axis
- $\hat{i}$ , $\hat{j}$ , $\hat{k}$
- Component
- Linear Transformation
- X , Y , Z
- Origin
- Basis Vector

Identity Matrix e.g.
$$
\begin{bmatrix}
1 & 0 & 0\\
0 & 1 & 0\\
0 & 0 & 1
\end{bmatrix}
$$
- Explain Why no changes occurs when multiplying a vector or a matrix by this matrix

The above identity matrix doesn't change vectors or matrix's when multiplied by this matrix. this is what is meant by the 'identity'.

This matrix in 3D and has 1s along the diagonal and 0s everywhere else. The first column of this matrix corresponds to the where i-hat ( The X direction basis vector ) moves; The second column of this matrix corresponds to the where j-hat ( The Y direction basis vector ) moves; The third column of this matrix corresponds to the where k-hat ( The X direction basis vector ) moves. The reason why multiplying a vector by this matrix doesn't change i-hat, j-hat or k-hat are already at these locations and don't move. the resulting vector is already determined by the what the x, y and z components of the vector where.


Scalar Matrix
$$
\begin{bmatrix}
2 & 0 & 0\\
0 & 0.5 & 0\\
0 & 0 & 1
\end{bmatrix}
$$
- Explain why this matrix scales space and only scales space

The above scaling matrix scales 3D space. It doesn't rotate, translate or share space. A matrix with the property has scalar values along the diagonal and 0s everywhere else. The basis vectors i-hats, j-hat and k-hat are changed after a linear transformation. in this case the basis vectors remain on their respective axis ( X for i-hat, Y for j-hat and Z for k-hat ) only scaled by some amount

In the case for this matrix. The X component will be squished / extended by a factor/scalar of 2; The Y component will be squished / shortened by a factor/scalar of 0.5; The Z component will be stay the same as its k-hat column has 1

Rotation Matrix
$$
\begin{bmatrix}
\cos(\theta) & \sin(\theta) & 0\\
-\sin(\theta) & \cos(\theta) & 0\\
0 & 0 & 1
\end{bmatrix}
$$
- A rotation matrix of pi over 6 radians about the z axis
- Explain why this matrix rotates space and only rotates space

This Matrix represents a linear transformation that is a rotation about the Z axis.
Multiplying a vector(point) by each column of this matrix changes the i-hat, j-hat, k-hat basis vectors post transformation.

In this matrix i-hat will move by some angle, j-hat wills also move by some angle. However k-hat will not change as there is no movement along the z axis

Combo Matrix
$$
\begin{bmatrix}
1 & 0 & 0\\
0 & 1 & 0\\
0 & 0 & 1
\end{bmatrix}
$$
- Explain how and why these two can be combined