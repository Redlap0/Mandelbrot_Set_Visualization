# Mandelbrot Set Visualization
Visualizing Mandelbrot in python using Matplotlib.pyplot and numpy


Mandelbrot set is a really amazing mathematical fractal, it just iterates a quadratic equation on a complex plane. It's
formula is: 
_z_n+1 = z_n2 + c_ (n+1 is subscript of z and so is n^2 for the second z, and "c" is a complex number).The set is named after *Benoit Mandelbrot*, a French mathematician, who discovered it in the 1970s while studying the behavior of complex iterative functions.
![image](https://github.com/user-attachments/assets/1019d597-b9b8-4291-b653-1e482a01b36f)

this is what your output will look like.

So, what bassically happens is that, we take a complex number and take 'z' as 0, then we repeteadly calculate the above given formula
may it be 100 or 1000 of repetitions. If 'z' stays below 2 forever then 'c' or the complex number,
is in a mandelbrot set. But if the value of 'z' exceeds 2, then our 'c' is not in the mandelbrot set.

Normally, fractal can be zoomed in infinetly, but since we are using matplotlib,pyplot we will not have that much of a granularity
when we zoom in, because to make it accurate at suck a high level more code and work is needed which I am still not at a level to do.

To know more and get an in depth knowledge about this set go to: [Dynamic Math – Mandelbrot Explorer](https://mandelbrot.page/?)

























*Pre-requisites* for this project is that you should have numpy and matplotlib.pyplot downloaded in your system which if not, you can easily download by going to cmd and using the 'pip install' command.
