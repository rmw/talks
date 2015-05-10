## Title: 
Testing your Javascript with Jasmine in Rails
Javascript testing with Jasmine and Rails

## Description: 

As Rails developers, we all know we should test our Javascript, but … it’s just such a pain in the ass.  Not only is testing JavaScript itself challenging, but Rails and the Asset Pipeline add another level of complexity.  This talk will to dig into the advantages of testing your JavaScript and using Jasmine as well as solutions to the little gotchas that can make Jasmine + Rails hell.   

## Topics covered:

* Advantages of testing your Javascript
* Advantages of Jasmine
* Jasmine & jQuery gotchas
* Jasmine & Rails gotchas
* Jasmine & CI

## Rough Outline: 
Do you test your JavaScript?

Why test your Javascript?

* TDD across stack
* Cross browser testing (in browser - IE)
* Write better and more OO JavaScript (ex: document.load vs OO with init)

Why Jasmine?

* Familiar rspec syntax
* mocks, spys
* Alternatives + Additions
* Jasmine-jQuery
* Jasmine-Ajax
* Sinon.js
* Qunit ...

The Gotchas

* ?Jasmine+JQuery 
  * doc.load - possibly covered already?
  * spy on jQuery functions
* Jasmine+rails
  * Asset pipeline + vendored gems (with pure JS)
  * Coffeescript + JasmineRice?
  * Fixtures 
* CI
  * headless
    * fixtures + inline scripts
    * cookies
  * envJasmine?



## Audience Level: 
Intermediate Rails Devs + JS devs new to Rails


