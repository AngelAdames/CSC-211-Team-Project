# Fall 2022 CSC 211 with Prof. Aydin Team Project 

## The Theme

  The purpose of our project will be to create a site that showcases the invetory of the assorted cars that we supply, and the quantity of each specific car, including a feature of a hyperlink and a scroll function for the simplicity of the user.

## Feature List

  There is going to be a button when the application is first launched.  From there, you are able to click the button to show the current list of cars and how many of them are currently in stock.  


### UML Diagram Link:
The Link to the UML: *https://tinyurl.com/yckuf8ct*

### 

### Issues and future work

  A few obvious issues could be seen in the program.  First, the scroll bar doesnt work with the inventory as intended.  You are supposed to be able to scroll up and down through the inventory.  Second, the hyperlink is supposed to bring you to a picture of the best selling car (Audi R8 2023).   It is probably not working because there is no established relationship between the two.  As for the hyperlink, the link was probably not entered into the right field.  Lastly, we were not able to push the project to Github.  When we got to the final part, it kept saying access denied even though we used the access token and everything.  In the future, we would like to add a variety of features and more types of vehicles after getting the scroll bar and hyperlink to work correctly.  As well as figuring out how to push it properly.

#### Self-Assessment of  Satisfying the Project Requirements:
a) Our project did contain the requirements we needed for the class hierarchy. Within the classes, we had 3 classes. One being Vehicle, another Car, and lastly SteeringWheel. Each class had a default constructor, at least one with parameters, all the required methods that would help the project function as intended, and a toString() method to be able to display it to the user. The @Override was neccesary so the child class' method would work over the parent.

b) Thankfully, there is a HAS-A relationship, in these classes, the Car class is the parent of the SteeringWheel class, thus, a Car has a steering wheel, fulfilling these requirements

c) There is a IS-A relationship, for the classes, the Car is the child of the Vehicle parent class, thus, making the IS-A relationship work. A Car is a kind of vehicle, making this inheritance logical and functional.

d) For the abstract class, the parent class seemed the most fitting, since it would be convinient to do so. Since nothing creates the parent class, it doesnt interfere with the inheritance at least in this project.

e) Unfortunately, we do not impliment a polymorphic call in this project, this is yet another thing that we can improve on for next time, and that we would add a polymorphic call for future projects.

f)  There is no Java array in our code.  Although, we definitely could have used an arraylist for listing the vehicles in the inventory.

g)  JavaFX FXML GUI

  i) Only an anchor pane was used unfortunately.  
  
  ii) We used a button, an attempted hyperlink, and an attempted scroll bar.  
