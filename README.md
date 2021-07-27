## CS 498 - UIUC - Narrative Visualization Final Project

UIUC CS 498 Final Project Essay By Sunil Kulkarni

Messaging: Given the increasing effects of climate change, and the high volume of automobiles in the world, we must seek to better understand the mileages of various automobiles. There are many factors that can affect the mileage of your car (See: ​Link​) but in this interactive visualization, we will explore 2017 data about the the respective highway and city MPGs of automobiles, with respect to just a few of these factors, like engine cylinders, fuel type and the make of the vehicle.

Narrative Structure: The above visualization utilizes the slideshow narrative visualization technique, while incorporating hybrid elements of the drill-down technique. Each slide contains guidance on how to interact with the visualization.
Visual Structure: The structure of the slides guides users from one idea to the next, but there is still room for individual exploration at each stage. We accomplish visual consistency by maintaining uniform elements throughout, introducing a mixture of text, image and chart elements, and having meaningful colors.
Scenes: The scenes themselves are constructed via HTML id tags. Each scene has a unique id that is linked via the buttons.The “Next/Previous” buttons allow users to navigate from scene to scene independently, but the structure helps guide the overall narrative. Each scene is composed of a unique chart that highlights its own distinct message.

Annotations: Annotations remain consistent on the charts, even throughout changes triggered by the interactions. This allows the user to have some grounding on the overall message the visualization is trying to communicate. For example, the annotation about a relatively good gas mileage stays consistent throughout the vis transformation from highway mileage to city mileage. This can help a user better understand which car makes consistently have good mileage across both parameters.

Parameters: The visualizations have a handful of relevant parameters that help the user better explore the data. By interacting with JavaScript input features, such as the toggle buttons or the interactive legend in vis2, the user can choose to see data about a specific category, or even filter out the datapoints by hovering over specific engine cylinder categories. The user input is used as a parameter that controls what the visualization portrays.

Triggers: The triggers are implemented via events and callbacks, such as “mouseover”, “mouseout” and “click”. When specific html elements experience these events, the callback function is invoked, and we can change the visualization with respect to the action indicated by the trigger. The example triggers we have here are the buttons and hovering legend.
