Set a API breakpoint at lstrcmpA:

![1](pic/1.png)

press F9 to continue, than input some words in textbox:

![2](pic/2.png)

click Check button, OD stops at the first instruction of lstrcmpA, check the stack window we can see:

![3](pic/3.png)

the string we input is compared with "cannabis", this seems to be the right one, let's have a try. Restart program and input "cannabis", than we got the right answer:

![4](pic/4.png)

