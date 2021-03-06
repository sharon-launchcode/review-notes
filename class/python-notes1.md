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
### Dave
##### You access the data the same way you assigned it
##### Type the name of the object, dot, then the name of the field.
###### Printing the last name
### >>> print(user1.last_name)
### Bowman
### >>>
### >>>
###### Do not capitalize fields, and if you use more than one name in a field, separate by underscores
### >>> first_name = "Arthur"
### >>> last_name = "Clarke"
##### Above are stand-alone variables, not attached to an object

### >>> print(first_name, last_name)
### Arthur Clarke
### >>> print (user1.first_name, user1.last_name)
### Dave Bowman
##### Classes are used to make objects, and each object can have different objects for the same variable name
## CLASS FEATURES
1. >> Methods
1. >> Initialization
1. >> Help Text

##### First add an init method
##### *init is short for initialization*
##### *Some languages call initialization methods contstructors*
#### A FUNCTION INSIDE A CLASS IS CALLED A METHOD

        class User:
          def__init__(self,full_name, birthday):


##### The name of the method is init with double underscores before and after the method
### This method is called every time you CREATE a new instance of the class
### The first argument of this class is the word 'self', which is a reference to the new object being created.
##### You can add additional arguments after self; in the example below full_name and birthday are the additional arguments
##### First store these VALUES to FIELDS in the OBJECT
##### We do this by typing SELF, then DOT, then the FIELD NAME, and then assign it a value.

        class User:
          def_init_(self, full_name, birthday):
            self.name = full_name


#### Dot notation: *self.*, the FIELD NAME (name) and assign it a VALUE (full_name)
##### We are storing the full_name in a FIELD called name
##### We will store the value of birthday in a FIELD also called birthday

    class User:
      def_init_(self, full_name, birthday):
        self.name = full_name
        self.birthday = birthday #yyyymmdd
     
##### NOTICE no comma after the first self.name = full_name

### TO CREATE A USER USING THE INIT METHOD
1. Type in the name of the class, and parenthesis.
1. Provide Two values because the INIT method is expecting two values
####

    user = User("David Bowie", "19710315")
    print(user.name)
    print(user.birthday)

   
### NOTICE QUOTES AROUND DATE
