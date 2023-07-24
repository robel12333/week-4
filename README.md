**Project Title: Simple Shape Hierarchy**

**Description:**
You are tasked with creating a Simple Shape Hierarchy to represent various geometric shapes. The project should demonstrate your understanding of inheritance, encapsulation, method overriding, and method overloading in Java.

**Classes:**
1. `Shape`: This is a base class representing a generic shape. It should have an attribute for color and a method to display the color of the shape.

2. `Circle`: This is a subclass of `Shape` representing a circle. It should have additional attributes for the radius and appropriate methods to calculate the area and perimeter of a circle. Override the specific display method to show the circle-specific color information along with the shape name "Circle".

3. `Rectangle`: This is a subclass of `Shape` representing a rectangle. It should have additional attributes for length and width, and appropriate methods to calculate the area and perimeter of a rectangle. Override the specific display method to show the rectangle-specific color information along with the shape name "Rectangle".

4. `Triangle`: This is a subclass of `Shape` representing a triangle. It should have additional attributes for the base and height, and appropriate methods to calculate the area and perimeter of a triangle. Override the specific display method to show the triangle-specific color information along with the shape name "Triangle".

**Requirements:**
1. Implement the `Shape` class with an attribute for color and a method to display the color of the shape.

2. Implement the `calculateArea()` and `calculatePerimeter()` methods in each subclass (`Circle`, `Rectangle`, `Triangle`) to provide specific implementations based on the shape's attributes.

3. Use encapsulation to protect the attributes of each class and provide public methods (getters and setters) to access and modify them.

4. Override the specific display method in each subclass to provide specific color information and include the name of the corresponding shape.

5. Create a main class to demonstrate the usage of the `Shape` hierarchy by creating instances of different shapes, setting their attributes (color, border thickness, etc.), calculating their areas and perimeters, displaying their specific color information along with the shape names, and showing the results.

**Additional Features (Optional):**
If you want to add a bit more complexity to the project, you can consider the following features:

1. Sorting Shapes: Implement a method to sort an array of shapes based on their areas or perimeters.

2. 3D Shapes: Extend the hierarchy to include 3D shapes and calculate their volumes and surface areas.
