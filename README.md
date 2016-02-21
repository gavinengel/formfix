# Formfix Framework

### A collection of polyfills to embiggen the HTML form-tag


File                 | Tags            | Attrs                           | Description                                            
---------------------|-----------------|---------------------------------|--------------------------------------------------------
formfix.js           |                 |                                 | All formfix polyfills                                  
core.formfix.js           |                 |                                 | All formfix polyfills                                  
net.formfix.js           |                 |                                 | All formfix polyfills                                  
tpl.formfix.js           |                 |                                 | All formfix polyfills                                  
xhr.formfix.js       | form            |                                 | Network IO engine for XHR; with consistent events      
method.formfix.js    | form            | method                          | Allow additional HTTP methods (PUT, PATCH, DELETE)     
for.formfix.js       | form -> any     | for, data-for -> id             | Allow `data-for` & `for` attr on form-tag              
tpl.formfix.js       | any -> template | template, data-template -> id   | Allow `data-template` & `template` attr on any-tag              
submit.formfix.js    |  input          | type=submit                     | Disable submit on form send; enable on receive         
checkbox.formfix.js  |  input          | type=checkbox                   | Allow unchecked to be sent on submit                   
radio.formfix.js     |  input          | type=radio                      | Allow `data-current` & `current` for easier templating 