# Questions

Q1: In software development process, 'Practices of Agile Developer' recommend us to use **Test Driven Development** to have a good framework for our code.  
What is the **good practice** of doing Test Driven Development **according to the book**?

Q2: Which following statements is **incorrect**.  

- [ ] Always use comment to explain the code
- [ ] Implement UnitTest beforehand
- [ ] Always using name that specify the intent
- [ ] Think and code ahead of the requirement

Q3: Correct the following code

```python
def Available(d, s):
  # Check if the day is in the future and day is wednesday
  if day - Day.C > 20 and day % 3 == 0:
    # Check if seat is available to add
    ok = addseat(seat)
    if ok == True:
      return True
    else:
      return False
```

Q3: In **Github Flow**, what should be up on each branches

1. Working clean tested code, ready for deployment.
2. Developing state of code, waiting for more thing to be added.
3. New thing in software in progress
4. Small patches for small flaw on deployed software.

| Branch  | Number |
| ------- | ------ |
| Master  |        |
| Develop |        |
| Feature |        |
| Hotfix  |        |

Q4: Which of following statements in **correct**.  

- [ ] You should only commit your work when it's done
- [ ] Always refactoring code for any defect
- [ ] Make your code work first, don't worry about a mess you've made.
- [ ] Reviewing your code and others code before deployment
- [ ] Use pull request frequently to be more updated with main branch
- [ ] You can revert master branch's commit at any time


## Answers

A1: According to the 'PAD Quick reference' and 'Clean code', the best practice for implementing Test Driven Developments are

- Use automated unit test to identify your error automatically.
- Run unit test on all supported platform to ensure that your software won't break.
- Write unit tests before write production code.
- Write production code that just sufficient for passing unit test, to prevent unexpected flaws.
- You should use one Assert per Test

A2: Which following statements is **incorrect**.  

- [X] Always use comment to explain the code
- [ ] Implement UnitTest beforehand
- [ ] Always using name that specify the intent
- [X] Think and code ahead of the requirement (To prevent unexpected flaws)

A3: In **Github Flow**, what should be up on each branches

1. Working clean tested code, ready for deployment.
2. Developing state of code, waiting for more thing to be added.
3. New thing in software in progress
4. Small patches for small flaw on deployed software.

| Branch  | Number |
| ------- | ------ |
| Develop | 2      |
| Hotfix  | 4      |
| Master  | 1      |
| Feature | 3      |

A4: Which of following statements in **correct**.  

- [x] You should only commit your work when it's done
- [x] Always refactoring code for any defect
- [ ] Make your code work first, don't worry about a mess you've made.
- [x] Reviewing your code and others code before deployment
- [x] Use pull request frequently to be more updated with main branch
- [ ] You can revert master branch's commit at any time