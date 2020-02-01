# Validation
A collection of C-Standard based functions to validate multiple types of strings. The "chkops.c" & "chkops.h" files are written to be reusable.
Bellow you'll find what you can do with them:

*	int findMainOptions( int optionsCount, char *availableOptions[], char *chosenOption )
	*	Checks in a list of available options whether the chosen one exists; if it does, returns its position in the array, otherwise it returns -1. Receives as argumens: the size of the array that contains the options available, an array of strings with the options, an option.

*	bool isUnsignedNumber(char* number)
	*	Checks whether the passed number (as string) is a valid UNSIGNED integer or float type of number.
*	bool isSignedNumber(char* number)
	*	Checks whether the passed number (as string) is a valid SIGNED integer or float type of number.
*	bool isUnsignedInteger(char* number)
	*	Checks whether passed argument is an UNSIGNED integer number
*	bool isSignedInteger(char* number)
	*	Checks whether passed argument is a SIGNED integer number
*	bool isUnsignedFloat(char* number)
	*	First checks whether passed argument is a valid number and then checks if it's a UNSIGNED float number
*	bool isSignedFloat(char* number)
	*	First checks whether passed argument is a valid number and then checks if it's a SIGNED float number
