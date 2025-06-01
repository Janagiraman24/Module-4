# File Handling in Python: Count the number of words in it

## 🎯 Aim
Write a Python program to read a file and count the number of words in it.
## 🧠 Algorithm
1.Open or create a file at the specified path in write mode.
2.Write the provided content to the file and close it.
3.Reopen the same file in read mode.
4.Read the entire content from the file.
5.Split the content into words using whitespace.
6.Count and return the number of words.
## 🧾 Program
```
def create_file(file_path,file_content):
    with open(file_path,'w') as file:
        file.write(file_content)
def count_words_in_file(file_path):
    with open(file_path,'r') as file:
        content=file.read()
    return len(content.split())
```
## Output
![image](https://github.com/user-attachments/assets/d61311b4-4a47-41cf-9edd-7760fcc82f19)

## Result
Thus the program has been successfully executed.
