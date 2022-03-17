# Project REST-Rant

REST-Rant is an app where users can review restaurants.
![International food](IMAGES/matthew-scott-illustration-childrens-cook-food-travel-around-the-world-dishes.jpeg)

## Routes

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

## Places
|Data Element|Data Type|Purpose|
| --- | --- | --- | 
|_id|object ID|Primary key|
|name|string|name of the restaurant|
|city|string|city of the restaurant|
|state|string|state the city is in|
|cuisines|string|type of food(s) the restaurant serves|
|img|string|URL to an image for the restaurant|

## Rants

|Data Element|Data Type|Purpose|
| --- | --- | --- | 
|_id|object ID|Primary key|
|rant|boolean|flag to indicate the place was disliked|
|rating|numberr|rating of 1 to 5|
|comment|string|captures user comments|
|reviewer|string|captures the user's name submission|

 ## Rant Model

|Field|Type|Notes|
| --- | --- | --- | 
|author|string|	Name of comment's writer; defaults to Anonymous if missing.|
|rant|Boolean|Each comment is either a rant (negative) or a rave (positive).Defaults to false.|
|stars|number|1 to 5 star rating in increments of 0.5; required, no default|
|content|string|The written content of the comment;defaults to an empty string.|

## Wireframe
### **Map of the application**

![Structure](https://github.com/BGZhao/project-REST-rant/blob/main/Wireframe.jpeg?raw=true)

## NOTES
### What you should see!
I change the original CSS Style from Blue, White colors, to warmer colors like yellow, orange, and red. Since is proven that those colors make people hungry.
## Wireframe
### **Map of the application**

![Structure](https://github.com/BGZhao/project-REST-rant/blob/main/Wireframe.jpeg?raw=true)

##  **What you should see!**
I change the original CSS Style from Blue, White colors, to warmer colors like yellow, orange, and red. Since is proven that those colors make people hungry.
###  **Home Page**

![Home page](https://github.com/BGZhao/RestRantEleven/blob/main/public/images/Home%20Page.jpeg?raw=true)

#### Starting page


### **Places Page**

![Places Page](https://github.com/BGZhao/RestRantEleven/blob/main/public/images/Places%20Page.jpeg?raw=true)

#### Restaurants added 

### **Edit Page**

![Edit Page](https://github.com/BGZhao/RestRantEleven/blob/main/public/images/Edit%20Page.jpeg?raw=true)    

#### Add or removed places

### **Comments Page**

![comments Page](https://github.com/BGZhao/RestRantEleven/blob/main/public/images/Comments.jpeg?raw=true)

#### Add or removed reviews of the restaurants