Set a API breakpoint at lstrcmpA:

![1575797368621](C:\Users\John\AppData\Roaming\Typora\typora-user-images\1575797368621.png)

press F9 to continue, than input some words in textbox:

![1575797480329](C:\Users\John\AppData\Roaming\Typora\typora-user-images\1575797480329.png)

click Check button, OD stops at the first instruction of lstrcmpA, check the stack window we can see:

![1575797617892](C:\Users\John\AppData\Roaming\Typora\typora-user-images\1575797617892.png)

the string we input is compared with "cannabis", this seems to be the right one, let's have a try. Restart program and input "cannabis", than we got the right answer:

![1575797830816](C:\Users\John\AppData\Roaming\Typora\typora-user-images\1575797830816.png)

