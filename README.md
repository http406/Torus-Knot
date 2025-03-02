# Torus-Knot

### **What is a Torus Knot?**  
A **Torus Knot** is a type of mathematical knot that lies on the surface of a torus (a donut-shaped surface). Unlike a simple circle around a torus, a torus knot winds around the torus multiple times in a complex yet symmetrical pattern. These knots are widely studied in **mathematics, physics, and computer graphics** due to their unique properties.

Torus knots are classified by two integers, \( p \) and \( q \), which define how many times the knot wraps around the torus in two perpendicular directions:
- \( p \) = Number of times it winds around the central axis of the torus.
- \( q \) = Number of times it winds around the hole of the torus.

---

### **Equation Used in the Code**  
The equation used to generate the Torus Knot in your code is:

![Image](https://github.com/user-attachments/assets/050f3405-ea39-423f-8dd2-389f6016060f)

#### **Breaking Down Each Term:**
- \( R1 \) and \( R2 \) define the major and minor radii of the torus.
- \( r \) defines the thickness of the knot.
- \( p \) and \( q \) control the number of twists in different directions.
- \( u \) and \( v \) are angular parameters that define the shape of the knot.

In this code:
- \( R1 = 3 \) (Main torus radius)
- \( R2 = 3 \) (Secondary torus radius)
- \( r = 0.35 \) (Tube thickness)
- \( p = 5.8 \) (Twists around one direction)
- \( q = -3.6 \) (Twists around the other direction)
- \( u \) and \( v \) are angles that control the shape.

Since this equation involves **trigonometric functions (sine & cosine)**, the knot is smoothly curved and loops around itself while maintaining symmetry.
