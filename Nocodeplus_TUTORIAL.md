# Nocode+

Yeah that is still no code BUT that is FILENAME!!!

## Print hello, world

FILETREE
```
print("Hello, world!").nocode
```

## Standard datatypes

- str
- int
- float
- bool
- list
- dict

## String escaping

As we know, you can't insert `* \ / : " ? | < >` in name of files.

So you can:

| plaintext | escape character |
| --------- | ---------------- |
| *         | &amp;ms;         |
| \\        | &amp;as;         |
| /         | &amp;ds;         |
| :         | &amp;colon;      |
| ?         | &amp;quem;       |
| "         | &amp;dquom;      |
| \|        | &amp;sep;        |
| &lt;      | &amp;lt;         |
| &gt;      | &amp;gt;         |

## Define a variable

SYNTAX:&nbsp;&nbsp;&nbsp;$`variable_name`=`variable_value`.nocode

like this:

FILETREE
```
$his_favourite_geme='minecraft'.nocode
$todays_Celsius_temperature=26.nocode
$debug=true.nocode
$shopping_list=['apple','banana'].nocode
$styled_text={'text'='hello','color'='#ffff00'}.nocode
$chat_record=[{"name"="Xiaoming","message"="Nice_to_meet_you"},{"name"="Xiaohong","message"="Nice_to_meet_you_too"}].nocode
```

## Define a function

Function should be a folder.

SYNTAX:&nbsp;&nbsp;&nbsp;function-`function_name`(`arg1_name`-`arg1_datatype`,`arg2_name`-`arg2_datatype`,`...`,`argN_name`-`argN_datatype`)



like this:
```
[FOLDER] function-foo(text-str)
    print(text).nocode
```

### Set a default value of a argument

SYNTAX:&nbsp;&nbsp;&nbsp;`arg_name`-`arg_datatype`=`arg_defaultvalue`

WARNING: All parameters with default values must come after those without default values.

## More about Nocode+

Coming soon...
