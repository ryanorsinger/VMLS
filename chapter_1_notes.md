## Vocabulary and definitions
- Vector - ordered finite list of scalars
- Elements (entries, coefficients, components) of a vector are the values in the array
- Size is the number of elements in the array (also called dimension or length)
- A vector of size n is called an n-vector
- n<sub>i</sub> signifies the i-th element of the vector (index starting at 1)
- <b>R</b> means the set of all real numbers
- <b>R</b><sup>2</sup> denotes the set of all real n-vectors
- Indexing in Linear Algebra, by definition, starts at 1
- Zero vector is a vector will all elements `0`. so `0 == [0, 0, 0, 0, 0]`
- Ones vector is a vector containing only 1s. 
- Unit vector - a standard unit vector is a vector with all elements equal to zero except for one element which is equal to one.
- Sparsity - a vector mostly composed of zeros.
- Sparsity pattern is the set of indeces of nonzero entries.

## Heads up!
The 1-vector `[3.3]` is equivalent to the scalar `3.3`.

## Operations
- Equality of two vectors occurs when both have the same elements at the same index.
- Subvectors a<sub>r:s</sub> = a<sub>r</sub>, ..., a<sub>s</sub>s

## Unit Vectors
- `[1, 0, 1]`, `[1, 0]`, `[0, 0, 0, 0, 1]` are each unit vectors
- (e<sub>i</sub>)<sub>j</sub> = {1: j=i, 0: j!=i}

## Examples of using an n-vector to represent n quantities or values in an application
- Location or displacement 
    - For instance(latitude, longitude) is a vector.
- Color 
- Portfolio
- Values across a population
- Proportions
- Time series
- Daily Return
- Cash Flow
- Images
- Video
- Word count and histogram
- Customer pourchases
- Occurence or subsets
- Features or attributes
- Vector Entry Labels