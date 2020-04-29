# Game
Web application game

This is a web application game that there are some objects in the playground that are moving around by random, but they have to keep the distance among each other and also from the cursor of the mouse. The application is written with Typescript.

To run the game, simply download the repository to your machine and open the index.html file using a web browser (Google Chrome, Mozilla Firefox, Microsoft Edge are tested).


# Game settings:

"Number of objects": The number of objects can be entered here. It is 10 by default.
"Field width", "Field height": The width and height of the playground can be set using these inputs. Default values are Field width: 2000, and Field height: 800. 

After setting the "Number of objects", "Field width" and "Field height", click the start button to start the game.
NB: In case of changing these settings during the game, the start button should be clicked to apply the new settings. However, the changes in other settings will be applied during the game. 

"Pause / Resume" button is to pause the object movements and resume them.

Speed: The movement speed of the objects can be choosed using speed dropdown.

Object distance: It is the distance that the objects should keep it from other objects.

Cursor distance: It is the distance that the objects should keep it from cursor of the mouse.

Avoid rate: It is the rate of keeping the distance. The range of the rate is from 1 to 5. If rate is 1, it means that the object will try to keep the distance, but not strictly at all. And the can get closer to each other sometimes. If rate is 5, it means that the object will keep the distance very strictly.

Same speed: This is an option to make the speed of the objects equal and constant. If yes is selected, all objects will move with same and constant speed. Otherwise, their speeds can vary from each other.

Object size: The size of the objects can be selected using this option. The values are the radius of the objects. Also it can be choosed to generate the random objet sizes.


In addition to the abowmentioned rules, you can add some fixed points in the playgroud that can be set to absorb the other objects or repel them. To do so, please click on the playground. This will add a point to playground. By adding a point, some other settings will be appeared.

To select a previously added point, simply click on the point. Then the settings of the selected point will be displayed in the control pannel.

point settings:
Point size: The size of the point can be choosed using this option.

Type: The type of the point can be selected here. It can be rather "absorbing point" or "repelling point".
Absorbing point will absorb the other objects that are in its range, 

