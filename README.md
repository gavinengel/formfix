# Formfix Framework

### A collection of polyfills to improve HTML form-tag and related tags


All   | Poly Group | Poly      | HTML-Tags       | Attrs                           | Description                                            
------|------------|-----------|-----------------|---------------------------------|----------------------------------------------------
formfix.js                   ||| form            | fix, data-fix                   |                                   
 | net.formfix.js             ||                 |                                 |  
 || method.net.formfix.js   |  form          | method                     | Allow additional HTTP methods (PUT, PATCH, DELETE)         
 || xhr.net.formfix.js   |  form          |                      | Network IO engine for XHR; with consistent events         
 | tpl.formfix.js          ||                 |                                 |   
 || for.tpl.formfix.js   |  form -> any          | for, data-for -> id                     | Allow `data-for` & `for` attr on form-tag         
 || template.tpl.formfix.js   |  input          | type=submit                     | Disable submit on form send; enable on receive         
 | inputs.formfix.js          ||                 |                                 |   
 || submit.inputs.formfix.js   |  input          | type=submit                     | Disable submit on form send; enable on receive         
 || checkbox.inputs.formfix.js |  input          | type=checkbox                   | Allow unchecked to be sent on submit                   
 || radio.inputs.formfix.js    |  input          | type=radio                      | Allow `data-current` & `current` for easier templating 

|for.tpl.formfix.js       | form -> any     | for, data-for -> id             | Allow `data-for` & `for` attr on form-tag              
|tpl.tpl.formfix.js       | any -> template | template, data-template -> id   | Allow `data-template` & `template` attr on any-tag              
