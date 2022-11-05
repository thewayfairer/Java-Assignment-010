# Java-Assignment-010 - Classes and Objects

## Part 1 - Analyze
* Add Comments to the Code below and label the following:
  1. Class name
  1. All **instance variables/fields** and their data-types
  1. The **Constructor** and the **Constructor Parameters**
  1. Where a **Student** object gets created.
  1. Where the **instance variables** value gets set and what its values are.
  1. All the instance methods for the class **Student**

```java
class Student{
    private String name; //field or data member or instance variable
    private int rollNo;//field or data member or instance variable
   
    Student(String s, int r) // this is a constructor
    {
   	    name = s;
   	    rollNo = r;
    }
   
     void methodforDisplay()
     {
         System.out.println(name+"'s Roll No: "+rollNo);
     }
   
    public static void main(String args[]){
        Student obj1=new Student("Ramboo",21);
        obj1.methodforDisplay();
    }
}
```

## Part 2 - Public VS Static
* Read the W3Schools page on class methods: [W3Schools Java Class Methods](https://www.w3schools.com/java/java_class_methods.asp)
* In your own words, write a few sentences below explaining the difference between static and public methods in relation to a class.

## Part 3 - Dogs
* View the image below, and from the image, construct a Java file **Dog** that mirrors the diagrammed class and the 3 dog objects.
![Dog Class](images/ClassVSObject.png)
* Your class should be named **Dog**
* You should have **private** instance variables/fields for all the data members.
* You should have a **constructor** that sets the initial state of the data members via passed parameters.
    * Think about what data-types the fields and parameters will need!!!
* You should have 4 instance methods for eat, run, sleep, and name
* You should have a **main** method that creates the 3 Dog objects in the diagram.
* Make at least 2 of your methods functional (i.e. perform some action)!!!
    * For Example: method eat might take a class parameter named **Food** (i.e. another class) that has an field **weight**, and your eat method might reduce the weight in **Food**.

## Part 4 - Turn-In
* Commit your code and push it back to your account.
* Create a Pull request as you have been doing for all assignments.
* Paste the Pull request URL back into the Canvass assignment page for credit.