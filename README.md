# EPAiV5-Session9
EPAiV5 assignment 

Name: Aravind D. Chakravarti

# Details of Regular Polygon

![alt text](image.png)

#### **Definition**

A **Regular Convex Polygon** is a special type of polygon that satisfies the following conditions:

1.  **Equal Side Lengths**: All sides of the polygon are of the same length. This means the distance between any two adjacent vertices (corners) of the polygon is identical.
    
2.  **Equal Angles**: All interior angles (the angles inside the polygon) are equal. This uniformity ensures the symmetry of the shape.
    
3.  **Convexity**: The polygon is convex, which means that all its interior angles are less than 180 degrees. In other words, no part of the polygon is "indented" or "caved in"; the line segment between any two points on the polygon's boundary always lies inside or on the polygon.
    

#### **Examples**

-   **Equilateral Triangle**: A triangle with three equal sides and three equal angles of 60 degrees each.
-   **Square**: A four-sided polygon with equal sides and four equal 90-degree angles.
-   **Regular Pentagon**: A five-sided polygon with equal sides and equal angles, each of 108 degrees.

#### **Properties of Regular Convex Polygons**

1.  **Number of Sides (n)**: The number of sides (or edges) of a regular polygon is denoted by $n$. This also equals the number of vertices.
    
2.  **Interior Angle**: The measure of each interior angle θ\thetaθ of a regular polygon is given by:
    $$
    \theta = \frac{(n - 2) \times 180^\circ}{n}
    $$
    This formula comes from dividing the total interior angle sum of a polygon (which is $(n-2) \times 180^\circ$ by the number of angles $n$.
    
3.  **Exterior Angle**: The exterior angle of a regular polygon (the angle between one side of the polygon and the extension of an adjacent side) is:
    $$
    {Exterior Angle} = \frac{360^\circ}{n}
    $$
    The exterior and interior angles of a regular polygon always add up to 180 degrees.
    
4.  **Circumradius**: The circumradius $R$ is the radius of the circle that passes through all the vertices of the polygon. For a regular polygon with side length $a$ and number of sides $n$, the circumradius is:
    $$
    R = \frac{a}{2 \times \sin\left(\frac{\pi}{n}\right)}
    $$
    Alternatively, if the circumradius is known, the side length can be computed as:
    $$
    a = 2R \times \sin\left(\frac{\pi}{n}\right)
    $$
5.  **Apothem**: The apothem is the distance from the center of the polygon to the midpoint of one of its sides. It is also the radius of the inscribed circle within the polygon. The apothem $r$ can be calculated using:
    $$
    r = R \times \cos\left(\frac{\pi}{n}\right)
    $$
6.  **Area**: The area $A$ of a regular convex polygon can be computed using :
    $$
    A = \frac{1}{2} \times n \times a \times r
    $$
   
7.  **Perimeter**: The perimeter $P$ of a regular polygon is simply the number of sides multiplied by the side length:
    $$
    P = n \times a
    $$
#### **Applications**

Regular convex polygons appear in various fields, including:

-   **Geometry**: Studying the properties and relationships between angles, sides, and other geometric elements.
-   **Architecture**: Designing buildings, tiling patterns, and structures with symmetrical shapes.
-   **Computer Graphics**: Rendering shapes with uniformity and symmetry in digital art and animation.
-   **Tessellations**: Filling a plane with no gaps using identical regular polygons.

#### **Common Regular Convex Polygons**

-   **Equilateral Triangle** (3 sides)
-   **Square** (4 sides)
-   **Regular Pentagon** (5 sides)
-   **Regular Hexagon** (6 sides)
-   **Regular Octagon** (8 sides)


