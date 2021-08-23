# stack-implentation
stack = []
def push():
    i=int(input('how many elements do you want to add: '))
    for e in range(i):
        n=input('enter the value:  ')
        stack.append(n)
        print(stack)    
   
def pop_():
    if len(stack)==0:
        print('stack is empty: ')
    else:
        stack.pop()
        print(stack)

while True:
    print('Do some functions using 1.push 2.pop or 3.quit')
    click = int(input())
    if click==1:
        push()
    elif click==2:
        pop_()
    elif click==3:
        break
    else:
        print('choose the given options')
