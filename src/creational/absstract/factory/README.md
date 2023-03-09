### Step 01
Create an interface(Shape) for Shapes.

### Step 02
reate concrete classes(Rectangle, Square, RoundedRectangle, RoundedSquare) implementing the same interface.

### Step 03
Create an Abstract class(AbstractFactory) to get factories for Normal and Rounded Shape Objects.

### Step 04
Create Factory classes(ShapeFactory, RoundedShapeFactory) extending AbstractFactory to generate object of concrete class based on given information.

### Step 05
Create a Factory generator/producer class(FactoryProducer) to get factories by passing an information such as Shape

### Step 06
Use the FactoryProducer to get AbstractFactory in order to get factories of concrete classes by passing an information such as type to demo class(AbstractFactoryPatternDemo).

### Step 07
Verify the output.
``` 
Inside Rectangle::draw() method.
Inside Square::draw() method.
Inside RoundedRectangle::draw() method.
Inside RoundedSquare::draw() method.
```