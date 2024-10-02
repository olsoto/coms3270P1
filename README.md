# coms3270P1
Author: Thomas Olson - olsoto@iastate.edu
Project: COM S 3270 Part 1 A - Point Cloud Data Processing

This program takes in a file and will read a point cloud stream and will track the coordinates of the input that has the lowest height and highest height respectively. The program also maintains the total height and at the end of the point cloud stream input it will calculate the average and print the coordinates of the max height point, coordinates of the minimum height point, and the average of all heights from the file. Known errors are if the user input to execute the program is not in file format, the program will not read the point cloud stream data and will run an error. The program does also not check for input file format.

This program is executed by typing "make" while in the main project directory to create the executable file stat.exe, then typing "./stat <filename>" to execute the program with the file of your choice.

e.g.
./stat myTest.xyz 
> 
Minimum Height: 0.000000 at coordinates 445000.500000, 4650999.500000
Maximum Height: 10.000000 at coordinates 445001.500000, 4650999.500000
Average Height of all the points: 1.000000