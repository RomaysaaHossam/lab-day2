![enter image description here](https://uteena.com//static/uteena/images/iti_logo.5b9a0fd125be.png)
# Who Am I?
My Name is : **Mohamed A. Bahnsawy**
 
## Foobar
Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s

## Heading

```
# Program to check if a number is prime or not

num = 407

# To take input from the user
#num = int(input("Enter a number: "))

# prime numbers are greater than 1
if num > 1:
   # check for factors
   for i in range(2,num):
       if (num % i) == 0:
           print(num,"is not a prime number")
           print(i,"times",num//i,"is",num)
           break
   else:
       print(num,"is a prime number")
       
# if input number is less than
# or equal to 1, it is not prime
else:
   print(num,"is not a prime number")
```
## license
[MIT](https://opensource.org/licenses/MIT)