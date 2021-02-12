---
layout: essay
type: essay
title: Cleaning the Lint
# All dates must be YYYY-MM-DD format!
date: 2020-02-11
labels:
- Javascript
- ESLint
- IDE's
---
## To be Lazy yet To be Perfect
According to the words of one my introductory to Computer Science professors, "all programmers like to be lazy."  The more I dabble into software engineering the more I find this statement to be true; my professors want to write less lines of code and I now I want to write less lines of code.  At the same time, I have also noticed that software engineers are meticulous in what they create, and now I too am detailed oriented in what I code.  To be lazy yet to be diligent. How can software engineers (or any person for that matter) be both at the same?  These two characteristics are almost contradictory to one another. Yet surprisingly, in practice, one would be surprised on how these two characteristics enhance the craft of software engineers.

## Appearance and Attire
When it comes to coding any type of project (even as simple as a "Hello World" project), the simplest of details can mess up a program in terms of its design.  Perhaps there was a lack of a semi-colon that went noticed.  Maybe a variable that was initiated with "let" should have been initiated with a "const" instead.  Or perhaps tracing the problem is too unwieldy because of inconsistent indentation and spacing.  Most likely, we as software engineers are bound to make these mistakes in some form of another.  Yet being the lazy individuals that we may be, sometimes we don't always want to look out for these mistakes.  So what do we do? We let someone else do the cleaning, or at the very least, have someone else call out what needs to be cleaned.

In other words, given the creative craft of software development, we have to be concerned in regards to how our code looks as well as how it functions.  Despite the laziness, we are also meticulous in the code we produce and thus are keen on the finer details of our code.  The concern for these details were as if we were to attend a fancy ball. Given our chosen attire for the formal party, our suit must look clean throughout.  While a simply functional suit may suffice for the event, for a formal party, there must be a sense of class in how we dress in which everything in regards to the attire must be accounted for.  That includes the lint that may sit on our clothes.

Consider these two samples of Javascript code:
```javascript
{
  var suitItems = new Array();
  suitItems[suitItems.length] = 'dress shoes'
  suitItems[suitItems.length] = "black pants"
  suitItems[suitItems.length] = "suit jacket";
  

  function showOff(mySuit) 
  {
    var clothes = mySuit.toString();
    return "Check out my suit:" + clothes;
  }
  console.log(showOff(suitItems));
}
    
  

```

```javascript
{
  const suitItems = [];
  suitItems.push('dress shoes');
  suitItems.push('black pants');
  suitItems.push('suit jacket');
  
  function showOff(mySuit) {
    return `Check out my suit: ${mySuit.toString()}`;
  }
  console.log(showOff(suitItems));
}
```

Comparing these two sets of code, they both are functional and work as expected, however one looks more refined than the other.  The first block of code has many things that can be ironed out; pieces of lint that we can (and should) clean up.  For example, we don't want to bring "var" to the party as that's generally not accepted, and there's usually a better way to lay out the outfit with an array.  We can fix how we pick out the items for the outfit and brush it up with single semicolons instead of double.  In contrast, the second block of code is more refined and uniform throughout. There are lines that condensed with functions or simpler notation. To simply put, the code is lint free in terms of its appearance.

## Looks Matter

If anyone cares about their style and appearance, generally most would want to follow the look of the second block of the code.  After all, that is the expected standard of what to wear to the party; nobody should look messy at a high-class party.  In other words, there is a standard of what our code should look like as there is more to it than functionality.  In the case of Javascript, one must generally adhere to the standards of the [AirBNB](https://github.com/airbnb/javascript) style guide.   

When presenting projects or working collaboratively on them, the goal in regards to the appearance is to make the code readable to not just creator, but to other people as well.  This especially important if someone else has to proof read the author's code.  Yet, as mentioned in the beginning, at first sometimes these details can be overlooked and often there is someone else that looks for these violations. For Javascript there is [ESLint](https://eslint.org/) that is implemented IDE's in order to check for details that would go against standard expectations in regards to appearance.  That is the product of a programmer's laziness: to have a product that cleans out the lint.  Yet through the usage of these linters, software engineers are able to hone the appearance of their craft.

## Learning from the Linter
Ultimately, these autonomous tools not only makes our code look prettier, they also improve how software engineers write their code.  Tedium is bound to ensue the more we make the same violations, and to rid of it, we learn from it so that it may never show up again. After all, the best way to learn is through making mistakes. The more times linters call out our faults, the less likely we are to produce them in the future.  Through the usage of linters, the laziness of programmers can lead to detailed and refine products of code.

