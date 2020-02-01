# Validation
A collection of C-Standard based functions to validate multiple types of strings. The "chkops.c" & "chkops.h" files are written to be reusable.
Bellow you'll find what you can do with them:

*	int findMainOptions( int optionsCount, char *availableOptions[], char *chosenOption )
	*	Checks in a list of available options whether the chosen one exists; if it does, returns its position in the array, otherwise it returns -1. Receives as argumens: the size of the array that contains the options available, an array of strings with the options, an option.

