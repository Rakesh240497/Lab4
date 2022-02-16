# Printing all the folders and subfolders of a directery. 

First we check wheather the number of arguments passed is two or not one is source file name and the other is directory path. if the number is not equal to 2 or less than two we print error and exit the program. 

Next we check weather the directory is empyt or not if the directory is empyt we print the according error. 

If all the above parameter safisfy we call the folder recursion function and do the iterations accordingly. 

1. using the while loop we go till end the of the hierarchy
2. Next we check the wheathe the subdirectory has some files using if condition. 
3. If there are files inside a directory we travers through the directory by using the recursive calls and updating the path, until the end of the subdirectory. 


