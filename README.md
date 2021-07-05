# bootcamp_project
import hashlib 
string = input("entre your string:")
encoded=string.encode()
result = hashlib.md5(encoded)
print("String : ", end ="")
print(string)
print("Hash Value : ", end ="")
print(result)
