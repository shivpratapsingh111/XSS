
# Reflected XSS:

  

## How XSS works: When the input directly goes in a particular code section where javascript can be executed.

  

## Where you can execute script

### Script tag

* [Inline Script] <script>alert()</script>

* [External Script] <script src=https://myserver.com/jsthegreat.js></script>

## With event handlers:

* With or Without user interaction
   > With User Interaction
   * onload

  * onerror
   > Wihtout User Interaction  
  * onerror 
  * onload
  

## Methodology:

  

* Identifying Entry Points:

>Parameters, Form Fields, Cookies, Request Headers, Error messages

* Check for allowed Characters:

> "'`<>()

> script, alert, confirm, prompt


