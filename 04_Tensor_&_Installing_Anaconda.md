# # What is Tensor ?

- A mathematical data structure that can represent scalars, vectors, matrices, and higher-dimensional data in a unified way.
- **`Tensor`** = Multi-dimensional array of numbers.


<img src="https://github.com/user-attachments/assets/646f2c68-5319-439d-a142-6874dfc7517b" width="500" height="600">

## Types of Tensors (by dimensions)

| Tensor Type | Dimension    | ML Example                          |
|-------------|--------------|-------------------------------------|
| **Scalar**  | 0D           | Learning rate = 0.01                |
| **Vector**  | 1D           | Feature list `[age, salary, score]` |
| **Matrix**  | 2D           | Dataset table (rows × columns)      |
| **Tensor**  | 3D / 4D / nD | Images, videos, batches of data     |

<img src="https://github.com/user-attachments/assets/e46c624a-8490-4c2f-9a15-474b6325d455" width="400" height="400">

# # Rank, Axes, Shape and Size

## (1.) Rank 

- Rank of a tensor = Number of dimensions (axes) it has.
- It indicates the number of dimensions present in a tensor.


| Tensor | Rank | Example         |
| ------ | ---- | --------------- |
| Scalar | 0    | `5`             |
| Vector | 1    | `[1, 2, 3]`     |
| Matrix | 2    | `[[1,2],[3,4]]` |
| Tensor | 3+   | Image, video    |


## (2.) Axes

- An axis is one specific dimension of a tensor.
- No. of Axis = Rank = No. of Dimension


#### Example : 

> Tensor shape = (3, 4, 5)
> 
> Axis 0 → size 3  
> Axis 1 → size 4  
> Axis 2 → size 5  
>
> Each axis tells how data is arranged


## (3.) Shape

- It describes how many elements are along each axis of the tensor.
- Shape = size of tensor along each axis

#### Example:

> Shape = (2, 3)
>
> Means:
> 2 rows
> 3 columns
>
> Shape fully describes tensor structure


## (4.) Size

- Size = total number of elements in a tensor.
- **Formula**: `Size = product of all shape values`

#### Example:

> Shape = (2, 3, 4)
> Size = 2 × 3 × 4 = 24 elements



## # Quick Comparison Table

| Term  | Meaning | Example |
|------|--------|---------|
| Rank | Number of dimensions | Rank of (3,4,5) = 3 |
| Axes | Individual dimensions | Axis 0, Axis 1 |
| Shape | Size along each axis | (3,4,5) |
| Size | Total elements | 3×4×5 = 60 |


<img src="https://github.com/user-attachments/assets/2d703de0-56cb-488f-ad5a-22bf72f02241" width="400" height="400">











