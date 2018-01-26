# Concentration

For magic afternoon, we're going to create a basic concentration game with images from an API. Hitting our api will give you back an image. Our application should save the number of that image and then let a user guess where the matching image exists.

The endpoint to grab images is 
```
https://hook.io/outsourcedguru/magic-afternoon-01
```
It supports a 4x4 grid of 400x400 pixel images, numbered from 1 through 16 with eight unique images.

For example (the param ID goes in and should be from 1 through 16):

```
https://hook.io/outsourcedguru/magic-afternoon-01/1
```

![1](https://user-images.githubusercontent.com/15971213/35172811-032b6792-fd1e-11e7-950a-4d0f8dace31b.jpg)


The microservice will return, for example: 
```
"https://user-images.githubusercontent.com/15971213/35172811-032b6792-fd1e-11e7-950a-4d0f8dace31b.jpg"
```


Resource:
 - [About Concentration](https://en.wikipedia.org/wiki/Concentration_(game))

___

### Level 1
The first level should consist of an initial scaffolding of the web application. At this point, the application should be able to retrieve data from the URL

### Level 2:
The second level consists of the main logic and mechanics of the user's side of the interface. At this point, you should be able to hit the endpoint, get the image, and display it on the user's side

### Level 3:
At level 3, you will add three states to each card:
  - Hidden: When the card is face down
  - Shown: When the image is shown
  - Solved: When the image has been paired with another image

### Level 4:
Add a page that shows when a user has completed the game.

### Level 5:
Add additional functionality like animations and upload the project to Github

## Conclusion
The specification is otherwise open-ended to the implementation of the page set-up.

* You may choose the form of user interface (e.g. React, Vanilla JS, Vanilla HTML/CSS).
* There are two base templates to help get you started. The standard one consists of main index/css/js files. The React one is a custom create-react-app template.
