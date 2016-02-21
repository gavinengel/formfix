# Formfix Framework

### A collection of polyfills to embiggen the HTML form-tag


| File                 | Group  | Tags  | Attrs                 | Description                                            |
|----------------------|--------|-------|-----------------------|--------------------------------------------------------|
| core.formfix.js      | core   |       |                       | Core Formfix polyfills                                 |
| input.formfix.js     | inputs |       |                       | Input-related Formfix polyfills                        |
|----------------------|--------|-------|-----------------------|--------------------------------------------------------|
| xhr.formfix.js       | net    | form           |                       | Network IO engine for XHR; with consistent events      |
| method.formfix.js    | net    | form           | method                | Allow additional HTTP methods (PUT, PATCH, DELETE)     |
| for.formfix.js       | tpl    | form -> any    | for, data-for -> id   | Allow `data-for` & `for` attr on form-tag              |
| tpl.formfix.js       | tpl    | any -> template    | template, data-template -> id   | Allow `data-template` & `template` attr on any-tag              |
| submit.formfix.js    | input  |  input          | type=submit           | Disable submit on form send; enable on receive         | 
| checkbox.formfix.js  | input  |  input          | type=checkbox         | Allow unchecked to be sent on submit                   |
| radio.formfix.js     | input  |  input          | type=radio            | Allow `data-current` & `current` for easier templating |