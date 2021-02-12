---
layout: essay
type: essay
draft: true
title: Cleaning the Lint
# All dates must be YYYY-MM-DD format!
date: 2020-02-11
labels:
- Javascript
- ESLint
- IDE's
---
## To be Lazy yet To be Perfect
According to the words of one my introductory to Computer Science professors, "all programmers like to be lazy."  The more I dabble into software engineering the more I find this statement to be true; my professors want to write less lines of code and I now I want to write less lines of code.  At the same time, I have also noticed that software engineers are meticulous in what they create, as I too am detailed oriented in what I code.  To be lazy yet to diligent. How can software engineers (or any person for that matter) be both at the same?  These two characteristics are almost contradictory to one another. Yet surprisingly, in practice, one would be surprised on how these two characteristics enhance the craft of software engineers.

## Autonomous Cleaning
When it comes to coding any type of project (even as simple as a "Hello World" project), the simplest of details can mess up the program.  Perhaps there was a lack of a semi-colon that went noticed.  Maybe a variable that was initiated with "let" should have been initiated with a "const" instead.  Or perhaps tracing the problem is too unwieldy because of inconsistent indentation and spacing.  Most likely, we as software engineers are bound to make these mistakes in some form of another.  Yet being the lazy individuals that we may be, sometimes we don't always want to look out for these mistakes.  So we do we do? We let someone else do the cleaning, or at the very least, have someone else call out what needs to be cleaned.

In other words, given the creative craft of software development, we have to be concerned in regards to how our code as well as how it functions.  Despite the laziness, we are also meticulous in the code we produce and thus are keen on the finer details of our code.  The concern for these details, yet to lack motivation to find these details is to attend a fancy ball. Given our chosen attire for the formal party, our suit must look clean throughout.  While a simply functional suit may suffice for the event, for a formal party, there must be a sense of class in how we dress in which everything in regards to the attire must be accounted for.  That includes the lint that may sit on our clothes.

Consider these two samples of code:
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
    return `Check out my suit: ${mySuit.toString()}`
  }
  console.log(showOff(suitItems));
  
}
```

