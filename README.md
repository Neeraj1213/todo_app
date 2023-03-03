Hey, all credits for teaching me to make this app using react goes to 
"Web Dev Simplified"

Bugs:
I had issue importing the random key generating library, 'uuid/v4'
I tried importing it in a different style, 'import { v4 as uuidv4 } from 'uuid';'
didn't work
Therefore all the items added to the todo list have the same key value '1'.

This does not directly affect the functionality of the app, but potentially might cause errors while implementing new features which need unique key for idnetification.
