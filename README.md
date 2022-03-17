# Project REST-Rant

REST-Rant is an app where users can review restaurants.

|Method|Path|Purpose|
| --- | --- | --- | 
|GET|/|Home Page|
|GET|/places|Places index page|
|POST|/places|Create new place|
|GET|/places/new|Formpage for creating a new place|
|GET|/places/:id|Details about a particular place|
|PUT|/places/:id|Update a particular place|
|GET|/places/:id/edit|Form page for editing an existing place|
|DELETE|/places/:id|Delete a particular place|
|POST|/places/:id/rant|Create a rant(comment) about a particular place|
|DELETE|/places/:id/rant/:rantId|Delete a rant(comment)about a particular place|
|GET|*|404 Page( matches any route not defined above)|

![International food](https://github.com/BGZhao/RestRantTen/blob/main/public/images/matthew-scott-illustration-childrens-cook-food-travel-around-the-world-dishes.jpeg);

## Wireframe
### **Map of the application**

![Structure](https://github.com/BGZhao/project-REST-rant/blob/main/Wireframe.jpeg?raw=true)

## What you should see!
I change the original CSS Style from Blue, White colors, to warmer colors like yellow, orange, and red. Since is proven that those colors make people hungry.
### Home Page
Starting page
![Home page](public/images/Home Page.jpeg)

### Places Page
Restaurants added 
![Places Page] (public/images/Places Page.jpeg)

### Edit Page
Add or removed Places
![Edit Page] (public/images/Edit Page.jpeg)    

### Comments Page
Add or removed reviews of the restaurants
![comments Page] (public/images/Comments.jpeg)
