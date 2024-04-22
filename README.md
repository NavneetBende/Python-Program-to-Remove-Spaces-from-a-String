Removing spaces from a string
Here we will write python program, we will Remove spaces from a string words whether the sentence is meaningful or meaningless and we can do this in two different ways:-

By traversing the string and removing spaces.
Using the join function.
 

Python program to remove spaces from a string
Method 1
Algorithm
Step 1:- Start.
Step 2:-  Take String Input.
Step 3:- Use join function to remove spaces.
Step 4:- Print String.
Step 5:- End.
Python code
Run
#take user input 
String = "PrepInsta is fabulous"

#Use join function 
String = "".join(String.split()) 

#print String 
print("After removing spaces string is :",String)
Output
After removing spaces string is : PrepInstaisfabulous
Note
A sentence may contain many words and each word join another word with a space in it that tells us about the completion of the word and start of another word so readability is maintained.
Method 2
Algorithm :
Take a string as an input from the user.
Count number of spaces in the string and store it in a variable say t
Use a loop to call replace() function t times
Replace space character with ” in a string.
Print output.
Python program to Remove spaces from a string
Run
# spaces from a string
# Input string
s="PrepInsta is fabulous"
# Count no. of spaces in a string
t=s.count(" ")
# replace all the spaces with ”
for i in range(t):
    s=s.replace(' ',"")

# Print the output
print("String after removing space: ")
print(s)
Output
String after removing space: 
PrepInstaisfabulous
Related Pages
Juggling algorithm for array rotation
 
Balanced Parenthesis Problem
 
Toggle each character in a string

Find the ASCII value of a character

Length of the string without using strlen() function

Prime Course Trailer

Related Banners
Get PrepInsta Prime & get Access to all 200+ courses offered by PrepInsta in One Subscription

Get Prime

Login/Signup to comment


Dhanush i=input(“Enter the sentence: “)
l=i.count(‘ ‘)
while(l):
i=i.replace(‘ ‘,”)
l-=1
print(“After removing spaces the sentence is: “,i)
0Log in to Reply

DuttLuri Lalithasri s = input(‘enter a string:’)
t = ”
for i in s:
if not i.isspace():
t+=i
print(t)
0Log in to Reply

Mohit a=input()
for i in a:
if(i==” “):
continue
print(i,end=””)
0Log in to Reply

nidhisingh151199 s=input()
l=s.split()
s1=””
for i in l:
s1=s1+i
print(s1)
2Log in to Reply

Tronic string = input()
new_str =[] for letter in string:
new_str.append(letter) for letter in new_str:
if letter == ” “:
new_str.remove(letter) print(”.join(new_str))
0Log in to Reply

divyakshirsagar19 string1=input()
string1=string1.replace(‘ ‘,””)
print(string1)
