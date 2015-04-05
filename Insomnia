import time
import random
from random import randint

users = {} 
status = ""

class one():
    def inst():
        clear = ('\n' * 50)
        print(clear)
        print("Loading.")
        time.sleep(1)
        clear = ('\n' * 50)
        print(clear)
        print("Loading..")
        time.sleep(1)
        clear = ('\n' * 50)
        print(clear)
        print("Loading...")
        time.sleep(1)
        clear = ('\n' * 50)
        print(clear)
        print("Loading....")
        time.sleep(1)
        clear = ('\n' * 50)
        print(clear)
        print("Loading.....")
        time.sleep(1)
        clear = ('\n' * 50)
        print(clear)
        print("Loading.....Done")
        time.sleep(1)
        clear = ('\n' * 50)
        print(clear)
        clear = ('\n' * 50)
        print("Booting into OS.0001.....Done")
        time.sleep(1)
        clear = ('\n' * 50)
        print(clear)
        print("Installing Drivers")
        print("Be patient, this will take some time")
        time.sleep(1)
        clear = ('\n' * 50)
        print(clear)
        print("Installing Drivers.")
        print("Be patient, this will take some time")
        time.sleep(1)
        clear = ('\n' * 50)
        print(clear)
        print("Installing Drivers..")
        print("Be patient, this will take some time")
        time.sleep(1)
        clear = ('\n' * 50)
        print(clear)
        print("Installing Drivers...")
        print("Be patient, this will take some time")
        time.sleep(1)
        clear = ('\n' * 50)
        print(clear)
        print("Installing Drivers....")
        print("Be patient, this will take some time")
        time.sleep(1)
        clear = ('\n' * 50)
        print(clear)
        print("Installing Drivers.....")
        print("Be patient, this will take some time")
        time.sleep(1)
        clear = ('\n' * 50)
        print(clear)
        print("Installing Drivers")
        print("Be patient, this will take some time")
        time.sleep(1)
        clear = ('\n' * 50)
        print(clear)
        print("Installing Drivers.")
        print("Be patient, this will take some time")
        time.sleep(1)
        clear = ('\n' * 50)
        print(clear)
        print("Installing Drivers..")
        print("Be patient, this will take some time")
        time.sleep(1)
        clear = ('\n' * 50)
        print(clear)
        print("Installing Drivers...")
        print("Be patient, this will take some time")
        time.sleep(1)
        clear = ('\n' * 50)
        print(clear)
        print("Installing Drivers.....Done")
        print("Be patient, this will take some time")
        time.sleep(1)
        Login.displayMenu()
       
       
       
class Amnesia():
    def text():
        print('''
Welcome to Amnesia, the amnesic text editor.
Type whatever it is you want once, and forget about it!
''')
        a = input("")
        a = input("")
        a = input("")
        a = input("")
        a = input("")
        a = input("")
        a = input("")

        input("Press ENTER when you are finished with your task")
        
class Insomnia():
    def about():
        print('''
Insomnia is a simulation of a text based operating system such as MS-DOS.
There is no UI, just a simulation of the shell.
''')
        input("Press ENTER when you are complete with your task")
        Insomnia.comwin()
    
    def sd():
        print("Thank you for using Insomnia, goodbye!")
        quit()
        
    def rt():
        print("Restarting Insomnia....")
        Login.displayMenu()
    
    def comwin():
        clear = ('\n' * 50)
        print(clear)
        print("Type help for a list of commands")
        command = input("!>> ").lower()
        
        if command == "lk":
            Login.displayMenu()
        
        if command == "help":
            print('''
Commands:
help-Displays this list
about-Displays information about Insomnia
am-Launches Amnesia text editor
lk-Locks Insomnia
sd-Shuts down Insomnia
rt-Restarts Insomnia
''')
            input("Press ENTER when you are complete with your task")
            Insomnia.comwin()
            
        if command == "about":
            Insomnia.about()
        
        if command == "sd":
            Insomnia.sd()
        
        if command == "rt":
            Insomnia.rt()
            
        if command == "am":
            Amnesia.text()
            
        else:
            Insomnia.comwin()
            
class Login():  
    def error():
        print('''
Command not recognized, please try again''')
        Login.displayMenu()
        
    def oldUser():
        login = input("Username: ")
        passw = input("Password: ")

        if login in users and users[login] == passw: 
            print ("Login successful!\n")
            Insomnia.comwin()
        else:
            print ("User doesn't exist\n")

    def displayMenu():
        clear = ('\n' * 50)
        print(clear)
        print('''Are you a registered user? Type y for yes and n for no''')
        status = input("!>> ")
        if status == "y":
            Login.oldUser()
        elif status == "n":
            Login.newUser()
        if status == "q":
            print("Thank you for using Amcita, goodbye!")
            quit()
        if status != "y":
            Login.error()
        if status != "n":
            Login.error()
        if status != "q":
            Login.error()

    def newUser():
        createLogin = input("Create Username: ")

        if createLogin in users: # check if login name exists
            print ("\nLogin name already exist!\n")
        else:
            createPassw = input("Create Password: ")
            users[createLogin] = createPassw # add login and password
            print("\nUser created!\n")     
            Login.displayMenu()
            
class First():
    def instmen():
        clear = ('\n' * 50)
        print(clear)
        print("Hi")
    
    def load():
        print('''
INSOMNIA 
''')
        
        input("Press ENTER to begin")
        Login.displayMenu()
        
        
one.inst()
