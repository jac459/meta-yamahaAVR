# meta-yamahaAVR

In the neeo app, add a device and search for YAMAHA.

Add the device in the room you want.
(Mandatory) go to the recipe list and make the Yamaha recipe visible.
By default, Yamaha is an AVR type and not immediately visible.

Ensure you are using POWER ON and POWER OFF when launching and Closing the recipe.
Power On and Power Off are the events used by the meta driver in order to listen to the device. In your case, if you don't do it, you will not be able to see the state change in your yamaha software.

Choose your shortcuts.
when loading the recipe, you can suppress all the slides except the ones with shortcuts.
