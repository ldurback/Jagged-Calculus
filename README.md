# Jagged Calculus and Cardinal Geometric Algebra
Calculus for Jagged Functions, as well as a new vector algebra to go with it

# Cardinal Geometric Algebra

## Cardinal Basis
The basis of a cardinal geometric algebra is a set of unit vectors that lie along the 2n cardinal directions of an n-dimensional Euclidean (or Minkowsi) space.

For instance, for 3+1D Minkowski space-time, the cardinal unit vectors are {<img src="https://latex.codecogs.com/gif.latex?\widehat{x_&plus;}" title="\widehat{x_+}" />, <img src="https://latex.codecogs.com/gif.latex?\widehat{x_-}" title="\widehat{x_-}" />, <img src="https://latex.codecogs.com/gif.latex?\widehat{y_&plus;}" title="\widehat{y_+}" />, <img src="https://latex.codecogs.com/gif.latex?\widehat{y_-}" title="\widehat{y_-}" />, <img src="https://latex.codecogs.com/gif.latex?\widehat{z_&plus;}" title="\widehat{z_+}" />, <img src="https://latex.codecogs.com/gif.latex?\widehat{z_-}" title="\widehat{z_-}" />, <img src="https://latex.codecogs.com/gif.latex?\widehat{t_&plus;}" title="\widehat{t_+}" />, <img src="https://latex.codecogs.com/gif.latex?\widehat{t_-}" title="\widehat{t_-}" />}.

I will call the carndinal basis vectors which point in opposite directions "opposite vectors".  "Negative vectors" also exist, but they are linearly independent from opposite vectors.

For instance, <img src="https://latex.codecogs.com/gif.latex?\widehat{x_&plus;}" title="\widehat{x_+}" /> and <img src="https://latex.codecogs.com/gif.latex?\widehat{x_-}" title="\widehat{x_-}" /> are opposites, while <img src="https://latex.codecogs.com/gif.latex?\widehat{x_&plus;}" title="\widehat{x_+}" /> and <img src="https://latex.codecogs.com/gif.latex?-\widehat{x_&plus;}" title="-\widehat{x_+}" /> are negatives.

## Axis Vectors

The axis vectors are given by averaging together a positively oriented cardinal basis unit vector with the negative of its opposite.

For instance:

<img src="https://latex.codecogs.com/gif.latex?\hat{x}&space;=&space;\frac{1}{2}&space;(\widehat{x_&plus;}&space;-&space;\widehat{x_-})" title="\hat{x} = \frac{1}{2} (\widehat{x_+} - \widehat{x_-})" />


## Multiplication Rules for the Cardinal Basis

### Squaring a Cardinal Unit Basis Vector

For any cardinal unit basis vector, squaring it yields its signature, which is either +1 or -1.  Both a cardinal unit basis vector and its opposite have the same signature.

For instance, for 3+1D Minkowski space-time:

<img src="https://latex.codecogs.com/gif.latex?\widehat{x_&plus;}^2=\widehat{x_-}^2=\widehat{y_&plus;}^2=\widehat{y_-}^2=\widehat{z_&plus;}^2=\widehat{z_-}^2=1" title="\widehat{x_+}^2=\widehat{x_-}^2=\widehat{y_+}^2=\widehat{y_-}^2=\widehat{z_+}^2=\widehat{z_-}^2=1" />

<img src="https://latex.codecogs.com/gif.latex?\widehat{t_&plus;}^2=\widehat{t_-}^2=-1" title="\widehat{t_+}^2=\widehat{t_-}^2=-1" />

### Multiplying a Cardinal Unit Basis Vector by its Opposite

For any cardinal unit basis vector, multiplying it by its opposite yields the negative of its signature, which is either -1 or +1.  Any vector commutes with its opposite.

For instance, in 3+1D Minkowski space-time, we have

<img src="https://latex.codecogs.com/gif.latex?\widehat{x_&plus;}&space;\widehat{x_-}&space;=&space;\widehat{x_-}&space;\widehat{x_&plus;}&space;=&space;-1" title="\widehat{x_+} \widehat{x_-} = \widehat{x_-} \widehat{x_+} = -1" />

<img src="https://latex.codecogs.com/gif.latex?\widehat{t_&plus;}&space;\widehat{t_-}&space;=&space;\widehat{t_-}&space;\widehat{t_&plus;}&space;=&space;1" title="\widehat{t_+} \widehat{t_-} = \widehat{t_-} \widehat{t_+} = 1" />

### Multiplying two Cardinal Unit Basis Vectors of Different Axes

The product of two carndinal unit basis vectors of different axes does not reduce.  Geometrically, we can identify this product, called a bi-vector, with the oriented area generated by the first and second vectors in the product.  We consider the product linearly independent from product of the second vector multiplied by the first vector.  However, by swapping both vectors in the product and taking the opposite of one of them, we get the same bi-vector.

For instance:

<img src="https://latex.codecogs.com/gif.latex?\widehat{x_&plus;}&space;\widehat{y_&plus;}&space;=&space;\widehat{y_&plus;}&space;\widehat{x_-}&space;=&space;\widehat{x_-}&space;\widehat{y_-}&space;=&space;\widehat{y_-}&space;\widehat{x_&plus;}" title="\widehat{x_+} \widehat{y_+} = \widehat{y_+} \widehat{x_-} = \widehat{x_-} \widehat{y_-} = \widehat{y_-} \widehat{x_+}" />

<img src="https://latex.codecogs.com/gif.latex?\widehat{y_&plus;}&space;\widehat{x_&plus;}&space;=&space;\widehat{x_&plus;}&space;\widehat{y_-}&space;=&space;\widehat{y_-}&space;\widehat{x_-}&space;=&space;\widehat{x_-}&space;\widehat{y_&plus;}" title="\widehat{y_+} \widehat{x_+} = \widehat{x_+} \widehat{y_-} = \widehat{y_-} \widehat{x_-} = \widehat{x_-} \widehat{y_+}" />

Which are both linearly independent.


## Dot-Product

If <img src="https://latex.codecogs.com/gif.latex?\vec{v}" title="\vec{v}" /> and <img src="https://latex.codecogs.com/gif.latex?\vec{w}" title="\vec{w}" /> are two vectors of the cardinal geometric algebra, then their dot product is given by the scalar (grade-0) part of their product

<img src="https://latex.codecogs.com/gif.latex?\vec{v}&space;\cdot&space;\vec{w}&space;=&space;\langle&space;\vec{v}&space;\vec{w}&space;\rangle_0&space;=&space;\langle&space;\vec{w}&space;\vec{v}&space;\rangle_0" title="\vec{v} \cdot \vec{w} = \langle \vec{v} \vec{w} \rangle_0 = \langle \vec{w} \vec{v} \rangle_0" />


# Jagged Calculus in 1 Dimension

## The Left and Right Derivatives

The left derivative is defined as

<img src="https://latex.codecogs.com/gif.latex?\frac{df}{dx}_-&space;=&space;\lim_{\epsilon&space;\to&space;0^-}&space;\frac{f(x&plus;\epsilon)&space;-&space;f(x)}{\epsilon}" title="\frac{df}{dx}_- = \lim_{\epsilon \to 0^-} \frac{f(x+\epsilon) - f(x)}{\epsilon}" />

while the right derivative is defined similarly

<img src="https://latex.codecogs.com/gif.latex?\frac{df}{dx}_&plus;&space;=&space;\lim_{\epsilon&space;\to&space;0^&plus;}&space;\frac{f(x&plus;\epsilon)&space;-&space;f(x)}{\epsilon}" title="\frac{df}{dx}_+ = \lim_{\epsilon \to 0^+} \frac{f(x+\epsilon) - f(x)}{\epsilon}" />

## The Jagged Derivative

The jagged derivative is defined as one half the vector difference of the right and left derivatives.  Specifically:

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac{d}{d&space;\vec&space;x}&space;=&space;\frac{1}{2}&space;(&space;\frac{1}{\widehat{x_&plus;}}&space;\frac{d}{dx}_&plus;&space;-&space;\frac{1}{\widehat{x_-}}&space;\frac{d}{dx}_-)&space;=&space;\frac{1}{2}&space;(\frac{d}{d\vec{x}}_&plus;&space;-&space;\frac{d}{d&space;\vec{x}}_-)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{d}{d&space;\vec&space;x}&space;=&space;\frac{1}{2}&space;(&space;\frac{1}{\widehat{x_&plus;}}&space;\frac{d}{dx}_&plus;&space;-&space;\frac{1}{\widehat{x_-}}&space;\frac{d}{dx}_-)&space;=&space;\frac{1}{2}&space;(\frac{d}{d\vec{x}}_&plus;&space;-&space;\frac{d}{d&space;\vec{x}}_-)" title="\frac{d}{d \vec x} = \frac{1}{2} ( \frac{1}{\widehat{x_+}} \frac{d}{dx}_+ - \frac{1}{\widehat{x_-}} \frac{d}{dx}_-) = \frac{1}{2} (\frac{d}{d\vec{x}}_+ - \frac{d}{d \vec{x}}_-)" /></a>

### Examples

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac{d&space;x}{d&space;\vec&space;x}&space;=&space;\frac{1}{2}&space;(&space;\frac{1}{\widehat{x_&plus;}}&space;\frac{d&space;x}{dx}_&plus;&space;-&space;\frac{1}{\widehat{x_-}}&space;\frac{d&space;x}{dx}_-)&space;=&space;\frac{1}{2}&space;(\widehat{x_&plus;}&space;-&space;\widehat{x_-})&space;=&space;\hat&space;x" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{d&space;x}{d&space;\vec&space;x}&space;=&space;\frac{1}{2}&space;(&space;\frac{1}{\widehat{x_&plus;}}&space;\frac{d&space;x}{dx}_&plus;&space;-&space;\frac{1}{\widehat{x_-}}&space;\frac{d&space;x}{dx}_-)&space;=&space;\frac{1}{2}&space;(\widehat{x_&plus;}&space;-&space;\widehat{x_-})&space;=&space;\hat&space;x" title="\frac{d x}{d \vec x} = \frac{1}{2} ( \frac{1}{\widehat{x_+}} \frac{d x}{dx}_+ - \frac{1}{\widehat{x_-}} \frac{d x}{dx}_-) = \frac{1}{2} (\widehat{x_+} - \widehat{x_-}) = \hat x" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac{d&space;\vec&space;x}{d&space;\vec&space;x}&space;=&space;\frac{1}{2}&space;(&space;\frac{1}{\widehat{x_&plus;}}&space;\frac{d&space;\vec&space;x}{dx}_&plus;&space;-&space;\frac{1}{\widehat{x_-}}&space;\frac{d&space;\vec&space;x}{dx}_-)&space;=&space;\frac{1}{2}&space;(\widehat{x_&plus;}&space;\hat&space;x&space;-&space;\widehat{x_-}&space;\hat&space;x)&space;=&space;1" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{d&space;\vec&space;x}{d&space;\vec&space;x}&space;=&space;\frac{1}{2}&space;(&space;\frac{1}{\widehat{x_&plus;}}&space;\frac{d&space;\vec&space;x}{dx}_&plus;&space;-&space;\frac{1}{\widehat{x_-}}&space;\frac{d&space;\vec&space;x}{dx}_-)&space;=&space;\frac{1}{2}&space;(\widehat{x_&plus;}&space;\hat&space;x&space;-&space;\widehat{x_-}&space;\hat&space;x)&space;=&space;1" title="\frac{d \vec x}{d \vec x} = \frac{1}{2} ( \frac{1}{\widehat{x_+}} \frac{d \vec x}{dx}_+ - \frac{1}{\widehat{x_-}} \frac{d \vec x}{dx}_-) = \frac{1}{2} (\widehat{x_+} \hat x - \widehat{x_-} \hat x) = 1" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac{d&space;x^2}{d&space;\vec&space;x}&space;=&space;\frac{1}{2}&space;(&space;\frac{1}{\widehat{x_&plus;}}&space;\frac{d&space;x^2}{dx_&plus;}&space;-&space;\frac{1}{\widehat{x_-}}&space;\frac{d&space;x^2}{dx_-})&space;=&space;\frac{1}{2}&space;(\widehat{x_&plus;}&space;2x&space;-&space;\widehat{x_-}&space;2x)&space;=&space;2&space;\vec&space;x" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{d&space;x^2}{d&space;\vec&space;x}&space;=&space;\frac{1}{2}&space;(&space;\frac{1}{\widehat{x_&plus;}}&space;\frac{d&space;x^2}{dx_&plus;}&space;-&space;\frac{1}{\widehat{x_-}}&space;\frac{d&space;x^2}{dx_-})&space;=&space;\frac{1}{2}&space;(\widehat{x_&plus;}&space;2x&space;-&space;\widehat{x_-}&space;2x)&space;=&space;2&space;\vec&space;x" title="\frac{d x^2}{d \vec x} = \frac{1}{2} ( \frac{1}{\widehat{x_+}} \frac{d x^2}{dx_+} - \frac{1}{\widehat{x_-}} \frac{d x^2}{dx_-}) = \frac{1}{2} (\widehat{x_+} 2x - \widehat{x_-} 2x) = 2 \vec x" /></a>

## The Double Cover of Space

We double-cover space with the functions

<a href="https://www.codecogs.com/eqnedit.php?latex=\vec&space;x&space;=&space;\vec&space;x_&plus;&space;&plus;&space;\vec&space;x_-" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\vec&space;x&space;=&space;\vec&space;x_&plus;&space;&plus;&space;\vec&space;x_-" title="\vec x = \vec x_+ + \vec x_-" /></a>

## Left and Right Differentials

The left differential of a function f is defined as <a href="https://www.codecogs.com/eqnedit.php?latex=d_-&space;f&space;=&space;\frac{df}{dx}_-&space;dx_-&space;=&space;\frac{df}{dx}_-&space;\frac{\widehat{x_-}}{\widehat{x_-}}&space;dx_-&space;=&space;\frac{df}{d&space;\vec{x}_-}&space;d&space;\vec{x}_-" target="_blank"><img src="https://latex.codecogs.com/gif.latex?d_-&space;f&space;=&space;\frac{df}{dx}_-&space;dx_-&space;=&space;\frac{df}{dx}_-&space;\frac{\widehat{x_-}}{\widehat{x_-}}&space;dx_-&space;=&space;\frac{df}{d&space;\vec{x}_-}&space;d&space;\vec{x}_-" title="d_- f = \frac{df}{dx}_- dx_- = \frac{df}{dx}_- \frac{\widehat{x_-}}{\widehat{x_-}} dx_- = \frac{df}{d \vec{x}_-} d \vec{x}_-" /></a>

The right differential of a function f is defined as <a href="https://www.codecogs.com/eqnedit.php?latex=d_&plus;&space;f&space;=&space;\frac{df}{dx}_&plus;&space;dx_&plus;&space;=&space;\frac{df}{dx}_&plus;&space;\frac{\widehat{x_&plus;}}{\widehat{x_&plus;}}&space;dx_&plus;&space;=&space;\frac{df}{d&space;\vec{x}_&plus;}&space;d&space;\vec{x}_&plus;" target="_blank"><img src="https://latex.codecogs.com/gif.latex?d_&plus;&space;f&space;=&space;\frac{df}{dx}_&plus;&space;dx_&plus;&space;=&space;\frac{df}{dx}_&plus;&space;\frac{\widehat{x_&plus;}}{\widehat{x_&plus;}}&space;dx_&plus;&space;=&space;\frac{df}{d&space;\vec{x}_&plus;}&space;d&space;\vec{x}_&plus;" title="d_+ f = \frac{df}{dx}_+ dx_+ = \frac{df}{dx}_+ \frac{\widehat{x_+}}{\widehat{x_+}} dx_+ = \frac{df}{d \vec{x}_+} d \vec{x}_+" /></a>

## The Jagged Differential

The jagged differential is defined as the sum of the right and left differentials

<a href="https://www.codecogs.com/eqnedit.php?latex=d&space;=&space;d_&plus;&space;&plus;&space;d_-" target="_blank"><img src="https://latex.codecogs.com/gif.latex?d&space;=&space;d_&plus;&space;&plus;&space;d_-" title="d = d_+ + d_-" /></a>

### Examples




## Indefinite Integrals

Since we have our double cover of space, we can perform indefinite integrals directly as functions of the double-cover.  Sometimes, the resulting functions will also be functions of the single-cover.

### Examples


