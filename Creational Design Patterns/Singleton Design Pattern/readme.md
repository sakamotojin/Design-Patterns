<b>Singleton</b> is a creational design pattern that lets you ensure that a class has only one instance, <br>while providing a global access point to this instance.


<br>All implementations of the Singleton have these two steps in common:

<br>Make the default constructor private, to prevent other objects from using the new operator with the <br>Singleton class.
<br>Create a static creation method that acts as a constructor. Under the hood, this method calls the private <br>constructor to create an object and saves it in a static field. All following calls to this method return <br>the cached object.

<br>
<br> Use the Singleton pattern when a class in your program should have just a single instance available to <br>all clients; for example, a single database object shared by different parts of the program.