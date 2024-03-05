1. Class - Engine
The Engine class has attributes like fuel type(should be an Enum), 
horsepower, and efficiency.
The constructor initializes these attributes when creating an Engine 
object.
Methods like start, stop, and displayDetails are included to perform 
actions related to the engine.
In the main function, create the engine object and execute start, stop 
and display details methods

2. Class - Car Engine
Class CarEngine should be derived from Engine class.
Should have attributes of Engine Class and additional attribute 
‘cylinders’ and ‘cc’ and ‘model’’
Override the display details to include cylinder details 
In the main function create the carEngine object and execute start, stop 
and display details.
Display details should print `Model - Car Engine` followed by the other 
details.
Create Factory methods for creating xuv300, xuv500, xuv700 with prefilled 
data for horsePower, efficiency, cylinders, cc and model(to be set to the 
variant xuv300, xuv500 and xuv700 respectively) and required params for 
fuel type.
Create objects for xuv300Petrol, xuv500Petrol and xuv700Petrol and 
similarly for diesel variants.

3. Convert Engine to an Abstract class.
Override  start, stop, and displayDetails in CarEngine

4. Interface - Service
Create an interface Service 
Define a checkEngineCondition method
Engine class should implement Service Interface
Car Engine class should override checkEngineCondition and print Good for 
all petrol vehicles and Bad Diesel vehicles 

5. Class - Truck Engine
Create a TruckEngine class and should be derived from Engine class
Should have attributes of Engine Class and additional attribute ‘Cargo’ 
capacity
Override the display details to include cargo capacity details. Display 
details should print `Truck Engine` followed by the other details.
In the main function create the carEngine object and execute start, stop 
and display details.


6. Class - SuperCar Engine 
Class SuperCar Engine should be derived from the CarEngine class.
Should have attributes of CarEngine and additional attributes 
‘hasTurbo(bool)’, specialFeatures(list), topSpeed
Display details should print `Model - SuperCar Engine` followed by the 
other details.

7. Extension - CarExtension
Create an Extension on Car class with method convertToSuperCar()
convertToSuperCar extension should convert the Car obj to a Super Car 
object.
Create a xuv500 object using the factory method 
Car.xuv500(FuelType.petrol) 
Execute xuv500.display details(). 
Expected output is - xuv500 - Car Engine followed by other details
Assign xuv500 = xuv500.convertToSuperCar()
Execute xuv500.displayDetails()
Expected output is - xuv500 - SuperCar Engine followed by other details



# 
FlutterAssignment2
