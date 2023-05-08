Download Link: https://assignmentchef.com/product/solved-practice-car
<br>
<ol>

 <li>Create a Java project in eclipse, called “PracticeCar”</li>

 <li>Create a class called “Simulator”, with a main() method.</li>

 <li>Create a “Car” class, with a run() method. The main() method of Simulator will create an instance of a car object, and call that object’s run() method.</li>

</ol>

Now, you will create additional classes that represent the different components of a car – the engine, the fuel tank, the wheels, etc. These classes should have methods related to their behaviors, and properties representing their various states (an engine is running or not, tires have levels of wear, etc).

<ol>

 <li>Every class representing a car part should inherit from a superclass called “CarPart.” The CarPart class will have all of the states and behaviors that are shared by all types of car parts (like condition and the ability to print a diagnostic report).</li>

 <li>Make sure that your Car class creates an instance of each CarPart subclass, as part of its constructor. Parts that a car has multiples of (like wheels) should be stored in a collection.</li>

 <li>Make sure that the run() method of the Car class does something with each instance of a CarPart subclass.</li>

</ol>