# Where to Eat?

We designed and developed an interactive webpage to facilitate rapid and reliable decision-making for restaurant selections.

This visualization tool showed the entire dataset on one display by using a multi-form interface which consists of: a scatter-plot on the Google map, range sliders for both distance and star rating, and bubble charts for reviews.

One of the highlights was that we filtered the review data based on the degree of the user's experience in the visualized restaurants, rather than sorted them by rating or date.

## Features

If the users put their mouse cursor on each state of the U.S. map, the name of state and the university in the state show up. The users can zoom in and out and panning using a mouse left button and a wheel. 

![The start page for proper selection of the restaurants using Yelp data](/Screenshots/1.jpg)

Once the users select the state and the university in the start page, they can see all the local restaurants on the Google map, and a set of sliders for distance and star rating filtering, and bubble charts presenting the "local foodies". Based on the selected star rating and distance the user preferred, the bubble charts will be automatically updated. 

![Multi-form interface which consists of a scatter-plot on the Google map, range sliders, and bubble charts](/Screenshots/2.jpg)

The users can freely select their location by dragging the flag sign. They can also zoom in and out the viewpoint by mouse-wheeling or pressing ‘+’ or ‘-’ button in the Google map GUI. 

When clicking the restaurants on the Google map, the description including the image, the average star rating, the number of reviews, and the link to the Yelp show up using a box. Our visualization tool supports the selection of multi-restaurants in the Google map, so the user can select many restaurants at a time. 

![The text and visual descriptions about the restaurants](/Screenshots/3.jpg)

Because there are large amounts of review information of each restaurant in Yelp datasets, it is difficult for the user to find the reliable reviews for specific restaurants among them. To overcome this, we filter the review data based on the degree of the user’s experience in the visualized restaurants. More specifically, we assumed that the reviews from the more experienced reviewers (i.e. local foodies!) are more reliable than the reviews from the less experienced reviewers. 

We leveraged bubble charts to show all reviewers’ names. If the user put the mouse cursor on each bubble, the user can see the details on the user’s experiences based on the number of visiting. Also, if the user clicks the bubble, the reviewer’s webpage in the Yelp site is opened to see their reviews.

![Bubble charts based on the review’s experiences](/Screenshots/4.jpg)

## Acknowledge

Thanks to Youngjib Ham for working with me in "CS 5764 Information Visualization" @ Virginia Tech 2012 Fall.
