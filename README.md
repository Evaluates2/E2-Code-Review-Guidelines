# Evaluates2 Code Review Guidelines

Reviewing a pull request can be a daunting task, but if you are new to reviewing code (or it has just been a while!) this guide should help you in figuring out how to do it!

Basically, if you are reviewing a PR you want the codebase to be in better shape once merged than it was before. The incoming code and changes (often referred to as CR or CL) should pass the checkpoints below:


## E2 Code Review Checklist: 

- [ ] Functionality 

    - [ ] Does the code do what it was intended to do?
    
    - [ ] Does it work on all browsers / screen sizes / displays?
    
    - [ ] Does it gracefully handle all the possible situations?
    
    
<br/>


- [ ] Style

    - [ ] Does this code pass linting / formatting standards for the project?
    
    - [ ] Were there good names used for new variables, functions, etc?
    
    - [ ] Are the functions / classes small and focused?
    
    - [ ] Is there anything "weird" about this code?
    
    
<br/>


- [ ] Tests 

    - [ ] Are there automated tests with the code? 
    
    - [ ] And these tests all passing?
    
    - [ ] Are these tests checking the correct things?
    
    - [ ] Are these tests doing what we think they are doing?
    
    - [ ] Is there any way these tests could be refactored?
        


<br/>

## Other things to Keep in Mind

- Checkout the incoming branch, run the tests, and try run the code if you have any doubts about it passing.
- "Filters For Feedback" - Only give feedback if it is true, **necessary**, and kind.
- Refer to the code and author's behavior, not the author themselves.
- Give an overabundance of praise- we are all on the same team here and like to feel good about our code.

```
Wrong: “Most of your code looks good, but the method calc() is too big.”

Right: “I really like the class ProductController, Tim. It has a clear single responsibility, 
is coherent, and contains nicely named methods. Good Job!
Despite this, I spotted the method calc() which is too big for me.”
```


## Other Excellent Resources:
- Phauer.com Code Review Guidelines - https://phauer.com/2018/code-review-guidelines/
- Google Eng Code Review Practices - https://google.github.io/eng-practices/review/reviewer/

