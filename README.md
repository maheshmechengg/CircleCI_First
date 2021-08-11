

Circle-CI Tutorial
```bash
https://www.youtube.com/watch?v=4dp4JFpOpX0
```

Create repository on github
```bash
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/maheshmechengg/CircleCI_First.git
git push -u origin main
```

Add code in main.py
```bash
def Add(a, b):
    # Use a breakpoint in the code line below to debug your script.
    return a + b  # Press Ctrl+F8 to toggle the breakpoint.

def SayHello():
    print("Hello! First Circle-CI")

# Press the green button in the gutter to run the script.
if __name__ == '__main__':
    SayHello()

```


Add code for test
```bash
#Import Library
from main import Add

def TestAdd():
    assert Add(2, 3) == 5
    print("Add Function works correctly!")

if __name__ =="__main__":
    TestAdd()
```

make dir for circleci
```bash
mkdir .cricleci
notepad/touch/nano .cricleci/config.yml
```



