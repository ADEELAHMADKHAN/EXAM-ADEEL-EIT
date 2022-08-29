# EXAM-ADEEL-EIT

# Exam Week 2

## Section 1

What is Swift and how is it unique?

Ans:  Swift is programming language used by IOS developers for software development for differen IOS devices.
      Swift is unique because of its certain features which includes include its value type "Struct" instead of reference type "CLASS". It makes this language more secure.
      Syntax is pretty easy as compared to some other languages. Presence of OPTIONAL is also a great feature which makes the swift programming language unique.

What is an optional?

Ans: Optionaal is a type of constant which can eitther hold a value or no value at all means nil. There are methods of unwrapping the optional by force aand safely.
     It is denoted by appending a "?" after the declaration.

What are the different ways we can unwrap an optional and explain each?

Ans: Following are some of the methods for unwrapping the optional:

1. By using an if-else block. Check the optional variable by putting not equal to nil and else print it 
Has no value.

2. Unwrap an optional type with forced unwrapping. This method is usually used when we are sure that an 
Optional has a value. We do this by us adding ! Sign with optional variable.

3. Unwrap an optional type with the nil coalescing operator. This method is similar to if else block with 
Just a single operator I.e. ??

4. Optional Binding unwrapping method. Check the optional variable by putting not equal to nil, if it has some value,
It can be stored to some temporary variable.

Methods 1,3,4 are safe to use.

What is optional chaining?

Ans: Optional chaining is a process of calling methods, properties and subscripts on an optional. It depends
     if the optional is returning value or returning nil but it will always return a type of optional value.


What is MVC? Go into detail and give some of the pros and cons.

Ans: MVC or model view controller is a widely used design pattern for architecting software applications.
     Model is the layer where your actual data resides like model obects and code.
     View is the layer which can be called face of your app. For example UILabel is a view that presents the text on the screen.
     Conrtoller is the medium between the view and the model via the delegation pattern. Example can be of UITableView comminicates with UITableViewDataSource protocol.
     Pros: Development becomes so fast due to easy process of working on multiple levels. Easier to debug.
     Cons: Hard to understand and some strict rules on methods. 

Explain the Viewcontroller Lifecycle.

Ans: This is the lifecycle in which different sets of functions are called for coordinating with model obects. ViewController funcions are called by itself when we load the app.
     func viewDidLoad() {}  is called when the content view gets created in memory. It is called once when we load unlike viewWillAppear which loads everyime when we move in between the tabs.
     func viewWillAppear() {} is called just before the content view is added to apps view hierarchy.
     func viewDidAppear() {} is called after the conten view is added to app's view hierarchy.
     func viewWillDisAppear() {} is called before the conent view is removed from the app's view hierarchy.
     func viewDidDisappear() {} is called when the content view is removed from the app's view hierarchy. 
     func viewWillLayoutSubviews() {} called when the content views bounds change but before it lays out its subviews.
     func viewDidLayoutSubviews() {}  called when the content views bounds are chaged.

In the Application LifeCycle, what does it mean when the application is Inactive?

Ans: It means that application is transitioning between the two state. It happens when there is call or message and app holds for limited time or when the phone is locked.

What is a closure? What is the difference between an escaping and non-escaping closure?

Ans: A closure is a special type of function that has no name, we may call a function without name.
     Syntax: { (parameters) -> returnType in
     // statements}
     An escaping closure is a type in which it is called after the function it was passed to returns the call whereas non-escaping closure is a type in which it is called before the function it was passed to returns the call.
     
          

What is the difference between reference types and value types?

Ans: Reference types are in which they are pointed to the memory by reference but in value type the actual memory location is created and copied. So if a reference type is changed it changes 
     the original memory location data as well but it doesnot happen in value type. 

In Swift, how do we pass a value by reference? 

Ans: In swift value is passed by reference through class. Make a class and object. Then pass a value through object of the class by making a function.



What are some higher order functions used in swift and what do they do? (Give 2)

Ans: Higher order functions are funcions that takes functions or Closure as Argumens and then return a function.

     "map" funciton works by performingg an operaiton on all the elements and returning a new collecttion with the rersults of that operation.
     ‘flatMap’ function works by taking different sets of arraay and transforming them into a set containg all the elements of those arrays.

What is Autolayout?

Ans: AutoLayout defines user interface using series of consrtaints. This method allows us to create views that dynamically adjusts to different size and classes.



## Section 2 Coding

### Find the second-largest value of an array, in linear time.
For this case, we'll consider unique values.

input: [1, 2, 3, 4, 5, 5]
output: 4
Also factor in empty or single-element arrays.

input: [1]
output: nil

