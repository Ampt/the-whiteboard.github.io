---
layout: post
title:  Debugging - The third intro to CS assignment
date:   2016-03-26 18:07:26 -0500
categories: coding debugging
author:	MichaelT
---

I'll admit to being a bit hazy about the exact homework problems and lectures in intro to CS all those decades ago.  I'll even admit to it being in Pascal (the other choices were C or Fortran 77).  I suspect the first homework problem was a "get familiar with writing in the IDE" and the second assignment was your typical "basic control structures."

If I could go back in time and change my course syllabus, I know what that third assignment would be: an introduction to the debugger.

Learning how to use a debugger was something that came *much* later for me. Initially, I was using printf and examining the logs (not that there's anything wrong with that). Then I started with a few breakpoints in gdb while trying to write part of a compiler for a class. It wasn't until many years later when working on a very large piece of third party software that I became proficient in using the debugger to it's full potential.

In my early years of programming the programs were relatively small things. A CGI to do something, a script to read some logs, a webservice to read something out of a database. They fit on a page or two of a printout if need be, or a few screens worth when looking at them in the editor. They were easy to understand.

Now, programs tend to be much larger. While small modular code is an ideal, [only Heaven and textbooks are ideal](http://www.scientificamerican.com/article/john-updike-poem-1969/). Every single bit of code you will find out there when doing actual work will be cringeworthy when re-examined later. Making sure you modularize your code will put this off for awhile, and make it easier to grasp the essence of each smaller block.  Writing testable code will help you ensure that things are working right.

But when code becomes complex, and it will, you will inevitably need to debug it, and when it comes to debugging, there is no tool more useful, accessible, and powerful than the debugger. I would go so far as to say that professionals who neglect to learn how to use the debugger border on incompetent. It would be just as bad for a chef to not know how to use a thermometer or craftsman to not know how to use a ruler. These are basic and necessary tools of the trade, and while the debugger is a bit more complex than either of those examples, it is just as fundamental.

I keep going back to an essay I read awhile ago.  [How to be a programmer - learn to debug](https://github.com/braydie/HowToBeAProgrammer/blob/master/en/1-Beginner/Personal-Skills/01-Learn%20To%20Debug.md).  This is the first item of the first set of skills to know. I am half glad that it wasn't written until 2002 so that I have a good excuse for not having read it for a decade (though I also wish I could have read it back when I started).

Learning to debug is, in part, learning how to use a debugger. Debugging means being able to read the code and understand what it does - be it working correctly, or incorrectly. It means being able to look at some code and describing the business logic that it encodes. It means being able to look at some code and consider the possible edge conditions that might cause problems.

While the creative process of writing code is something that we get into programming for, it is the understanding and extending of existing code, along with debugging, that is the daily task of programmers everywhere.
