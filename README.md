package Pack1; 

// A class to demonstrate the usage of Shape subclasses like Rectangle and Circle
public class Shapedemo {

    // The main method where the execution begins
    public static void main(String[] args) {
        // Create a Rectangle instance with length 5 and width 4
        Rectangle rect = new Rectangle(5, 4);
        
        // Create a Circle instance with radius 10
        Circle c = new Circle(10);
        
        // Output the area and perimeter for the Rectangle instance
        System.out.println("Rectangle: ");  
        System.out.println("Area of rectangle is: " + rect.getArea());  
        System.out.println("Perimeter of rectangle is: " + rect.getPerimeter());  
        
        // Output the area and perimeter for the Circle instance
        System.out.println("\nCircle: ");  
        System.out.println("Area of circle is: " + c.getArea());  
        System.out.println("Perimeter of circle is: " + c.getPerimeter());  
    }
}
