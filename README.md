# An Error

You will be studying each error you come across in a repository much like a Snippet Study, and collecting them in your Error-Log index repository. This repo contains instructions for how to document different classes of error. (Each bulleted link should have it's own section in your Error-Log repo):

* [Warnings](#warnings)  
* [Syntax Errors](#syntax-errors)
* [Runtime Errors](#runtime-errors)
* [Logic Errors](#logic-errors)

All JS engines execute JavaScript code in the same way (at least the central bits of JS), but not all engines will throw the same errors and warnings.  So for the error logs you will need to record the messages logged by each main JS engine:
* V8 (Chrome, Node)
* SpiderMonkey (Firefox)
* Edge (Internet Explorer)
* Webkit

___

## Warnings

When you do something that might cause trouble, but won't break everything right away.  Often these will have to do with _strict mode_ or browser compatibility.

___

## [Syntax Errors](./syntax-errors.md)

Your code is so bad JavaScript doesn't even understand the sounds you're making.  These will throw an error in the _creation phase_ before running a single line of your code.

You can identify syntax errors because PythonTutor will throw an error before entering the step-through page. (ie. while still on the page where you paste the code.)

___

## [Runtime Errors](./runtime-errors.md)

A runtime error happens when JavaScript successfully passes the _creation phase_ and enters the _execution phase_, but your code attempts to do something that is not possible.  JavaScript doesn't have too many laws so usually it means you tried to access something that doesn't exist, tried to execute something that's not a function, or over-used some resource (memory or time usually).  

You'll know you have a runtime error because PythonTutor will make it to the step-through page, but not be able to finish.   You can sometimes see this before clicking "forward" when there are fewer steps than there should be.


___

## Logic Errors

Everything runs, but it doesn't behave how you would expect it to. You'll usually figure this out when your tests fail or your tracing predictions don't match the the actual step-through behavior.


___

## Resources

* Syntax vs Runtime vs Logic errors:
  * [Syntax vs Logic - in cinema](https://www.youtube.com/watch?v=tV0tQisuxPo)
  * [MDN - What went wrong?](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_went_wrong)
  * [TutorialsPoint](https://www.tutorialspoint.com/javascript/javascript_error_handling.htm)
  * [On Quora](https://www.quora.com/What-is-the-difference-between-a-logical-error-and-a-semantic-error)
* ["Strict Mode" warnings](http://www.javascriptkit.com/javatutors/serror.shtml)

___
___
### <a href="http://elewa.education/blog" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/34921062-506450ae-f97d-11e7-875f-6feeb26ad72d.png" width="100" height="40"/></a>