sudo update-grub
sudo apt update && sudo apt install virtualbox -y
username = input("Enter username: ")
password = input("Enter password: ")

if username == "islam" and password == "1234":
    print("hello admin islam welcome back")
else:
    print("wrong username or password")
