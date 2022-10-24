-First we use "wget" to download the file from source 
-Next we are opening up the .png with EOG 
	-Whats EOG? --> Image viewer
-We see a png with random numbers 
-First thing that comes to mind is that it is kind of in flag format picoctf{}
	-Could the numbers translated into something equal the flag?
-John points out that they are all less than 26? Could they all be equal to letters?	

First Possible Solution: 
-Manually translate
Johns Solution: 
Python
How? 

````
>> from string import ascii_uppercase as uppercase
>> uppercase
````
 Output: ABCDEFGHIJKLMNOPQRSTUVWXYZ
```
>>uppercasep[16]
```
 - Remember that ascii is zero based so picture tells us 16 but we need to go minus 1 to find the actual letters

Script:
//
**Note
If you dont have sublime text follow this guide to install it based on the OS you are running 
https://www.sublimetext.com/docs/linux_repositories.html#apt
//


Script: 
```
5:14 in video
```

Run the script and our result 
PICOCTF{THENUMBERSMASON}

Now we could have manually solved that faster but what fun would that have been 

-we learned how to install sublime text 
-we reviewed some python :) 

finally we move the python script output into a txt file to save for reference 


