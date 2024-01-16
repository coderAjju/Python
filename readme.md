# Python tutorial 
Python ek high-level, general-purpose programming language hai jo apni readability, simplicity, aur versatility ke liye prasiddh hai. Guido van Rossum ne ise 1991 mein banaya tha

## What python can do?
Python ek versatile and popular programming language jo bahut sare kaam kar sakti hai alag alag field main.
kuch field niche diye gaye hain...

- #### Web development
Hum python ko web development field main as a backend language use kar sakte hain Django aur Flask jaise framework ka use karke.

- #### Data science and analysis
Kuch python ki library jaise NumPy, Pandas, and SciPy ka use karke data manipulation, analysis aur visualization kar sakte hain.

- #### Artificial Intelligence and Machine Learning
Kuch popular library jaise TensorFlow aur PyTorch ka use kiya jata hain machine learning model aur artificial application banane ke liye.

- #### Cybersecurity
Python language ka use bahut saare cybersecurity task ko complete karne ke liye kiya jata hain including ethical hacking, penetration testing, and developing security tools.

- #### Game development
Python ki library Pygame ka use karke game bhi banaye ja sakte hain.

- #### Database
Python bahut saare database management system ko support karta hai jaise SQLAlchemy for relational database management system aur pymongo for mongoDB.

## Why python ?
 - Python ek beginner friendly language hai jiske syntax kafi similer hain english language se, jise samajhna aasan hai other programming language ke comparison main.
 - python ek cross platform independent language hai jisse ki ek baar likha gya code kisi bhi platform jaise Windows, Mac, Linux, aur Raspberry Pi per chalaya ja sakta hai.
 - Python ek interpreter programming language hai, iska matlab hai ki jab bhi code likha jata hai, usko turant execute kiya ja sakta hai. 
 - Jaisa ki python ek versatile programming language hai, iska matlab hai ki python ko procedural programming ke taur per , Object - oriented programming ke taur per ya phir functional programming ke taur per use kiya ja sakta hai.

 ## Python main aap hello world ka program kuch es tarah se likh sakte hain
    print("Hello, World!")

## Comments in Python
 - Hum kisi bhi program main comments likhte hain jisse us program ki readability badh jati hai aur us program ko achhe se samajha ja sakta hai. Python main comment likhne ke liye hum # (hash) ka use karta hain. Python language ke andar koi multi line comment likhna ka symbol nhi hain hame each line ke liye hash (#) use karna padega.
    
    ```
    print("Hello, World!") #this is comment
    ```
 
 ## Variables
 - Variables are just like a container for store data.
 - Python programming language mein aisa koi keyword nhi hain jisse hum variable ke type of define kar paye.
 - Variable name jo hote hain wo case-sensitive hote hain jaise ajay aur AJAY both are different.
   1. kisi bhi variable ko aap number se nhi bana sakte jaise 2x,3name.
   2. aap kisi bhi variable ko symbol se nhi bana sakte jaise #name,@value.
   3. aap kewal character aur underscore ka use kareinge variable banane ke liye jaise x,y,name,_value.
 - Declaration of python variables...
 ```
    a = 4                                          # int type variable
    b = 4.5                                        # float type variable
    c = "Ajay Upadhyay"                            # string type variable
    d = True or False                              # boolean type variable
    print(a)                                       # printing value of a
    print(b)                                       # printing value of b
    print(c)                                       # printing value of c
    print(d)                                       # printing value of d
 ```
 [aur bhi kai tarah ke variable hote hain jaise lists,dictionaries,sets,tuples aage hum enke barein main padhenge].

 ## Type Casting
 -Type casting(type conversion) ek aisa method main jisme hum kisi variable ke type ko kisi dusre type mein convert kar dete hain niche diye gaye code ko aap apne computer per run karke output dekh sakte hain.
 ```
    x = 3                   # x is int(integer) type variable
    z = str(x)              # here x converted in string and assgin to z
    print(type(z))          # str(string)
    print(z)                # output:=> 3
 ```
 - Type casting ke bhi do type hote hain
    > 1. Implicit type casting
    > 2. Explicit type 
    
    - Implicit type casting :- Kabhi-kabhi programming language apne aap hi ek data type ko doosre data type mein convert kar deta hai, bina kisi explicit instruction ke. For example, ek integer ko float mein add karne par automatic conversion ho sakta hai.
    ```
    x = 5                       # int type of variable
    y = 3.14                    # float type of variable
    result = x + y              # Implicit type casting
    print(type(result))         # <class 'str'>
    ```
    - Explicit type casting := Explicit type casting mein programmer interpreter ko bata hai ki ek data type ko dusre data type main convert karna hai.
    ```
        x = 5               # int type of variable
        z = float(x)        # explicit type casting int to float
        print(z)            # output:=> 5.0
        print(type(z))      # output:=> <class 'float'>
    ```

### Many Values to Multiple Variables
- Python apne user ko allow karta hai jisse wo ek saath kayi variable main value ek hi line main assgin kar sakte hain
```
   x, y, z = "Ajay", "Ramesh", "Suresh"
   print(x)
   print(y)
   print(z)
```

### Unpacking
- Agar aapke pass collection of value hain kisi list ya tuple main to aap us values ko extract kar sakte ho multiple variable main. esi prakriya ko unpacking kahte hain.
```
   marks = [98,76,87]
   x, y, z = marks
   print(x)
   print(y)
   print(z)
```

## Print function
- Print() function ek aur ek se jyada parameter le sakta hai jise wo print karta hai console per.ab wo 2 ya 2 se jyada number ka addtion karna ho ya aur koi mathemetical operation ho jaise...
```
   print(3 + 4)
   print(12 * 43)
   print("hello world")
```

## Global Variable
- Global variable wo variable hote hain jinhe hum pure program main kahi bhi access kar sakte hain
  global variable ko hum us program ke kisi bhi functin main use kar sakte.Jaise..
```
   x = "awesome"                       # string type variable

   def myfunc():                       # function declaration
   print("Python is " + x)             

   myfunc()                            # function call
```

   agar koi variable kisi function ke andar define hua hai aur aap usse vahi global variable banana chahta hain to aap use variable ko define karte wakt 'glabal' keyword se define karein.
```
   def myfunc():
   global x
   x = "fantastic"

   myfunc()

   print("Python is " + x)
```

## Data Types
 -
