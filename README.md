# singleton design pattern

•Singleton is a design pattern which ensures that only one object of its kind exists and provides a single point of access to it for any other code
•It can be achieved by making constructor of the class private which prevents it to be instantiated anywhere else
•This is useful when exactly one object is needed to coordinate actions across the system
•This one object will be instantiated in the class and access will be given to it with a static get method
•It is very commonly used with driver instance for Selenium scripts