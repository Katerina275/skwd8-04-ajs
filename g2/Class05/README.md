# Let's build StarWarsArchives 🛸
## Phases of building an app 🏗
Applications are not built only by coding and drinking coffee. Applications are also built by thinking, researching, planning and testing. All these things are called a development cycle of an application.  Today we are going to build an application. These are the phases that we are going to pass:
* Analyzing and researching
* Planning and discussion
* Coding the planned features
* Testing the code that we have written

### Analyzing and research phase 🔹
We need to make a single page application. This application will have one view with two tables:
* People Info - A table that shows info about people from Star Wars universe
	* Name
  * Height ( cm )
  * Mass ( kg )
  * Gender
  * Birth Year
  * Appearances ( Count of movies they appeared in )
* Ships Info - A table that shows info about ships from Star Wars universe
	* Name
  * Model
  * Manufacturer
  * Cost ( credits )
  * People Capacity ( crew + passengers )
  * Class
#### About the API 🛰
We will be using the [swapi](https://swapi.co/) API. This API is free. You can try some links out on the API page it self. Here are some useful links:
* **API:** https://swapi.co/api/

* **People Link:** https://swapi.co/api/people/?page=1 ( page=1 is the first page )

* **Ships Link:** https://swapi.co/api/starships/?page=1 ( page=1 is the first page )

* **Limit:** 10,000 requests per day

### Planning phase 🔹
In this step we already analysed the stuff that we need and the requirements for the application. Now we have to plan it. Planning is one of the most important part of the development process. We take the whole problem of building the app and create smaller chunks or tasks that we can complete. 
1.  Create HTML page and connect a script, css document and libraries
2. Create the intro page with the link images to the tables
3. Connect the images with the script
4. Create a function for making an API request
5. Connect the function with the images so that when any of the images is clicked, the corresponding request is made
6. Create a function for printing a table of 10 people
7. Create buttons for next and previous
8. Create functions for next and previous
9. Create a logic so that next/previous buttons make a call to the next page as request

### Coding phase 🔹
In this phase we start coding all the tasks that we have planned and written in the planning phase. So we are building and creating the application here. We can always go back and add a task in the planning list if we encounter some feature that we missed in the planning. 

### Testing phase 🔹
This is a phase where we spend time testing our code and checking if the built product correlates with the requirements. When we encounter a problem, missing requirement or something out of place we go back to the coding phase to fix the problems and then go back to testing. This cycle is done when we are satisfied with the complete product. 
