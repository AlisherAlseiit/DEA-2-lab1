
this is a web application that accepts user requests for alcoholic beverages and responds with a list of available brands
I used intellij idea, and created the project through the maven and selected the webapp archype

HTML page, the first page that users will see when they visit. This page will ask the user to select the type of alcohol and confirm the choice. After clicking the submit button, the application will send a POST request. the enum class is used to store the liquor types of our application. We also have a service class for storing the business logic of the application. It is a simple java class that defines the required methods. There is a SelectLiquorSevlet.java class that handles a custom request from an HTML page. Finally, we need to create a ZhJSP to display the result
