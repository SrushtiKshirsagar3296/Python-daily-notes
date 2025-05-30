#FUNCTIONS
----
## Area of a cylinder
![Image](https://github.com/user-attachments/assets/ce20e1e8-71c4-4313-b2c5-9ad6b51d4910)
----
## If we are providing arguments to a function instead of a list or tuple we use the concept of *
So whenever we do not specify the contents into tuple , list , dictionary and just initialize it as just arguments, we use to concept of * , when we apply * in front of any name , it converts the items in that name into tuple and thus the loop iterates through each element in it 
*args allows you to pass any number of positional arguments to a function.
The arguments are collected into a tuple.
You can iterate through *args to access each argument.

![Image](https://github.com/user-attachments/assets/8ec1888e-2809-4f25-bd39-127f3f7014a5)
----
You can use *args along with other fixed arguments:
![Image](https://github.com/user-attachments/assets/dd8ff6bc-744d-405b-8f40-d0d77e15012f)
![Image](https://github.com/user-attachments/assets/4dc89efa-20aa-42e2-8cd8-1df88c8e9638)
---
If we don't want to use function we can use a new concept known as lambda
![Image](https://github.com/user-attachments/assets/b88c5959-a49e-477b-9f6a-3ac0c12f4d2d)

| Tuple | List |
|------------------|------------------|
| (1,2,3)   | [1,2,3]    |
|These are immutable , ie we cannot add any element in the tuple   | We can append or add in the list        |
-------------
![Image](https://github.com/user-attachments/assets/f7e870d7-cdd0-4fab-9614-ae6827d88c59)

 \, thus the data can be quickly accesed as compared to stack memory location . 
![Image](https://github.com/user-attachments/assets/2bdf3f5a-b102-42ba-bd10-fcde984c5d88)
This is the diagram of stack memory allocation and Hash map , to retrieve any data from the stack we need to go through each element in stack memeory location which would be very lenthly process if we have large data set , but if we use hash map , in hash map a data is alllocated to some memory location


-----
#DICTIONARY 
Dictionary consists of keys and values
![Image](https://github.com/user-attachments/assets/52e4d2d7-e31e-46ca-a4d4-9372b76f1979)

![Image](https://github.com/user-attachments/assets/a16b9d6b-025b-4c8e-9bf2-d4a8954605b1)

------

![Image](https://github.com/user-attachments/assets/9e985ce9-c4ba-49fa-afe0-8cca99231cbf)
![Image](https://github.com/user-attachments/assets/29cb9a37-3269-45ab-b271-972d2ed9de3e)
![Image](https://github.com/user-attachments/assets/a6976f37-4e72-48ec-adfe-ea8bc4c0d321)
-------
#OPERATOR OVERLOADING 

<br>ex:print(1+2) ; O/P = 3
<br>ex:print("1"+"2") ; O/P = 1 2
<br>contructor uses various methods such as init , add
the same code we can write as follows by using add method ( which tells us the working of + operator)

<br>ex: print(int.__add__(1,2))  ; O/P = 3
<br>ex: print(str.__add__("1","2"))  ; O/P = 1 2
----
__Addition of Complex Numbers__
![Image](https://github.com/user-attachments/assets/4bc0a4cd-67dc-47ad-8521-eaee2e664cbb)
 _or we can use ( return str(self.real+other.real) + "+" + str(self.imag+other.imag)+"i"_

__Age Comparison example using :>" operator__
![Image](https://github.com/user-attachments/assets/8ea6b16f-cadd-4c02-9333-95bb6abc6942)

__here we are passing parameters , but if we dont want to pass parameters in the defination function
def __init__(self):
  self.num=2
  self.eyes=
------
#INHERITANCE
-----
*basic example*
![Image](https://github.com/user-attachments/assets/53f7f462-e1b8-46e9-a999-9e3a3ec4a98c)
-----
##Super Function##
_super fucntion allows us to access parent class attributes_

![Image](https://github.com/user-attachments/assets/49e556fa-165a-4f0d-9e03-d3acc4554ead)

![Image](https://github.com/user-attachments/assets/96a411db-f818-4297-bba2-da270cbf024c)

![Image](https://github.com/user-attachments/assets/b28b3de8-c510-408b-8d0d-3dfd2f68bfa7)


![Image](https://github.com/user-attachments/assets/07ead313-363a-40eb-aae1-370b87ba08d2)

![Image](https://github.com/user-attachments/assets/b6dd2609-052d-4565-b84b-73537c862bb8)

![Image](https://github.com/user-attachments/assets/e20ad605-4619-44dd-93d2-b92ff9379963)

------
#EXCEPTION HANDLING
![Image](https://github.com/user-attachments/assets/1d263e48-8ada-4825-9755-9100e097551a)

![Image](https://github.com/user-attachments/assets/b02fbbf3-25ec-43b4-8255-66405af7cb18)


#__name__ ( Special variable)
**basic of __name__ concept)**
![Image](https://github.com/user-attachments/assets/0caca564-b3b4-42e9-a5ef-fae6d09e2c80)

![Image](https://github.com/user-attachments/assets/21e52923-9b7f-4eb7-b8b4-dda8c96bc1f0)
when we are in the python page(module- the page which is supposed to get imported ) and we trigger __name__ , it gives us the name of the python function but when we import that module in our main python page and then if we trigger the __name__ we get the o/p as main )
<br> it's usage is demonstarted in the below example :
![Image](https://github.com/user-attachments/assets/182f7011-b341-4e01-8f3c-7fe388dc3a4f)
So the badic usage is that if a user is entering first time and he runs the demo file so he is in the main and gets the o/p = hello welcome to python , but if we are in the next file that is calculate so it does gives us the o/p = its time to calculate , so the logic behind this is it will only give the o/p of demo file if the user is accesing the file 1st time elese it will always give the o/p = its time to calculate
![Image](https://github.com/user-attachments/assets/8dcc88a1-d0e2-40a5-8268-b65ad8ce89f9)

 

