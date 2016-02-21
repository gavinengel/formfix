# Formfix Framework

### A collection of polyfills to embiggen the HTML form-tag


All   | Group      | Poly      | Tags            | Attrs                           | Description                                            
------|------------|-----------|-----------------|---------------------------------|----------------------------------------------------




formfix.js           |                 |                                 | all formfix polyfills                                  
| core.formfix.js      |                 |                                 | core formfix polyfills 
|net.formfix.js       |                 |                                 | net formfix polyfills                                  
|tpl.formfix.js       |                 |                                 | tpl formfix polyfills                                  
|for.tpl.formfix.js       | form -> any     | for, data-for -> id             | Allow `data-for` & `for` attr on form-tag              
|tpl.tpl.formfix.js       | any -> template | template, data-template -> id   | Allow `data-template` & `template` attr on any-tag              
|inputs.formfix.js    |                 |                                 | tpl formfix polyfills                                  
|submit.formfix.js    |  input          | type=submit                     | Disable submit on form send; enable on receive         
|checkbox.formfix.js  |  input          | type=checkbox                   | Allow unchecked to be sent on submit                   
|radio.formfix.js     |  input          | type=radio                      | Allow `data-current` & `current` for easier templating 
|xhr.formfix.js       | form            |                                 | Network IO engine for XHR; with consistent events      
method.formfix.js    | form            | method                          | Allow additional HTTP methods (PUT, PATCH, DELETE)     