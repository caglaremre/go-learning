- every go file **must have** ==package== declaration.
- every go program **must have** a function name ==main==.
- if the name of a function, variable starts with Capital letter, that function variable is accessible from other files. exp: `var name string` is ==private== and `var Name string` is ==public==
- ==defer== is used to postpone execution of function until surrounding function is done
- ==nil== is used for null
- `template.ParseFiles(templates...)` templates... will add one by one