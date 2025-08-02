# Design a Car class with make, model, and year as instance variables. Create an object of Car, set its attributes, and print them. [Low]

```java
// Car.java
class Car {
    String make;
    String model;
    int year;

    public static void main(String[] args) {
        Car myCar = new Car();

        myCar.make = "BWM";
        myCar.model = "XYZ";
        myCar.year = 2005;

        System.out.println("Car Make: " + myCar.make);
        System.out.println("Car Model: " + myCar.model);
        System.out.println("Car Year: " + myCar.year);
    }
}
```

### Output:
```java
Car Make: BMW
Car Model: XYZ
Car Year: 2005
```
