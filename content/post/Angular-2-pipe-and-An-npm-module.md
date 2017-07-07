+++
date = "2016-12-25T01:55:50+05:30"
title = "Angular 2 pipe and An npm module"
author = "Ankit Singh"
+++

Few days ago , while working on a project which required around 200 names to be displayed at once and that too on a mobile screen ...that's berzerk!!!

So thought of letting the user enter the names rather than searching from giant list of hundreds so made a sweet input box and then thought of applying the filter like we do in Angular 1 using its pre-defined search filter...but wait I was working on Angular 2 and surprise surprise it doesnt has a pre-defined search filter like Angular 1 did ..bummed!!


So thought lets make one then , i looked over the Angular 2 official docs and saw pipes(*_*)

By the way a pipe is nothing just this | , Yes this is a pipe .

So i dug little deeper and found PipeTransform implementing which i thought of making a filer for myself and offcourse for my project.

So ng2-search filter was born which allowed to filter large list of names based on the character that user writes i.e.

* If you write letter 'q' , then it will filter all the names having 'q' in them so it totally solved my purpose.

Demo Below,

![demo-image](http://i.imgur.com/dI5Mzvq.gif)


I then thought why not make it an open-source npm module , so i uploaded it on the ever-increasing npm global module repository consisting of lakhs of packages.

Mine is called "ng2-search-filter"(https://www.npmjs.com/package/ng2-search-filter).

By the way , the module got 117 downloads in its first 14 hrs online .

