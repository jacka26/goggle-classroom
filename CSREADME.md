This is a Python program that uses the matplotlib and numpy libraries to plot a trigonometric function (sine, cosine, or tangent) based on user input.

Here is how it works:
1. Run the program by typing python trigonometric_plot.py and pressing Enter.
2. The program will prompt you to enter a trigonometric function (sin, cos, or tan). Enter the desired ratio and press Enter.
3. The program will generate a plot of the selected function using matplotlib and display it.

Small explanation of the code:
- The import statements at the beginning of the file import the necessary libraries.
- The plot_trigonometric_function function takes a string argument which will represent the trigonometric function to plot. It creates an array of x values using numpy.linspace, it calculates the corresponding y values based on the selected function, and then it plots the function using matplotlib.pyplot.plot.
- The if __name__ == "__main__": part at the end of the file is just used there to make sure that the code is only executed when the script is not imported as a module by another script. In this case, it prompts the user for input and then calls the plot_trigonometric_function function with the selected function.
- A specific point, the ylim function is used to set the y-axis limits to -5 and 5, which helps me avoid plotting the full y-range for the tan function, which is supposed to diverge to infinity.
