## NOTES FROM VIDEO:
## Python Classes and Objects || Python Tutorial || Learn Python Programming
#### https://www.youtube.com/watch?v=apACNr7DC_s

### >>> class User:
### ... pass

###### It is necessary to type pass and then enter because you need at least one line
###### Now that we have created a class, we can use it to define users
###### To make a user, type in the name of the class followed by parenthesis
### >>> user1 = User()
##### This looks like you are calling a method .... and you ARE
##### user1 is an INSTANCE of the User class
##### You can also call user1 an OBJECT
##### To attach data to the object, you first type the NAME of the object, a dot, the name of the VARIABLE, and then give it a value
### >>> user1.first_name = "Dave" 
##### example two -- also, notice no semicolon follows the value
### >>> user1.last_name = "Bowman"
##### Since first name and last name are attached to the object user1, we call them FIELDS.  They store data SPECIFIC to user1
#### *FIELD: Data attached to an object*
##### To see that the data is in the user1 object, you can PRINT them
### >>> print(user1.first_name)



