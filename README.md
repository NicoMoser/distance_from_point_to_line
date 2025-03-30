# Computing the Distance from a Point to a Line

Suppose you have a line, $L$, defined via two distinct points, $A$ and $B$, and a point, $P$ and want to know how far from $L$ is $P$.

Let $Q$ be the point on $L$ nearest to $P$. There is some real value, $t$, such that $Q = t \left( A-B \right) + B$

The line through $P$ and $Q$ is perpendicular to $L$ which means that the dot or inner product of $A-B$ and $P-Q$ is $0$. Substituting for $Q$ we have

$$ 0 = \left( A-B \right) \cdot \left( P-Q \right) $$
$$ = \left( A-B \right) \cdot \left( P- \left( t \left(A-B \right) + B \right) \right) $$
$$ = \left( A-B \right) \cdot P - \left( A-B \right) \cdot (t(A-B) + B) $$
$$ = \left( A-B \right) \cdot P - \left( A-B \right) \cdot t \left( A-B \right) - \left( A-B \right) \cdot B $$
$$ = \left( A-B \right) \cdot \left( P - B \right) - t \left( A-B \right) \cdot \left( A-B \right) $$
$$ t \left( A-B \right) \cdot \left( A-B \right) = \left( A-B \right) \cdot \left( P - B \right) $$
$$ t  = \dfrac {\left( A-B \right) \cdot \left( P - B \right) } { \left( A-B \right) \cdot \left( A-B \right) } $$

Now that we have $t$ we can compute $Q$. The squared distance from $P$ to $L$ is the squared distance from $P$ to $Q$ which is $\left(  P-Q \right) \cdot \left(  P-Q \right)$
