## Title:
Javascript vs. Rails
Daddy + Papa fighting and they’re both wrong.  Thinking through Javascript’s relationship to Rails.

## Description:  
DHH and Yehuda Katz -- whom I’ve affectionately referred to as Daddy and Papa -- are fighting about JavaScript. Is TurboLinks the answer? Is Ember? Is Backbone?

I think it’s neither.  Modern web apps are complicated and a little messy.  They need more than a single page.  On the other hand, sending the entire html page across the wire doesn’t make sense for highly interaction sites and has serious performance and security considerations.

So what’s the answer? BOTH.

Javascript MVC frameworks provide an excellent foundation of conventions for any app.  Using AJAX to get html fragments can make sense in certain cases, especially as part of a process to move logic from the backend to the frontend. Pushing some display logic to JavaScript can hand you caching on a platter.

Real apps require appropriate solutions for their specific problems.  Let’s discuss the techniques and trade-offs for using various JavaScript techniques in a real application, including progressively moving parts of a site to MVC and cases where using HTML fragments make perfect sense.

## Rough Outline:

The fight: 
DHH vs Yehuda 
Turbolinks vs Ember
(Ember vs Backbone/Angular)

The reality:
Existing apps - need techniques to upgrade, use new tools
Complex apps - need more than one solutions (single page doesn’t work)
New apps - need foundations and conventions that make sense and don’t box them in

Techniques
Progressively add MVC 
Use models for reusable components. EX: wishlist
Use HTML fragments with MVC ajax to move rendering into JavaScript
Standarize HTML + use JS or CSS to customize (TurboLinks)
caching the standard html fragments or the entire page
no security


## Audience Level: 
Intermediate Rails Devs

## Given at:

* Manhattan.js 2014 (variation)



