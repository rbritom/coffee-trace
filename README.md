![Coffee-Trace](https://github.com/xenomuta/coffee-trace/raw/master/img/coffee-trace.png "Coffee-Trace")
Coffee-Trace: _easier to follow stack-trace for coffee-script_. 
===============================================================

### About Coffee-Trace
If you love Coffee-Script and Node.js as much as me, you will provably also be frustrated by the challenges of quickly finding and debugging the corresponding javascript line on the stack-trace. I wrote Coffee-Trace in an attempt to make this task easier.
 
I've been searching myself for a solution, and have found some very useful [links and discussions], but am yet unsatisfied. So, while [SourceMaps] [1] implementation in Coffee-Script is a reality, this is the least I can do.

  [1] http://www.html5rocks.com/en/tutorials/developertools/sourcemaps/ "SourceMaps"
  [2] http://www.adaltas.com/blog/2012/02/15/coffeescript-print-debug-line/ "links and discussions"
  [3] https://github.com/jashkenas/coffee-script/issues/558 "links and discussions"
  [4] http://www.quora.com/CoffeeScript/Is-there-a-CoffeeScript-debugger-yet "links and discussions"


### Usage

Become a masochist by enjoying uncaught exceptions and crashes. Just `require()` it at the very beginning of your app...

