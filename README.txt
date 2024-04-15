1) I used HTML to create the structure of the webpage and CSS to make 
sure that it it looks similar to the main page and fits in to the theme.
2) Each item on the menu has an input field that will only accept values from 
0-5. If any other number is chosen the user will get an alert telling them 
the specific item and error. To do this I used JS after I had created divisions
for each item, to check the value that was entered I assigned quantity with the integer of
the user entered value once they have clicked off of the input field. Then I checked
if the enteger is less than 0 or greater than 5. If the user did enter a value
out of range than the user will get an alert stating that the item's quantity is out
of range and to enter a positive number from 0-5. This was done for every item on the menu. 
3) If the user chooses at least 1 of an item on the menu where topping and ingredients can be
personally chosen for example the Loaded Nachos, Pizza, and Stir-fry then checkboxes will 
appear to personalize the order to their liking. To do this I first created 
each item using HTML divisions, then I made another for toppings that are linked to the
specific item. Then using JavaScript if the user chooses a number between the accepted range but still 
not 0 then it will be displayed, else: nothing will be displayed. I did this using if else 
statements. I also used JavaScript to make clear which input was in focus by 
insuring that the input field color changed to yellow, then when it is out of focus
or blured the input field goes back to white. 
