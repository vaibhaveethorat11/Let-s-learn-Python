## Length of string :
To determine length of string we can use built-in function abbrievated as len(). It returns the numbers of characteres in strings, even blank spaces.
```py
len("Hello")

str1 = "Vaibhu"
len(str1)

phrase = "Fantastic!!!"
len(phrase)
```
Output:
```
4
5
12
```
Strings are indexed sequences so positive indices start at 0 from the left; negative indices start at -1 from the right.
Eg: 
```py
name = "Swara"
print(name[1])
print(name[-1])
```
Output:
```
w
a
```
## Slicing
Slicing is a way to extract a portion of a string by specifying the start and end indexes. The syntax for slicing is string[start:end], where start starting index and end is stopping index (excluded).
Eg:
```py
s="Fantastic"
print(s[1:3]) # from index 1 to index 3
print([:2])  # from 0 to index 2
print([4:]) #from index 4 to end
print([::-1]) #reverse string
```
Output:
```
an
Fa
astic
citsatnaF
```
