Updated script.js line 40 to read:
  showGlobals();
It incorrectly showed as "showGlobal()".
I located the error by following the console. It advised that the call at line 40 was not defined. A quick glance up the script revealed that the function showGlobals was most likely the intended name of the broken function, as a typo explained the error. 


Error Message:
script.js:40 Uncaught ReferenceError: showGlobal is not defined
    at startMeUp (script.js:40)
    at onload (index.html:9)
