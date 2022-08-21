# cs465-fullstack
CS-465 Full Stack Development with MEAN

Architecture 
The Angular project structure is used to create the administrator single-page application for the travel booking web application this allows Travlr Getaways to add and edit packages once login to their accounts. The administrator single-page application shows the travel package name, length, start date, resort, per person, image, and description for each package. The Express project structure is graphical interface compared to the Angular project structure. To see all the travel packages the user has to scroll down. Express has the packages information to the left of the image while Angular has the information up and down with the image right under the name of the package and the information below it. To test the Angular project structure the add button is pressed to show the add screen where the user fills out the information for the new page once done the save button is pressed to save the package. Once the new package is saved it will go back to the home page showing the new package added. Every package has an edit button to allow the user to make changes to the package when clicked the edit page will show with the information in each text box. The user can make changes to the text box and then click the save button. Once the save button is clicked the home page will show the edited information along with all the travel packages. JavaScript is the language used to create both the SPA and client side of the program allowing the user to click a tab on the client side and be redirected to another page or on the SPA side click the add button and be taken to the add page. 
The backend of the program used NoSQL MongoDB database to handle the travel packages along with packages added later to the web application. For the program to be a MEAN full stack it has to use what MEAN stands for and the first part is MongoDB there for the database was created using MongoDB. 

Functionality

The different between JavaScript Object Notation (JSON) and JavaScript are what language they work with, how the data is shown, and how they are presented. JavaScript will not work with any other programing language while JSON works with many other programing languages including JavaScript (Gamez, 2022). For example, JavaScript cannot work with Python, but JSON works with Python. “JSON cannot have comments or other lines of code while JavaScript can have function and methods” (Gamez, 2022). This means if any information needs to be processed it must be done in a program language not in JSON. “JSON is a presented in a string whine JavaScript is presented in objects containing strings” (Gamez, 2022). For example, for JavaScript to be used an object must be created and stings of JavaScript inside the object are created but JSON does not need to be created this way.       
During the full stack process the code had to be refactored to improve the web application. One instance was using MVC Routing. “MVC routing is a pattern matching system that is responsible for mapping incoming browser requests to specified MVC controller actions” (Shekhawat, 2020). This improved the routing for the web application allowing the program to move from the home page to the other pages and giving the web application a location off the information. Another change to the code was moving from static HTML to templates with JSON. This allowed for change to be made from the single-page application such as adding more trips and changing prices of packages without taking down the whole page.

Testing

Methods to request and retrieval necessitate various types of API testing of endpoints are using Mongoose and another way using Angular. One method is using Mongoose to gather all information or pieces. For example, in the project Mongoose was used to gather both the list of trip packages and a single trip package. To show the list of trip packages in the browser localhost:3000/api/trips but when the user wanted to see only one of the trips the user would go to localhost:3000/api/trips/”trip code” entering the trip code they want to see in where trip code is written. Another method is using Angular to show the list of trip packages and allow the user to add and edit those packages in the system. Both of these methods also send a code when working properly to the command prompt in the Travlr Getaways because it shows the code 401 and if it fails it show the code 401. Methods are very helpful to programing by breaking the program into methods rather then having it in the same class the program is easier to understand, and errors can be found faster. Endpoints allow web application to not just see then information being enter but also give the user an easier way to change data from the administrative side of the web application. Security in full stack applications keep the program from being used by any user that does not have permission to access then account along with helping to protect the company from losing data and putting client in harms way.   
 
Reflection

This course has helped me in many different was from professional goals, concerns, and skills. First this course has helped me to learn how to create a web application using the MEAN full stack development. Which I have never used before this class. This course has also helped me with concerns I had before this class. For one thing I have been concerned that when I finish my degree, I will not be able to create a web application. Which is something I have been wanting to learn to help with my goal of being a computer scientist. The skills I have gained from this course are learning how to create a web application using the MEAN full stack development technique, how to create a database for web applications, different frameworks like Angular and Express and what they can do, and how to create both sides of a web application administrative and client side. I will not say I have master web application development, but I have gained experience in developing web applications and plan to further study on these techniques and creating my own to help further my goals.    








				References

Gamez, J. (2022, January 31). JSON Vs. JavaScript: What is the Difference? Koombea. 
	https://www.koombea.com/blog/json-vs-javascript/

Shekhawat, S. (2020, September 24). Routing in MVC. C# Corner. 
	https://www.c-sharpcorner.com/UploadFile/3d39b4/routing-in-mvc/
