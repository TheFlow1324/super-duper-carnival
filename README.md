# super-duper-carnival
Test Mason Dill (mjd159) and Scott Sullivan (scs128) present you with the greatest project, this side of the Mississippi, for CPMINF0010 week 7!

## What is does
DoSomething™ takes a *phrase* and a *key* between 0 and 26. The shift function then takes that name and *shifts* the letters by the *key* number, for example if *key* is 2 and the *phrase* is 'a': ('a' + 2 -> 'c')

'z' would become 'b' because when it overflows it loops back on itself.

 This is also known as a Caesar cypher.

	>What is your name
	>Mason
	>Enter a number between 0 and 26
	>1
	>Nbtpo

## How To Use super-duper-carnival
> ### 1. Installation
> > *Concerning licensing*
> > > DoSomething is under the MIT license, and as such those using this software are free to do as they wish with my code. Feel free to run, test, or improve.
> >
> > DoSomething.ipynb can be manipulated using JupyterLab. The installation is very simple
> > -Download DoSomething.ipynb
> > -import DoSomething.ipynb into JupyterLab
>
> ### 2. Usage
> > ****************
> > **Testing DoSomething**
> >
> > DoSomething includes a main() function, so that the functionality can be tested.
> > To test shift(), include a call to main in DoSomething
> > 	`main()`
> > *****************
> > **Importing/Implementing shift()**
> >
> > This is how you can import and use the shift() function I have created in other Jupyter Notebooks
> > -Run `! pip install ipynb`
> > -Include these imports at the top of your program
> > ```python
> > import import_ipynb
> > import shift from DoSomething
> > ```
> > -example of using shift as an imported module
> >
> > ```python
> > shift( str_myPhrase , int_myShiftkey )
> > ```
> > ****

## How To Contribute
If you would like to contribute additional string encryption modules to DoSomething please email me at
<mjd159@pitt.edu>

Please note:

1. Pull Requests will be ignored until I receive a message from the contributor.
2. Issue Requests will be ignored - this is a full release.
3. Please refer to the [code of conduct]() for further details on contribution

>Code of conduct
>
>>Enter quote here
********
### License Justification
I chose to use the MIT license with DoSomething so that I could maximize the usability of my code for others. I have no vested interests in profiting off of it in any way, so I went with a license that I believe granted the most liberties to those who want to use my code.